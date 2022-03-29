# Costume Templates
This repo contains easy to use costume references/templates for Repentance.

It does not contain instructions on how to apply them. 

In all of the costumes, except for Full costumes, the left side is the right side, flipped. In the case of the body costume, the walk down animation is also the walk up animation.
# Contents
- Head texture and anm2
  - Standard
  - Colored
  - Full
  - Animated
- Body texture and anm2
  - Standard
  - Colored
  - Full
- Combined body & head anm2

# Usage

## General
To use them, replace the correct texture in the corresponding anm2.

For example, when creating a head-only costume use `head.anm2`. Replace the original head spritesheet with the new one.

You can also replace them both in `combined.anm2` in order to create a full body costume.

## Color costumes
Color costumes behave the same as regular costumes. They differ in the game.
Colored costumes automatically apply the correct texture for the corresponding skin color.

**When changing the file name, do not change the color part.**
A color part is whatever comes after the underscore, including the underscore.
For example, in `head_blue`, the color part is `_blue`.
Changing that will result in the color costume not applying correctly.

In order to mark a costume as a color costume, add `hasSkinAlt="true"` to the costume's entry in `costumes2.xml`

## Animated costumes
Change the spritesheet until you're satisfied.
When you're done, add `hasOverlay="true"` to the costume's entry in `costumes2.xml`
