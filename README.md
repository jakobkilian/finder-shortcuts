I wanted to create md files in macOS Finder with one click and ended up creating multiple little buttons for my Finder task bar that I would like to share:

![preview](preview.jpg)

- create-local-note: **Create New Markdown File**
- get-path: **Get Path / Link to Selected File**
- goto-obsidian: **Go To / Create Obsidian Note with Folder Name**
- compress-pdfs: **Compresses Selected PDFs**

## Install & Use

All helper buttons are essentially macOS Apps, created with the built in [script editor](https://support.apple.com/guide/script-editor/scpedt1072/2.11/mac/15.0) using Apple Script. There are other ways to use them (e.g. services triggered by shortcuts), but I suggest:

1. Download files and place the .app file somewhere on your computer (e.g. `/Applications/Tools`). Do either of these:
   1. Use the .app file provided by me. This needs [unblocking in system settings](https://support.apple.com/guide/mac-help/mh40616/mac)
   2. Use the .script file to create your own .app in [script editor](https://support.apple.com/guide/script-editor/scpedt1072/2.11/mac/15.0)
2. Right click on the Finder toolbar, select `Customize Toolbar`
3. Drag and drop the just created .app file
  **Usage**
4. Click on the icon, while using Finder... 💥

## Icon

If you want to change the icon, open the .app with right-click → show contents and replace the .icns file under "Contents" → "Resources"

## Edit & Adapt

The helpers are tailored to my needs (e.g. the .md files get a date stamp in the YYMMDD format), but can easily edited and adapted to your needs!

Simply **open the .app with the script editor** or use the **Apple Script file to create your own app or workflow** and proceed with install step 2.

## License & Sharing

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This work is dedicated to the public domain under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

I am happy to link your creations here, send them over!



