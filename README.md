\# The Binding of Isaac: Quake 4 Mod



A Quake 4 gameplay modification inspired by \*The Binding of Isaac\*. This mod introduces Isaac-themed weapons, randomized enemy encounters, player upgrades, weapon modifications, and custom in-game interfaces.



\## Requirements



\- A working installation of Quake 4.

\- The `thebindingofisaac\_mod` folder installed in the Quake 4 directory.

\- The mod's compiled game DLL and required game assets.



\## How to Launch the Mod



1\. Make sure Quake 4 is installed.

2\. Use the provided desktop shortcut to launch the mod.

3\. Start or load a level where the mod's gameplay features are available.

4\. Open the in-game help screen from the main menu to learn about the mod's features.



\## Features and How to Test Them



\### 1. Isaac-Themed Weapons



The mod rethemes Quake 4's weapons with weapons and items inspired by \*The Binding of Isaac\*.



| Original Quake 4 Weapon | Isaac-Inspired Retheme |

|---|---|

| Blaster | Isaac's Tears |

| Machinegun | Soy Milk |

| Shotgun | Mom's Shotgun |

| Hyperblaster | Freezing Tears |

| Grenade Launcher | Scatter Bombs |

| Nailgun | Poison Tears |

| Rocket Launcher | Brimstone |

| Railgun | Haemolacria |

| Lightning Gun | Chocolate Milk |

| Dark Matter Gun | Death's Touch |



Use the corresponding weapons in-game to experience their rethemed appearances and effects.



\### 2. Random Enemy Encounters



The mod supports randomized enemy encounters and tracks the enemies spawned for each encounter.



To test:



1\. Open the in-game console.

2\. Run `spawnLevel <count>`, replacing `<count>` with the number of enemies to spawn. The maximum supported count is 10.

3\. Defeat all enemies spawned for the encounter.

4\. Once the encounter is cleared, the reward-selection menu appears.



\### 3. Reward Selection



After completing an encounter, the player can choose from three distinct randomized rewards.



Select one of the three options to apply the corresponding upgrade or weapon modification. The reward menu closes after a selection is made.



\### 4. Player Attributes



The reward system includes five player upgrades:



\- \*\*Damage Up:\*\* Increases player damage.

\- \*\*Fire Rate Up:\*\* Improves the player's firing rate.

\- \*\*Speed Up:\*\* Increases movement speed.

\- \*\*Max Health Up:\*\* Increases maximum health and restores additional health.

\- \*\*Projectile Speed Up:\*\* Increases projectile velocity.



These upgrades let players improve their abilities as they progress through encounters.



\### 5. Weapon Modifications



The mod includes five weapon modifications inspired by Isaac's tear effects:



\- \*\*Homing Tears:\*\* Projectiles steer toward nearby living enemies.

\- \*\*Piercing Tears:\*\* Adds projectile behavior intended to allow shots to pass through enemies.

\- \*\*Explosive Tears:\*\* Adds an explosive effect to projectiles.

\- \*\*Burning Tears:\*\* Adds a burning effect to projectiles.

\- \*\*Lifesteal Tears:\*\* Allows the player to recover health through the lifesteal effect.



\*\*Important Limitation:\*\* Only one weapon modification can be active at a time. Selecting a different weapon modification replaces the currently active one.



Weapon modifications are obtained through the reward-selection system.



\### 6. In-Game Help Screen



The mod includes a custom in-game help screen that explains its features and gameplay systems.



The help screen \*\*replaces the original Mods button in Quake 4's main menu\*\*. Instead of using that button for its original purpose, players can access information about the mod directly from the main menu.



\### 7. Custom Reward Menu



The mod includes a custom reward-selection interface that displays three available rewards after an encounter is completed.



Players can select a reward directly from the menu, applying the selected upgrade or weapon modification.



\## Development and Testing



The mod's game code is built using Visual Studio 2022 with the \*\*Win32 Release\*\* configuration.



When making code changes:



1\. Open the project solution in Visual Studio 2022.

2\. Build the game code using the appropriate configuration.

3\. Replace the mod's game DLL with the newly compiled version if necessary.

4\. Launch the mod and test the changes in-game.



\## Credits



\- \*\*Quake 4:\*\* Original game and engine.

\- \*\*The Binding of Isaac:\*\* Inspiration for the mod's weapons, upgrades, and gameplay themes.

\- \*\*Mod Developer:\*\* Adreanna Danao.



