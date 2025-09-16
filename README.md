# Calculator Desktop App for Windows
### This is a Calculator Desktop Application built for Windows.  
## Resource Compilation  
After every change to the resource file, recompile it using the following command:  
`pyrcc5 resources.qrc -o rc_resources.py`  
## Building the Executable  
To create the desktop application executable, run:  
`pyinstaller --noconfirm --onefile --windowed --icon=icon.ico main.py`
This will bundle the app into a standalone executable.  

- -- **pyinstaller --noconfirm --onefile --windowed --icon=icon.ico --hidden-import=PyQt5 main.py**

