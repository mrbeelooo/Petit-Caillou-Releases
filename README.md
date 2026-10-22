# PetitCaillou

**PetitCaillou** is a free four-stage phaser in the spirit of 1970s phase pedals, with a fully vector interface and three skins (Warm Red, Raw Alu, Cold Blue).

- **Windows 10/11 (64-bit)**: VST3 + standalone application
- **macOS 10.13 or later (Apple Silicon and Intel)**: AU, VST3 + standalone application

### Download
Go to the [**Releases**](../../releases/latest) page and download the zip for your system:
`PetitCaillou-<version>-win.zip` or `PetitCaillou-<version>-mac.zip`. Each Release's notes describe installation and features.

- **Windows**: copy the `PetitCaillou.vst3` folder to `C:\Program Files\Common Files\VST3\`, then rescan plugins in your DAW.
- **macOS**: follow `README.txt` (included in the zip). The plugin is free and not notarized by Apple: unblock it once with a single Terminal command (`xattr -dr com.apple.quarantine <path to the plugin>`).

Every Release includes `SHA256SUMS.txt` to check your downloads (Windows: `certutil -hashfile <zip> SHA256`; macOS: `shasum -a 256 <zip>`).

### Found a problem, have an idea?
Open an issue in the [Issues](../../issues) tab, with your system, your DAW, the plugin version and what happened.

### License
The plugin is free to use, including in commercial music productions. The source code is not distributed (all rights reserved). Built with JUCE and the Steinberg VST3 SDK. VST is a registered trademark of Steinberg Media Technologies GmbH. Audio Units is a trademark of Apple Inc.
