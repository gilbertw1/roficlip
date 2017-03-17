# rofellite
A simple shell script that surfaces clipboard history from parcellite in Rofi

## Dependencies

- ```parcellite``` (forked version: https://github.com/gilbertw1/parcellite)
- ```xsel```

## Running

    > ./rofellite

## Install Forked Parcellite

    git clone git@github.com:gilbertw1/parcellite.git
    cd parcellite
    libtoolize --force
    aclocal
    autoheader
    automake --force-missing --add-missing
    autoconf
    sudo make install
