# 42power Installation and Usage Guide

This repository contains scripts to enhance your development environment with useful tools and aliases for 42 school projects.

## Installation

1. Clone this repository:
   git clone https://github.com/yourusername/42power
2. Navigate to the cloned directory:
   cd 42power
3. Run the installation script:
   ./install.sh
   
The installation script will:
- Offer to install the c_formatter_42
- Add useful aliases to your `.zshrc` file
- Create a desktop shortcut named 'Batman' for quick access

### Aliases
The following aliases will be added to your `.zshrc`:
- `clean12`: Remove existing headers from files
- `formatta`: Format all files in the current directory
- `header`: Add your personal header to files
- `power42`: Run the main power42 script with a menu interface

### Desktop Shortcut
A shortcut named 'Batman' will be created on your desktop, linked to the power42 script.

## Usage

After installation, you can use the `power42` command (or the 'Batman' desktop shortcut) to access the main menu:
./power42 [parameter]
The menu offers the following options:
1. clean12: Remove existing headers from files
2. formatta: Format all files in the current directory
3. header: Add your personal header to files
4. Exit

Each option will run the corresponding script with the parameter you provided.

### Script Functions

- `clean12`: Removes any existing header from the specified files.
- `formatta`: Applies formatting to all relevant files in the current directory.
- `header`: Adds your personal 42 header to the specified files.
- `power42`: Provides a menu interface to choose between the above options.
