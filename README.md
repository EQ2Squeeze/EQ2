# Squeeze's DPS Priority Calculator

## Overview

Squeeze's DPS Priority Calculator is a web-based tool designed to help players optimize their damage per second (DPS) in gaming scenarios by calculating and prioritizing spells based on their damage, cast time, recovery time, and special properties like DOT (Damage Over Time), AOE (Area of Effect), and Encounter abilities. The tool provides an interactive interface to input spell details, visualize DPS data through a bar chart, and manage spell entries in a table.

## Features

- Spell Input: Add spells with customizable parameters including name, damage, cast time, recovery time, and whether they are DOT, AOE, or Encounter spells.
- DOT Support: Include tick damage and duration for DOT spells to calculate total damage accurately.
- AOE and Encounter Handling: Automatically generates DPS values for 1 to 8 mobs for AOE and Encounter spells.
- DPS Calculation: Computes DPS based on total damage divided by the sum of cast time and recovery time, adjusted for DOT and mob counts.
- Visualization: Displays a bar chart to compare DPS across spells, with color coding for different spell types (red for non-AOE/Encounter, blue for AOE, green for Encounter).
- Table Management: Lists all spells with options to edit or delete entries, showing only relevant data (1-mob, 8-mob, and lowest DPS for grouped AOE/Encounter spells).

## Usage

1. Input Spell Details:
   - Enter the spell name, damage, cast time, and recovery time in the respective fields.
   - Check the DOT checkbox to reveal tick damage and duration fields, and use AOE or Encounter checkboxes for multi-mob calculations.

2. Add or Edit Spells:
   - Click "Add Spell" to include a new spell or "Update Spell" to save edits. Use "Cancel" to discard edits.
   - Edit or delete existing spells via the table's action buttons.

3. View Results:
   - The bar chart updates automatically to show DPS for all visible spells.
   - The table lists spells, showing only 1-mob, 8-mob, and the lowest DPS entry for grouped AOE or Encounter spells with the same base name.
