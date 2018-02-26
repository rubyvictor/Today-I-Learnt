## NPM
**Node package manager is a Command line interface (CLI) for installing packages otherwise known as libraries or dependencies.**

`YARN` is better than `NPM` because it is:
* Faster. `YARN` caches every package it downloads.
* More secure. `YARN` uses checksums to verify the integrity of each installed package before its code is executed.
* Performs version locking. `YARN` guarantees that an install which worked on one system will work on any other system.

    ##  How to install `YARN`
        mac: `brew install yarn`
        windows: `choco install yarn`
    ## Key  `YARN` commands
    ## Create a package.json file
        yarn init

    ## Add a package locally
        yarn add <package-name>

    ## Add a package globally (i.e. at system level)
        yarn global add <package-name>

    ## Remove a package locally
        yarn remove <package-name>

    ## Remove a package globally
        yarn global remove <package-name>
