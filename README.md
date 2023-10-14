<div align="center">

<img src="https://github.com/onhq11/TrayDrop/blob/main/img/banner.jpg?raw=true" style="border-radius: 20px"><br><br>

# TrayDrop

High privacy and Lightweight Files and Clipboard cloud storage with share feature.<br>
**[Check it out »](https://traydrop.pl/)**<br><br><br>
**[Website](https://traydrop.pl/) · [Desktop App](https://github.com/onhq11/Traydrop) · [TrayDrop Server](https://github.com/Szurag/TrayDropLaravel) · [TrayDrop CLI](https://github.com/onhq11/Traydrop-cli) · [Mobile App (in progress)](about:blank)**

</div><br><br>

## About

TrayDrop is an open-source website that allows you to upload files and clipboard content to the server and automatically synchronize between devices using websockets. Traydrop is also providing share links with expiration date, for easy share files. This lightweight solution will run even on the slowest machines, with instant synchronization. We offer our [Website](https://traydrop.pl/), [Desktop app](https://github.com/onhq11/Traydrop) and [Command line tool](https://github.com/onhq11/Traydrop-cli), but if you have an iOS based phone, you can use our Apple Shortcuts for faster access from the sharing drawer [Send to Traydrop](https://www.icloud.com/shortcuts/216ad9c4c6874202a36bbe2e14722118) and [Share via Traydrop](https://www.icloud.com/shortcuts/4c6c3fed6eb94ae6acae0142efc409a3). Also if you want to set up a server on your hardware, you can do it using our [TrayDrop Server](https://github.com/Szurag/TrayDropLaravel) based on Laravel. There you will find a guide on how to do it and enjoy your private server.

## How to use?
- Download tool from [releases menu](https://github.com/onhq11/Traydrop-cli/releases) (choose latest version)
- Go to [credentials page](https://traydrop.pl/credentials) and copy credentials
- Install using dpkg tool ```sudo dpkg -i traydrop.deb```, when you will be prompted paste your credentials
- If your package will be installed successfully you can use ```traydrop <file>``` to send file to Traydrop (example: ```traydrop index.html```)

## Command line tool roadmap
Now our tool is in early alpha and we have created this cli in 10 minutes, so don't expect too much.

- Replace credentials with login form
- Add clipboard send

## Used technologies

- Shell (Script)
- dpkg-deb (Installer)

## Features

- Easy installation
- Easy file send

## Contributors

The project needs contributors to test the application in terms of privacy, vulnerability and bugs. If so, feel free to [open an issue](https://github.com/onhq11/Traydrop-cli/issues) or [pull request](https://github.com/onhq11/Traydrop-cli/pulls)

## Authors

- [@onhq11](https://github.com/onhq11)
