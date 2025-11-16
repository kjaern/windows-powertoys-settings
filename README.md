git clone https://github.com/kjaern/windows-powertoys-settings %userprofile%\AppData\Local\Microsoft\PowerToysTmp
mv %userprofile%\AppData\Local\Microsoft\PowerToysTmp %userprofile%\AppData\Local\Microsoft\PowerToys
rmdir -Force -Recurse %userprofile%\AppData\Local\Microsoft\PowerToysTmp
