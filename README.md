git clone https://github.com/kjaern/windows-powertoys-settings $env:LOCALAPPDATA\Microsoft\PowerToysTmp
move -Path $env:LOCALAPPDATA\Microsoft\PowerToysTmp\.git -Destination $env:LOCALAPPDATA\Microsoft\PowerToys\.git
rmdir -Force -Recurse $env:LOCALAPPDATA\Microsoft\PowerToysTmp
