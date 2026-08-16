# m5stack-core2-firmware

Build artifacts for [m5stack-core2](https://github.com/ardroudi/m5stack-core2)
(private). Public so the device can fetch its own updates without carrying a
GitHub token in firmware.

**Nothing secret is here.** WiFi credentials live in the device's NVS, not in
the image — that is what makes publishing these safe.

| File | Purpose |
|---|---|
| `manifest.json` | Version and download URL the device polls |
| `ClaudeFace.ino.bin` | The firmware image |

Published automatically by CI on every push to the source repo's `main`.
