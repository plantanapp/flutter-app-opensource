# flutter-app-opensource

[Getting Started with Flutter](https://docs.flutter.dev/get-started/install)

Starter flutter app for wrapping your Plant an App website in a Flutter Webview.

`lib/main.dart` -> `appUrl` is where you will put the https URL that points to the desired Plant an App instance.

Barcode Scanning is implemented by using the `barcode_scan2` flutter package and calling `window.paa.scan()` in your Action Form, the method returns a `Javascript Promise`.
