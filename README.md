# Chrome HotKey Extension
A Chrome extension that trigers other extension via hotkeys.

For security reasons, extensions in Chrome cannot be triggered programatically, you need to phiscally click on them. This creates a major problem for purposes of web scrapping.

In our specific case, we want to perform a meta-analysis of the scientific literature, and thus want papers to be loaded directly into zotero on any given search. Since we have thousands of keywords to search, doing it manually is a no go.

Here we provide a chrome extension that allows calling an extension via a simulation of pressing the hot hotkeys taht call the given extension. The app loads automatically on any new page.


## Installation
> Download the folder **AutoLoadExt**, with all files in it.

> Install Host App
- Go into the folder **host_app**, inside the folder **AutoLoadExt** and run **native_host**
- Go into the folder **host_app**, inside the folder **AutoLoadExt** and double click on **install_host**
- Go to Chrome and **Open [the extensions page](chrome://extensions)** in your browser: `chrome://extensions`. 
- If you did not do it already, **toggle the "developer mode"**. This is usually a toggle button at the top right of the extensions page.
- Click the button **_load unpacked extension_**.
- In the window that pops up, **select the folder that contains this extension**, then **click _ok_**.
- Upom clicking on the app, you can manually set any hotkeys that trigger other extensions.
- **Done!**
This extension will be called automatically upon loading any future page, and simulate the pressing of hotkeys used to open any other extension.

To modify the hotkeys for the app you want to open, simpky press the Hotkeey extension, enter the set of keys that trigger the other extension, click save.

## About the project
Generally, chrome extensions cannot call or access other extensions.
Only self-developed extensions can communicate in the form of sending and receiving notifications.
To solve this problem, we used an auxiliary program that supports extension.
This cannot be realized with only general extension development technology and can be solved only with low-level technics such as operating system, Windows API, and C/C++.
## About the developer.
This project was not done by me, owner of this repository, but hire a developer to do it. If in interest for further develop it, contact him directly.
phone number: +381611114128

email: truebluedragon93@gmail.com

