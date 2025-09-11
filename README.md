*This will be a calculator desktop app for Windows*
- Recompile resource collection file (resources.qrc) after every resource change
- -- **pyrcc5 resources.qrc -o resources_rc.py**
- Create .exe file with command
- -- **pyinstaller --noconfirm --onefile --windowed --icon=icon.ico --hidden-import=PyQt5 main.py**

