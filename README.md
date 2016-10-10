# vlc_vaapi_crash

Play "crash_video.ts" to crash VLC with VAAPI enabled. It happens if the video changes
the aspect ratio or the resolution for a commercial break (recorded from a dvb-c stream).

Tested with vlc 2.2.4 Weatherwax, kernel 4.3.0-gentoo, VA-API version 0.38.1, (libva 1.6.2), 
Intel i965 driver for Intel(R) Haswell Mobile - 1.6.2
xf86-video-intel Driver 2.99.917_p20160621-r1
