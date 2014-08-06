I am not maintaining for PAC-man.  This is proof of concept only

    repo init -u git://github.com/CJDubbsy/pacman-serranolteusc.git -b pac-4.4
    repo sync

Then to build:

    ./build-pac.sh serranolteusc

For a list of supported commands run the script on it's own:

    ./build-pac.sh

To build with flags, this is the layout needed:
    ./build-pac.sh <Optional_flags> <device codename>

For an o3 optimization and Dex optimisations -if you don't understand, best to leave it:

    ./build-pac.sh -o3 -d serranolteusc

You can also add a -j# before device_code_name for a selected number of jobs, usually No. of cores + 1 or 2
