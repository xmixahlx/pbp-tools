# pbp-tools

## pbp-tools: pinebook pro tools 

tools for system management, hardware acceleration, and wayland environment for the pinebook pro.

**system:**<br>
pbp-install-ap6256-firmware<br>
pbp-install-postinstall<br>
pbp-install-boot<br>

**hwaccel:**<br>
pbp-install-alacritty<br>
pbp-install-ffmpeg<br>
pbp-install-gstreamer<br>
pbp-install-jellyfin-kodi<br>
pbp-install-kodi<br>
pbp-install-kodi-inputstream-adaptive<br>
pbp-install-kodi-p8-platform<br>
pbp-install-kodi-platform<br>
pbp-install-libudfread<br>
pbp-install-libva<br>
pbp-install-libva-utils<br>
pbp-install-libva-v4l2-request<br>
pbp-install-linux<br>
pbp-install-mesa<br>

**wayland:**<br>
pbp-install-dmenu-wayland<br>
pbp-install-fontawesome<br>
pbp-install-sway<br>
pbp-install-waybar<br>
pbp-install-wdisplays<br>
pbp-install-wlogout<br>

**notes:**<br>
* system management tools borrow manjaro configurations for mainline kernel and mrfixit2001 boot images.<br>
* many scripts have variable override via commandline (ffmpeg, kodi, linux, etc.).<br>
* recommended core hwaccel setup includes, in build order: linux, mesa, ffmpeg, and kodi.<br>
* libudfread is an optional kodi dependency.<br>
* kodi addons include kodi-platform, kodi-p8-platform, jellyfin-kodi and kodi-inputstream-adaptive.<br>
* libva, libva-utils, and libva-v4l2-request are VAAPI related packages that have some use, but are currently less useful due to an ffmpeg bug.<br>
* gstreamer includes v4l2codecs from upstream and VAAPI is enabled, so depends on VAAPI packages.<br>
* alacritty is a GL(ES) enhanced terminal.<br>
* to use sway, first build the sway suite (wlroots, sway, swaybg, swaylock, and swayidle), then optionally dmenu-wayland, waybar, wdisplays, and wlogout.<br>
* fontawesome is an optional dependency of waybar for fancy icons.<br>
* please feel free to modify and adapt to your own distro, and contribute changes.<br>
* REVIEW EACH SCRIPT PRIOR TO USAGE.<br>

**discussion:**<br>
[pbp-tools forum thread at pine64](https://forum.pine64.org/showthread.php?tid=10190)<br>
[mainline kernel froum thread at pine64](https://forum.pine64.org/showthread.php?tid=8968)<br>
[mainline hwaccel forum thread at pine64](https://forum.pine64.org/showthread.php?tid=9171)<br>
[mesa forum thread at pine64](https://forum.pine64.org/showthread.php?tid=8953)<br>
[kodi forum thread at pine64](https://forum.pine64.org/showthread.php?tid=9877)<br>
[sway forum thread at pine64](https://forum.pine64.org/showthread.php?tid=9036)<br>
[danielt's unofficial debian installer forum thread at pine64](https://forum.pine64.org/showthread.php?tid=8487)<br>

**reference:**<br>
[pine64 website: pinebook pro page](https://www.pine64.org/pinebook-pro/)<br>
[pine64 wiki: pinebook pro page](https://wiki.pine64.org/index.php/Pinebook_Pro)<br>
