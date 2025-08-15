# Task 8 : Working with VPNs 

## 1. Objective
Understand the role of VPNs in protecting privacy and secure communication.

---

## 2. Tools Used
- **VPN Service:** ProtonVPN (Free Plan)
- **OS:** Windows 11
- **Websites for Testing:**
  - [ProtonVPN Website](https://protonvpn.com)
  - [WhatIsMyIPAddress.com](https://whatismyipaddress.com)
  - Flipkart.com (for HTTPS check)

---

## 3. Steps Performed

### 1. Choose a reputable free VPN service and sign up
Selected **ProtonVPN** due to:
- Strong privacy policy
- No-logs commitment
- Uses secure protocols like **WireGuard** and **OpenVPN**

<img width="800" height="600" alt="proton_vpn_website" src="https://github.com/user-attachments/assets/a471e3f9-c345-46dd-92a0-56dd4f9cf65f" />

---

### 2. Download and install the VPN client
- Downloaded **Windows** client from ProtonVPN official site.
- Chose not to install additional Proton services.
  
<img width="800" height="600" alt="proton_vpn_installation" src="https://github.com/user-attachments/assets/28601de0-826e-49dd-8bf7-fdd5e720e240" />

---

### 3. Connect to a VPN server
- Connected to the **Fastest Free Server – Netherlands (NL-FREE#45)** using **WireGuard (TCP)** protocol.
  
<img width="800" height="600" alt="proton_vpn_on" src="https://github.com/user-attachments/assets/fff69eaa-088b-4884-9501-5e305d5005ff" />

---

### 4. Verify IP address change
- **Before VPN (blurred for privacy):**  
<img width="800" height="600" alt="ip_before_vpn" src="https://github.com/user-attachments/assets/544832fe-619e-49c1-b250-f0a7933038e3" />


- **After VPN:**  
<img width="800" height="600" alt="ip_after_vpn" src="https://github.com/user-attachments/assets/d5aaa551-a460-4d40-ba25-27ae8c24d90f" />

The IP changed from an **India-based IP** to a **Netherlands-based IP**.

---

### 5. Browse a website to confirm traffic is encrypted
Visited Flipkart.com and confirmed HTTPS lock icon → connection is secure.

<img width="800" height="600" alt="connection_secure" src="https://github.com/user-attachments/assets/8192c77a-ed90-4493-8207-f8dfe5dda8f6" />

---

### 6. Disconnect VPN and compare browsing speed and IP
- Upon disconnecting, IP reverted to the original ISP-assigned one.
- Speed difference: Minimal, but VPN connection adds latency due to encryption.

---

### 7. Research on VPN encryption and privacy features
- **Encryption:** ProtonVPN uses AES-256 encryption with Perfect Forward Secrecy.
- **Protocols:** WireGuard, OpenVPN (UDP/TCP), and IKEv2/IPSec.
- **Privacy Features:**
  - No-logs policy
  - Kill switch (blocks traffic if VPN disconnects)
  - Secure Core (multi-hop through privacy-friendly countries)

---

### 8. Summary – VPN Benefits and Limitations

#### Benefits:
- **Privacy:** Hides real IP from websites & ISPs.
- **Security:** Encrypts data between your device and VPN server.
- **Bypass Restrictions:** Access geo-restricted content.
- **Protection on Public Wi-Fi:** Prevents man-in-the-middle attacks.

#### Limitations:
- **Not Complete Anonymity:** VPN provider can still see traffic (must trust provider).
- **Speed Reduction:** Due to encryption and routing through remote servers.
- **Blocked by Some Services:** Streaming platforms or websites may detect VPN usage.
- **Requires Trust:** Logs policy depends on provider’s honesty.

---

## 4. Conclusion
VPNs are essential tools for enhancing online privacy and securing communications. In this task:
- Successfully connected to ProtonVPN
- Verified IP change and encryption
- Compared pre/post VPN connection details
- Understood both strengths and weaknesses of VPN usage

**Final Note:** Even with a dynamic IP, it’s safer to hide or blur original IPs in public reports to maintain privacy.

---
