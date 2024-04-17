# build-your-first-website-challenge
This repo contains a challenge that allows the reader to practice html &amp; CSS.

Welcome to the website building challenge.

You have been picked to create the website for an exciting new ai startup.

## Prerequisite

- Visual Studio Code (VSC)
- Live Server extension


Clone this repository into your Visual Studio Code instance.
This guide assumes that you are using VSC, but any editor will work.


## Viewing the files

The files of the repo are visible in the explorer area of your editor.
This section is visible on the lefthand side of the screen by default.

If you don't see the explorer area, try activating the explorer:
- click the top left icon called Explorer 
- use the shortcut shift+cmd+e

## Folder structure

- The example styles are located in the "styles" directory.
- The example html files are located in the "examples" directory.
- You will be working at the top level of the directory, commonly referred to as the root.

## set up dev server

We will use an extension called Live Server to enable a feature called live reloading.
Live reloading reloads or refreshes the entire app when a file changes. For example, if you were four links deep into your navigation and saved a change, live reloading would restart the app and load the app back to the initial route.

Feel free to skip this step if you already have the extension.

## Add Live Server

- open the Extensions Marketplace by clicking the icon depicting four boxes (lowest top left by default) or using the shortcut shift+cmd+x
- this feature allows most of our code edits to be visibile directly in the browser.
- some changes, like editing references to external files, can cause the server to lose track of the changes.
- if this happens, restart the server.

## Add a new file
- bring your cursor above the root area of the explorer
- right click in the explorer area to open the context menu
- click new file
- enter the file name: index.html
- double click the file to open it in its own window

## Add the basic html structure

- we will use a handy shortcut that is available by default in VSC
- make sure your blinking cursor is at the top of the page
- write a single exclamation mark: !
- press the TAB key on your keyboard (above caps-lock on my keyboard layout)
- enjoy a sip of your coffe while the shortcut does the hard work
- save your work by pressing cmd+s or by navigating the top menu: File > Save.

If the command was successfull, your file should contain the following structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```


## 