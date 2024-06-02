# Another Online

Another simple, oneline, minimal, keyboard-centered Firefox CSS theme.

![Screenshot](ass/screenshot.png)

![Screenshot0](ass/screenshot2.png)

## Setup and installation
1. Clone this repository or download the `userChrome.css` file to your local machine
2. On Firefox, go to `about:config`, click *"Accept the Risk and Continue"* and enable `toolkit.legacyUserProfileCustomizations.stylesheets`
3. Go to `about:profiles`, locate your profile under *"This is the profile in use and it cannot be deleted"* and open the directory
4. On the profile directory folder, open (or create) the folder `chrome`
5. Copy the `userChrome.css` file to `chrome`
6. Restart the browser to apply the theme

## Customization

By default, all buttons and icons are hidden, except for the *"Application Menu"* (☰) button. This includes:
- The window control buttons (minimize, resize and close window)
- Backward and foward buttons
- Extensions button
- All tabs (⌄) button
- "This time search with..." when searching in the url
- ALL URL bar icons (permissons, bookmarks, extension icon, picture-in-picture, tracking protection, reader mode and translations)

You can change the visibility of elements in the `userChrome.css` file, just delete or comment out the lines or block for the ones you want to see.

```css
/* This is an ~example~ with code from the userChrome.css file */

/* Extensions button */
#unified-extensions-button {
  /* display: none !important /* Makes the Extensions button visible */
}

/* URL bar icons */
#identity-permission-box,
/* #star-button-box, /* Makes only the Bookmarks (star) icon visible */
#identity-icon-box,
#picture-in-picture-button,
#tracking-protection-icon-container,
#reader-mode-button,
#translations-button
{
  display: none !important
}
```

## Optional

You can use the [Adaptative Tab Bar Color](https://addons.mozilla.org/en-US/firefox/addon/adaptive-tab-bar-colour/) extension with the following settings:

![extension1](ass/screenshot-extension.png)
![extension2](ass/screenshot-extension2.png)

## Credits
This theme uses code snippets from [JarnotMaciej/Essence](https://github.com/JarnotMaciej/Essence) 👈 Thank you~~ 🤗 
