# activate-ditto
Script to activate [Ditto](https://ditto-cp.sourceforge.io/) when installed under [winehq](https://www.winehq.org/) (In my expirience Ditto require winehq > 7.0 to work).

## Installation 
Root or sudo permission is needed to install this package.

After install Ditto under Wine, go to "Options" then "Keyboard Shortcuts" and set in the field "Activate Ditto" the value "Control + \".

Then install this package with this command:

~~~bash
sudo dpkg -i activate-ditto_<version>-<revision>_all.deb
~~~

Last but not least create a global shortcut on your desktop manager that associate "Control+backslash" to the Command "activate-ditto".

Enjoy.



