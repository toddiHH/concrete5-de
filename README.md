# concrete5 German localization

These files contain German localization files for the concrete5 Content Management System.

## Version

5.6.0

## Caveats

The official place for community-approved translations is:
https://www.transifex.com/projects/p/concrete5/language/de_DE/

This repository is mainly designed to track changes made to the Transifex translation repository and to add files and strings that are not available for translation in Transifex.

The translations here are a group effort by the German translation team.

The .mo/.po files here differ from the Transifex translations in a few added string that are missing in the base translation files from the concrete5 core team.

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
