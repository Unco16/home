This repository provides an overview of some of my IT projects, home lab setup, tools I've worked with, and technical hobbies.

---

## 🛠 Tools & Platforms I've Worked With

The following tools are part of my professional experience but are not listed on my CV:

- **Support & Collaboration Tools:** Zendesk, RingCentral, Guru
- **Cloud & Identity Management:** Azure AD / Enterprise Applications (SSO)
- **APIs & Network testing:** Postman (REST API testing), Nmap
- **Remote Access & Troubleshooting:** TeamViewer, VNC, AnyDesk  
- **Virtualization:** VirtualBox, QEMU/KVM, VMware Workstation


---

## 🏠 Home Lab & Network / Infrastructure Projects

I maintain a home server running **Proxmox** to explore virtualization, networking, and security concepts.

### Virtual Machines & Containers
- **pfSense VM** – Main firewall

**pfSense Configuration Highlights
- Multiple physical interfaces (1 WAN, 2 LAN), with segmented VLANs:
  - Main VLAN for trusted devices
  - IoT VLAN, VoIP VLAN, IP Camera VLAN, Guest VLAN  
- **Traffic Monitoring:** ntopng integration  
- **VPN:** OpenVPN server for remote access + selective VLAN routing through VPN  
- **Wi-Fi Setup:** Access points mapped to dedicated VLANs for better segmentation


- **Pi-hole Container** – Ad blocking & local DNS  
- **Home Assistant VM** –  
  - Smart home automation (lights, alarms, Sonos, TVs) using of scripts and Node Red.
  - LED matrix displays for time/date, events, stock prices, notifications
  - Centralized sensors (temperature/humidity, light sensor, motion sensor)
  - MQTT broker (Mosquitto)
  - ZigBee gateway integration
- **Wazuh VM** – Monitoring and security event management  
- **Ubuntu VM** – NFS server  
- **Linux Test VMs** – Ubuntu, Debian for experimentation
- **Jellyfin Server** – Media streaming  


---

## 🎨 Technical Projects & Hobbies

### 🔌 Electronics & Microcontrollers
- Programming & IoT: Developed projects with ESP32, ESP8266, and Arduino using APIs, REST/JSON data, and MQTT protocols (crypto/stock ticker displays, WS2812B LED setups, synchronized electronic Airsoft targets).
- Hardware Skills: Performed basic electronics repair (fault isolation, component replacement) and circuit prototyping.

### 🖨️ 3D Design & Fabrication
- **CAD:** Fusion 360 for modeling
- **3D Printing:** Functional parts and prototypes using Creality printers  
  - Workflow with Cura slicer & OctoPrint server

### 🚁 Drones & Robotics
- Building and tuning custom drones (PID tuning, component selection)
- Programming flight controllers (Betaflight, F4 boards)
- Configuring RC transmitters & receivers (FrSky)
- Flying both assisted drones (DJI) and manual FPV drones (GEPRC, Mobula)
