# Pointillism Flower

🇺🇸 **English** | 🇧🇷 [Português](README.pt-BR.md)

A flower made of thousands of tiny dots that sprouts from the soil, grows, blooms and stays alive and glowing forever. Everything is generated with NumPy and drawn pixel by pixel, with no pre-made images.

![Flower stages](flower_stages.png)

## Requirements

- Python 3.9+
- NumPy, Pillow and PyInstaller
- Tkinter (bundled with Python on Windows and macOS; on Linux you may need to install `python3-tk`)

## Installation

**Windows**: create the virtual environment and install the dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install numpy Pillow pyinstaller
```

**Linux / macOS**:

```bash
python3 -m pip install numpy Pillow
```

In that case, run the commands below with `python3` instead of `.\.venv\Scripts\python.exe`.

## Usage

Open the animation in a window:

```powershell
.\.venv\Scripts\python.exe flower.py
```

### Window controls

| Key | Action |
|-----|--------|
| `Space` | Pause / resume |
| `R` | Restart from the beginning |
| `S` | Save the current frame to `flower_frame.png` |
| `Esc` | Close |