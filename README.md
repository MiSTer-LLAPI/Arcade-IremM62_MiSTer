LLAPI Note : 

1. Place the rbf core file in a folder named _LLAPI/cores/
2. Place the MRAs files in _LLAPI/_Arcade/
3. Dont forget to enable LLAPI in the core OSD (this has to be done for each MRA for now)
4. Play !

In order to play with 2 players you need to insert 2 coins at least and press START2P button.
This button has been mapped to the LEFT shoulder button (SNES controller used as a reference)

Irem M62 Hardware
=================

Based on old PACE code by Mark McDougall(tcdev), enhanced by Gyorgy Szombathelyi in March 2020.

Games supported:
- Lode Runner 1-4
- Kung Fu Master
- Horizon
- Battle Road
- Spelunker 1-2
- Kid Niki
- Youjyudn

# Keyboard inputs :
```

   MAME/IPAC/JPAC Style Keyboard inputs:
     1           : Start 1 Player
     2           : Start 2 Player
     5           : Coin 1
     6           : Coin 2
     R,F,D,G     : Player 2
     A           : Fire2 A
     S           : Fire2 B 
	
 Joystick support. 
```

# Known Bugs

- Kung-Fu Master has a sprite color problem
- Lot Lot isn't fully implemented


# ROMs
```
                                *** Attention ***

ROMs are not included. In order to use this arcade, you need to provide the
correct ROMs.

To simplify the process .mra files are provided in the releases folder, that
specifies the required ROMs with checksums. The ROMs .zip filename refers to the
corresponding file of the M.A.M.E. project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for
information on how to setup and use the environment.

Quickreference for folders and file placement:

/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/_Arcade/mame/<mame rom>.zip
/_Arcade/hbmame/<hbmame rom>.zip

```

Launch game using the appropriate .MRA

