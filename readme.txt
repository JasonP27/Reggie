=== Reggie! Level Editor Mod (Release 3.6) by JasonP27 ===

Advanced level editor for New Super Mario Bros. Wii, created by Treeki and
Tempus using Python, PyQt and Wii.py.

3.6 version by JasonP27 modified from Reggie! Release 3 by Treeki and Tempus.

Homepage: http://www.rvlution.net/reggie/ (Original Release)
Support:  http://www.rvlution.net/forums/

Source code package for Reggie 3:
- http://www.rvlution.net/reggie/downloads/Reggie_r3_source.zip
Source code for Reggie Mod:
- http://github.com/JasonP27/Reggie/tree/reggiemod

=== Changelog: ===

- Release 3.7: (January 31st, 2013) -

-The following sprites now render using images:
--
*Path Controlled Ice Flow
*Bowser
*Iggy Koopa
*Kamek
*Ludwig Von Koopa
*Morton Koopa
*Roy Koopa
*Larry Koopa
*Lemmy Koopa
*Wendy Koopa
*Rotation Controlled Dish Platform
*Rotation Controlled Hanging Chain Platform
*Minigame Flip Panel
*Effect Glare
*Line Controlled Tilt Controlled Girder
*Rising Tilt Controlled Girder
*Rising Tilt Controlled Girder Controller
*Line Platform with Bolt
*Cannon - Multi Use
*Airship Nut Platform
*Continuous Flame Cannon
*Synchronized Flame Jet
*Rotating Flame Jet Cannon
*Line Controlled Dragon Coaster
*Sand Pillar
*Lava Geyser
--
Other New Features:

- Made NumberFont for Zones and Locations boxes bold in Dark version. (previously only in Light)
- Added a new menu option to enable or disable the labels on the tabs
- Added new option to menu and toolbar to enable or disable the viewing of sprites
- Added new option to menu and toolbar to enable or disable the viewing of locations
- Added and fixed various tooltips and descriptive text

*Added a new tab: List
- Like the Entrances tab only for Sprites, this tab lists every sprite loaded into Reggie (the current Area)
- Like the Entrances tab, you can double-click an entry in the list to jump to it instantly
- If the tab has focus, the currently selected sprite in the scene will be highlighted in the list
- Lists several key aspects of the sprite:

    *x,y position
    *which events trigger it
    *which events it activates
    *Coin/Set ID
    *Movement ID
    *Rotation ID
    *Location ID
    *which Star Coin number it is

For more information visit the Sprite Image Contributions thread on RVLution:
- http://www.rvlution.net/forums/viewtopic.php?f=20&t=1226

Special Thanks:
- to joietyfull64 for providing several images
- to Treeki his time and help
- to various members of RVLution and DarkUmbra for their support and suggestions

Release 3.6: (December 2nd, 2012) 

-The following sprites now render using images:
--
*Giant Floating Bubble (with arrow overlay to show direction of travel)
*Lighting - Rotation Controlled Spotlight
*Path Controlled Block Train
*Pipe Bubbles
*Lighting - Underwater Lamp
*Lighting - Giant Glow Block
*Big Breakable Brick Block
*Giant Wiggler
*Move-When-On Platform
*Chestnut Goomba
*Rotation Controlled Event Deactivation Block
*Bowser Switch (Small !)
*Bowser Switch (Large !)
*Fire Chomp
*Move-When-On Ghost House Boxes
*King Bill
*Freefall Ghost House Platform
*Rotation Controlled Cage Blocks
*Floating Question Block
--
- Made NumberFont for Zones and Locations boxes bold.
- Added 2px border to Tooltips
- Added Tooltip to Area Options -> Default Events to explain purpose of default events.
- Raw Data Textbox now turns red with bold white text when containing invalid data.
- Minor changes to other tooltips (Area Timer, Shift Objects).
- Two separate Reggie executables. One for normal light theme and one for dark theme, your choice :)

For more information visit the Sprite Image Contributions thread on RVLution:
- http://www.rvlution.net/forums/viewtopic.php?f=20&t=1226

