<p align="center"><img src="icon.png" width="128" alt="Undertone icon"></p>

<h1 align="center">Undertone</h1>

<p align="center">Per-app volume control for your Mac's menu bar.</p>

<p align="center"><a href="https://github.com/SkirnirStudios/Undertone/releases/latest"><b>⬇︎ Download the latest version</b></a></p>

---

macOS has one volume slider for everything. Undertone gives every app its own.

- **Per-app volume** from 0 to 200%, plus mute
- **Per-app output**: music on the speakers, calls in your AirPods
- **Calls and voice chat**: other apps fade down while you're on a call, or, for voice chat like Discord, only while someone is actually talking
- **Volume limits**: cap how loud each output can get; the volume keys stop there, and app boosts stay under it
- **Protection from sudden loud sounds**: for the apps you choose, a notification after silence or a bang in a quiet scene eases in instead of hitting at full force
- **Balance and mono** for each app, including playing an app entirely in your left or right ear
- **Microphone mute** from anywhere with ⌃⌥⌘0, with a red menu bar icon while you're muted
- **Keyboard control**: ⌃⌥⌘U opens Undertone, the arrow keys choose an app and set its volume, and ⌃⌥⌘↑ / ⌃⌥⌘↓ / ⌃⌥⌘M change the app that's playing from anywhere
- **Works with VoiceOver**: every control is labeled, and each app's actions are in the Actions rotor
- Smooth fades, live level meters, and a soft limiter so boosted audio stays clean
- Automatic updates

Apps you leave at 100% aren't touched at all, so they get no added delay. And when nothing is playing, Undertone lets your speakers or headphones sleep, so AirPods can still switch to your iPhone.

## Install

1. Download the `.dmg` from the [latest release](https://github.com/SkirnirStudios/Undertone/releases/latest) and drag **Undertone** to **Applications**. Or, with [Homebrew](https://brew.sh):
   ```bash
   brew install --cask skirnirstudios/tap/undertone
   ```
2. Open it. Undertone lives in the menu bar (the slider icon), not the Dock, and opens its menu the first time to show you around.
3. Click **Allow Access** when asked. macOS calls this *System Audio Recording*: it's how Undertone passes an app's sound through its volume control. Nothing is recorded, saved or sent anywhere. While Undertone adjusts an app that's playing, macOS shows a purple dot in the menu bar; it goes out a few seconds after the sound stops.

Requires macOS 14.2 (Sonoma) or later, on Apple silicon or Intel. Undertone is signed and notarized by Apple.

## Privacy

Undertone doesn't collect any data. The only time it goes online is to check this page for updates, which you can turn off in its settings menu.

## Uninstall

Choose **Quit Undertone** from its settings menu (the gear), then drag it from Applications to the Trash. If you installed it with Homebrew, run `brew uninstall --cask undertone` instead.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/SkirnirStudios/Undertone/issues).

---

<p align="center">Made by <a href="https://www.skirnirstudios.com">Skirnir Studios</a></p>
