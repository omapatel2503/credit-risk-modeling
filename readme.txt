### `app.py` - Single-File Executable

This project packages a Python script (`exe.py`) into a single, standalone executable file. This allows users to run the script on their system without needing to have Python or its dependencies installed.

-----

### Features

  * **Cross-Platform:** The executable can be built to run on different operating systems (Windows, macOS, Linux).
  * **Dependency Bundling:** All necessary libraries and dependencies are bundled directly into the executable.
  * **Ease of Use:** Users can simply double-click the executable to run the script.

-----

### Prerequisites

To build the executable from the source script, you need to have **Python** and **PyInstaller** installed on your system.

To install PyInstaller, run the following command:

```bash
pip install pyinstaller
```

-----

### Installation

You can use the executable directly, or you can run the Python script from its source code.

1.  **Using the Executable:**

      * Find the `exe.exe` (or similarly named) file in the `dist/` folder after building.
      * Simply double-click the file to run the program.

2.  **Using the Python Script:**

      * Clone or download this repository.
      * Install the required libraries listed in `requirements.txt` (if applicable).
      * Run the script directly using the command below.

-----

### Usage

Run the program from your terminal:

```bash
# To run the executable
.\exe.exe

# To run the script directly (requires Python)
python app.py
```

-----

### Building the Executable

To create the single executable file, navigate to the project directory in your terminal and run the following command:

```bash
python -m PyInstaller --onefile app.py
```

This will generate a `dist/` directory containing the `exe.exe` file and a `build/` directory with temporary files. The final executable is the file in the `dist/` folder.

-----

### License

This project is licensed under the MIT License. See the `LICENSE` file for more details.