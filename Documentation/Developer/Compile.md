# Compile

1. Install and run the [Microsoft HTML Help Workshop installer](https://www.helpandmanual.com/downloads_mscomp.html)
1. Copy `hhc.exe` from the install location (default: `"C:\Program Files (x86)\HTML Help Workshop\hhc.exe"`) to `Documentation/MacroCreator_Help-doc`
1. Copy `"C:\Windows\SysWOW64\hha.dll"` to `Documentation/MacroCreator_Help-doc`
1. Run [Compile.ahk](../../Compile.ahk)
1. Click "OK" on the prompts to sign the files (todo what do the prompts mean?)
1. Compile the new [`Installer.iss`](../../Installer.iss) with [Inno Setup Compiler 6.3.2](https://jrsoftware.org/isdl.php)

[Compiled/MacroCreator-setup.exe](../../Compiled/MacroCreator-setup.exe) should now contain an adware-free installer 😊
