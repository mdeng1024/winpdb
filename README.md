
# A *fork* of Winpdb - A GPL Python Debugger

* Original Author: Nir Aides
* Email:   nir@winpdb.org
* Website: http://www.winpdb.org/
* Base Version: 1.4.8



# Introduction
This is a fork of the original *Winpdb* project with some modification to get it working on OS X El Capitan with *Brew* installed *wxPython* library. For the detailed documentation and usage of *Winpdb*, please refer to the [Official site](http://winpdb.org/).
	
# Installation
*Winpdb* require *wxPython* to be installed to provide the GUI support. To install the *wxPython* on OS X, first install and setup the *Brew*. 

``` ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

Then run the following to install the *pthone* (if not installed) and *wxPython*:

``` 
brew install python
brew install wxpython 
```

Checkout the *winpdb* source code and change into the source location, run following to install:

``` sudo python setup.py install -f ```

# Quick Usage

    On Linux systems start the debugger from a console with:

        winpdb

    On Windows systems start the debugger with:

        %PYTHONHOME%\Scripts\winpdb

    Note that the Python interpreter must be in the PATH for this to work.

    Start the debugged script using:

        rpdb2 -d <script.py> arg1 arg2

    Then from the *winpdb* GUI menu select File -> Attach to attach to the running script to start debuging.



# Documentation

    Use the -h command-line flag for command-line help.

    Use the RPDB2 console 'help' command for detailed description of debugger 
    commands.

    Online documentation is available at:
    http://www.winpdb.org

	

