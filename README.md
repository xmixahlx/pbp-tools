# pbp-tools

**pbp-tools: pinebook pro tools**

management and build tools for system management, hardware acceleration, and wayland environment for the pinebook pro.

**system:**<br>
pbp-update-ap6256-firmware<br>
pbp-update-postinstall<br>
pbp-update-systempartitions<br>

**hwaccel:**<br>
pbp-build-ffmpeg<br>
pbp-build-gstreamer<br>
pbp-build-jellyfin-kodi<br>
pbp-build-kodi<br>
pbp-build-kodi-inputstream-adaptive<br>
pbp-build-libudfread<br>
pbp-build-libva<br>
pbp-build-libva-utils<br>
pbp-build-libva-v4l2-request<br>
pbp-build-linux<br>
pbp-build-mesa<br>

**wayland:**<br>
pbp-build-dmenu-wayland<br>
pbp-build-sway<br>
pbp-build-waybar<br>
pbp-build-wdisplays<br>
pbp-build-wlogout<br>

**notes:**<br>
system management tools borrow manjaro configurations for mainline kernel and mrfixit2001 uboot.<br>
some scripts have variable override via commandline (ffmpeg, kodi, linux, etc.).<br>
recommended core hwaccel setup includes, in order: linux, mesa, ffmpeg, and kodi.<br>
libudfread is an optional kodi dependency.<br>
kodi addons include jellyfin-kodi and kodi-inputstream-adaptive.<br>
libva, libva-utils, and libva-v4l2-request are VAAPI related packages that have some use, but are currently less useful due to an ffmpeg bug.<br>
gstreamer includes v4l2codecs from upstream and VAAPI is enabled, so depends on VAAPI packages.<br>
to use sway, first build the sway suite (wlroots, sway, swaybg, swaylock, and swayidle), then optional wayland tools: dmenu-wayland, waybar, wdisplays, and wlogout.<br>
please feel free to modify and adapt to your own distro, and contribute changes.<br>
REVIEW EACH SCRIPT PRIOR TO USAGE.<br>

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
