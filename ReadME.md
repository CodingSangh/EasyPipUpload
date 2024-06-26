## EasyPipUpload(Pip Script Uploader) for PyPi

This Flask application provides a user-friendly graphical user interface (GUI) for effortlessly uploading your Python scripts to the Python Package Index (PyPI). No more command-line struggles!

## Features:

- Simplified Uploading: Upload your Python script directly through the GUI, bypassing the need for complex command-line interactions.
- Intuitive Interface: The straightforward layout makes the upload process clear and easy to follow, even for users unfamiliar with PyPI or command-line tools.
- Python Packaging Essentials: Leverages Flask to create a web-based GUI, and includes necessary dependencies in requirements.txt for a seamless setup.
Installation:

## Install the package from PyPI:

### Installation:
```bash
pip install EasyPipUpload
```

### Usage:

Ensure you have a PyPI account and have obtained the necessary API credentials(API Key) for uploading packages.

```bash
import runpy
from EasyPipUpload import run_app

runpy.run_module(mod_name='run_app', run_name='__main__', alter_sys=True)
```

It will automatically open the web browser and you can see the GUI for uploading the script.



## License:

MIT License (https://opensource.org/license/mit)

## Contributions:

Feel free to submit pull requests to improve this project! We welcome contributions that enhance functionality, fix bugs, or improve the user experience.
