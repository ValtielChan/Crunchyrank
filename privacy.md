# Crunchyrank — Privacy Policy

_Last updated: April 19, 2026_

Crunchyrank ("the extension") is a browser extension that filters and sorts anime
cards displayed on crunchyroll.com based on their star rating and vote count.

This document explains, in plain language, exactly what the extension does and
does not do with your data.

## Summary

**Crunchyrank does not collect, transmit, sell, or share any personal data.**

There are no servers, no analytics, no tracking, no advertising, no accounts,
and no telemetry of any kind.

## What data the extension handles

The extension only handles two categories of information, and both remain
entirely on your own device:

1. **Your filter preferences.** The settings you choose in the extension popup
   (minimum rating, minimum vote count, sort order, display mode, whether the
   filter is enabled, whether the rating badge is shown, and whether to hide
   unrated anime) are stored locally in your browser using Chrome's built-in
   `chrome.storage.sync` API. This is the standard mechanism Chrome provides
   for extensions to remember user preferences between sessions. If you are
   signed in to Chrome with sync enabled, Chrome may synchronize these
   preferences across your own devices; this is handled entirely by Google
   Chrome, not by Crunchyrank, and the extension author never has access to
   this data.

2. **Publicly visible rating data on pages you are already viewing.** When you
   load a page on crunchyroll.com, the extension reads the star rating and
   vote count that Crunchyroll itself already displays on each anime card,
   in order to decide whether to hide, dim, reorder, or badge that card. This
   reading happens locally in your browser. The data is never stored, logged,
   or transmitted anywhere.

## What data the extension does NOT collect

- No personal information (name, email, account, IP address, etc.)
- No browsing history
- No watch history, queue, or any Crunchyroll account data
- No cookies or authentication tokens
- No analytics or usage statistics
- No crash reports or telemetry

## Permissions and why they are needed

- **`storage`** — used only to save your filter preferences locally so they
  persist between sessions.
- **Host access to `crunchyroll.com`** — required so the extension can read
  the rating numbers that Crunchyroll already shows on anime cards and
  adjust the visibility or order of those cards on the page.

These permissions are used solely for the single purpose described above.

## Third parties

The extension does not communicate with any third-party service. It does not
load any remote code, fonts, images, or scripts.

## Changes to this policy

If the extension's data practices ever change, this document will be updated
and the "Last updated" date at the top will reflect the change. Any material
change will also be noted in the extension's store listing.

## Contact

For questions about this policy or the extension, please open an issue on the
project's GitHub repository, or contact: fabien.boco@gmail.com
