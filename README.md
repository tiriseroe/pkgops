# pkgops
Script to process text file list of packages on Ubuntu/Mint platforms

pkgops, version (1.0-7) A utility to process a list of packages.
  Usage :  pkgops option filename
  Option:  -c   apt-get check installed status of apps
           -i   apt-get install apps
           -l   print pkgops change log
           -m   dpkg    import apps (experimental)
           -p   apt-cache policy installed/candidate
           -r   apt-get remove apps (does not remove user configs)
           -R   apt-get remove apps with prejudice (removes user configs)
           -s   apt-get simulate install of apps 
           -x   dpkg    export apps 
           -z   dpkg fuzzy check installed status of apps
                Input file format (-c,-i,-s): one package per line. 
                Input file format (-m,-r,-R,-x): dpkg file format.
