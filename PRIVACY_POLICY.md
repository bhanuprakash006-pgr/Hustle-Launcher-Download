# Hustle Launcher Privacy Policy

**Effective Date:** November 15, 2026  
**Developer:** Bhanu Prakash  
**Contact:** bhanu.prakasht006@gmail.com

## 1. Introduction

Hustle Launcher is an Android launcher designed to help users organize their applications, reduce digital distractions, and manage their device usage.

Its features include application organization, Focus Mode, app restrictions, screen-time information, and a built-in browser.

This Privacy Policy explains what information Hustle Launcher accesses, how it is used, and how users can manage the permissions required by the application.

## 2. Information Accessed by the Application

### 2.1 Installed Applications

Hustle Launcher accesses information about applications installed on your device, including application package names and related application information.

This information is used to:
- Display installed applications in the app drawer.
- Allow users to select and organize applications.
- Support application restrictions and Focus Mode.

### 2.2 Screen-Time Information

Hustle Launcher uses Android's UsageStatsManager through the Android Usage Access permission.

This permission allows the application to access application usage events and durations.

The information is used to:
- Calculate total screen time.
- Display application-level usage information.
- Provide screen-time statistics and usage summaries.

### 2.3 Accessibility Service

Hustle Launcher provides an Accessibility Service named **Hustle Focus Protection**.

When enabled by the user through Android Settings, this service:
- Detects which application is currently in the foreground.
- Checks whether the application is restricted.
- Checks whether an application is allowed during an active Focus Mode session.
- Returns the user to the Home screen when an application violates an active restriction.

The Accessibility Service is used to enforce application restrictions and Focus Mode functionality.

The implementation reviewed for this policy listens for application window-state changes and reads the foreground application's package name.

It does not show functionality for reading screen text, keystrokes, messages, passwords, or website contents.

The service requires the user's explicit activation through Android Settings. Users can disable it at any time through the device's Accessibility settings.

### 2.4 Browser Information

Hustle Launcher includes a built-in browser powered by Android WebView.

When using the browser:
- Websites receive the network requests necessary to load their content.
- JavaScript and DOM storage are supported.
- Websites may use cookies and browser storage for their own functionality.
- Cookies may be used when processing supported downloads.
- Supported downloads are handled through Android's Download Manager.

The browser also applies selected website and download restrictions.

These restrictions do not guarantee that every distracting, inappropriate, or potentially harmful website or file will be blocked.

External websites operate independently and are responsible for their own data collection and privacy practices.

## 3. Information Stored on Your Device

Hustle Launcher stores certain settings and activity information using Android's application storage.

Depending on the features you use, this may include:
- Selected and arranged applications.
- Restricted application package names.
- Focus Mode settings and allowed applications.
- Focus session start, end, and pause information.
- Completed Focus Mode sessions and total focus time.
- Daily focus statistics and historical records.
- Browser download references and related browser data.
- Other application preferences.

Screen-time information is calculated using Android usage events.

The application uses Android private SharedPreferences for various settings and records.

Browser cookies and website storage may also be managed by Android WebView.

## 4. Data Sharing and Third-Party Services

The application code reviewed for this policy does not show a dedicated Hustle Launcher backend or an explicitly declared analytics, advertising, authentication, or crash-reporting SDK.

However, this does not mean that no information is ever transmitted outside your device.

For example:
- The built-in browser connects to websites selected by the user.
- External websites may receive IP addresses, browser requests, cookies, and other information required for their services.
- Android's Download Manager processes supported downloads.
- Android operating-system backup services may process application data according to device settings.

Hustle Launcher does not sell users' personal information.

## 5. Data Security and Backups

Hustle Launcher uses Android application storage mechanisms to store local settings and activity information.

The application allows Android backup functionality. Its backup configuration files do not contain customized include or exclude rules.

Therefore, whether application data is included in Android backups or device transfers may depend on the Android version, device configuration, and the user's backup settings.

Hustle Launcher does not guarantee that all locally stored information is excluded from backups.

Users who do not want application data included in backups should review their Android device's backup settings.

## 6. User Control and Permissions

Users can manage the permissions granted to Hustle Launcher through Android Settings.

These include:
- Usage Access.
- Accessibility Service access.
- Other Android permissions required by the application.

Disabling required permissions may affect the functionality of certain features.

Users can also uninstall Hustle Launcher through Android Settings.

Uninstalling the application may remove locally stored application data. However, it does not necessarily remove information already received by external websites or information included in Android backups.

## 7. Children's Privacy

Hustle Launcher is not specifically designed to collect personal information from children.

Parents and guardians should supervise children's use of applications and internet services where appropriate.

## 8. Changes to This Privacy Policy

This Privacy Policy may be updated when application functionality, permissions, or data practices change.

The latest version will be made available through the official Hustle Launcher repository or other official distribution channels.

## 9. Contact

For privacy-related questions, concerns, or requests, contact:

**Developer:** Bhanu Prakash  
**Email:** bhanu.prakasht006@gmail.com

---

**Hustle Launcher**  
*Focus can't be negotiated.*