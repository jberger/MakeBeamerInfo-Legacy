

# Installation Instructions #

Follow the directions for your platform.

Note: I run Ubuntu Linux and my information will always be most accurate for this platform. If you are using this software on other platforms, please contact me regarding your experience.

## Linux (Ubuntu) ##

### Installing Requirements ###

First you need to install perl, either in Synaptic Package Manager or via command line with

```
sudo apt-get install perl
```

Further if you do not have Impress!ve you can install it, again via Synaptic or command line

```
sudo apt-get install impressive
```

If you need to install LaTeX, you can use these package managers (which is an outdated version) or (recommended) get it from http://www.tug.org/texlive/acquire.html or http://miktex.org/

### Installing the Script ###

Install for only yourself or system-wide (for all users)

#### Installing for Yourself ####

The script will run from any location however it will be easier if it is in your path. Many of the folders in your path are write protected but a folder named `bin` in your home folder (i.e. `/home/username/bin/`) will automatically be part of your path. Therefore this is the recommended location if you are going to be the only user.

Check that the folder exists and if it doesn't create it either in your home folder window or in the command prompt with

```
mkdir ~/bin
```

Next, move the script into the `bin` folder by dragging it in or command prompt
```
cp makebeamerinfo ~/bin
```

Next, make sure the script is executable by typing (assuming you are in the folder that you copied makebeamerinfo into)

```
chmod +x ~/makebeamerinfo
```

#### Installing for All Users ####

If you want to install it for all the users, you will need `sudo` privileges.

Move it into the system path with

```
sudo cp makebeamerinfo /usr/bin
```

Next, make sure the script is executable by typing (assuming you are in the folder that you copied makebeamerinfo into)

```
sudo chmod +x /usr/bin/makebeamerinfo
```

# Usage #

Now that you are ready to go visit the [Usage](Usage.md) page for instruction on using makebeamerinfo.