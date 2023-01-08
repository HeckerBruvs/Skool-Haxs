# Skool-Haxs
Some nice bypassing tools to make school laptops more fun.

**NOT ALL HACKS WILL WORK ON ALL DEVICES!**

# Web Hacks
There are 2 chrome hacks to choose from, both of them being proxies.

## 1: Ultraviolet

Ultraviolet is the simplest and easiest proxy.
![image](https://user-images.githubusercontent.com/98992380/211188587-4dbe9c46-ba7d-4bd3-b342-8e821de924cc.png)
To install, go to https://replit.com, and search for "Ultraviolt", and fork one of the many repls. Then start the repl.

After this, highlight this code and drag to bookmarks, and replace 'YOUR LINK HERE' with the repl site link.

javascript: var win = window.open(); var url = 'YOUR LINK HERE'; var iframe = win.document.createElement(%27iframe%27); iframe.style="position:fixed;width:100vw;height:100vh;top:0px;left:0px;right:0px;bottom:0px;z-index:2147483647;background-color:white;border:none;"; iframe.src = url; win.document.body.appendChild(iframe);

Now you can open Ultraviolet from javascript supported sites.

## 2: Womginx

Womginx is a mix of Wombat and nginx proxies.

This is more advanced, so view the official repo for info. 
![image](https://user-images.githubusercontent.com/98992380/211189354-53e8c301-b440-4ade-b657-ffdb914031ba.png)
https://github.com/binary-person/womginx

# .EXE Hacks
.EXE hacks allow you to run alternate programs on your device that may have been blocked. For this we use what we call "Vix Hack" which uses inno and other methods. Not all programs work, and we will make a list of every program that we know works.

## Method #0, RunAsInvoker

This method forces admin, but is a very weak method. I/We personally have trouble getting this to work, but We might as well include it.

To start, Create a new folder. Create a new batch file, and name it "Start.bat". Right click this batch file, and edit it. Then paste this code in it:

set __COMPAT_LAYER=RunAsInvoker && start "Program.exe"

Replace "Program.exe" with an installer indside the directory of the batch file, then run the batch file.

## Method #1, Plain install.

This method only requires a .exe file, and will run! Not many programs run this way on School devices.

To do this, download the file, and run the installer, and your done!

Apps That work:

Gimp,

CMMM Plus+ (https://milenakos.itch.io/cmmm-plus-milenakos-mod)

## Method #2, inno method #1

This method requires innoextract, and we will leave a link to get that.

https://constexpr.org/innoextract/

Open this link, scroll down, and download "Windows Binaries". Extract the .ZIP to an easy location to access. Next, take your installer, and put it in the innoextract folder that you just unzipped. Then drag your installer onto the innoextract.exe file, and installation will start. Once you are done, you will have a new folder named "App", and you can run the file inside of that.

Apps that work:

Notepad++,

Sublime text editor,

Clone Hero,

Vim

## Method #3, inno method #2

This method requires innoextract, which we used in method #1.

Follow all the steps in method #1, but instead of dragging the installer onto innoextract.exe, drag innoextract.exe onto the installer. This will start the program instead of making an "App" folder.

Apps that work:

Discord (Better discord can be installed with this method too),

Minecraft (Note: You have to use lunar client instead of the Minecraft Launcher),

Firefox,

Opera GX,

Spotify,

Roblox,

Paradox Launcher

# More information will be added soon!
