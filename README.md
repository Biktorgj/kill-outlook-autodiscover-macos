# kill-outlook-autodiscover-macos
Script to stop Outlook 2016 to keep asking for password in Exchange accounts

Outlook 16.12 introduced a new feature where if you have an on premise Exchange 2016 account, it will randomly kick you out of it and ask for a password. If you randomly get a prompt asking you for your exchange password, and you press No, and then hit Send and receive and it reconnects, you might want to try this script to temporarily solve the issue

If you run the AppleScript file called OutlookOSX_KillAutodiscover, it will iterate through all your exchange accounts and disable Autodiscover in all of them.

If, sometime from now (maybe a year or ten), Microsoft decides to fix their software and you want to enable autodiscover again, you can run OutlookOSX_Enable_Autodiscover and it will undo everything the other script did
