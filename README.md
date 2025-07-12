# Smart Application Launcher

A powerful, intelligent application launcher with multiple interfaces and automatic application detection.

![Smart Launcher](bulletproof_launcher_icon_128.png)

## Features

- **🚀 Automatic Detection**: Scans your system for 1,500+ applications
- **🎯 Smart Categorization**: Organizes apps into 9 categories automatically
- **🎨 Three Interfaces**: GUI, CLI, and Rofi launcher options
- **⚡ Fast Performance**: Lightweight and responsive
- **🖥️ Desktop Integration**: Appears in system application menu
- **🔍 Real-time Search**: Find applications instantly
- **🎨 Beautiful UI**: Modern, clean interface design

## Quick Start

```bash
# Clone the repository
git clone https://github.com/username/smart-launcher.git
cd smart-launcher

# Run the installer
chmod +x install.sh
./install.sh

# Launch the GUI
python3 bulletproof_launcher.py
```

## Available Launchers

### 1. GUI Launcher (Recommended)
```bash
python3 bulletproof_launcher.py
```
- Modern PyQt5 interface
- Visual application cards
- Category-based browsing
- Integrated search

### 2. CLI Launcher
```bash
python3 smart_cli_launcher.py
```
- Terminal-based interface
- Keyboard navigation
- Perfect for SSH sessions
- Menu-driven interaction

### 3. Rofi Launcher
```bash
./launcher.sh
```
- Integration with Rofi
- Keyboard-only operation
- Unlimited directory nesting
- Breadcrumb navigation

## Categories

Applications are automatically organized into:

- 🔧 **Development**: IDEs, editors, compilers
- 🎨 **Graphics**: Image editors, design tools
- 🌐 **Internet**: Browsers, email, chat
- 🎵 **Media**: Audio/video players, streaming
- 📄 **Office**: Documents, spreadsheets, PDFs
- 🎮 **Games**: Gaming applications
- ⚙️ **Utilities**: System tools, file managers
- 🔒 **Security**: VPNs, password managers
- 📦 **Other**: Everything else

## System Requirements

- Linux (tested on Ubuntu, Fedora, Arch)
- Python 3.8+
- PyQt5 (for GUI)
- Rofi (optional, for rofi launcher)

## Dependencies

All dependencies are automatically installed by the installer:

- PyQt5 (GUI framework)
- PyYAML (configuration)
- Pillow (icon processing)

## Desktop Integration

After installation, the launcher appears in your system menu under "Utilities" as "Smart Launcher".

## Manual Installation

If you prefer manual setup:

```bash
# Create virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Make executable
chmod +x *.py *.sh

# Run
python3 bulletproof_launcher.py
```

## Configuration

The launcher automatically detects applications from:
- `/usr/share/applications/` (desktop files)
- System PATH (command-line tools)

No manual configuration required!

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Screenshots

### GUI Launcher
Modern interface with categorized applications and search functionality.

### CLI Launcher
Terminal-based navigation with keyboard shortcuts and pagination.

### Rofi Integration
Seamless integration with the Rofi application launcher.

---

Made with ❤️ for the Linux community