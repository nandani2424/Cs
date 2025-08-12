# Cs
# Computer Science Lecture Notes

## 1. Networking Basics
- **Network**: A group of interconnected devices for sharing resources and communication.
- **NIC (Network Interface Card)**: Hardware that connects a device to a network.
- **MAC Address**: Unique identifier assigned to a NIC.
- **LAN (Local Area Network)**: Network in a small area (office, school).
- **WAN (Wide Area Network)**: Network over a large geographical area.
- **Router**: Device that forwards data packets between networks.
- **Switch**: Connects devices within a LAN.
- **Hub**: Basic device for connecting network devices (less intelligent than switch).

---

## 2. IP Addressing

### 2.1 Types of IP Addresses
- **Private IP**
  - Used within a local network.
  - Examples:
    - `192.168.x.x`
    - `10.x.x.x`
    - `172.16.x.x – 172.31.x.x`
- **Public IP**
  - Assigned by ISP, accessible over the internet.

### 2.2 Special IPs
- **Loopback / Localhost** → `127.x.x.x`
- **APIPA (Automatic Private IP Addressing)**
  - Assigned when DHCP fails.
  - Range: `169.x.x.x`

---

## 3. IPv4 vs IPv6
- **IPv4**
  - 32-bit addresses.
  - Example: `192.168.1.1`
- **IPv6**
  - 128-bit addresses.
  - Example: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`

---

## 4. Protocols & Standards
- **IP (Internet Protocol)**: Governs addressing and routing.
- **DNS (Domain Name System)**: Converts domain names into IP addresses.
- **VPN (Virtual Private Network)**: Encrypts data, hides IP.
- **HTTP/HTTPS**: Web communication protocols.
- **FTP**: File Transfer Protocol.
- **SMTP/IMAP/POP3**: Email protocols.

---

## 5. Internet vs Intranet

| Feature        | Internet | Intranet |
|----------------|----------|----------|
| Scope          | Global   | Local/Private |
| Access         | Public   | Restricted |
| Example        | Google, WhatsApp | Office LAN |
| IP Type        | Public IP | Private IP |

---

## 6. Processor Architectures

| Architecture | Examples | Type |
|--------------|----------|------|
| x86          | Intel, AMD | Closed Source |
| ARM          | Qualcomm, Apple M-series | Closed Source |
| RISC-V       | Various | Open Source |

---

## 7. Devices in a Network
- **Mobile Phones**
- **Desktops / Laptops**
- **Servers**

---

## 8. Storage & Memory
- **RAM**: Temporary storage for active processes.
- **ROM**: Permanent storage for firmware.
- **Storage**: Long-term data storage (HDD, SSD).

---

## 9. Examples from Class
- **WhatsApp**: Uses public internet.
- **Phonebook analogy for DNS**: Domain = name, IP address = phone number.

---

## 10. Additional Notes from Whiteboard
- APIPA range: `169.x.x.x`
- Loopback: `127.x.x.x`
- Private IP common range: `192.168.x.x`
- DNS converts domain to IP.
- VPN hides IP and encrypts traffic.
- Network types: LAN, WAN, MAN.
- NIC is required to connect to a network.
- 
