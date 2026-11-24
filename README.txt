BASS BOOST TV v1.1 - always-on

BUILD
 A) Android Studio: open folder, sync, Build > Build APK(s).
 B) GitHub: upload all files (keep .github folder), Actions > "Build APK" > Run workflow,
    download artifact "BassBoostTV-apk".

INSTALL: adb connect <TV-IP>:5555 ; adb install app-debug.apk (or copy via USB / Send Files to TV).

FIRST RUN: open "Bass Boost TV" once. After that it starts by itself on every TV boot
and re-applies the effects every 15 seconds.
