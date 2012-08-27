# concrete5 German localization

These files contain German localization files for the concrete5 Content Management System.

## Version

5.6.0 Beta2

## Contents

- The .mo/.po files containing the German localization based on the translatable strings in the CMS source.
- An updated TinyMCE folder (version 3.5.6) with the custom Concrete plugins and full German localization strings

## Installation

Place the files into your web root folder (or where the concrete5 CMS is located).
The default concrete5 installation provides two empty folders in your web root:
- js
- languages
The files in this repository belong there.
Do not copy the files into the CMS's system folder "concrete".

The included TinyMce version overrides the one that ships with concrete5 in order to provide German localization here as well and allows for updating the editor independently from concrete5.

## Caveats

The concrete5 community is discussing appropriate ways to improve localization and its maintenance, but currently no unified solution exists, so this is an attempt to provide (yet another) repository with a complete and updated set of translations.

A number of German translation files from various authors exist, none of which were complete or up to date, so I merged the most fitting translations and harmonized a number of terms. 

Unfortunately, it seems impossible at this point to fully translate the user interface, as a number of strings are stored into the database at install time.

There is still much room for improvement in these translations, in terms of spelling, style and decisions on fitting terms for things like the file manager (which I currently refer to as "Dateiverwaltung").

Comments and Pull Requests are welcome.

## Links

Actively maintained repositories with translations for older concrete5 versions exist at
https://github.com/furehead/concrete5/tree/german-language/web/languages/de_DE/LC_MESSAGES
https://github.com/seebaermichi/german-translation-concrete5.5.2

Other resources:
http://www.concrete5.org/community/forums/chat/any-news-about-i18n/
http://forum.concrete5-cms.de
http://gengo.com/string/p/concrete5-1/