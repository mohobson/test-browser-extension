# Browser Extension Template

This browser extension serves as a basic template for creating browser extensions. It is derived from the [Google Chrome extension tutorial](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world).

## Introduction

This browser extension template consists of an HTML file, a JavaScript file, and a manifest file, which together create a basic extension that displays a popup with the message "Hello Extensions".

## Usage

To use this template for your own extension development, follow these steps:

1. Clone or download this repository.
2. Modify the files to suit your extension's functionality and appearance:
   - `hello.html`: Customize the HTML content of your extension's popup.
   - `popup.js`: Add JavaScript logic as needed for your extension.
   - `manifest.json`: Update the manifest file with your extension's name, description, version, and any additional permissions or settings required.

3. Load the extension in your browser:
    - For Google Chrome:
        1. Open the Extension Management page by navigating to `chrome://extensions`.
        2. Enable Developer Mode by clicking the toggle switch next to "Developer mode".
        3. Click the "Load unpacked" button and select the directory containing the cloned/downloaded files.

4. Once the extension is loaded, click on its icon in the browser toolbar to see the popup with the message "Hello Extensions".

## Files

- `hello.html`: This HTML file contains the basic structure for the extension popup.
- `popup.js`: This JavaScript file contains the logic to display the popup message.
- `manifest.json`: This manifest file defines the extension's metadata and settings, including its name, description, version, and default popup.

## Icon

The extension icon is provided in the file `browser-ext-wheel.png`. You can replace this with your own icon by modifying the `default_icon` property in the `manifest.json` file to point to your desired icon file.

