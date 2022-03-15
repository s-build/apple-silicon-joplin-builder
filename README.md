# silicon-joplin-builder
A mac arm64 builder for joplin desktop

## “Joplin” is damaged and can’t be opened. You should move it to the Trash.

Look into https://developer.apple.com/documentation/macos-release-notes/macos-big-sur-11_0_1-universal-apps-release-notes/ and electron-userland#5850.
use `sudo xattr -r -d com.apple.quarantine Joplin.app` to open the app.
the arm64 show you dmg is Damaged, move to trashTo install img files. Try running sudo xattr -r -d com.apple.quarantine something.app for your built app.
