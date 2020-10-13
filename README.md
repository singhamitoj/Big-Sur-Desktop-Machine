# Big-Sur-Desktop-Machine
Transform your desktop into a lovely big sur theme.
To use this tool, make sure you have git installed. If you don't have it, just type in a terminal (for debian-based distros only):
sudo apt install git
Once you have git installed, you need to find a place on your disk to put the files. When you are ready, type:
git clone https://github.com/singhamitoj/Big-Sur-Desktop-Machine.git
This will clone all the needed files.
Next, cd into the folder. After you have done this, you can type:
./theme.sh
This will run the script, and you just have to wait for a little bit. It should not take long.
Things get different after this script is run. Use the tweak tool of your choice (eg. Gnome-tweaks, elementary tweaks, etc.) and choose the themes.
This tool will change your:
- Cursor
- Icons
- Wingpanel (Pantheon desktop only)
- Plank (If you have it installed)
- Window border
Even though the script automated the process, there is still some more configuration to do.
One thing you have to do is change the wallpaper (optional). This differs by distro. You can pick the light or dark wallpaper.
You need to add a startup script to play the silicon mac startup chime (I used mpg123). Again, this differs by the distro you are using.
For users using elementary os, you will need to install the desktop folder app. This will allow you to put files, folders and more on your desktop.
Lastly, you need to log out and log back in. This will allow the changes to the wingpanel to take effect.
Now, we will look at how this has changed your desktop.
First, let us take a look at the cursor. It looks the the macOS cursor, but the behavior has not changed.
Now, we will look at the icons. You will have a choice of a macOS icon theme and the Papirus icon theme. Some icons will be untouched and will look the same.
The window border will look like macOS, but the spacing between each button is not correct, though in some cases (like Chrome) the icons will be less apart from each other.
The plank dock will look kind of dark, but I for one do not care. Putting the files app (which now looks like the finder) on the beginning of the dock.
Lastly, the wingpanel. If you are a user who enjoys the pantheon desktop, then you will notice that the wingpanel (the top bar) will become black when a window is maximized. Well, with some file editing, I made the wingpanel transparent, even when a window is maximized.
# Important Notes
This is not guaranteed to work on all systems! If you find a problem, please report it in the issues section.
This repository is a work in progress! if you find any missing files, that means this is not yet done. This line will be removed once I am done.

Happy tweaking!
