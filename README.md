## Digispark ATtiny85 – Wi-Fi Security Demonstration

### Overview

This project demonstrates how a Digispark ATtiny85 USB development board can act as a USB HID device and simulate keyboard input on a Windows computer.

It explores security risks associated with malicious USB devices, particularly unauthorized Wi-Fi credential access and data exfiltration.

### Hardware Requirements

- Digispark ATtiny85 USB development board
- Windows computer
- Arduino IDE

### Technologies Used

- Arduino C/C++
- DigiKeyboard library
- USB HID emulation
- Windows Command Prompt
- PowerShell
- Windows WLAN utilities
- Webhook communication

### Attack Concepts Demonstrated

1. USB HID keyboard emulation.
2. Automated Windows command execution.
3. Wi-Fi profile information exposure.
4. Sensitive data extraction.
5. HTTP-based data exfiltration.
6. Concealment of command windows.
7. Temporary-file cleanup.

### Security Risks

A malicious USB device can potentially execute commands without the user's awareness when connected to an unlocked computer.

Unauthorized access to saved Wi-Fi credentials can expose private networks and connected devices.

### Defensive Recommendations

- Never connect unknown USB devices.
- Restrict unauthorized USB HID devices.
- Monitor unexpected Command Prompt and PowerShell activity.
- Monitor WLAN profile export operations.
- Inspect suspicious outbound HTTP requests.
- Use Windows Defender or an endpoint detection solution.
- Avoid storing sensitive information unnecessarily.

### Disclaimer

This repository is intended for cybersecurity education, security awareness, and authorized laboratory research only.

The original credential-extraction and exfiltration functionality is not provided as a deployable demonstration. Never collect, transmit, or disclose credentials without explicit authorization.

**Platform:** Digispark ATtiny85  
**Programming Language:** Arduino C/C++  
**Category:** USB HID Security | Wi-Fi Security | Cybersecurity Research
