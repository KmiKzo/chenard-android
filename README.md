
# Chenard for Android ♟️📱

An unofficial Android port of **Chenard**, the classic open-source C++ chess engine originally created by **Don Cross**.

This repository provides a playable Android build and the necessary adaptations to run Chenard natively on modern ARM-based Android devices.

## 🌟 About the Project

Chenard is well-known among computer chess enthusiasts for its unique playing style and its ability to learn from its own games by building an opening book over time. While official versions exist for Windows and Linux, there was previously no readily available port for Android.

This project bridges that gap so retro-chess fans can enjoy playing against Chenard directly on their smartphones and tablets.

## 🚀 Features & Installation

* **Native ARM Execution:** Compiled specifically for Android architectures (`arm64-v8a`).
* **Playable on Android:** [Hier kurz anpassen, z. B.: *Standalone Android app with a clean chessboard interface* ODER *Packaged as an OEX engine compatible with apps like Chess for Android and DroidFish*.]

### How to Install
1. Go to the **[Releases](../../releases)** section of this repository.
2. Download the latest `.apk` file onto your Android device.
3. Open the file to install it (you may need to allow installation from unknown sources in your Android settings).
4. [Falls OEX-Engine, hier ergänzen: *Open your favorite OEX-compatible chess GUI (e.g., Chess for Android) and select Chenard as the active engine.*]

## 🛠️ How It Was Built

Porting the original C++ codebase to Android required adapting file I/O paths for Android's storage permissions and cross-compiling the source code for ARM processors using the Android NDK. 

*Transparency note:* The porting process, troubleshooting, and Android build configuration were developed with the assistance of AI tools, guided and tested on real Android hardware.

## 🙏 Credits & License

* **Original Chess Engine:** All credit for the chess engine logic, algorithms, and original C++ source code goes to **Don Cross** ([Original Chenard Repository](https://github.com)).
* **Android Port:** Maintained by **Ahmet Delice**.

This port respects the original open-source / public domain spirit of Don Cross's work. Please refer to the original repository for full source code history and licensing details.
