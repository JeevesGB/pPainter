# pPainter

pPainter is a lightweight painting/drawing application built with Python and PyQt6.  
It allows users to create and edit images with a simple and intuitive interface supporting basic brush tools, layers, color selection, and file export.

---

## Features (Incomplete)

- Brush and eraser tools with adjustable size  - no
- Color picker and palette support  - yes
- Multiple layers with basic layer controls (add, delete, reorder)  
- Undo/redo functionality  - no
- Export drawings as PNG files  - yes
- Simple UI optimized for quick sketches and edits - no

---

## Requirements

- Python 3.9 or newer  
- PyQt6  
- (Windows) Python 3.x with PyQt6

---

## Installation and Build Instructions

---

### Windows

1. Install Python 3.x for Windows from https://python.org  
2. Open Command Prompt and install PyQt6:

```cmd
pip install pyqt6
```

3. Run the application:

```cmd
python timage.py
```

---

## Building Windows EXE

### Method 1: On Windows (Recommended)

1. Install Python and dependencies:
```cmd
pip install pyqt6 pillow pyinstaller
```

2. Build the executable:
```cmd
pyinstaller --onefile --windowed --name pPainter timage.py
```

3. Your `.exe` will be in the `dist/` folder

---

## PyInstaller Options Explained

- `--onefile`: Creates a single executable file instead of a folder with dependencies
- `--windowed`: Prevents console window from appearing (GUI apps only)
- `--name pPainter`: Sets the executable name to "pPainter.exe"

---

---

## License

MIT License

---

## Author

_jej_
