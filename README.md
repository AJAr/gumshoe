Gumshoe
=======

Gumshoe is a Chrome extension for discreet password logging. It monitors
the submission of all forms with a password field and stores any unique
login details in a local database.


Installation
-----------

~~This thing's actually on the [Chrome Web Store](http://goo.gl/z8SIH).
Can you believe it?~~

This extension has been on the Chrome Web Store for three years. Can you believe it?
In order to manually install this extension you need to:
* Fork repository
* Open Extension tab in Your Chrome browser [by clicking here](chrome://extensions/)
* Turn on "Developer Mode"
* Click "Load Unpacked" and locate extension directory
* Click "Open"

Congrats, you DID it =)



Getting Started
---------------

Once installed, typing `gselog` anywhere should reveal the log management
page. From here, you can search for records, delete those records, and
change `gselog` to something more creative.

Provided that the extension is enabled and the user/password pair has not
previously been recorded, login attempts to most (semantically correct)
websites should be available for review through the log management page
(see above).


Screenshot
----------

![Gumshoe for Chrome (Windows 7)](http://i.imgur.com/1xyDl.png)


FAQ
---

**Aren't keyloggers scary and malicious?**

You could call it a keylogger, but 3 out of 4 pedants agree that it logs
form submissions, not keystrokes. (It monitors strokes as it listens for
the passcode, but they aren't recorded.)

**Right, but couldn't _you_ steal _my_ passwords?**

No. All data is stored locally using Web SQL; Gumshoe never communicates
with another machine.


Disclaimer
----------

Gumshoe doesn't hurt users; users hurt users.
