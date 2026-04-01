The cellular device is One Plus Nord CE 3 with Android. 

The web browsers are Google Chrome and Via. Directories are accessible, but files aren't. 

Every time I try to access a file in whatever repository, I get the following error: "Error loading page - An unexpected error occurred - Try reloading the page".

**Surprisingly, this error does not occur from Windows 11 Home with LibreWolf web browser.**

## Tried but did NOT work
- Confirming system, Chrome, and WebView were fully updated.
- Confirming that no DNS filters or ad-blocking apps.
- Resetting all Chrome flags.
- Clearing caches in Google Chrome.
- Clearing caches in Android System WebView.
- Removing Via Browser.

## What WORKED
- In system settings, uninstalling updates for Android System WebView.
- Then clearing Chrome caches again.

After that, GitHub files loaded normally, confirming the problem was a broken WebView update.
