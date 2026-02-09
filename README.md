# MonkeySpeed Adimo Edtion

MonkeySpeed backported for 1.12 and updated for Turtle WoW (vanilla 1.12).

## What It Does
Displays your current movement speed as a percentage of run speed. It works while running, swimming, mounted, and in other movement states.

## What Changed in This Edition
- Single addon folder layout with MonkeyLibrary bundled inside.
- Calibrate button added next to the speed display (runs /mscalibrate).
- Adimo edition name and contributor credit.
- Safer zone updates for 1.12 map-based speed calculations.

## Installation
1. Download or clone this repo.
2. Copy the folder into WOW\Interface\AddOns\ so it is named MonkeySpeed.
3. Confirm the folder contains MonkeySpeed.toc and a MonkeyLibrary subfolder.

## Calibration
1. Start running at normal speed (no modifiers).
2. Click the Cal button or run /mscalibrate.
3. Recalibrate when changing zones if values drift.

## Commands
- Calibrate at 100%: /monkeyspeedcalibrate or /mscalibrate
- Toggle display: /monkeyspeed or /mspeed
- Toggle percent: /monkeyspeedpercent or /mspercent
- Toggle bar: /monkeyspeedbar or /msbar
- Toggle debug: /monkeyspeeddebug or /msdebug
- Toggle lock: /monkeyspeedlock or /mslock

## Notes
Settings UI is not available in 1.12 because the original interface options panel was added in later expansions.
