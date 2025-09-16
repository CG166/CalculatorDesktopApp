# Calculator Desktop App for Windows
### This is a Calculator Desktop Application built for Windows.  
## Resource Compilation  
After every change to the resource file, recompile it using the following command:  
`pyrcc5 resources.qrc -o rc_resources.py`  
## Building the Executable  
To create the desktop application executable, run:  
`pyinstaller --noconfirm --onefile --windowed --icon=icon.ico main.py`  
This will bundle the app into a standalone executable.  
## Installing the App (.exe Installer)
1. Download the installer file: [calculator.exe](https://github.com/CG166/CalculatorDesktopApp/blob/main/Output/calculator.exe)

2. Install the application by double-clicking the ***calculator.exe*** file and follow the installation instructions.
## Uninstalling the App
To remove the calculator application
