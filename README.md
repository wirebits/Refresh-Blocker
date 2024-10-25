# Refresh-Blocker
JS Code to stop reload webpages.

# How To
1. Open any browser.
2. Open any web page.
3. Open Developer Options by pressing `Ctrl + Shift + I`.
4. Click on `Console` tab.
5. Paste the following code snippet : <br>
```
setInterval(function() {
    window.location.reload();
    window.stop();
}, 1000);
```
6. Click Enter Key.
7. Close the Developer Options.
- Now when click on reload button on browser then it is disabled.
