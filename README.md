## Linden Scripting Language syntax highlight for Notepad++

last update: `2014-01-02`

### Readme contents

* [Quick start](#quick-start)
* [Bugs, issues & feature requests](#bugs-issues--feature-requests)
* [Visit the Builder's Brewery](#visit-the-builders-brewery)
* [Screenshot and screencast](#screenshot-and-screencast)
* [Style definition for grammar and coloring](#style-definition-for-grammar-and-coloring)
* [Language definition for autocompletion and tooltips](#language-definition-for-autocompletion-and-tooltips)

___

### Quick start

* [Download the latest release](https://github.com/buildersbrewery/lsl-for-notepadplusplus/archive/master.zip).
* Clone the repo: `git clone git://github.com/buildersbrewery/lsl-for-notepadplusplus.git`

### Bugs, issues & feature requests

* Before opening a new issue, please search for existing issues.
* Please [open a new issue](https://github.com/buildersbrewery/lsl-for-notepadplusplus/issues/).

### Visit the Builder's Brewery

* Homepage: [http://www.buildersbrewery.com/](http://www.buildersbrewery.com/)
* In Second Life: [Builders Brewery &lt;128, 154, 24&gt;](http://maps.secondlife.com/secondlife/Builders%20Brewery/128/154/24/)
* Calendar with class schedule: [http://www.buildersbrewery.com/calendar/](http://www.buildersbrewery.com/calendar/)

### Screenshot and screencast:

![Screenshot](https://raw.github.com/buildersbrewery/lsl-for-notepadplusplus/master/static/lsl_syntax_for_notepad_plus_plus.png)

![GIF Screencast](https://raw.github.com/buildersbrewery/lsl-for-notepadplusplus/master/static/notepadplusplus_with_lsl_screencast.gif)

### Style definition for grammar and coloring:

1. If `...\Notepad++\userDefineLang.xml` exists where Notepad++ is installed:
  * Copy and paste everything within and including the `UserLang` tags from the `userDefineLang.xml` file from this repository into the file `...\Notepad++\userDefineLang.xml` where Notepad++ is installed.

```xml
<?xml version="1.0" encoding="Windows-1252" ?>
<NotepadPlus>
    <UserLang name="someOtherLanguage">
        <!--
            ...
            ...
            ...
            ...
        -->
    </UserLang>
    <!-- put the LSL language here -->
</NotepadPlus>
```

2. If `...\Notepad++\userDefineLang.xml` does not exists where Notepad++ is installed:
  * Download the file `userDefineLang.xml` from this repository. If you download and unzip the archive (from the link in [Quick start](#quick-start)) make sure the file's encoding is `ANSI/ASCII`!
  * Open Notepad++ and go to `Language > Define your language > Import`
  * Load previously saved file.
  * Close the language definition window and select `Language > LSL` from the menu. You should should be able to find the language at the bottom of the language menu in the section for user defined languages.
  * After successful import you can delete the files and/or archive you downloaded.

### Language definition for autocompletion and tooltips:

* Copy and paste the `lsl.xml` file from this repository to `...\Notepad++\plugins\APIs\lsl.xml` where Notepad++ is installed.
* Make sure the file's encoding is `ANSI/ASCII`!
* Goto `Settings > Preferences > Backup&Autocompletion` and make sure you set `enable auto-completion on each input` to `function completion` and you enable `function parameter hints on input`.
