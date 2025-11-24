# My Shop Thing (shop.py)

**A dead-simple inventory + billing script I've been using daily since 2020**

This is literally one Python file that runs my entire kirana store.  
No installation, no database, no internet — just double-click and the shop opens.

Works on any old laptop (even Windows 7). My uncle (60+) uses it without any training.

### Features
- Add / edit / delete items
- Search anything by typing just 2-3 letters
- Ring up sales (type item name → quantity → "done")
- Automatically reduces stock when you sell
- Calculates 18% GST and shows final bill
- Everything saved in a single `stuff.json` file (easy backup)
- Zero crashes in 5+ years of daily use

### Technologies Used
- Python 3 (only built-in modules)
- `json` — for saving data
- `os` & `time` — for clearing screen and tiny pauses
- One file: `shop.py`
- One data file: `stuff.json` (created automatically)

### How to Install & Run

1. Make sure Python is installed  
   (Download from https://python.org if not)

2. Download `shop.py` (the script you’re reading the code of)

3. Put it anywhere (Desktop, D:, pen drive — doesn't matter)

4. Double-click `shop.py` → it will run  
   (or right-click → Open with → Python)

First run creates `stuff.json` automatically in the same folder.

That's it. Shop is open.

### Testing Instructions
- Just use it like a real shop
- Try adding 50 biscuits, sell 20, check if 30 remain
- Close suddenly (Alt+F4) → reopen → data should still be there
- Works even if electricity goes (saves after every change)
