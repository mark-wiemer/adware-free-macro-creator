# Pulover's Macro Creator, adware-free (PMC-AF)

## ⚠️ Under construction, install at your own risk 🚧

PMC-AF aims to provide an easy-to-install fork of PMC without bundling any unnecessary software. PMC's default installer includes sponsored adware and has for years, and Pulover has not shown any intention of removing it. Check back later for updates.

To help remove the Web Companion adware from your machine, I recommend these steps:

1. Remove "Web Companion" via Settings > Apps > Installed Apps
1. Remove the registry keys for Web Companion [learn more](https://github.com/Pulover/PuloversMacroCreator/issues/243#issuecomment-1272645212):
   1. Open Registry Editor (you can find this in the Start Menu)
   1. Ensure there is no entry for `HKEY_LOCAL_MACHINE\SOFTWARE\Lavasoft\Web Companion` (you can remove entries via the right-click menu)
   1. Ensure there is no entry for `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Lavasoft\Web Companion`
1. Run your preferred malware scanner. I use [MalwareBytes](https://www.malwarebytes.com). (This project is not sponsored or endorsed by MalwareBytes or any third-party)

If you have any issues, please open an issue on this repo and I will do my best to help :)

## Overview

Pulover's Macro Creator (PMC) is a free automation tool and script generator built in AutoHotkey. It features a large range of automation commands, has a built-in recorder, and can capture inputs in its interface. The macros can be executed from the program itself or export to AutoHotkey scripts for advanced editing. Learn more at [www.macrocreator.com](https://www.macrocreator.com)

## Translations

You can make corrections to the interface language translations inside the application itself (Settings > Language editor). You can submit your corrections or new translations from there too. To translate the help file, use the markdown files in `Documentation\MacroCreator_Help.ahk`

The application is prepared to recognize a help file in the same directory of MacroCreator.exe, if named according to the .lang file of the currently selected language. For example, if the help file is for Chinese Simplified it must be named `MacroCreator_Help_Zh_CN.chm` or `MacroCreator_Help_Zh.chm`.

## Developer notes

See [Compile.md](./Documentation/Developer/Compile.md) for how to compile this project from source.

* Setup and Help project files are maintained and created by *BuildFiles.ahk*.
* Language files may be edited in Languages.xls. Run ExtractLangFiles.ahk to create the .lang files in the Lang directory.

