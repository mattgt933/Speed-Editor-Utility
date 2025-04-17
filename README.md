# Speed Editor Utility

## Overview

Speed Editor Utility is a software tool designed to enhance the functionality of your BMD Speed Editor. It provides customizable key mappings, software support, and seamless integration with popular editing software, allowing users to streamline their editing workflows.

## Features

- **Custom Key Bindings**: Reassign keys on your Speed Editor to suit your editing style.
- **Software Integration**: Compatible with Adobe Lightroom, Bitfocus Companion, and and as a generic keyboard.
- **User-Friendly Interface**: Intuitive GUI for easy configuration and setup.

## Installation

1. **Download the Latest Release**:
   - Visit the Releases page and download the latest version for your operating system.
2. **Install the Software**:
   - For Windows: Run the `installer.exe` installer and follow the prompts.
3. **Connect Your Speed Editor**:
   - Plug in your Speed Editor device via USB or connect via Bluetooth.
4. **Launch the Utility**:
   - Open the application. It will start in the background. To open it go to the hidden icons tab in the task bar.

## Usage

1. **Configure Key Bindings**:
   - Open the utility and navigate to the "Hot Keys" tab.
   - Select a key on the virtual Speed Editor layout and assign a keystroke.
2. **Adobe Lightroom**:
   - Go to the "Lightroom" tab and press "Start" if you opened Lightroom after the Speed Editor Utility application.
3. **Bitfocus Companion**:
   - Go to the "Companion" tab and enter the ip address of the computer running Companion.
   - In companion, turn on OSC Listener in Setting > Protocols.
   - Enter the OSC Listen Port port number into the "Port" input.
   - Enter the page you want your Speed Editor to send commands to. There is a template Companion page comfiguration you can download. Each of the buttons are labled with what button on the Speed Editor presses them.
   - Enter the button you want the scroll wheel to control. It only send rotate-left and rotate-right commands. This button does not have to be on the same page as the rest of the buttons. Enter it in the standard order: {page}/{row}/{column}


## System Requirements

- **Operating System**: Windows
- **Supported Devices**: Blackmagic Design Speed Editor


## License

See the LICENSE file for details.

## Support

For issues, feature requests, or questions:

- Open an issue on the GitHub Issues page.

## Acknowledgments

- Thanks to  Sylvain "tnt" Munaut for providing the authentication code. https://github.com/smunaut/blackmagic-misc/
