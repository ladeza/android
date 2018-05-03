Repositories:
---------------

Before you continue --> run this in the terminal
----------------------------------------
    repo init -u https://github.com/ladeza/android.git -b cr-6.1 && repo sync -f

Building the System
---------------

    . build/envsetup.sh
    lunch

Enter the number of the build you want to start and press enter

Build the Code:

    make carbon -j8 (or as many threads your hardware can handle)

Submitting Patches
------------------
Patches are always welcome!  Please submit your patches via CarbonROM Gerrit!
You can do this by using these commands:

    (From root android directory)
    . build/envsetup.sh
    repo start cr-6.1 .
    (Make your changes and commit)
    repo upload .

