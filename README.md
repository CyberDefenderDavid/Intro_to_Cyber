# My Network Project

## Objectives
The primary objectives of this project are to:
1. Map the network.
2. Use specific commands and websites to gather necessary information.
3. Capture and analyze network traffic using Wireshark.

## 1. Network Mapping

### Network Map
- Present a detailed network map showing all the devices connected to your network.

### Connection Types
- Indicate whether devices are connected via wireless or ethernet.

### Device Details
- **Internal IP Addresses:** Display the internal IP addresses of all devices.
- **MAC Addresses:** Display the last 3 bytes of the MAC addresses of all devices.
- **Router’s Internal IP Address:** Display the internal IP address of the router.
- **Router’s External IP Address:** Display the last 2 blocks of the router’s external IP address.
- **Device Names:** Display the names of all devices.
- **DNS and DHCP Addresses:** Display the DNS and DHCP addresses in your network.
- **Internet Service Provider (ISP):** Display your ISP.
- **Operating System and Version:** Display the OS and version of your device.

## 2. Commands and Websites

### Commands and Websites Used
- Provide screenshots of the commands and websites used to gather the information.
- Include descriptions for each screenshot explaining the commands and websites used.

## 3. Wireshark Analysis

### Wireshark Capture
- Run Wireshark and capture the traffic of your device while visiting a selected website.
- **IP Address of the Website:** Identify and screenshot the IP address of the visited website as seen in Wireshark.

## 4. Submission

### PDF Document
- Compile all information into a PDF document.

### Optional: Steganography
- After watching the steganography lesson, use method 2 to zip the PDF and hide the zip behind a picture.

## Detailed Steps and Commands

### Network Mapping
1. **Scan Network for Devices:**
    - Use tools like `nmap` or `arp-scan` to identify devices on the network.
    - Example Command: `nmap -sP 192.168.1.0/24`
  
2. **Identify Connection Types:**
    - Check device settings or use network management tools to determine connection types.
  
3. **Retrieve Device Information:**
    - **Internal IP Address:** Use `ipconfig` (Windows) or `ifconfig`/`ip a` (Linux).
    - **MAC Address:** Use `getmac` (Windows) or `ifconfig`/`ip link` (Linux).
    - **Router's Internal IP Address:** Typically `192.168.1.1` or `192.168.0.1`.
    - **Router's External IP Address:** Use websites like `whatismyip.com`.
    - **Device Names:** Use `hostname`.
    - **DNS and DHCP Addresses:** Check router settings or use `ipconfig /all` (Windows) or `cat /etc/resolv.conf` and `cat /var/lib/dhcp/dhclient.leases` (Linux).
    - **ISP:** Check via router admin page or ISP bill.
    - **Operating System and Version:** Use `winver` (Windows) or `uname -a` (Linux).

### Commands and Websites
- **Screenshot Example:** `nmap` scan result, `ipconfig /all` output, etc.
- **Description Example:** "The command `nmap -sP 192.168.1.0/24` was used to scan the network and list all connected devices."

### Wireshark Analysis
1. **Capture Traffic:**
    - Open Wireshark and start a capture on the network interface.
    - Visit a selected website.
  
2. **Identify IP Address:**
    - Stop capture and filter for the website's traffic.
    - Identify and screenshot the IP address of the website.

## Conclusion
By following the steps outlined in this document, you will be able to map your network, gather necessary information using commands and websites, capture and analyze network traffic using Wireshark, and compile all findings into a comprehensive report for submission.

---

Make sure to replace placeholders with your specific details and include all relevant screenshots and descriptions in the final document. Good luck!
