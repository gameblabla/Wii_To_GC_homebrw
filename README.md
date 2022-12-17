# Wii to GC ports

# DONE

- Hydra Castle Labyrinth

https://github.com/gameblabla/OpenHCL/releases/tag/1.0-mus

- Wiicross

This one was already ported to the Gamecube but the GC build of it disappeared
and the source code was so old it wasn't building either.

https://github.com/gameblabla/wiicross/releases/tag/1.01


# Attempted but not working

- Giddy 3
Source : https://github.com/pete-gordon/Giddy3-Wii

The source code does not build a working executable, even on the Wii.

- OpenBOR
Source : https://github.com/DCurrent/openbor

Has compiling errors, needs older toolchain it seems.

- QRevPack

Quake 2 can boot with a stripped down executable but then fails.
Quake 1 GX does not even boot at all.

- WoxelCraft

Latest commit does not build a working executable (as shown by his own prebuilt binaries).
Last one to work is "Adding Missing loading background".
The one after that no longer boots.

I also tried the last known working version but it just crashes dolphin and presumbly real hardware
as well... I'm tired of trying this one and i have ported Crafti to the Gamecube
for those that are curious anyway.

# Doable

- Descent-Wii

# Possibly doable but RAM limitations could occur

- ONScripter
- DanceClone (https://github.com/lefrac01/DanceClone)

# Very hard, not possible ?

- Neverball (Might work but Wii version struggles to reach 30 FPS)
- Hexen II (uses 32MB heap like PC version)
- EasyRPG (RAM limitations, would need custom GX backend before even considering GC port)
- Italian Parking (relies heavily on Wiimote, https://wiibrew.org/wiki/Italian_Parking)
