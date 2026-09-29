RESHUU - how to get your APK (free, no Android Studio needed)
1. Make a free account on github.com and create a new repository named reshuu.
2. Upload these files to the repository: package.json, capacitor.config.json and the www folder.
3. In the repository click Add file > Create new file. In the name box type:
   .github/workflows/build.yml
   Then copy everything from the build.yml file in this zip and paste it. Click Commit.
4. Click the Actions tab. Wait 5 to 10 minutes until "Build APK" shows a green tick.
5. Open that run, scroll to Artifacts, download Reshuu-apk, unzip it. Inside is app-debug.apk.
6. Send app-debug.apk to your phone and install it (allow "install unknown apps").

This is a test APK. For the Play Store you need a signed release file (.aab).
