BILLY'S BIRTHDAY SURPRISE

FILES
- index.html : complete website
- billy.jpg  : Billy's photo (keep beside index.html)

TEST
1. Extract the folder if zipped.
2. Double-click index.html to open it in Chrome.
3. Click anywhere on the black screen.
4. Press F11 or Esc to test leaving full screen.

KIOSK STARTUP (Windows / Chrome)
1. Put the folder somewhere permanent, e.g. C:\Birthday\Billy.
2. Create a shortcut to Chrome.
3. In the shortcut Target field, add these arguments after chrome.exe:
   --kiosk "file:///C:/Birthday/Billy/index.html"
   Example:
   "C:\Program Files\Google\Chrome\Application\chrome.exe" --kiosk "file:///C:/Birthday/Billy/index.html"
4. Test the shortcut manually before adding it to Windows Startup.
5. Add the shortcut to shell:startup only after testing.

NOTES
- Keep index.html and billy.jpg in the same folder.
- Fullscreen is requested after the first click; kiosk mode itself is configured separately.
- Fireworks are drawn locally in JavaScript. No internet connection or external libraries are needed.
- The surprise does not play music, so there is no unexpected audio.
- If you want to exit kiosk mode during testing, use Alt+F4.
