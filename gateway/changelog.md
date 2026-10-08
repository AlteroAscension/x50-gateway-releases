# X50 Gateway 2.30.19-sensor-transport

- Bundles ESP firmware 1.1.21 with negotiated USB baud: 921600, 460800 and 115200 fallback.
- Separate CRC-protected binary live snapshots at 20 Hz and timestamped sensor history; legacy USB clients remain supported.
- Separate USB reading, processing and request scheduling; OTA is paced at the active baud rate.
- Pipeline Wi-Fi requests and accelerate history catch-up without reviving stale live steering.
- Report active USB baud, processing delay, cursor losses and history queue age.
- Install the Magisk module and reboot, then update ESP firmware from Gateway. Use Navigation 0.15.100 and Simulator 1.11.23 for linked compact trip journals. Relay needs no update.

High-speed UART stability on the actual head unit still requires a live test; fallback is automatic.