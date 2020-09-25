[![NuGet](https://img.shields.io/badge/Nuget-1.0.0-blue.svg)](https://www.nuget.org/packages/PlayCore/)
# XamarinPlayCoreUpdater
This repo conatins a NuGet package that allows you to Support in-app updates in your Xamarin Forms Android Apps.
This repo has been forked to support the in-app rate flow in your Xamarin Forms Android app.
Supported and tested is the Immediate update variant.

See https://developer.android.com/guide/playcore/in-app-updates for more info.
 
Please see the PlayCoreUpdateTest Sample for how to use the PlayCore Updater.

Possible Pitfall:
If you use "Google App signing https://support.google.com/googleplay/android-developer/answer/7384423?hl=en" you can only test the update process with an app from the store and an update from the store.
You can just disable automatic app updates, wait for the new version to appear in the Play Store and than manually start your App.
