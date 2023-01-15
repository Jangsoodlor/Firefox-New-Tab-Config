# Firefox Startpage Config
 Set Firefox Default Startpage without additional 
 Here's How

## 1. Find your Firefox installation directory

Go to [about:support](about:support) . In the "Application Binary" section (highlighted below) is where your Firefox directory is.

![img1](pic/appbin.png)

Then, open the directory

![img2](pic/dir.png)

You need to create 2 files. Namely `autoconfig.js` in `defaults/pref` folder and `firefox.cfg` in the main directory.

## 2. Create autoconfig.js file
Then copy the code below

`pref("general.config.filename", "librewolf.cfg");
pref("general.config.obscure_value", 0);`

