# Mint-Help Scripts

These scripts are a variation of the single-line commands contained in
[Two-Dog's Repo] (https://github.com/two-dogs/the-kennel).  They're
still primarily his (and any other contributor's work), I've just added
script wrappers around their functions, and updated some things to
conform to more current "standards" for scripts.

### OPERATION

Download the package, and run the _minthelp_ script.  This is the main
menu for program operation, and will handle execution of all other
scripts.

### ROOT ACCESS

The menu requires elevated (i.e. root) permissions to update inxi and
the pci id list.  Once these operations are completed, the remainder of
the program will execute as your currently logged in user.  

The "Drives" and "Sound" options have some features that require
elevated permissions.  However, you can successfully run these two
sections without permitting root execution -- it just means that the
section(s) of those scripts that need elevated permissions will be
skipped over.

The "Used Space" option requires root permissions for basic execution,
and cannot be run without allowing this -- a non-privileged user simply
cannot obtain the usage information for enough locations on the drive in
order to paint an accurate picture of the utilization when not knowing
the source of the drive's space issues.
