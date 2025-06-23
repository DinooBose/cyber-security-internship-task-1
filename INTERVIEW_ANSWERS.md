# Interview Questions Answers

1. What is an open port?
   A network port that accepts incoming packets and has an associated service listening for connections.

2. How does Nmap perform a TCP SYN scan?  
   It sends SYN packets to target ports. If a SYN-ACK is received, the port is open. The connection is then reset (RST) without completing the handshake.

3. What risks are associated with open ports?  
   - Unauthorized access to services
   - Exploitation of vulnerable services
   - Increased attack surface
   - Data exfiltration opportunities

4. TCP vs UDP scanning differences:
   | TCP Scan              |         UDP Scan      |
   |-----------------------|-----------------------|
   | Connection-oriented   | Connectionless        |
   | Reliable responses    | Unreliable responses  |
   | Faster scanning       | Slower scanning       |
   | SYN/RST packets       | Specific UDP payloads |

5. Securing open ports:
   - Use firewalls to restrict access
   - Disable unused services
   - Keep services patched
   - Implement network segmentation
   - Use VPNs for remote access

6. Firewall role for ports:  
   Acts as a gatekeeper that controls traffic flow based on predefined rules, blocking unauthorized access while permitting legitimate communications.

7. Port scan purpose for attackers:  
   Reconnaissance technique to identify:
   - Running services
   - System vulnerabilities
   - Network architecture
   - Potential entry points

8. Wireshark complement to scanning:  
   Provides packet-level visibility to:
   - Verify scan accuracy
   - Analyze network behavior
   - Detect unexpected traffic
   - Troubleshoot connectivity issues

