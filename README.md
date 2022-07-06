# Building a chrome extension

## Description
#### This extension changes the backgroundColor of the body element of the current page 

### This follows the [official chrome extension tutorial](https://developer.chrome.com/docs/extensions/mv3/getstarted/).

### Key takeaways

-    every chrome extension needs a `manifest.json` file
-    chrome provides APIs for accessing various functionalities like accessing tabs, storage, etc (and some really cool ones too). [Check here for a list of available APIs](https://developer.chrome.com/docs/extensions/reference/)
-    most of these APIs require that you specify the permission to use them in the `manifest.json` file

### How to install the chrome extension (Running the project locally)
-    clone the repo `git clone https://github.com/MikeyOnyedika/build-a-chrome-extension.git
-    open chrome browser
-    go to More Tools > Extensions from the menu
-    click the `Developer Mode` button to enable it
-    from the extra buttons that pop up, click the `load unpacked` button (this opens a file chooser dialog)
-    from the file chooser dialog, navigate to where the cloned repo is and select the folder
-    you will now have the extension included in your browser
