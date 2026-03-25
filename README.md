# TempestRaidTools - Raid Cooldown Tracker

Highly configurable addon custom made for Ascension-Bronzebeard created to provide raid tools for the **\<Tempest\>** guild. Currently includes functionality to track spell cooldowns for all raid/party members by showing cooldown bars for user-enabled tracked spells. 

## Features

- Visual cooldown bars for raid/party member's available spells.
- Auto detection of cooldowns and available spells for players in the user's party/raid.
- Communication of cooldown availability and durations between fellow addon users for more accurate durations.

## Installation

1. Download the latest release.
2. Copy the `TempestRaidTools` folder into `Ascension Launcher\resources\client\Interface\AddOns`.
3. Restart the game or reload UI (`/reload`).

## Usage

- **/trt** opens the options menu also located in Interface->Addons.
- Configure behaviors in the `General` tab.
- Configure spells to be tracked and tracking behaviors in the `Spells` tab. Add custom spells if they are not present by default.
- Configure the look of the cooldown bars in the `Customization` tab.

## Known issues

- Spell detection currently relies on scraping invisible inspection panels, which may show the wrong Mystic Enchants or talents due to an Ascension specific bug.
- Spell detection relies on inspected players being within inspection range.
