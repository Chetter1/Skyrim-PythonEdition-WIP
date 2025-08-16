# The Elder Scrolls V: Skyrim - Python Edition
## Installation and Running Guide

### Quick Start

You now have several ways to run your Skyrim Python Edition game:

#### Option 1: Batch File (Recommended for Windows)
1. Double-click `SkyrimPythonEdition.bat` 
2. The game will start automatically!

#### Option 2: PowerShell Script
1. Right-click `SkyrimPythonEdition.ps1` 
2. Select "Run with PowerShell"
3. If you get a security warning, type `Y` to allow the script to run

#### Option 3: Python Launcher
1. Double-click `skyrim_launcher.py` (if Python is associated with .py files)
2. OR open Command Prompt/PowerShell and run: `python skyrim_launcher.py`

#### Option 4: Direct Python Execution
1. Open Command Prompt or PowerShell in this folder
2. Run: `python main_game.py`

### Requirements

- Python 3.7 or higher must be installed
- All game files must be in the same folder:
  - main_game.py
  - game_core.py
  - character_creation.py
  - combat.py
  - crafting.py
  - inventory.py
  - quests.py
  - world.py
  - SkyrimPythonEdition.bat (launcher)
  - skyrim_launcher.py (alternative launcher)

### Creating a True Executable (Optional)

If you want a standalone .exe file that doesn't require Python to be installed:

1. Install PyInstaller: `pip install pyinstaller`
2. Run: `pyinstaller --onefile --console --name "SkyrimPythonEdition" main_game.py`
3. Find your executable in the `dist` folder

Note: There may be dependency issues with PyInstaller on some systems. The batch file method is more reliable.

### Troubleshooting

**"Python is not recognized"**
- Install Python from https://python.org
- Make sure to check "Add Python to PATH" during installation

**Game won't start**
- Make sure all .py files are in the same folder
- Try running `python --version` to verify Python is installed

**Save files**
- The game creates `skyrim_save.json` for saving your progress
- Keep this file in the same folder as the game

### Game Features

- Character creation with multiple races
- Combat system
- Inventory management
- Crafting (Smithing, Alchemy)
- Quest system
- World exploration
- Save/Load functionality

Enjoy your adventure in Skyrim!
