# Roll20
Roll20 Virtual Tabletop Resources - Scripts, Tables, Macros, and more!


This repository is organized using the following hierarchy:

Path: /Roll20/Game/Version/Source/Other/Paths/File

Roll20 is the root repository directory.

Game is a game that Roll20 supports, like Dungeons and Dragons (DnD), Pathfinder, etc.

Version is the version of the game, such as DnD's 3.5 or 5.0.

Source is the original source of the table data, such as Original tables created by myself, other developers, or Reddit's r/d100 forum.  Sources may also be the game publisher's resources, such as D&D's Dungeon Master Guide (DMG) or Player's Handbook (PHB).

Other/Paths are other subsequent directory paths that make sense for the way the Source material is organized, or how a developer organizes their original content.

File is the resource file, such as a script's source code, table import script, or macro source code.


Dependencies:

Rollable tables make use of The Aaron's fantastic "TableExport" API Script.  You can add this script to your game from the Roll20 Script Library to be able to import the tables.  Many rollable tables also make use of The Aaron's fantastic "RecursiveTable" API Script which allows the output of tables to be parsed for additional tables to be rolled and dice rolls.

Many macros make use of The Aaron's fantastic "RecursiveTable" API Script to roll and collect items from multiple rollable tables.  You can add this script to your game from the Roll20 Script Library.

