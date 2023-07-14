<h1>Network Incident Report</h1>

<h2> Incident Description:</h2>
A malicious actor sent a flood of ICMP packets to the organization's network, which overwhelmed the network and prevented normal traffic from accessing resources. The attack lasted for two hours, but the organization's incident response team was able to mitigate the damage and restore service within that time. The cybersecurity team is now working to improve the organization's security posture to prevent future attacks.

<h2>Frameworks Used:</h2>

- <b>NIST CSF</b>

<h2>Environments Used:</h2>

- <b>Windows 10</b>

<h2>Incident walk-through:</h2>
The organization was recently attacked by a distributed denial of service (DDoS) attack. The attack was carried out by sending a flood of ICMP packets to the organization's network. ICMP packets are a type of network packet that is used to test the connectivity between two devices.<br/>
<br/>
The attack was successful because the organization's firewall was not configured properly. The firewall should have been configured to block ICMP pings from unauthorized sources.<br/>
<br/>
The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
