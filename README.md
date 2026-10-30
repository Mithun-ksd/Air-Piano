# Air Piano

> Play a piano in the air using hand tracking.

Air Piano lets you play a virtual piano by pointing your index finger at keys on the screen. It uses your camera and hand tracking, so you do not need a physical keyboard or touch input.

## Download

**Windows executable:** [Download the latest release](../../releases/latest)

1. Open the latest release.
2. Download the `Air Piano.exe` file from the **Assets** section.
3. Run the downloaded file on a compatible Windows computer.

Only download releases published from this repository. Windows may display a SmartScreen or antivirus warning for an unsigned or less widely downloaded application. Do not bypass a warning unless you trust the publisher and have independently verified the file.

## How to use

1. Sit or stand about an arm's length from the camera, with light in front of you.
2. Launch Air Piano. Your camera view and a piano keyboard should appear.
3. Point your index fingertip at a piano key to play it. You can use one or both hands.
4. Use the Up and Down arrow keys to adjust volume. Press M to mute or unmute.
5. Press Q or Esc to quit.

## Features

- 13 virtual keys: 8 white and 5 black, spanning C to the next C
- Supports two hands at the same time
- Computer-generated piano-like sound; no audio files required
- Visual key feedback when a note is played
- Stabilized fingertip pointer
- Volume controls and mute

## Keyboard controls

| Key | Action |
|---|---|
| Up / Down | Increase / decrease volume |
| M | Mute / unmute |
| Q / Esc | Quit |

## How it works

1. The camera captures frames while the application is running.
2. MediaPipe Hands detects a hand and estimates 21 landmarks on it.
3. The application tracks the index fingertip landmark.
4. When the fingertip overlaps a piano key, the corresponding note is played.

## Camera and privacy

The application uses your camera to track hand movement. Use it only in a setting where people being recorded by the camera have agreed to its use. The publisher has not made a claim here about network traffic; consult the application's behavior and your firewall/network monitor if offline operation is important.

The application may display or process camera imagery. Obtain consent before using a camera where other people may be visible. Avoid capturing or sharing images of people without their permission.

## System requirements

- A Windows computer.
- A working camera.
- Sufficient lighting for reliable camera detection.
- A keyboard for the controls listed above.

The publisher should add the tested Windows versions, minimum hardware requirements, and any known limitations here after testing the release on a clean Windows installation.

## Troubleshooting

- **Camera not available:** Close other applications that may be using the camera and check Windows camera permissions.
- **Detection is unstable:** Improve lighting, keep the relevant hand or face in view, and avoid blocking it.
- **Application does not start:** Confirm that you downloaded the latest release from this repository. If the issue continues, report it using the repository's Issues page and include your Windows version and the exact error message. Do not attach private images or personal data.

## Security

See [SECURITY.md](SECURITY.md) for how to report a security concern.

## Third-party components

See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for the direct dependencies declared for this app. The final executable may contain additional transitive or bundled components; their notices must also be reviewed and included as required.

## License

Copyright (c) 2026 Mithun C. All rights reserved. See [LICENSE](LICENSE).

This repository distributes the compiled application only. The application's source code is not included.
