# Battle Bot Builder for Bigfoot Country

⚔️ **Build attack sequences for your Bigfoot Country battle bot with a visual GUI**

## What is This?

This is a web-based tool that helps you design battle sequences for the Bigfoot Country game automation bot. Instead of manually coding unit selections and attack patterns, use this GUI to:

- Select units with a searchable dropdown
- Build attack sequences visually
- Set up unit positioning with drag operations
- Generate ready-to-use Python code

## How to Use

1. **Add Units**: Click "Add Unit" and search for your units (Mega Tank, Veteran, etc.)
2. **Set Quantities**: Choose how many of each unit to select
3. **Add Drags** (optional): Reposition units on the battlefield
4. **Build Attack Sequence**: Click "Add Attack" and configure each attack
5. **Copy Code**: Click "Copy All" to get your Python code
6. **Paste**: Add the generated code to your battle bot script

## Features

- ✅ 100+ unit types from Bigfoot Country
- ✅ Searchable unit selector
- ✅ Multiple attack types (First Enemy, Battle Click, Smart Attack, etc.)
- ✅ Drag-and-drop unit positioning
- ✅ Collapsible attack cards for managing 30+ attacks
- ✅ Live Python code preview
- ✅ One-click copy to clipboard

## Generated Code Structure

The tool generates two main sections:

1. **`select_battle_units()`** - Unit selection function
2. **Attack Sequence** - Complete battle loop with all attacks

Just copy/paste into your battle bot Python script!

## Requirements

To use the generated code, your battle bot script needs:
- `pyautogui` for mouse/keyboard control
- `smart_scroll_to_unit()` function for unit selection
- `drag_unit_to_position()` helper function (for drag operations)
- Battle position dictionaries (`unit_battle_locations`, `enemy_battle_locations`)

## Made By

Created for the Bigfoot Country automation community.

---

**Live Tool**: [Access the builder here](https://yourusername.github.io/battle-bot-builder)

*Replace `yourusername` with your actual GitHub username in the URL above*
