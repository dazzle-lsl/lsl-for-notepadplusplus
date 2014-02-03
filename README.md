## Linden Scripting Language syntax highlight for Notepad++

last update: `2014-02-04`

### Readme contents

* [Quick start](#quick-start)
* [Bugs, issues & feature requests](#bugs-issues--feature-requests)
* [Visit the Builder's Brewery](#visit-the-builders-brewery)
* [LSL Syntax](#lsl-syntax)
* [LSL Autocompletion](#lsl-autocompletion)
* [LSL Snippets via FingerText](#lsl-snippets-via-fingertext)
* [Screencast](#screencast)
* [Screenshot](#screenshot)

___

### Quick start

* [Download the latest release](https://github.com/buildersbrewery/lsl-for-notepadplusplus/archive/master.zip).
* Clone the repo: `git clone git://github.com/buildersbrewery/lsl-for-notepadplusplus.git`

### Bugs, issues & feature requests

* Before opening a new issue, please search for existing issues.
* Please [open a new issue](https://github.com/buildersbrewery/lsl-for-notepadplusplus/issues/).

### Visit the Builder's Brewery

* Homepage: [http://www.buildersbrewery.com/](http://www.buildersbrewery.com/)
* In Second Life: [Builders_Brewery/128/154/24/](http://maps.secondlife.com/secondlife/Builders%20Brewery/128/154/24/)
* Calendar with class schedule: [http://www.buildersbrewery.com/calendar/](http://www.buildersbrewery.com/calendar/)

___

### LSL Syntax:

* If `...\Notepad++\userDefineLang.xml` exists where Notepad++ is installed:
  * Copy and paste everything within and including the `UserLang` tags from the `userDefineLang.xml` file from this repository into the file `...\Notepad++\userDefineLang.xml` where Notepad++ is installed.
  * When saving changes to the file make sure the file's encoding is `ANSI/ASCII`!

```xml
<?xml version="1.0" encoding="Windows-1252" ?>
<NotepadPlus>
    <UserLang name="someOtherLanguage">
        <!--
            settings
            keyword lists
            styles
        -->
    </UserLang>
    <!--
        put the LSL language here
    -->
</NotepadPlus>
```

* If `...\Notepad++\userDefineLang.xml` does not exist where Notepad++ is installed:
  * Download the file `userDefineLang.xml` from this repository. If you download and unzip the archive (from the link in [Quick start](#quick-start)) make sure the file's encoding is `ANSI/ASCII`!
  * Open Notepad++ and go to `Language > Define your language > Import`
  * Load previously saved file.
  * Close the language definition window and select `Language > LSL` from the menu. You should should be able to find the language at the bottom of the language menu in the section for user defined languages.
  * After successful import you can delete the files and/or archive you downloaded.

### LSL Autocompletion:

* Copy and paste the `lsl.xml` file from this repository to `...\Notepad++\plugins\APIs\lsl.xml` where Notepad++ is installed.
* Make sure the file's encoding is `ANSI/ASCII`!
* Goto `Settings > Preferences > Backup&Autocompletion` and make sure you set `enable auto-completion on each input` to `function completion` and you enable `function parameter hints on input`.

### LSL Snippets via FingerText:

Install [FingerText](https://github.com/erinata/FingerText) from the Notepad++ Plugin Manager. Then from the menu go to `Plugins > FingerText > Import Snippets from ftd file` to import the LSL snippets from the provided snippets file.

### Screencast:

![Screencast](https://raw.github.com/buildersbrewery/lsl-for-notepadplusplus/master/static/screencast_lsl_notepadplusplus.gif)

### Screenshot:

![Screenshot](https://raw.github.com/buildersbrewery/lsl-for-notepadplusplus/master/static/screenshot_lsl_notepadplusplus.png)
