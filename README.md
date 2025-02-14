# GCO (Graphic Creation Object)

GCO is a powerful tool that simplifies the creation of simple/basic Windows interfaces using the Win32 API for c/c++ win32 developers. With GCO, you can visually design windows with buttons, edit boxes, combo boxes, colors, and fonts without writing a single line of code.

## Features

* **Visual Interface Design**: Create your Windows UI by dragging and dropping elements, customizing their appearance and properties in a user-friendly environment.
* **No Code Required**: Design complex interfaces without needing to write any C code. GCO handles the underlying Win32 API calls for you.
* **Export to C Source Code**: Generate clean and well-structured C Win32 source code from your visual designs. This code can be directly integrated into your projects.
* **Resource Loading**: GCO saves your designs in a `.gco` file, which can be loaded as a resource in your application. This allows you to easily recreate your UI at runtime.
* **Customization**: Full control over the look and feel of your interface with options for colors, fonts, and element properties.

## How to Use

1. **Design your interface**: Use the GCO editor app to create your window, add elements, and customize their appearance.
2. **Export to .gco file**: Save your design as a `.gco` file.
3. **Generate C source code (optional)**: Export your design as C Win32 source code if you want to further customize it.
4. **Load the .gco resource**: Include the `.gco` file as a resource in your application and load it at runtime to create your interface.

## Installation

1. **Download the appropriate release**: Go to the [Releases] page and download the setup executable for your system (x86 or x64).
2. **Run the setup**: Execute the downloaded file and follow the instructions to install GCO.
3. ** you can Also use a test 's folder also in Releasem if you don't want any installation.
## Example Usage

The `expleOfProduct` folder contains another app(manitext.exe) that demonstrates how to use GCO to create a simple Windows application. You can explore this project to learn how to:

* Create a window with various UI elements.
* Load a `.gco` file as a resource.

## Releases

GCO is distributed as pre-built executables for x86 and x64 architectures. You can find the latest releases on the [Releases] page. Each release includes:
**Setup** for both x86 and x64 architecture
**test app .exe** for both x64 and x86 architecture, note theses .exe, need to be executed with dll present in the same folder.
## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to report bugs or suggest new features.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
## Contact
edouardochristian4@gmail.com
