## Git Submodules Cheat Sheet

The config file is ``.gitmodules``

#### Add submodule
    git submodule add git://github.com/me/module.git directory
    git status

### Get Repository with Submodules
    git clone git://github.com/schacon/myproject.git
    git submodule init
    git submodule update

### Remove submodule 
    git submodule deinit -f -- directoryOrName
    rm -rf .git/modules/directoryOrName
    git rm –cached directory

Remove related rows from .gitmodules

    ``vim .gitmodules``
