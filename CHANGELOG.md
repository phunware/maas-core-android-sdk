MaaSCore Change Log
==========

Version 1.3.2 *(2013-11-08)*
----------------------------
 * Session Pause events are sent much more accurately (when the app closes, the screen turns off, or device rotates, aka when there are no active activities).
 * Removed Session Stop events.
 * Duplicate Session Start events are no longer being sent.
 * Using Location object to help convert location payloads.
 * Added Throwable method variants to PwLog
 
Version 1.3.1 *(2013/10/23)*
----------------------------
 * Bug fixes
 * Optimization of network and analytic calls
 * Requires Retrofit 1.2.2 jar
 * Requires Gson jar
 * Android Minimum SDK 8
 * Android Target SDK 18

Version 1.2.1 *(2013-08-07)*
----------------------------
 * Updated Analytics Caching to be more reliable.
 * Added PwLog. This class can be used to view logs from all MaaS SDKs.
 * Bug fixes

 Version 1.2.0 *(2013-07-31)*
----------------------------
 * Deprecated activityStartSession(context) in favor of activityStartSession(activity)
 * Deprecated activityStopSession(context) in favor of activityStopSession(activity)
 * Minor bug fixes

Version 1.1.1 *(2013-07-24)*
----------------------------
 * Changed OpenUDID package name from *org* to *com* to fix integration issues with other apps using OpenUDID.
 * Minor bug fixes

 Version 1.1.0 *(2013-07-16)*
----------------------------
 * Minor bug fixes
 * Includes support for integration with Google Play Services Location API