
# gnome-screenshot-ocr

A Gnome Shell extension that passes screenshots through an OCR engine and places the text on the clipboard. 

[<img src="https://raw.githubusercontent.com/andyholmes/gnome-shell-extensions-badge/master/get-it-on-ego.svg?sanitize=true" height="100">](https://extensions.gnome.org/extension/9338/screenshot-ocr/)


# Usage

To use, simply use the print screen key (or whatever shortcut currently takes screenshots). 

<img width="431" height="235" alt="image" src="https://github.com/user-attachments/assets/596cf1d9-6407-455c-b3b8-d4b41df9a9d0" />

Select the "<>" icon, and any text appearing in the image and detected by the OCR will be copied onto the clipboard.

To disable / enable languages and determine their OCR priority, you can edit the settings using the extension manager.

<img width="690" height="626" alt="image" src="https://github.com/user-attachments/assets/e12e609b-f80d-4fa6-985a-30ed2196227b" />

# Installation

Requires tesseract, which may be installed via `sudo apt install tesseract-ocr libtesseract-dev`

May be installed by running `gnome-extensions install --force screenshot-ocr.zip`

