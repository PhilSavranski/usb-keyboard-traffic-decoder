# USB Keyboard Decoder

This repository contains a Python script designed to decode USB keyboard data captured in hexadecimal format. The script translates USB HID scancodes into human-readable keystrokes by mapping each byte to its corresponding character.

## Context
This code was written as part of the **Huntress CTF 2024** event to solve the "Keyboard Junkie" challenge. The traffic was extracted from a PCAP file.

## Features
- Decodes USB keyboard scancodes from hex data.
- Maps scancodes to standard alphanumeric characters and special keys.
- Outputs the decoded keystrokes in real-time.

## How to Use
1. Extract USB keyboard data from a PCAP file (e.g., using `tshark`).
2. Prepare a file (`extract.txt`) containing hex-encoded USB keyboard data.
3. Run the script to decode the data and display the keystrokes.

## Example Usage
```bash
python keyboard.py
