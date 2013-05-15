# Linden Scripting Language syntax highlight for Notepad++ #

[Issue tracker](https://github.com/buildersbrewery/lsl-for-notepadplusplus/issues)

last update: 2013-05-15

----------

Please feel free to visit:
* [our Builder's Brewery homepage](http://www.buildersbrewery.com/)
* [our Builder's Brewery calendar with in-world classes](http://www.buildersbrewery.com/calendar/)
* [the Brewery in Second Life](http://maps.secondlife.com/secondlife/Builders%20Brewery/128/154/24/)

----------

![Screenshot](https://raw.github.com/buildersbrewery/lsl-for-notepadplusplus/master/static/lsl_syntax_for_notepad_plus_plus.png)

----------

## Style definition for grammar and coloring: ##

* Create a new temporary XML file anywhere on your harddrive, then copy and paste the code from `userDefineLang.xml` in this repository into your file. Make sure the file's encoding is ANSI/ASCII!
* Open Notepad++ and go to `Language > Define your language > Import`
* Load previously saved file.
* When the import was successful close the language definition window and select `Language > LSL` from the menu. You should should be able to find the language at the bottom of the language menu in the section for user defined languages.
* You can now delete the temporary file.

## Language definition for autocompletion and tooltips (hints): ##

* Copy and paste the `lsl.xml` file from this repository to the Notepad++ subdirectory `...\Notepad++\plugins\APIs\lsl.xml`
* Make sure the file's encoding is ANSI/ASCII!
* Goto `Settings > Preferences > Backup&Autocompletion` and make sure the autocompletion is enabled for words (not only functions) and the function hints are enabled.
