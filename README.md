# WinRTCSample
This sample shows how Win32App register Win Runtime Component (backgroundtask), and the later one can launches Win32 Process on background if timezone is changed.

This is one Desktop Bridge sample

#### Win32App is the main app
#### BackgroundTask is WinRTC
#### WinForm is the process will be launced by BackgroundTask
#### MyDesktopApp.Package is to package the whole Desktopbridge app

# Run
#### Build and set MyDesktopApp.Package as startup project in latest VS2017 (15.9)
#### Launch MyDesktopApp.Package, Win32App will execute
#### Close Win32App
#### Change TimeZone, the toast will show up, and winform will launch as well.


