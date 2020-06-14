# pbp-tools

**pbp-tools: pinebook pro tools**

management and build scripts for hardware acceleration, system management, and wayland.

**notes:**<br>
recommended hwaccel setup includes linux, mesa, ffmpeg, and kodi.
system management designed for use with danielt's unofficial debian installer, but works fine with many other distros.
some scripts have variable override via commandline (ffmpeg, linux, linux-crossbuild)
REVIEW EACH SCRIPT PRIOR TO USAGE.

**system:**<br>
pbp-update-ap6256-firmware<br>
pbp-update-ap6256-firmware_current<br>
pbp-update-postinstall<br>
pbp-update-systempartitions<br>

**hwaccel:**<br>
pbp-build-ffmpeg<br>
pbp-build-jellyfin-kodi<br>
pbp-build-kodi<br>
pbp-build-kodi-inputstream-adaptive<br>
pbp-build-libudfread<br>
pbp-build-libva<br>
pbp-build-libva-utils<br>
pbp-build-libva-v4l2-request<br>
pbp-build-linux<br>
pbp-build-linux-crossbuild<br>
pbp-build-mesa<br>

**wayland:**<br>
pbp-build-sway<br>
pbp-build-dmenu-wayland<br>
pbp-build-wlogout<br>
pbp-build-waybar<br>
pbp-build-wdisplays<br>

**discussion:**<br>
[pbp-tools forum thread at pine64](https://forum.pine64.org/showthread.php?tid=10190)

**references:**<br>
[danielt's unofficial debian installer](https://forum.pine64.org/showthread.php?tid=8487)
