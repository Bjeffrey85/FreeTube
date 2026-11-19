# FreeTube

**YouTube in its own sandboxed browser for Windows.**

FreeTube is a stripped-down copy of Firefox that can only open YouTube. Sign in to your Google account here and it stays here. Your everyday browser stays logged out of Google, and YouTube's tracking stays out of the rest of your browsing.

It looks and feels like a standalone app. It has its own icon in the taskbar and Start menu, and there's no address bar, no tabs and no menus. It opens straight to YouTube, with back, forward and reload buttons.


<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/bf6f0313-26b6-4a97-87c5-cd0285c71638" />

[![Download](https://img.shields.io/badge/Download-FreeTube--Setup.zip-14b8a6?style=for-the-badge&logo=windows)](https://github.com/Bjeffrey85/FreeTube/releases/latest/download/FreeTube-Setup.zip)


## Features

- **Separate from your main browser.** FreeTube has its own copy of Firefox ESR (the long-term-support version) and its own profile. Nothing is shared with your regular browser: no cookies, no history, no logins.
- **YouTube only.** Firefox's built-in enterprise policies allow only YouTube and Google sign-in pages. Click any other link (a video description, a comment, a channel's website) and it opens in your normal browser instead.
- **Ad-free.** uBlock Origin is preinstalled and can't be removed. SponsorBlock skips sponsor segments. Return YouTube Dislike and DeArrow are optional.
- **Stays signed in.** Log in once. Your session survives restarts and updates.
- **Locked down.** Settings pages, add-on installs, developer tools, private windows and safe mode are all disabled. Camera, mic, location and notification requests are blocked. WebRTC is off, so it can't leak your IP address. HTTPS-only mode is on.
- **No telemetry.** Mozilla studies, Pocket, sync, password saving and onboarding pop-ups are all turned off.
- **Keeps itself patched.** The engine updates itself. FreeTube's config survives every update.
- **Nothing to trust blindly.** The installer downloads Firefox directly from Mozilla and stops if the file isn't signed by Mozilla. The launcher is compiled on your own PC from the included C# source, using the compiler built into Windows.

## Install

1. Download and extract the zip.
2. Double-click `Install-FreeTube.cmd`. No admin rights needed.
3. Sign in to YouTube. That's it.

Everything lives in `%LOCALAPPDATA%\FreeTube`. Uninstall from Settings → Apps.

## Requirements

Windows 10 or 11 (x64 or ARM64).
