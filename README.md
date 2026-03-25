# Linux Mint Windows 12 Like Panel Theme

## Replace cinnamon.css file of your theme with following cinnamon.css file below

Before you replace the cinnamon.css file make a copy of your cinnamon.css file first

<p>(<a href="cinnamon.css" download>Click here to download</a>)</p>

If download doesn't work, simply download the repo from code and select download zip and unzip and copy & replace cinnamon.css to your current active theme folder in Linux Mint.

# How to find active theme folder

## Theme folder is sometime hidden press CTRL + H to view hidden folders

First look into this folder /home/<YOUR_USER_NAME>/themes

In Linux, theme files are generally stored in one of two primary directories, depending on whether they are installed for all users or a single user. 
System-wide themes (all users): /usr/share/themes/
User-specific themes (hidden folder in your home directory): ~/.themes/ (or occasionally ~/.local/share/themes/) 
The specific active theme is not defined by a single folder location but rather by a configuration setting managed by your desktop environment (e.g., GNOME, KDE, XFCE, Cinnamon). 
How to Find the Active Theme
You can typically determine and change the active theme using the graphical settings application provided by your desktop environment. 
Alternatively, for GNOME-based systems, you can use the gsettings command in the terminal to find the currently used GTK theme name: 
bash
gsettings get org.gnome.desktop.interface gtk-theme
This command will output the name of the active theme (e.g., "Adwaita", "Mint-Y-Dark"), which you can then locate within one of the directories mentioned above. 
Notes
The ~/.themes folder is a hidden directory. To view it in your file manager, you typically need to enable "Show Hidden Files" (often done by pressing Ctrl+H).
It is generally recommended to install custom themes in your local ~/.themes directory. Editing system-wide themes in /usr/share/themes/ requires root permissions and changes may be overwritten during a system update. 
