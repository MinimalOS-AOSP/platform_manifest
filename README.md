Minimal OS
===========
Minimal and Snappy 

Getting Started
---------------
To get started with the Minimal sources, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/version-control.html).


Create the Directories
----------------------

You will need to set up some directories in your build environment.

To create them run:

    mkdir -p ~/bin
    mkdir -p ~/minimal


Install the Repository
----------------------

Enter the following to download the "repo" binary and make it executable:

    curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo && chmod a+x ~/bin/repo

You may need to reboot for these changes to take effect. 
Now enter the following to initialize the repository:

    cd ~/minimal


Repositories:
---------------

For initializing repo use:

    repo init -u https://github.com/MinimalOS-AOSP/platform_manifest.git -b mr1


sync repo:

    repo sync -j$(# of CPUs x2)

Happy Compiling!
===========
