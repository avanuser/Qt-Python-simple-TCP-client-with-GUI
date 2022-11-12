# Qt-Python-simple-TCP-client-with-GUI
Qt Python simple TCP client with GUI (PySide6).

The program can be used to facilitate testing of TCP servers, etc.

Received messages can be seen in the main black field.
Transmitted messages can be assigned to individual buttons or entered into editable text fields during testing.
Additional black field in "TCP client" area is intended for displaying client's status messages.

If you need to migrate from PySide6 to PySide2 just rename "PySide6" to "PySide2" in imports and change the following lines at the end of main.py:

\# sys.exit(app.exec())  # PySide6
sys.exit(app.exec_())   # PySide2


![Qt Python simple TCP client with GUI](https://github.com/avanuser/Qt-Python-simple-TCP-client-with-GUI/blob/main/qt-python-simple-tcp-client-with-gui.png)
