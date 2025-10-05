This is Matar's code for Saxii2 but with the relevant files organized and slightly modified to fix installation issues.

Changes:
1. Installation.py is no longer needed.
2. Instead, use the new requirements.txt that contains all dependencies.

IMPORTANT:

Run the code from terminal directly and NOT from PyCharm/VS Code/etc...
Clone this repo to your computer and follow this guide to open a terminal in that folder:
https://www.lifewire.com/open-command-prompt-in-folder-8681085


---------------------------------------------
First time running:

pip install -r requirements.txt

or

pip3 install -r requirements.txt


If pip or pip3 are not recognized, you need to add pip to PATH (then reopen terminal and try again):
https://superuser.com/a/1560330


---------------------------------------------
To run the main code, use:

python main.py

or

python3 main.py


---------------------------------------------
Common first time issues:

1. if it opens microsoft store, search in windows search bar 'Manage app execution aliases' and turn off python.exe and python3.exe aliases.

2. if it says 'Python was not found; run without arguments to install from the Microsoft Store, or disable this shortcut from Settings > Manage App Execution Aliases.', search in windows search bar 'Manage app execution aliases' and turn off python.exe and python3.exe aliases.

3. if python and python3 follow https://superuser.com/a/1560330 to add python to path but this time remove /Scripts from the path, so like in their example:
 C:\Users\neubert\AppData\Local\Programs\Python\Python38\Scripts
is now
 C:\Users\neubert\AppData\Local\Programs\Python\Python38

NOTE, both
 C:\Users\neubert\AppData\Local\Programs\Python\Python38\Scripts
AND
 C:\Users\neubert\AppData\Local\Programs\Python\Python38
SHOULD BE IN YOUR PATH! Reopen terminal for it to update!
