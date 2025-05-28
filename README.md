# DigitalFish homebrew-tap

Customized homebrew packages for convenience.

## cmake@3 

This is a fork of the last of the cmake 3.x series formulas before the
homebrew community moved forward to cmake 4.

Uninstall cmake if you have it installed already, to allow linking our formula:

    brew uninstall cmake

Install. There are no pre-built “bottles” here; the formula builds from source.

    brew tap digitalfish/tap
    brew install digitalfish/tap/cmake@3

Use

    $ cmake -version
    cmake version 3.31.6

    CMake suite maintained and supported by Kitware (kitware.com/cmake).
