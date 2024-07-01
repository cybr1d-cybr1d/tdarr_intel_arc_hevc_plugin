# tdarr_intel_arc_hevc_plugin
Tdarr Plugin for Intel Arc GPUs to convert to HEVC

I made this plugin to work with my Intel Arc GPU and give me the ability to adjust the values I typically use since there didn't seem to be any other working plugins that offered the same thing. I am using ffmpeg 6.1.1 and an Intel Arc A380.

## To Use
Add the plugin file to "/Tdarr_Updater/server/Tdarr/Plugins/Local/" and restart server.

## Features
Global Quality - Enter the global quality level you want (0-51, lower = higher quality, bigger file). Defaults to 19. Example: 19 (I use 15 for 1080p REMUXs)
ffmpeg preset - Specify the preset speed (I use slow for 1080p REMUXs)
bframe - Specify the number of B-frames to use (0-16, defaults to 3). Example: 3 (I use 3 for movies and 5 for anime)
force 10-bit - enables 10-bit
