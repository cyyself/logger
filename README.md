# Logger
A kernel-based keylogger for Windows.

## Dependencies
* Windows 7 or higher
* .NET Framework v4.0

## Download
Simply [download](https://github.com/felipebocolowski/logger/releases/) the executable and run it.

## Usage
This software uses the .NET Framework to interact with `user32.dll` and `kernel32.dll` from `System` library and intercept all keys pressed by the input user and saving all the output to `log.txt` within the application path.

* Since 1.3.0.0, Logger is shown at the system tray by default. To hide it, execute by passing the `-s` parameter (`"Logger.exe" -s`).

## Credits
Licensed under the MIT License.
