# New Tab Plus
So, as you may know if you are reading this, firefox's new tab page is VERY limited. This extension serves to take away a few of those limits by adding support for local html and css.

# Installation
I'm not going to lie and bullshit you. 
DO NOT DO THIS IF YOU ARE NOT COMFORTABLE WITH TURNING OFF FIREFOX'S DEFAULT SIGNATURE CHECKING. SERIOUSLY.

IF YOU ARE OKAY WITH TURNING IT OFF, go to about:config and search xpinstall.signatures.required and click it to make it say false. This allows you to install any extension that is not directly verified by firefox/mozilla. If you somehow (I'm being pretty step by step) mess this up or don't understand what this is doing, it is not my, or mozilla, or tabliss, or anyone elses fault other than your own. Even though it's not a major change, know your fucking browser before you directly edit the settings. Theres a warning for a reason.

To put this simply, download the repository as a zip and unpack it. Take whatever html/css/fonts and copy them into wherever the unpacked zip files are. Make sure your html is called index.html and zip it all back up and rename it "extensions@newtabplus.xpi" and blam-o there you go. Now all you have to do is go to firefox addons (aka about:addons) and click on the settings gear and add from file.

As a bonus, the icons folder holds four icons which you can change to whatever you want. Just keep the file names and image sizes. The defaults (pog) are there to make sure someone who doesn't care doesn't break everything (or whatever does happen, I'm not going to test it). 

To make this site your home page, go back to the add-ons/extensions page, and click the gear and debug extensions. Copy the manifest url, change the "manifest.json" to "index.html", and slap that bad boy into the homepage custom url, and there you go, customized home page and new tabs. 

Do remember, I am not a expert web dev and this may be buggy. I am running Firefox Developer Edition, and will test this on standard at a later date. Thank you for trying out my hate extension filed with spite for one of the most standard browser tools.

# Credit
Tabliss created all of the framework behind this, I just hacked it to fit my needs. I noticed tabliss managed to get their extension to modify the new tab page and just wanted to change a few things to get what I want. If something is broken, it's probably because I fucked it up to do something it was never supposed to do.
