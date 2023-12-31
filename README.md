# quickPassGenerator

Simple console-based tool to quickly generate a username and a password entry with just a few clicks.

Note: Only use it for your **insignificant and unimportant** accounts.

Usage:

- Run the source.py file:
   1. You will be asked to enter a name for your account/website. This name will also be used as the filename for the exported text file.
   You can leave it blank, in that case, a random filename with the following format will be generated: "blank<random digit 0 - 500>".\
   An entry containing account name/website (if provided), a username with "someUser<random digit 0 - 9999>, and a password with the following format will be generated for you.

        ``<4 random lowercase letters><4 random UpperCase letters><random 4 number digit 0 - 9999><4 random symbol character>``

   2. You will be asked if you want to export the entry as a text file. If choose yes, a text file containing the generated entry will be created right next to the source.py file.
