Phone Defense — starter project
This is a first-stage Android project for the Phone Defense prototype.
Current features
Basic app screen
Add a test incident
Save and display test incidents locally using Android app-private storage
Clear test incidents
Not implemented yet
This starter does not monitor unlock attempts, capture photos, record location, or send email. Those features will be added in later stages and must work within Android's permissions and background-access rules.
Build an APK from your Samsung phone using GitHub Actions
Open your private PhoneDefense repository on GitHub in your phone browser.
Tap Add file → Upload files.
Upload the contents of this ZIP, preserving the folder structure. If GitHub's mobile page does not show upload options, use your browser's Desktop site option.
Commit the files to the main branch.
Open the repository's Actions tab. If GitHub asks you to enable workflows, enable them.
Select Build Phone Defense APK and tap Run workflow if a run has not started automatically.
Open the completed workflow run and find the Artifacts section.
Download PhoneDefense-debug-apk and extract it to find app-debug.apk.
Open the APK on your Samsung phone and follow Android's installation prompts only if you trust the build.
Important
Keep the repository private.
A debug APK is for testing, not public distribution.
Keep your GitHub account protected with a strong password and two-factor authentication.
Never put email passwords, API keys, or other secrets in the app source code.
