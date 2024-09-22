# Pulover's Macro Creator, adware-free (PMC-AF)

## Overview

Pulover's Macro Creator (PMC) is a free automation tool and script generator built in AutoHotkey. It features a large range of automation commands, has a built-in recorder, and can capture inputs in its interface. The macros can be executed from the program itself or export to AutoHotkey scripts for advanced editing. Learn more at [www.macrocreator.com](https://www.macrocreator.com)

This is designed to create scripts/programs for (and run on) AHK v1. See [Pulovers-Macro-Creator (AHKv2)](https://github.com/samfisherirl/Pulovers-Macro-Creator-for-AHKv2) by **[@samfishirl](https://github.com/samfisherirl)** for an AutoHotkey v2 rewrite.

## Adware-free

PMC-AF provides an easy-to-install fork of PMC without bundling any unnecessary software. PMC's default installer includes sponsored bloatware "[Web Companion](https://www.pcrisk.com/removal-guides/14231-web-companion-unwanted-application)" and has for years, and Pulover has not shown any intention of removing it.

See [removing bloatware](./Documentation/removing-bloatware.md) for details on how to remove Web Companion.

Yes, this project might be better named "bloatware-free" but "AF" is just such a fun acronym :)

## Translations

You can make corrections to the interface language translations inside the application itself (Settings > Language editor). You can submit your corrections or new translations from there too. To translate the help file, use the markdown files in `Documentation\MacroCreator_Help.ahk`

The application is prepared to recognize a help file in the same directory of MacroCreator.exe, if named according to the .lang file of the currently selected language. For example, if the help file is for Chinese Simplified it must be named `MacroCreator_Help_Zh_CN.chm` or `MacroCreator_Help_Zh.chm`.

## Developer notes

See [Compile.md](./Documentation/Developer/Compile.md) for how to compile this project from source.

* Setup and Help project files are maintained and created by *BuildFiles.ahk*.
* Language files may be edited in Languages.xls. Run ExtractLangFiles.ahk to create the .lang files in the Lang directory.

