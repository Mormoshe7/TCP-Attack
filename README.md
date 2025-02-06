# TCP-Based Network Attacks Project

This project demonstrates various TCP-based attacks, including SYN Flood, TCP RST attacks on Telnet and SSH connections, TCP RST attacks on video streaming applications, and TCP Session Hijacking. The goal is to understand how these attacks exploit vulnerabilities in the TCP protocol to disrupt services, disconnect active connections, or hijack sessions. The project includes detailed steps, tools used, and outcomes for each attack.

## Files
- **211783519_323915363_315824508.docx**: The main report document detailing the attacks and their outcomes.

## Tools and Techniques
1. **SYN Flood Attack**: Overwhelms the server with SYN requests, causing it to become unresponsive.
2. **TCP RST Attacks**: Disrupts active Telnet and SSH connections by sending forged RST packets.
3. **TCP RST Attacks on Video Streaming**: Interrupts video streaming by sending a TCP RST packet to the client.
4. **TCP Session Hijacking**: Attempts to hijack an active TCP session by guessing sequence numbers.

## Usage
To replicate or understand the attacks:
1. Review the **211783519_323915363_315824508.docx** file for detailed steps and findings.
2. Use the mentioned tools (HPing3, Netwox, Wireshark, Python) to perform similar attacks.
3. Ensure ethical use and proper authorization before conducting any network attacks.

## Ethical Considerations
This project is for educational purposes only. Ensure you have proper authorization before conducting any network attacks. Unauthorized access to computer systems is illegal and unethical.

## Requirements
- **HPing3**: For crafting and sending custom TCP packets.
- **Netwox**: For network manipulation and attack execution.
- **Wireshark**: For network traffic analysis and packet inspection.
- **Python**: For scripting custom attack scenarios.

## Installation
1. **HPing3**: Install via package manager (e.g., `sudo apt-get install hping3`).
2. **Netwox**: Download and install from the official website or package manager.
3. **Wireshark**: Install via package manager (e.g., `sudo apt-get install wireshark`).
4. **Python**: Ensure Python is installed (e.g., `sudo apt-get install python3`).
