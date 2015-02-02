# AppGyverize Release notes

These release notes are separated from (RELEASENOTES.md) in order to prevent
conflicts when plugin is updated from the upstream.

This file lists the AppGyver related changes to this plugin. Plugin version numbers change according to the upstream version.


## 0.4.8-ag1

Changes:
- Use the cordova.getCookie() method instead of CookieManager.getInstance().getCookie().
  This will provide cross-compatibility between the Crosswalk and Platform WebView
  runtimes. Fixes [#627](https://github.com/AppGyver/steroids/issues/627).
