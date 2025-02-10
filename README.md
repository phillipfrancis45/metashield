# MetaShield

MetaShield is a Python application designed to fine-tune display settings for various applications on Windows to ensure optimal visual performance. It allows you to configure settings such as brightness, contrast, resolution, and refresh rate.

## Features

- Adjust display brightness and contrast
- Configure resolution and refresh rate
- Save and load display settings from a file

## Installation

1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

2. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/metashield.git
    ```

3. Navigate to the cloned directory:
    ```bash
    cd metashield
    ```

## Usage

1. Customize the display settings in the `MetaShield` class as needed.
2. Run the program:
    ```bash
    python metashield.py
    ```
3. The program will load settings from `settings.json` (if available) and apply them. Otherwise, it will use default settings.

## Configuration

- You can modify the default settings directly in the `MetaShield` class or by editing the `settings.json` file created after running the program for the first time.

## Saving and Loading Settings

- **Save Settings:** Save current settings to a file for later use.
- **Load Settings:** Load settings from a file to quickly apply a preferred configuration.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Disclaimer

The current implementation uses simulated functions for changing display settings. Actual implementation would require hardware-specific APIs or system calls.