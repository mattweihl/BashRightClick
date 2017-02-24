# BashRightClick

# TODO:
Investigate using REG_EXPAND_SZ type instead REG_SZ for path to Bash.exe (instead of hardcoding Windows directory - REG_EXPAND_SZ supports environment variables, i.e "%windir%\System32\bash.exe" instead of "C:\Windows\System32\bash.exe". Mostly a best practices thing (should never hardcode Windows directories).
