# Scenario 1:
The Johannesburg Headquarters of TransGlobe Logistics hosts four main departments (Finance, HR, IT, and Operations) plus shared services (Server Farm, Corporate Wi-Fi, Guest Wi-Fi, and a dedicated Network Management subnet). You are provided with the block 10.20.0.0/22 for all internal HQ addressing.

The organisation requires both wired LAN and wireless connectivity:

Finance and HR staff use mainly wired PCs.
Operations and IT staff need a mix of wired and wireless access.
Corporate Wi-Fi allows authenticated employee devices.
Guest Wi-Fi is for visitors and must be isolated from internal resources.
Servers must be reachable from all departments but isolated in their own VLAN.
Network Management requires a secure subnet for SNMP, syslog, and administrative access.

# Scenario 2:
As TransGlobe Logistics grows, the Johannesburg HQ must be fully interconnected with the London and Singapore offices, as well as remote warehouses that depend on satellite links. Currently, the WAN uses static routing, which has resulted in inefficient paths, delayed shipment updates, and slow failover when a primary link fails. The executive team has asked for a more scalable and resilient routing strategy that can handle the mixed fibre and satellite environment, while also allowing the network to expand into new regions without frequent redesigns

# Scenario 3:

The management team wants to see a working prototype of the new network in action before full rollout. You have been tasked with building a Packet Tracer simulation of the Johannesburg HQ, interconnecting it with the London and Singapore offices, and attaching a remote warehouse via a simulated satellite link. The prototype must demonstrate the VLSM subnetting plan from Question 1 and the routing strategy recommended in Question 2. It should also show that the WAN can recover from failures and maintain communication between sites.

# Scenario 4:
While the new WAN design has improved routing and resilience, TransGlobe Logistics is still facing two critical challenges. First, during peak shipment hours, bandwidth congestion is causing jitter and delays in real-time applications such as shipment dashboards and tracking updates. Second, a malware infection on a warehouse PC recently disrupted communications with HQ, raising concerns about how vulnerable hosts could affect the wider network.

Management wants you to recommend a strategy that addresses both performance optimization and endpoint protection, ensuring that the network remains fast and reliable while minimizing the risk of disruptions from infected devices
