# IDS Attack Simulation: Detecting a SYN Flood with Wazuh and Suricata

This project demonstrates an **Intrusion Detection System (IDS)** setup using **Wazuh** and **Suricata** to detect a **SYN flood attack**. The attack is simulated using **hping3** on a Kali Linux machine, targeting a victim machine. **Suricata** monitors network traffic while **Wazuh** processes system logs to detect and generate alerts for the attack.

## Files in this Project:
- **[Demo Project IPS_IDS.mp4](Demo_Project_IPS_IDS.mp4)**: Video demonstrating the IDS attack simulation and detection.
- **[IDS-1-Travaux.pdf](IDS-1-Travaux.pdf)**: Detailed documentation explaining the setup, configuration, and steps for the IDS attack simulation.

## Project Setup:
1. **Victim Machine**: Windows with **Wazuh Agent** installed.
2. **IDS Server**: Ubuntu running **Wazuh** and **Suricata** for log and traffic analysis.
3. **Attacker Machine**: Kali Linux, where the **hping3** attack is launched.

## Steps to Run the Simulation:
1. Install **Wazuh** and **Suricata** on the Ubuntu machine.
2. Configure **Wazuh Agent** on the Windows victim machine.
3. Run the **hping3** command from the Kali Linux machine to simulate the **SYN flood attack**.
4. Monitor Suricata’s logs for alerts related to the attack.

## Key Tools Used:
- **Wazuh**: For log management, file integrity monitoring, and intrusion detection.
- **Suricata**: For network traffic monitoring and analysis.
- **hping3**: For generating the SYN flood attack.

## How It Works:
- The **Kali Linux** machine launches a flood of SYN packets towards the **Windows victim machine**.
- **Suricata** detects the abnormal traffic and logs it.
- **Wazuh** analyzes the logs and generates alerts based on suspicious activities.

## Video Demo:
Watch the demo video to see the simulation in action and understand how **Wazuh** and **Suricata** work together to detect and respond to the attack.



Watch the demo video: [Watch Demo on Google Drive](https://drive.google.com/file/d/1YXdhdV0utL9DSgjkvrjXH4TTpMiwE4FD/view?usp=sharing)



## [Download Detailed Documentation - IDS-1-Travaux.pdf](IDS-1-Travaux.pdf)

## Requirements:
- Ubuntu or any Linux distribution to install **Wazuh** and **Suricata**.
- Kali Linux for launching the **hping3** attack.

## License:
This project is open-source and free to use.
