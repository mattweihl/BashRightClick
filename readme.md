# BashRightClick

Creates right-click context menu for opening WSL shell from current directory (similar to open Command Prompt here when shift clicking feature). Launches wsl.exe - which will launch your default shell (if you have multiple installed). Tested on Fall Creator's Update. 

# TODO:
Investigate using REG_EXPAND_SZ type instead REG_SZ for path to WSL.exe (instead of hardcoding Windows directory - REG_EXPAND_SZ supports environment variables, i.e "%windir%\System32\WSL.exe" instead of "C:\Windows\System32\WSL.exe". Mostly a best practices thing (should never hardcode Windows directories).