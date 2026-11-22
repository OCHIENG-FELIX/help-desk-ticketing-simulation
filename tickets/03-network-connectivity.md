## Ticket 003 – Network Connectivity

### Escalation Report

**Issue:** Employee unable to access the company network or internet.

**Initial findings:**
- Computer connected to the correct company Wi-Fi.
- Windows displayed "No Internet, secured."
- `ipconfig /all` showed an APIPA IPv4 address (`169.254.45.120`).
- Default gateway and DNS server were not assigned.
- DHCP was enabled.
- Running `ipconfig /renew` did not resolve the issue.

**Troubleshooting performed:**
- Verified the company Wi-Fi connection.
- Checked wireless signal strength (95%).
- Confirmed that other employees could access the company network.
- Inspected the wireless adapter in Device Manager.
- Confirmed that the adapter was functioning properly.
- Confirmed that the DHCP Client service was running.
- Tested connectivity using another network (mobile hotspot).

**Additional findings:**

The computer successfully connected to the mobile hotspot and received valid network settings. Internet access worked normally on that network.

**Suspected cause:**

The issue appears specific to the company network connection or configuration. Possible causes include DHCP communication failure, wireless access point configuration, VLAN assignment or network access controls.

**Escalation request:**

Please investigate DHCP communication and the wireless network configuration affecting this workstation.

**Status:** Escalated to Network Administrator – Simulated.

**Note:** This is a simulated help desk investigation for learning and portfolio purposes.
