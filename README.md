# Screen Recorder

A simple **Windows Screen Recorder** inspired by open-source recording tools such as Recorderly.

This project is mainly intended as a **learning project, starting point, and base implementation** for anyone who wants to build or experiment with a screen-recording application.

> **Note:** This is not a production-ready replacement. It is an independent implementation inspired by existing open-source concepts and may contain bugs, limitations, or unfinished features.

## Features

- Screen recording on Windows
- Audio recording
- System audio recording
- Cursor tracking
- Click-based zoom effects
- Custom cursor support
- Custom cursor can replace the user's actual cursor in the recorded video
- Simple recording workflow
- Windows `.exe` build included
- Full source code included

### Cursor Zoom

The recorder can add a small zoom effect around the cursor when the user clicks.

This helps make important actions more visible in tutorials, demonstrations, and screen-recording videos.

Currently, the cursor zoom effect is relatively basic and **does not include advanced smoothing or animation interpolation**.

### Custom Cursor

Users can configure a custom cursor that will be displayed in the final recording instead of the normal system cursor.

This can be useful for creating tutorials, demonstrations, presentations, and other instructional videos.

## Installation

The easiest way to install and run the application is through the provided repository.

### 1. Download the Repository

Download the complete repository and extract the ZIP file.

### 2. Open the Extracted Folder

After extracting the repository, you will find the required files inside the project folder.

### 3. Run the Installer

Run the provided `.exe` file located inside the extracted repository folder.

The application will automatically perform the required installation/setup.

### 4. Start Screen Recorder

After installation, launch **Screen Recorder** and start recording.

No complicated manual setup should be required.

## Development

The complete source code is included in this repository.

You can use the project as a **base for your own screen-recording application**, modify the existing features, fix bugs, improve the recording engine, or add completely new functionality.

Some areas that could be improved include:

- Better cursor smoothing
- More advanced zoom animations
- Improved recording performance
- Better audio synchronization
- More recording formats
- Additional video settings
- Better error handling
- Multi-monitor improvements
- More customization options

## Known Limitations

This project is still relatively basic and may contain bugs.

In particular:

- Cursor zoom is not highly polished.
- Cursor movement does not currently have advanced smoothing.
- Some features may behave differently depending on the Windows configuration.
- Recording performance may vary between systems.
- Some edge cases may not be handled correctly.

If you encounter a bug, feel free to investigate the source code and improve it.

## Why This Project Exists

The goal of this project is to provide a **working starting point** for developers who want to learn how screen-recording software works or want to build their own recorder from an existing foundation.

Instead of starting completely from scratch, you can use this repository as a base and gradually improve it.

## License

Check the repository for the applicable license and the licenses of any third-party components used by the project.

## Disclaimer

This project is an independent implementation and is not affiliated with, endorsed by, or officially connected to Recorderly.

Use the software at your own discretion.
