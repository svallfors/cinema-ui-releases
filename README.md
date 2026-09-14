# Cinema UI

Cinematic teaser videos from Figma frames. A Mac app and a Figma plugin.

**[Download the latest release →](https://github.com/svallfors/cinema-ui-releases/releases/latest)**

## Install

1. Open the `.dmg` and drag **Cinema UI** to Applications. It is signed and notarized, so it opens like any other Mac app.
2. Open Cinema UI once.
3. In Figma: **Plugins → Development → Import plugin from manifest…** and pick `manifest.json` from the plugin folder in the release (`cinema-ui-figma-plugin.zip`, unzipped).

Cinema UI runs on Apple silicon Macs with macOS 14 or later.

## How it works

1. Select one or more frames in Figma. Each becomes a scene, left to right.
2. Run **Plugins → Cinema UI**. The plugin opens the Mac app if it is not running, shows the frames it will send, and asks whether to create a new project or update the one these frames already belong to.
3. In Cinema UI, pick a camera pose, press space to play, and export an MP4.

### Make layers fly

Start a layer's name with `@` in Figma and it lifts off the background as its own animated layer. A digit right after the tag pins its entrance order (`@1`, `@2`, `@3`); the rest stagger top to bottom. Text layers get a little extra. Everything untagged stays in the backdrop.

Video fills ride along as posters. Drop the source file on the Cinema UI window to play it.

## Feedback

Something broke, or something is missing? [Open an issue](https://github.com/svallfors/cinema-ui-releases/issues/new). In the app, **Help → Report a Problem…** prefills one with your versions, and **Help → Export Project for Debugging…** makes a zip you can attach.