Special Thanks:
- to joietyfull64 for providing several images 
- to Treeki and Tempus for their help with PyQt
- various members of RVLution and DarkUmbra for their support and suggestions

Release 3.5: (November 17th, 2012) 

-The following sprites now render using images:
--
*Micro Goomba
*Giant Goomba
*Mega Goomba
*Huckit Crab
*Clam (including all contents)
*Porcu-Puffer
*Bulber
*Jellybeam
*Spiny Cheep-Cheep
*Cheep-Chomp
*Fishbones
*Urchin
*Mega Urchin
*Fire Snake
*Poltergeist Item (QBlock & Stand)
*Jumbo Ray (including Fly Left/Right)
*Little Mouser (Facing left and right, swarm of 1-4)
*Roulette Block
*Player Block
*Player Block Platform
*Invisible 1-Up - Mini Mario Only
*Flying Question Block
*Pipe Cannon
*Box Generator
*Moving Chain Link (with arrow overlay to show direction of travel)
*Toad Balloon
--
-Increased number of Zoom Levels
-Added Zoom to Minimum and Zoom to Maximum functions
-Completely re-colored interface with darker style.


Release 3: (April 2nd, 2011)
- Unicode is now supported in sprite names within spritedata.xml
    (thanks to 'NSMBWHack' on rvlution.net for the bug report)
- Unicode is now supported in sprite categories.
- Sprites 274, 354 and 356 now render using images.
- Other various bug fixes.


Release 2: (April 2nd, 2010)
- Bug with Python 2.5 compatibility fixed.
- Unicode filenames and Stage folder paths should now work.
- Changed key shortcut for "Shift Objects" to fix a conflict.
- Fixed pasting so that whitespace/newlines won't mess up Reggie clips.
- Fixed a crash with the Delete Zone button in levels with no zones.
- Added an error message if an error occurs while loading a tileset.
- Fixed W9 toad houses showing up as unused in the level list.
- Removed integrated help viewer (should kill the QtWebKit dependency)
- Fixed a small error when saving levels with empty blocks
- Fixed tileset changing
- Palette is no longer unclosable
- Ctrl+0 now sets the zoom level to 100%
- Path editing support added (thanks, Angel-SL)


Release 1: (March 19th, 2010)
- Reggie! is finally released after 4 months of work and 18 test builds!
- First release, may have bugs or incomplete sprites. Report any errors to us
  at the forums (link above).


=== Requirements: ===

If you are using the source release:
- Python 2.5 (or newer) - http://www.python.org
- PyQt 4.6 (or newer) - http://www.riverbankcomputing.co.uk/software/pyqt/intro
- NSMBLib 0.4 - included with the source package (optional)

If you have a prebuilt/frozen release (for Windows or Mac OS)
you don't need to install anything - all the required libraries are included.

For more information on running Reggie from source and getting the required
libraries, check the Getting Started page inside the help file
(located at reggiedata/help/start.html within the archive)


=== Reggie! Team: ===

Developers:
- Treeki - Creator, Programmer, Data, RE
- Tempus - Programmer, Graphics, Data
- AerialX - CheerIOS, Riivolution
- megazig - Code, Optimisation, Data, RE
- Omega - int(), Python, Testing
- Pop006 - Sprite Images
- Tobias Amaranth - Sprite Info (a lot of it), Event Example Stage

Other Testers and Contributors:
- BulletBillTime, Dirbaio, EdgarAllen, FirePhoenix, GrandMasterJimmy,
  Mooseknuckle2000, MotherBrainsBrain, RainbowIE, Skawo, Sonicandtails,
  Tanks, Vibestar

- Tobias Amaranth and Valeth - Text Tileset Addon


=== Libraries/Resources: ===

Qt - Nokia (http://qt.nokia.com)
PyQt - Riverbank Computing (http://www.riverbankcomputing.co.uk/software/pyqt/intro)
Wii.py - megazig, Xuzz, The Lemon Man, Matt_P, SquidMan, Omega (http://github.com/icefire/Wii.py)
Interface Icons - Yusuke Kamiyamane (http://www.pinvoke.com)


=== Licensing: ===

Reggie! is released under the GNU General Public License v2.
See the license file in the distribution for information.
