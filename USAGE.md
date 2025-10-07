# USAGE

- This fork is a modified extension based on my preferences
- Tested on Firefox
- Check [Releases](https://github.com/VMPYRC/wayback-machine-webextension/releases) for changes

## Installing the Latest Build from Source

(From the [README](README.md))

First tap on the **Code** button of this repo, **Download ZIP**, unzip the file in a location where you can find on your computer, then follow the steps below for your browser.

Alternatively, get it from [Releases](https://github.com/VMPYRC/wayback-machine-webextension/releases)

<img width="40px" align="left" src="webextension/images/about/chrome64.png">

### Chrome

1. Open Chrome and navigate to `chrome://extensions` in your browser. You can also access this page by clicking on the 3 vertical dots menu on the top-right, hovering over **More Tools**, then selecting **Extensions**.
2. Turn on the switch next to **Developer mode**.
3. Click the **Load unpacked** button and select the `wayback-machine-webextension/webextension` directory that contains this code.
4. Click on the _Extensions_ puzzle-like icon in the toolbar.
5. Now click on the **Pin** icon next to _Wayback Machine_ to pin it.
6. Click on the newly added icon.
7. Read the terms, then _Accept and Enable_. Click on the icon again to use the extension.

See [What are extensions?](https://developer.chrome.com/extensions) for more information on Chrome extensions.

<img width="40px" align="left" src="webextension/images/about/edge64.png">

### Edge

1. Open Edge and navigate to `edge://extensions` in your browser. You can also access this page by clicking on the 3 horizontal dots menu on the top-right, then clicking **Extensions**.
2. Turn on the switch next to **Developer mode**.
3. Click the **Load unpacked** button and select the `wayback-machine-webextension/webextension` directory that contains this code.
4. Click on the newly added icon in the toolbar.
5. Read the terms, then _Accept and Enable_. Click on the icon again to use the extension.

<img width="40px" align="left" src="webextension/images/about/firefox64.png">

### Firefox

1. Open Firefox and navigate to `about:debugging` in the browser. You can also access this page by clicking on the hamburger menu on the top-right, select **Add-ons**, then the **Gear Tools button** on the top-right, then **Debug Add-ons**.
2. Click **This Firefox** on the left.
3. Click **Load Temporary Add-on...**
4. Open the `wayback-machine-webextension/webextension` directory and select any file.
5. Click on the newly added icon in the toolbar.
6. Read the terms, then _Accept and Enable_. Click on the icon again to use the extension.

See [Temporary installation in Firefox](https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/) for more information on Firefox extensions.

<img width="40px" align="left" src="webextension/images/about/safari64.png">

### Safari 14+

This will require Xcode to compile from source.

1. Open Safari.
   - If Develop menu is hidden, go to Preferences > Advanced > check "Show Develop menu in menu bar".
   - Then Develop menu > Allow Unsigned Extensions (enter password).
2. Open the project file `safari/Wayback Machine.xcodeproj` in Xcode. Click Play to run.
3. Follow directions in splash window:
   - Safari menu > Preferences > Extensions tab.
   - Check to activate Wayback Machine.
   - Select "Always Allow on Every Website..." button and confirm.
4. Click on the newly added icon in the toolbar.
5. Read the terms, then _Accept and Enable_. Click on the icon again to use the extension.
