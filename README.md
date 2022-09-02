# spotify-api-plusplus

A C++ wrapper for the Spotify Web API.

## Building

First, install necessary dependencies, if you don't already have them.

    sudo apt-get install cmake
    sudo apt-get install libcurl4-openssl-dev

Clone the repository

    git clone https://github.com/smaltby/spotify-api-plusplus.git

Initialize submodules

    cd spotify-api-plusplus
    git submodule update --init --recursive

And finally, build using CMake

    mkdir build
    cd build
    cmake ..
    make
