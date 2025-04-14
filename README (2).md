
# ECU Tool

A professional-grade tool for ECU file analysis and modification.

## Features

- Hex viewer and editor for ECU binary files
- VIN number modification
- Pre-defined ECU modifications with safety checks
- Automatic backup system
- Comprehensive logging and error handling
- Diagnostic tools
- Modern, user-friendly interface

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ecu-tool.git
cd ecu-tool
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python main.py
```

## Safety Features

- Automatic backups before modifications
- Integrity checks for ECU files
- Risk level indicators for modifications
- VIN validation
- Checksum verification and correction

## Configuration

The tool can be configured through the Settings dialog, accessible from the main menu.
Configuration files are stored in `~/.ecu_tool/`.

## Logging

Logs are stored in `~/.ecu_tool/logs/` and include:
- Information about loaded files
- Applied modifications
- Errors and warnings
- System diagnostics

## Support

For support, please open an issue on GitHub or contact support@ecutools.com

## License

This project is licensed under the MIT License - see the LICENSE file for details.
