# Learning about Lifecycle Activities.
This project explains and shows lifecycle callbacks.
The **Lifecycle library** is also used so that the app is less error-prone.
**Timber** library is also implemented.
In the last *commit*, a counter is implemented (threads). It counts the seconds (via Logcat using TImber) that the application is visible (focused or not). It's an example of at what moments a song would be playing. In this implementation is where **Lifecycle library** is used.

## Quick steps to implement **Timber library**
- Add Timber to *build.gradle* 
- Make Application class
- Add Application to Manifest
- Initialize Timber in Application class

### To remember:
`onPause()` and `onResume()` are mirror functions. Here, activity is always visible.
`onStop()` and `onStart()` are mirror functions.
`onCreate()` and `onDestroy()` are mirror functions.
