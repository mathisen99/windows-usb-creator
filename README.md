# Bootable USB Creator

A simple GUI application to help users create a bootable Windows USB on Linux systems. The application is built using Python's `tkinter` module.

## Features

- Intuitive GUI to select a Windows ISO file.
- Display and selection of attached USB drives.
- Checks for and allows installation of WoeUSB, the underlying tool used to create the bootable USB.
- Informative status updates and prompts.

## Prerequisites

- Python 3.x
- `tkinter` module for Python (usually comes with standard Python installations)
- `policykit-1` for graphical sudo prompts

## Usage

1. Clone the repository:
```git clone foobar ```
2. Run the application:
```python3 main.py```
3. Follow the on-screen instructions to select an ISO file and a USB drive.
4. Install WoeUSB if not already installed.
5. Click on "Create Bootable USB" to start the process.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)