# bitVice Style Guide for JavaScript

The general JavaScript coding styles that our team uses in our code.
If you find this useful, we encourage you to [fork it](https://github.com/bitvice/JS-StyleGuide) and use it for your own team's guide.

## Table of contents

1. [File naming](#file-naming)
2. [Syntax and Formatting](#syntax-and-formatting)
3. 

## File naming
The names that we give to a file is important as it should describe it's contents. We are using lowercase, dashed splitted letters when naming a file. We suggest not to combine letters as the filename will be verry hard to read and understand.

We are using this composition rule: ``` {file descriptor}.[{file type}].js ```

##### File type table

File type         | Suffix    | Example
------------------|-----------|---------
Generic file      |           | `` generic-file.js ``
Bootstrap file    | index     | `` index.js ``
Simple Class file | class     | `` my-first-car.class.js ``
Abstract Class    | abstract  | `` service.abstract.js ``
Interface file    | interface | `` animal.interface.js ``
Module file       | mod       | `` bitvice-osi.mod.js ``



## Syntax and Formatting

One of the simplest forms of a styleguide is a set of rules regarding syntax and formatting. Having a standard way of writing code means that code will always look and feel familiar to all members of the team.

* Use `4` spaces indents - use spaces over tabs because tabs aren't always displayed the same size on all devices;
* Never mix spaces with tabs;
* Use 80 character wide columns;
* Meaningful use of whitespace helps reading code much faster;
* Use `UTF-8` as the source file encoding;
* Delete trailing whitespace;
* Each file ends with a blank newline.

##### Syntax table

Type             | Convention                                   | Example
-----------------|----------------------------------------------|-----------
ClassName        | PascalCase - with an initial capital letter  | ``` MightyBalrog, MagicWeapon ```
Public method    | CamelCase - with an initial lowercase letter | ``` castDimensionalDoorway, rollForInitiative ```
Public variable  | CamelCase - with an initial lowercase letter | ``` materialComponents, hasTrackingAbilities ```
Private method   | Underscore followed by a camelCase phrase    | ``` _getHealth ```
Private variable | Underscore followed by a camelCase phrase    | ``` _backstabAbility  ```
Method arguments | CamelCase - with an initial lowercase letter | ``` halfOrcArmy ```
Local variables  | CamelCase - with an initial lowercase letter | ``` isHumanoid, levelCount ```
jQuery objects   | Dollar symbol followed by a camelCase phrase | ``` $mainMenu ```
Constant         | Uppercase with underscores                   | ``` CLERIC_PLAYER, GAME_MASTER  ```

