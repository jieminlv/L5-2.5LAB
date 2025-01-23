# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 270 | 126 | 144 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| leaf1 |  50 | 26 | 24 | Interface State, LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| leaf2 |  50 | 26 | 24 | Interface State, LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| leaf3 |  50 | 26 | 24 | Interface State, LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| leaf4 |  51 | 27 | 24 | Interface State, LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| spine1 |  23 | 7 | 16 | LLDP Topology, IP Reachability, BGP |
| spine2 |  23 | 7 | 16 | LLDP Topology, IP Reachability, BGP |
| spine3 |  23 | 7 | 16 | LLDP Topology, IP Reachability, BGP |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  7 | 7 | 0 |
| Interface State |  80 | 76 | 4 |
| LLDP Topology |  32 | 8 | 24 |
| MLAG |  4 | 4 | 0 |
| IP Reachability |  24 | 0 | 24 |
| BGP |  59 | 11 | 48 |
| Routing Table |  36 | 12 | 24 |
| Loopback0 Reachability |  28 | 8 | 20 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 46 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 48 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 50 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 52 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 90 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | FAIL | spine1.atd.lab - Ethernet2 |
| 91 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | FAIL | spine2.atd.lab - Ethernet2 |
| 92 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet3 | FAIL | spine3.atd.lab - Ethernet2 |
| 95 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | FAIL | spine1.atd.lab - Ethernet3 |
| 96 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | FAIL | spine2.atd.lab - Ethernet3 |
| 97 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet4 | FAIL | spine3.atd.lab - Ethernet3 |
| 100 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | FAIL | spine1.atd.lab - Ethernet4 |
| 101 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | FAIL | spine2.atd.lab - Ethernet4 |
| 102 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet5 | FAIL | spine3.atd.lab - Ethernet4 |
| 105 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet6 | FAIL | spine1.atd.lab - Ethernet5 |
| 106 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet6 | FAIL | spine2.atd.lab - Ethernet5 |
| 107 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet6 | FAIL | spine3.atd.lab - Ethernet5 |
| 108 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet3 | FAIL | leaf2.atd.lab - Ethernet3 |
| 109 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet3 | FAIL | leaf3.atd.lab - Ethernet3 |
| 110 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet3 | FAIL | leaf4.atd.lab - Ethernet3 |
| 111 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet3 | FAIL | borderleaf1.arista.lab - Ethernet3 |
| 112 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet4 | FAIL | leaf2.atd.lab - Ethernet4 |
| 113 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet4 | FAIL | leaf3.atd.lab - Ethernet4 |
| 114 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet4 | FAIL | leaf4.atd.lab - Ethernet4 |
| 115 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet4 | FAIL | borderleaf1.arista.lab - Ethernet4 |
| 116 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet5 | FAIL | leaf2.atd.lab - Ethernet5 |
| 117 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet5 | FAIL | leaf3.atd.lab - Ethernet5 |
| 118 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet5 | FAIL | leaf4.atd.lab - Ethernet5 |
| 119 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet5 | FAIL | borderleaf1.arista.lab - Ethernet5 |
| 124 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet3 | FAIL | 100% packet loss |
| 125 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet3 | FAIL | 100% packet loss |
| 126 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet5 - Destination: spine3_Ethernet3 | FAIL | 100% packet loss |
| 127 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet4 | FAIL | 100% packet loss |
| 128 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet4 | FAIL | 100% packet loss |
| 129 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet5 - Destination: spine3_Ethernet4 | FAIL | 100% packet loss |
| 130 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet5 | FAIL | 100% packet loss |
| 131 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet5 | FAIL | 100% packet loss |
| 132 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet5 - Destination: spine3_Ethernet5 | FAIL | 100% packet loss |
| 133 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet6 | FAIL | 100% packet loss |
| 134 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet6 | FAIL | 100% packet loss |
| 135 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet5 - Destination: spine3_Ethernet6 | FAIL | 100% packet loss |
| 136 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf1_Ethernet3 | FAIL | 100% packet loss |
| 137 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf2_Ethernet3 | FAIL | 100% packet loss |
| 138 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf3_Ethernet3 | FAIL | 100% packet loss |
| 139 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet6 - Destination: leaf4_Ethernet3 | FAIL | 100% packet loss |
| 140 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf1_Ethernet4 | FAIL | 100% packet loss |
| 141 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf2_Ethernet4 | FAIL | 100% packet loss |
| 142 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf3_Ethernet4 | FAIL | 100% packet loss |
| 143 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet6 - Destination: leaf4_Ethernet4 | FAIL | 100% packet loss |
| 144 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet3 - Destination: leaf1_Ethernet5 | FAIL | 100% packet loss |
| 145 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet4 - Destination: leaf2_Ethernet5 | FAIL | 100% packet loss |
| 146 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet5 - Destination: leaf3_Ethernet5 | FAIL | 100% packet loss |
| 147 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet6 - Destination: leaf4_Ethernet5 | FAIL | 100% packet loss |
| 156 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | FAIL | Session state Active |
| 157 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | FAIL | Session state Active |
| 158 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | FAIL | Session state Active |
| 160 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | FAIL | Session state Active |
| 161 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | FAIL | Session state Active |
| 162 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | FAIL | Session state Active |
| 164 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | FAIL | Session state Active |
| 165 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | FAIL | Session state Active |
| 166 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | FAIL | Session state Active |
| 168 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | FAIL | Session state Active |
| 169 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | FAIL | Session state Active |
| 170 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | FAIL | Session state Active |
| 171 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | FAIL | Session state Active |
| 172 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | FAIL | Session state Active |
| 173 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | FAIL | Session state Active |
| 174 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | FAIL | Session state Active |
| 175 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | FAIL | Session state Active |
| 176 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | FAIL | Session state Active |
| 177 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | FAIL | Session state Active |
| 178 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | FAIL | Session state Active |
| 179 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | FAIL | Session state Active |
| 180 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | FAIL | Session state Active |
| 181 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | FAIL | Session state Active |
| 182 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | FAIL | Session state Active |
| 183 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 184 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 185 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 186 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 187 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 188 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 189 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 190 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 191 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 192 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 193 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 194 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 195 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | FAIL | Session state: Active |
| 196 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | FAIL | Session state: Active |
| 197 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | FAIL | Session state: Active |
| 198 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | FAIL | Session state: Active |
| 199 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | FAIL | Session state: Active |
| 200 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | FAIL | Session state: Active |
| 201 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | FAIL | Session state: Active |
| 202 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | FAIL | Session state: Active |
| 203 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | FAIL | Session state: Active |
| 204 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | FAIL | Session state: Active |
| 205 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | FAIL | Session state: Active |
| 206 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | FAIL | Session state: Active |
| 208 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | FAIL | VTEP 192.168.102.3 is not in the routing table |
| 210 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | FAIL | VTEP 192.168.102.3 is not in the routing table |
| 211 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | FAIL | VTEP 192.168.102.1 is not in the routing table |
| 213 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | FAIL | VTEP 192.168.102.1 is not in the routing table |
| 217 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | FAIL | Lo0 192.168.101.3 is not in the routing table |
| 218 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | FAIL | Lo0 192.168.101.4 is not in the routing table |
| 219 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 220 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 221 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 224 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | FAIL | Lo0 192.168.101.3 is not in the routing table |
| 225 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | FAIL | Lo0 192.168.101.4 is not in the routing table |
| 226 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 227 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 228 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 229 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | FAIL | Lo0 192.168.101.1 is not in the routing table |
| 230 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | FAIL | Lo0 192.168.101.2 is not in the routing table |
| 233 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 234 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 235 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 236 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | FAIL | Lo0 192.168.101.1 is not in the routing table |
| 237 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | FAIL | Lo0 192.168.101.2 is not in the routing table |
| 240 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 241 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 242 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 245 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | FAIL | 100% packet loss |
| 246 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | FAIL | 100% packet loss |
| 247 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 248 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 249 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.13 | FAIL | 100% packet loss |
| 252 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | FAIL | 100% packet loss |
| 253 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | FAIL | 100% packet loss |
| 254 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 255 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 256 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.13 | FAIL | 100% packet loss |
| 257 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | FAIL | 100% packet loss |
| 258 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | FAIL | 100% packet loss |
| 261 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 262 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 263 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.13 | FAIL | 100% packet loss |
| 264 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | FAIL | 100% packet loss |
| 265 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | FAIL | 100% packet loss |
| 268 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 269 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 270 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.13 | FAIL | 100% packet loss |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | leaf1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | leaf2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | leaf3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | leaf4 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | spine1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | spine2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | spine3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2_Ethernet1 | PASS | - |
| 9 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2_Ethernet2 | PASS | - |
| 10 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet3 | PASS | - |
| 11 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet3 | PASS | - |
| 12 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet3 | PASS | - |
| 13 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet1 | PASS | - |
| 14 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1_Ethernet1 | PASS | - |
| 15 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1_Ethernet2 | PASS | - |
| 16 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet4 | PASS | - |
| 17 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet4 | PASS | - |
| 18 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet4 | PASS | - |
| 19 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet2 | PASS | - |
| 20 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4_Ethernet1 | PASS | - |
| 21 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4_Ethernet2 | PASS | - |
| 22 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet5 | PASS | - |
| 23 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet5 | PASS | - |
| 24 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet5 | PASS | - |
| 25 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet1 | PASS | - |
| 26 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3_Ethernet1 | PASS | - |
| 27 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3_Ethernet2 | PASS | - |
| 28 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet6 | PASS | - |
| 29 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet6 | PASS | - |
| 30 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet6 | PASS | - |
| 31 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet9 -  | PASS | - |
| 32 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet2 | PASS | - |
| 33 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF1_Ethernet3 | PASS | - |
| 34 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF2_Ethernet3 | PASS | - |
| 35 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF3_Ethernet3 | PASS | - |
| 36 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_LEAF4_Ethernet3 | PASS | - |
| 37 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF1_Ethernet4 | PASS | - |
| 38 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF2_Ethernet4 | PASS | - |
| 39 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF3_Ethernet4 | PASS | - |
| 40 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_LEAF4_Ethernet4 | PASS | - |
| 41 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF1_Ethernet5 | PASS | - |
| 42 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF2_Ethernet5 | PASS | - |
| 43 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF3_Ethernet5 | PASS | - |
| 44 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_LEAF4_Ethernet5 | PASS | - |
| 45 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2_Po1 | PASS | - |
| 46 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 47 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1_Po1 | PASS | - |
| 48 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 49 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4_Po1 | PASS | - |
| 50 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 51 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3_Po1 | PASS | - |
| 52 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 53 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 54 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 55 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 56 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 57 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 58 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 59 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 60 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 61 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 62 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 63 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 64 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 65 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 66 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 67 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 68 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 69 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 70 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 71 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 72 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 73 | leaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 74 | leaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 75 | leaf3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 76 | leaf4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 77 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 78 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 79 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 80 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 81 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 82 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 83 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 84 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 85 | spine1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 86 | spine2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 87 | spine3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 88 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2_Ethernet1 | PASS | - |
| 89 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2_Ethernet2 | PASS | - |
| 90 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | FAIL | spine1.atd.lab - Ethernet2 |
| 91 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | FAIL | spine2.atd.lab - Ethernet2 |
| 92 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet3 | FAIL | spine3.atd.lab - Ethernet2 |
| 93 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1_Ethernet1 | PASS | - |
| 94 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet2 | PASS | - |
| 95 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | FAIL | spine1.atd.lab - Ethernet3 |
| 96 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | FAIL | spine2.atd.lab - Ethernet3 |
| 97 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet4 | FAIL | spine3.atd.lab - Ethernet3 |
| 98 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4_Ethernet1 | PASS | - |
| 99 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4_Ethernet2 | PASS | - |
| 100 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | FAIL | spine1.atd.lab - Ethernet4 |
| 101 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | FAIL | spine2.atd.lab - Ethernet4 |
| 102 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet5 | FAIL | spine3.atd.lab - Ethernet4 |
| 103 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3_Ethernet1 | PASS | - |
| 104 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3_Ethernet2 | PASS | - |
| 105 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet6 | FAIL | spine1.atd.lab - Ethernet5 |
| 106 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet6 | FAIL | spine2.atd.lab - Ethernet5 |
| 107 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet6 | FAIL | spine3.atd.lab - Ethernet5 |
| 108 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet3 | FAIL | leaf2.atd.lab - Ethernet3 |
| 109 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet3 | FAIL | leaf3.atd.lab - Ethernet3 |
| 110 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet3 | FAIL | leaf4.atd.lab - Ethernet3 |
| 111 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet3 | FAIL | borderleaf1.arista.lab - Ethernet3 |
| 112 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet4 | FAIL | leaf2.atd.lab - Ethernet4 |
| 113 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet4 | FAIL | leaf3.atd.lab - Ethernet4 |
| 114 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet4 | FAIL | leaf4.atd.lab - Ethernet4 |
| 115 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet4 | FAIL | borderleaf1.arista.lab - Ethernet4 |
| 116 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet5 | FAIL | leaf2.atd.lab - Ethernet5 |
| 117 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet5 | FAIL | leaf3.atd.lab - Ethernet5 |
| 118 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet5 | FAIL | leaf4.atd.lab - Ethernet5 |
| 119 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet5 | FAIL | borderleaf1.arista.lab - Ethernet5 |
| 120 | leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 121 | leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 122 | leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 123 | leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 124 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet3 | FAIL | 100% packet loss |
| 125 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet3 | FAIL | 100% packet loss |
| 126 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet5 - Destination: spine3_Ethernet3 | FAIL | 100% packet loss |
| 127 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet4 | FAIL | 100% packet loss |
| 128 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet4 | FAIL | 100% packet loss |
| 129 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet5 - Destination: spine3_Ethernet4 | FAIL | 100% packet loss |
| 130 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet5 | FAIL | 100% packet loss |
| 131 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet5 | FAIL | 100% packet loss |
| 132 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet5 - Destination: spine3_Ethernet5 | FAIL | 100% packet loss |
| 133 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet6 | FAIL | 100% packet loss |
| 134 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet6 | FAIL | 100% packet loss |
| 135 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet5 - Destination: spine3_Ethernet6 | FAIL | 100% packet loss |
| 136 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf1_Ethernet3 | FAIL | 100% packet loss |
| 137 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf2_Ethernet3 | FAIL | 100% packet loss |
| 138 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf3_Ethernet3 | FAIL | 100% packet loss |
| 139 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet6 - Destination: leaf4_Ethernet3 | FAIL | 100% packet loss |
| 140 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf1_Ethernet4 | FAIL | 100% packet loss |
| 141 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf2_Ethernet4 | FAIL | 100% packet loss |
| 142 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf3_Ethernet4 | FAIL | 100% packet loss |
| 143 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet6 - Destination: leaf4_Ethernet4 | FAIL | 100% packet loss |
| 144 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet3 - Destination: leaf1_Ethernet5 | FAIL | 100% packet loss |
| 145 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet4 - Destination: leaf2_Ethernet5 | FAIL | 100% packet loss |
| 146 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet5 - Destination: leaf3_Ethernet5 | FAIL | 100% packet loss |
| 147 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet6 - Destination: leaf4_Ethernet5 | FAIL | 100% packet loss |
| 148 | leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 149 | leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 150 | leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 151 | leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 152 | spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 153 | spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 154 | spine3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 155 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 156 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | FAIL | Session state Active |
| 157 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | FAIL | Session state Active |
| 158 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | FAIL | Session state Active |
| 159 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 160 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | FAIL | Session state Active |
| 161 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | FAIL | Session state Active |
| 162 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | FAIL | Session state Active |
| 163 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 164 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | FAIL | Session state Active |
| 165 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | FAIL | Session state Active |
| 166 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | FAIL | Session state Active |
| 167 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 168 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | FAIL | Session state Active |
| 169 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | FAIL | Session state Active |
| 170 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | FAIL | Session state Active |
| 171 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | FAIL | Session state Active |
| 172 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | FAIL | Session state Active |
| 173 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | FAIL | Session state Active |
| 174 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | FAIL | Session state Active |
| 175 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | FAIL | Session state Active |
| 176 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | FAIL | Session state Active |
| 177 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | FAIL | Session state Active |
| 178 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | FAIL | Session state Active |
| 179 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | FAIL | Session state Active |
| 180 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | FAIL | Session state Active |
| 181 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | FAIL | Session state Active |
| 182 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | FAIL | Session state Active |
| 183 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 184 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 185 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 186 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 187 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 188 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 189 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 190 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 191 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 192 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | FAIL | Session state: Active |
| 193 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | FAIL | Session state: Active |
| 194 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | FAIL | Session state: Active |
| 195 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | FAIL | Session state: Active |
| 196 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | FAIL | Session state: Active |
| 197 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | FAIL | Session state: Active |
| 198 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | FAIL | Session state: Active |
| 199 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | FAIL | Session state: Active |
| 200 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | FAIL | Session state: Active |
| 201 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | FAIL | Session state: Active |
| 202 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | FAIL | Session state: Active |
| 203 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | FAIL | Session state: Active |
| 204 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | FAIL | Session state: Active |
| 205 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | FAIL | Session state: Active |
| 206 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | FAIL | Session state: Active |
| 207 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 208 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | FAIL | VTEP 192.168.102.3 is not in the routing table |
| 209 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 210 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | FAIL | VTEP 192.168.102.3 is not in the routing table |
| 211 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | FAIL | VTEP 192.168.102.1 is not in the routing table |
| 212 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 213 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | FAIL | VTEP 192.168.102.1 is not in the routing table |
| 214 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 215 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 216 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 217 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | FAIL | Lo0 192.168.101.3 is not in the routing table |
| 218 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | FAIL | Lo0 192.168.101.4 is not in the routing table |
| 219 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 220 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 221 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 222 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 223 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 224 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | FAIL | Lo0 192.168.101.3 is not in the routing table |
| 225 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | FAIL | Lo0 192.168.101.4 is not in the routing table |
| 226 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 227 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 228 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 229 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | FAIL | Lo0 192.168.101.1 is not in the routing table |
| 230 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | FAIL | Lo0 192.168.101.2 is not in the routing table |
| 231 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 232 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 233 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 234 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 235 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 236 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | FAIL | Lo0 192.168.101.1 is not in the routing table |
| 237 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | FAIL | Lo0 192.168.101.2 is not in the routing table |
| 238 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 239 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 240 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | FAIL | Lo0 192.168.101.11 is not in the routing table |
| 241 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | FAIL | Lo0 192.168.101.12 is not in the routing table |
| 242 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.13 | FAIL | Lo0 192.168.101.13 is not in the routing table |
| 243 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 244 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 245 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | FAIL | 100% packet loss |
| 246 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | FAIL | 100% packet loss |
| 247 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 248 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 249 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.13 | FAIL | 100% packet loss |
| 250 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 251 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 252 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | FAIL | 100% packet loss |
| 253 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | FAIL | 100% packet loss |
| 254 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 255 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 256 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.13 | FAIL | 100% packet loss |
| 257 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | FAIL | 100% packet loss |
| 258 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | FAIL | 100% packet loss |
| 259 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 260 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 261 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 262 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 263 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.13 | FAIL | 100% packet loss |
| 264 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | FAIL | 100% packet loss |
| 265 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | FAIL | 100% packet loss |
| 266 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 267 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 268 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | FAIL | 100% packet loss |
| 269 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | FAIL | 100% packet loss |
| 270 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.13 | FAIL | 100% packet loss |
