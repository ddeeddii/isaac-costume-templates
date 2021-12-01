# Costume Templates
This repo contains easy to use costume references/templates for Repentance.

It does not contain instructions on how to apply them. 

All provided textures have the left side flipped from the right side.
That means the left side of a costume will be the same as the right side.


# Contents
- Head texture and anm2
- Body texture and anm2
- Colored head and body textures for skin colors
- Combined head and body anm2

# Usage

## General
To use them, replace the correct texture in the corresponding anm2.

For example, `head.png` link to `head.anm2`.

You can also replace them both in `combined.anm2` in order to create a full body costume.

## Color costumes
Color costumes behave the same as regular costumes. They differ in the game.
Colored costumes automatically apply the correct texture for the corresponding skin color.

**When changing the file name, do not change the color part.**
A color part is whatever comes after the underscore, including the underscore.
For example, in `head_blue`, the color part is `_blue`.
Changing that will result in the color costume not applying correctly.

In order to mark a costume as a color costume, add `hasSkinAlt="true"` to the costume's entry in `costumes2.xml`