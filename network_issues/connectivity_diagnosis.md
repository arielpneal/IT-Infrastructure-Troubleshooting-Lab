# Network Connectivity Diagnosis

### Description
Network connectivity issues occur when devices cannot establish or maintain a connection to the network, affecting access to resources and communication within the network.

### Symptoms
- No network access or “Limited Connectivity” messages.
- Dropped or intermittent connections.
- Slow network responses and timeout errors.

### Possible Causes
- Physical connection issues (e.g., loose cables, damaged ports).
- IP conflicts within the network.
- Incorrect IP or DNS configurations.
- Network device issues, such as routers or switches.

### Resolution Steps
1. **Check Physical Connections**
   - Ensure network cables are securely connected.
   - Test cables and ports with a known working device.

2. **Verify IP Configuration**
   - Check if the device has a valid IP address:
     - Windows: `ipconfig`
     - macOS/Linux: `ifconfig`
   - Release and renew the IP address if needed.

3. **Ping Test for Connectivity**
   - Ping the gateway to test local network access.
   - Ping an external IP (e.g., `8.8.8.8`) to verify internet access.

4. **Resolve IP Conflicts**
   - Check for duplicate IP addresses and set unique IPs as necessary.

5. **Reset Network Settings**
   - Windows: `netsh int ip reset`
   - macOS/Linux: Restart the network service.

6. **Check Wireless Connection** (if applicable):
   - Ensure device proximity to the router.
   - Switch Wi-Fi channels to minimize interference if needed.

### Preventative Measures
- Regularly check connections and cables.
- Use DHCP to manage IP assignments.
- Position routers to reduce interference.

### Additional Notes
This guide is part of the IT Infrastructure Troubleshooting Lab repository, covering typical steps to diagnose and resolve connectivity issues.


