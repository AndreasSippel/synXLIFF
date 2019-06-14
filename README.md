# synXLIFF

The main purpose of this repo is to track issues for the latest version of synXLIFF.

Download link: https://www.synalis.de/synxliff/

If you encounter any problems regarding a translation of synXLIFF feel free to create a pull request.
We will then look into it.

Also if your language is still missing you can create a pull request with the translated xliff file.

## Changelog

### Version 1.0.3.0

 - the default export file name should now have the full language code. ("fr-ca" instead of "fr") [#20](/../../issues/20)
 - added support for files translated with the "Multilingual App Toolkit" before. (Attibute "datatype" is now valid) [#19](/../../issues/19)
 - the import can now handle captions with more than 1024 characters [#18](/../../issues/18)
 - fixed an issue with our notification if a new version is available [#17](/../../issues/17)
 - it is now possible to filter out locked captions while translating a project [#15](/../../issues/15)
 

### Version 1.0.2.0

- if a project language is deleted, all translations for this project and language are now deleted as well
- auto translation now translates only for the current project language
- the translation assist edit should now always have the correct translation text
- if a caption is changed in the code and import the global file again, the translation gets the status "changed" 
- TableExtension and PageExtension were added to the object types

### Version 1.0.1.2

- fixed a problem with importing option captions with a leading whitespace
  
### Version 1.0.1.1

- the export now only exports translated items. This assures that if an item is not translated the default translation is used by BC.
- the "&" symbol is now replaced with "\&amp;" during export.
- fixed some display problems with the translation language on the project page.

### Version 1.0.1.0

- added support for files which where already translated before using Dynamics LCS
- synXLIFF now automatically checks for a new version on a daily base
  - the check is executed "OnOpenPage" on "synXLIFF Project List"
  - in the new setup table you can:
    - deactivate the automatic check
    - check manually for updates if you want to

### Version 1.0.0.1

- fixed an issue with actions that were not shown
- fixed an error when importing file with "maxwidth" attribute
