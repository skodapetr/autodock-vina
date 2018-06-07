# autodock-vina
Rork of autodock vina, from http://vina.scripps.edu/.

## Depedencies
*  [Boost 1.67](https://www.boost.org/doc/libs/1_67_0/) 

## Installation

### Windows (Visual Studio 2017)
 * Download and unpack Boost into `dependencies/boost_1_67_0`
 * Start `x64 Native Tools Command Prompt for VS 2017`
 * cd into `dependencies/boost_1_67_0`
 * run `bootstrap.bat`
 * run `b2 -a -j8 address-model=64 architecture=x86`
 * open Visual Studio solution (`autodock-vina.sln`) in `build/windows/`
 * build `vina` or `vina-split` project

## Change log
 * Fix issue with hardcoded limit on generated models
