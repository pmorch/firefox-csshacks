## My Use of firefox-csshacks

This is just a tiny wrapper around
https://github.com/MrOtherGuy/firefox-csshacks
that allows me to have multiple tab rows in firefox.

Remember after checkout:

    git submodule update --init

And go to about:config and set:

    toolkit.legacyUserProfileCustomizations.stylesheets

to `true`.

If you need to find the profile folder, it is

    /home/peter/.mozilla/firefox/*.default

on linux and

    C:\Users\pvm\AppData\Roaming\Mozilla\Firefox\Profiles\*.default-release

on Windows. You can find the folder by opening `about:support`, finding
"Profile Folder" and then clicking on "Open Folder".
