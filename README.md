# bitVice Style Guide for JavaScript

The general JavaScript coding styles that our team uses in our code.
If you find this useful, we encourage you to [fork it](https://github.com/bitvice/JS-StyleGuide) and use it for your own team's guide.

## Table of contents

1. [Syntax and Formatting](#syntax-and-formatting)
* 

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

