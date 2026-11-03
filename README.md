# 🔐 Cybersecurity Lab Setup – Week 1 (WK1-PM1)

**Program:** NetworkWalks Cybersecurity Program  
**Participant:** Dhoni Kumar Shah  
**Cohort:** B082  
**Project:** WK1-PM1 – Cybersecurity Lab Setup  
**Platform:** Oracle VirtualBox

---

## 📌 Project Overview

This project focuses on building a virtual cybersecurity testing environment using Oracle VirtualBox.

The lab consists of Kali Linux as the attacking machine and Windows 10 as the target machine.

Both virtual machines are configured with NAT and Host-only networking to support internet connectivity and communication within the lab environment.

## 🖥️ Lab Environment

| Component | Configuration |
|---|---|
| Virtualization | Oracle VirtualBox |
| Attacking Machine | Kali Linux |
| Target Machine | Windows 10 |
| Network Modes | NAT and Host-only |
| NAT Subnet | 10.0.2.0/24 |
| NAT DHCP | Enabled |
| Kali Host-only IP | 192.168.10.2 |
| Windows 10 Host-only IP | 192.168.10.3 |
| Internet Connectivity | Working |

**Configuration note:** The reference project specifies NAT subnet 10.0.0.0/24. My actual VirtualBox NAT configuration uses 10.0.2.0/24. This difference is documented transparently.

---

## 🌐 Network Architecture

### Host-only Network

Configured for communication between Kali Linux and Windows 10.

- Kali Linux: `192.168.10.2`
- Windows 10: `192.168.10.3`
- Connectivity: Successful in both directions.

### NAT Network

Configured to provide internet connectivity to the virtual machines.

- Subnet: `10.0.2.0/24`
- DHCP: Enabled
- Internet connectivity: Working

---

## 📸 Screenshots & Lab Evidence

### 1. VirtualBox – Kali Linux Overview

![VirtualBox Kali Overview](screenshots/01-virtualbox-kali-overview.png)

### 2. Kali Linux Running

![Kali Linux Running](screenshots/02-kali-linux-running.png)

### 3. Windows 10 VM Settings

![Windows 10 VM Settings](screenshots/03-windows10-vm-settings.png)

### 4. Windows 10 Running

![Windows 10 Running](screenshots/04-windows10-running.png)

### 5. Host-only Network Configuration

![Host-only Network](screenshots/05-host-only-network.png)

### 6. NAT Network Configuration

![NAT Network](screenshots/06-nat-network.png)

---

## 🧪 Connectivity Testing

The following checks were performed:

- Kali Linux internet connectivity – Successful.
- Kali to Windows 10 communication – Successful.
- Windows 10 to Kali communication – Successful.
- Host-only network connectivity – Successful.

---

## ⚙️ Additional Configuration

The following VirtualBox features were configured:

- Shared Folder
- Shared Clipboard
- Drag and Drop
- NAT Network
- Host-only Network

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Virtual machine deployment and management.
- Kali Linux configuration.
- Windows 10 virtual machine setup.
- NAT and Host-only networking.
- DHCP configuration.
- VM-to-VM connectivity testing.
- Shared folder and clipboard configuration.
- Building a virtual cybersecurity practice environment.

---

## 📝 Conclusion

Successfully configured a virtual cybersecurity lab using Oracle VirtualBox, Kali Linux, and Windows 10.

This lab provides a foundation for future cybersecurity learning, networking experiments, and authorized security testing.

---

**Completed by:** Dhoni Kumar Shah  
**Program:** NetworkWalks Cybersecurity Program  
**Project:** WK1-PM1 | Cohort B082
