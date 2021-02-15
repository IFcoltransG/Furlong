# Furlong Text
A bookmarklet-based text editor, for your convenience.

#### Features
* Accessible from your browser with a simple bookmark
* Loads in an instant
* Save button is large and easy to click
* Persistent when you reload
* Edited pages are also bookmarkable
* Native spellchecking

The basics
---
#### Why is it in HTML?
Notepad may be useful, but it doesn't nestle snugly among your tabs.

#### Why is it a data url?
By encoding the entire page in the URL itself (even the favicon image!) Furlong avoids making any web requests. It loads in a fraction of a second. Data urls start with `data:` rather than `https://` and don't need to connect you to any external website.

#### Why have you made so many 'fur' puns?
If you don't like them, consider forking the repo and replacing them with other puns.

#### Why have you done this?

How do I use it?
---

#### Installation
Open up [firefox.txt](https://raw.githubusercontent.com/IFcoltransG/Furlong/main/firefox.txt) or [chrome.txt](https://raw.githubusercontent.com/IFcoltransG/Furlong/main/chrome.txt) and copy and paste its contents into a your address bar. Bookmark it with a memorable name, and hey presto! (I'd link to them directly, but GitHub doesn't like urls that are 3.6 kilobytes long and full of special characters.)

#### Usage
Whenever you have something to jot down, click your handy-dandy bookmark. The page should load instantly, although if the title doesn't show at first, simply click on the big blank area to update it. Once you've written something worth remembering (and changed the title from the default) press the 'Save' button. Your work will download for you.

If you don't like local files, you can also bookmark the URL again. Everything you type is stored at the end of the URL, and will magically reappear when you reload or re-enter the updated URL. Whenever you press the Save button, what you've typed is added to the browser back-button history so that you can review past versions.

Unfortunately, data urls on Firefox are not saved to the history sidebar of every visited site, only the tab-specific history. On Chrome, data urls are saved to history, but with a new history event after almost every edit. For those reasons, I recommend only using the tab-specific back button in either browser, rather than the full history. 

Roadmap
---
Syntax Highlighting
Dark Mode
Button to update browser history without asking you to save the file
