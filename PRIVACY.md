# Lummn privacy policy

_Last updated: 19 November 2026_

Lummn doesn't collect any data. It has no accounts of its own, no analytics, no advertising and
no tracking, and it contains no third-party code that collects data.

## Your Immich server

Lummn talks only to the Immich server whose address you enter. Your sign-in details, photos,
videos and their metadata go directly between your device and that server, which you or your
server's administrator run. The developer of Lummn never receives any of it.

## On your device

- **Session:** after you sign in, the server address and the session token from your server are
  kept on the device. The token is stored in the system keychain (in the Mac version downloaded
  outside the App Store, in the app's sandboxed storage). Your password is not stored.
- **Library cache:** Lummn keeps a local copy of your library's details and thumbnails so it opens
  quickly. Signing out deletes it; deleting the app removes everything Lummn stored.
- **Photo library:** with your permission, Lummn shows the photos on your device and backs up the
  ones you choose to your Immich server. Nothing is sent anywhere else.
- **Local network:** with your permission, Lummn looks for Immich servers on your network to fill
  in the server address for you.

## Updates on the Mac

The Mac version downloaded outside the App Store checks `api.magicsk.eu` for updates. That request
carries only what any web request does (your IP address and the app's version) and is used only to
offer the update. The App Store versions update through the App Store and make no such request.

## Contact

Questions about privacy: [open an issue](https://github.com/magicsk/Lummn-issues/issues/new).
Changes to this policy are published here, with the date above updated.
