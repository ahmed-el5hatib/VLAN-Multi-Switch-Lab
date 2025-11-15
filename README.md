# VLAN Multi-Switch Lab (CCNA)

This is a practical, hands-on lab demonstrating how to configure VLANs and 802.1Q Trunking across multiple switches. The goal is to properly segment a network for security while allowing specific VLANs (like the Development team) to span multiple physical locations.

## 🚀 Interactive Lab Demo (Live)

You can view the full, interactive walkthrough for this lab—complete with a detailed scenario, CLI commands, and explanations—hosted live on GitHub Pages.

[**➡️ Click Here to View the Interactive Lab Demo**](https://ahmed-el5hatib.github.io/VLAN-Multi-Switch-Lab/)


##  Topology (Network Diagram)

This is the logical topology designed for the "Pro-Dev Solutions" scenario, as implemented in the Packet Tracer file.

![Lab Topology](topology.png)


## 🗂️ Lab Files

This repository contains the following files:

* **`index.html`**: The interactive HTML/CSS/JS file used for the GitHub Pages live demo.
* **`VLAN-Multi-Switch-Lab.pkt`**: The Cisco Packet Tracer source file. You can download this to run the simulation yourself. (Remember to upload your `.pkt` file and rename this link accordingly).

---

### Lab Scenario & Technologies

* **Scenario:** "Pro-Dev Solutions" office expansion.
* **Technologies:** VLANs, `switchport mode access`, `switchport mode trunk`, 802.1Q encapsulation.
* **VLANs Configured:**
    * **VLAN 10:** DEVELOPERS (Spans SW1 & SW2)
    * **VLAN 20:** ADMIN (On SW1)
    * **VLAN 30:** MARKETING (On SW2)
