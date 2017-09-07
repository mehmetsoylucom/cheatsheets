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
    git submodule rm directory
    git rm –cached directory
