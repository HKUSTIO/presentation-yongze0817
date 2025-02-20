# LaTeX Presentation Setup Guide

This repository contains LaTeX beamer presentation templates for HKUST. Follow these instructions to set up your development environment.

## Prerequisites

### 1. Install TeXLive

#### Windows
1. Download TeXLive from [https://tug.org/texlive/windows.html](https://tug.org/texlive/windows.html)
2. Run the installer and select "Install for all users" (recommended)
3. Choose "Full installation" for complete package support
4. Add TeXLive to your system PATH if the installer hasn't done so

#### macOS
1. Download MacTeX from [https://tug.org/mactex/](https://tug.org/mactex/)
2. Run the installer package
3. MacTeX includes TeXLive and additional tools for macOS

#### Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install texlive-full
sudo apt install latexmk
```

### 2. VS Code/Cursor Setup

1. Install VS Code from [https://code.visualstudio.com/](https://code.visualstudio.com/) or Cursor from [https://cursor.sh/](https://cursor.sh/)
2. Install the "LaTeX Workshop" extension:
   - Open VS Code/Cursor
   - Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
   - Search for "LaTeX Workshop"
   - Click Install

## Usage

1. Clone this repository
2. Open the project folder in VS Code/Cursor
3. Navigate to `slide/main.tex`
4. Edit the presentation content
5. Save the file to automatically compile
6. View the PDF output in VS Code/Cursor's built-in viewer

## Features

- HKUST-themed color scheme
- Clean, modern design
- 16:9 aspect ratio
- Ready-to-use presentation structure

## Troubleshooting

### Common Issues

1. **Command 'latexmk' not found**
   - Make sure TeXLive is properly installed
   - Verify that TeXLive is in your system PATH
   - Restart VS Code/Cursor

2. **PDF viewer not showing**
   - Try switching between different PDF viewers in settings
   - Make sure no other program is locking the PDF file

3. **Compilation errors**
   - Check the LaTeX Workshop output panel for detailed error messages
   - Verify all required packages are installed
   - Try cleaning auxiliary files and rebuilding

For more help, check the [LaTeX Workshop Documentation](https://github.com/James-Yu/LaTeX-Workshop/wiki).