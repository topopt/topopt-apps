# TopOpt apps: downloads

Desktop versions of the interactive topology optimization apps from the
[TopOpt group](https://www.topopt.mek.dtu.dk) at the Technical University of Denmark (DTU).
TopOpt 2D for phones and tablets: [App Store](https://apps.apple.com/app/topopt/id507454646) (iPhone, iPad) and [Google Play](https://play.google.com/store/apps/details?id=com.TopOpt.TopOpt) (Android).

TopOpt 3D for phones and tablets: [App Store](https://apps.apple.com/app/topopt-3d/id881472301) (iPhone, iPad) and [Google Play](https://play.google.com/store/apps/details?id=com.TopOpt.TopOptApp3D) (Android).

## TopOpt 2D, version 3.0

Place loads and supports, and the optimized structure appears and updates in real time.
Minimum compliance and compliant mechanisms (force inverter, gripper), extended with a local
volume constraint for bone-like infill, a stress constraint and the robust formulation.
More, and the user guide: [Interactive 2D TopOpt App](https://www.topopt.mek.dtu.dk/apps-and-software/interactive-2d-topopt-app).

| Platform | Download |
|---|---|
| macOS 14 or later (Apple Silicon, M1 or later) | [TopOpt2D_v3.0_macOS.zip](https://github.com/topopt/topopt-apps/releases/download/topopt2d-v3.0/TopOpt2D_v3.0_macOS.zip) |
| Windows 10/11 (64-bit) | [TopOpt2D_v3.0_Windows.zip](https://github.com/topopt/topopt-apps/releases/download/topopt2d-v3.0/TopOpt2D_v3.0_Windows.zip) |
| Linux x86_64 (double-click) | [TopOpt2D_v3.0_Linux.AppImage](https://github.com/topopt/topopt-apps/releases/download/topopt2d-v3.0/TopOpt2D_v3.0_Linux.AppImage) |
| Linux x86_64 (plain folder) | [TopOpt2D_v3.0_Linux.tar.gz](https://github.com/topopt/topopt-apps/releases/download/topopt2d-v3.0/TopOpt2D_v3.0_Linux.tar.gz) |

## TopOpt 3D, version 3.0.1

Place loads, supports and passive regions in a box-shaped design domain, and the optimized
structure appears and updates in real time. Minimum compliance under up to four load cases and
compliant mechanisms (force inverter, gripper), extended with a local volume constraint for
bone-like infill, a stress constraint, the robust formulation and min-max design. STL files can be
imported as the design domain, and the design is exported as STL or OBJ.
More, and the user guide: [Interactive 3D TopOpt App](https://www.topopt.mek.dtu.dk/apps-and-software/interactive-3d-topopt-app).

| Platform | Download |
|---|---|
| macOS 14 or later (Apple Silicon, M1 or later) | [TopOpt3D_v3.0.1_macOS.zip](https://github.com/topopt/topopt-apps/releases/download/topopt3d-v3.0.1/TopOpt3D_v3.0.1_macOS.zip) |
| Windows 10/11 (64-bit) | [TopOpt3D_v3.0.1_Windows.zip](https://github.com/topopt/topopt-apps/releases/download/topopt3d-v3.0.1/TopOpt3D_v3.0.1_Windows.zip) |
| Linux x86_64 (double-click) | [TopOpt3D_v3.0.1_Linux.AppImage](https://github.com/topopt/topopt-apps/releases/download/topopt3d-v3.0.1/TopOpt3D_v3.0.1_Linux.AppImage) |
| Linux x86_64 (plain folder) | [TopOpt3D_v3.0.1_Linux.tar.gz](https://github.com/topopt/topopt-apps/releases/download/topopt3d-v3.0.1/TopOpt3D_v3.0.1_Linux.tar.gz) |

Example files: [jet engine bracket](https://github.com/topopt/topopt-apps/releases/download/topopt3d-v3.0/TopOpt3D_v3.0_jet-engine-bracket.zip) (three STL files, used in the guide's tutorial).

## Installation

- **macOS:** unzip and move the app to Applications. The app is not notarized by Apple yet, so the
  first start is blocked: open it once, then choose System Settings > Privacy & Security > Open Anyway.
- **Windows:** unzip and run `TopOpt2D.exe` (TopOpt 2D) or `TopOpt3D.App.exe` (TopOpt 3D) in the folder. The app is not signed yet, so Windows
  SmartScreen may warn: choose More info > Run anyway. If it reports a missing VCRUNTIME140 or
  MSVCP140 DLL, install the [Microsoft Visual C++ Redistributable (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe).
- **Linux (AppImage):** `chmod +x TopOpt2D_v3.0_Linux.AppImage` (TopOpt 3D: `TopOpt3D_v3.0.1_Linux.AppImage`), then run it.
- **Linux (tar.gz):** `tar -xzf TopOpt2D_v3.0_Linux.tar.gz` and run `TopOpt2D` in the folder (TopOpt 3D: `TopOpt3D_v3.0.1_Linux.tar.gz` and `TopOpt3D.App`).

All versions: [releases](https://github.com/topopt/topopt-apps/releases).

## Privacy

The apps collect no data and do not connect to the internet: [privacy policy](https://www.topopt.mek.dtu.dk/apps-and-software/app-privacy-policy).

Questions: Niels Aage, naage@dtu.dk
