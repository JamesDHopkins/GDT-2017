# gdt-2017
Game Development Tool for a touch screen device written in Arduino C

GDT 2017 
Game Dev Tool README

Program Structure:

GDT.ino represents the core of the project. All OS/UI Functions and variables reside there. Shared memory must reside there since the linking order of an Arduino project is not defined well.

BaseEngine.ino will be the gameplay file. When a user playtests their game, this file will be used to run the engine.

SpriteMaker.ino is the paint window that allows a user to draw sprites to use in other parts of the game.

SpriteManager.ino is the window that allows a user to select a sprite.
