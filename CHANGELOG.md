# CHANGELOG

## 1.3.0 (2015-06-05)

- Fixed 400 Bad Request errors

- Added additional text to autoload configuration

- PHP >= 5.5 is now required

## 1.2.1 (2015-06-02)

- Performance Enhancements

- Refactored many functions

## 1.2.0 (2015-05-25)

- Removed PHP 5.3 Support
    - PHP >= 5.4 is now required

- Chinease Language Support
    - Special thanks to Zhang Meng

- Performance Enhancements

- getID3 Support

- All known bugs are resolved

## 1.1.4 (2014-07-31)

- Resolved many PSR-2 issues

- General Code Cleanup

- .m4a File Extension is now supported and tested without any known issues

- Added autoload_classmap.php

- Added template_map.php

- Speed should have been improved between searches and general viewing

- Fixed an issue where the search.txt was not being created on import

## 1.1.3 (2014-03-13)

- Fixed a bug when playing single songs (File Not Found Error). Guess I got used to playing full albums and missed this, my bad =)

## 1.1.2 (2014-01-25)

- Fixed missing Translations

- Renamed Translation Files

- Set Default Language as en_US

- Minor CSS color changes

## 1.1.1 (2014-01-25)

- New Download Folders in .zip, .tar, .bz2, and .rar Formats (Requires PHP Phar Extension)
    - Based on your PHP configuration of ```memory_limit``` this may not work.
      See the [Wiki](../../wiki) for more details.
    - Downloading is handled by a simple JS snippet.
      If you have JS disabled, this feature will not work for you.

- Added Exceptions for error handling

- Disable Layout for entire Module, including Errors

## 1.1.0 (2014-01-24)

- New Search Feature!
    - Console Support for importing Search Results

- Fixed Routes
    - Changed Default Route from search to index

- Fixed View Template Stack

- Out of Memory issues can be expected if you have a large amount of songs in your library
    - To resolve this you can increse your PHP's memory_limit setting
    - Or, reduce the files in your library into different folders

- Translation Support
    - Updated Translations
    - English is the default language
    - Must have "translator" in your ServiceManager for Translations to work properly

- Many minor improvements

## 1.0.2 (2014-01-23)

- Code Comments have been updated

- Fixed return points

## 1.0.1 (2014-01-22)

- [1: Navigation Folder Names](https://github.com/diemuzi/mp3/issues/1)

- [2: Play Single Songs](https://github.com/diemuzi/mp3/issues/2)

## 1.0.0 (2014-01-21)

- Initial Release
