# Third-party notices — Air Piano

This application declares the following direct Python dependencies. These entries identify their upstream project licenses; they are **not a complete binary bill of materials** for the final `.exe`.

### MediaPipe 0.10.14
- Declared package license: Apache License 2.0.
- Project: https://github.com/google-ai-edge/mediapipe
- Exact package metadata: https://pypi.org/project/mediapipe/0.10.14/
- Preserve the upstream LICENSE and any NOTICE/third-party notices shipped with the exact wheel. MediaPipe wheels include native/bundled components, so this entry alone is not a complete inventory of all binary contents.

### OpenCV Python package 4.10.0.84
- Python distribution package (`opencv-python` or `opencv-contrib-python`) license: MIT.
- OpenCV library: Apache License 2.0 (OpenCV 4.5.0 and later).
- Project/package: https://github.com/opencv/opencv-python
- Package licensing notes: https://pypi.org/project/opencv-python/4.10.0.84/
- The Windows wheels bundle additional components, including FFmpeg; the package's `LICENSE-3RD-PARTY.txt` and other bundled notices must be retained/reviewed. FFmpeg is identified by the package project as LGPLv2.1.

### NumPy 1.26.4
- Project license: BSD 3-Clause.
- Project: https://numpy.org/
- License information: https://github.com/numpy/numpy/blob/v1.26.4/LICENSE.txt
- Note: binary wheels may bundle additional components (for example, BLAS libraries) with their own notices. Preserve the license files shipped with the exact wheel/build.

### Pygame 2.6.1
- License: GNU Lesser General Public License version 2.1 (LGPL-2.1).
- Project: https://www.pygame.org/
- Exact package metadata and dependency/license notes: https://pypi.org/project/pygame/2.6.1/
- Pygame depends on SDL and related multimedia libraries, which have their own license notices. Retain the LGPL text and all notices shipped with the exact Windows wheel/build. Because this app is distributed as a bundled executable, verify that the packaging and distribution method satisfies the LGPL conditions before publishing.
