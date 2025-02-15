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
| 270 | 266 | 4 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| leaf1 |  50 | 49 | 1 | Interface State |
| leaf2 |  50 | 49 | 1 | Interface State |
| leaf3 |  50 | 49 | 1 | Interface State |
| leaf4 |  51 | 50 | 1 | Interface State |
| spine1 |  23 | 23 | 0 | - |
| spine2 |  23 | 23 | 0 | - |
| spine3 |  23 | 23 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  7 | 7 | 0 |
| Interface State |  80 | 76 | 4 |
| LLDP Topology |  32 | 32 | 0 |
| MLAG |  4 | 4 | 0 |
| IP Reachability |  24 | 24 | 0 |
| BGP |  59 | 59 | 0 |
| Routing Table |  36 | 36 | 0 |
| Loopback0 Reachability |  28 | 28 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 46 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 48 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 50 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 52 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |

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
| 10 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet2 | PASS | - |
| 11 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet2 | PASS | - |
| 12 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet2 | PASS | - |
| 13 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet1 | PASS | - |
| 14 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1_Ethernet1 | PASS | - |
| 15 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1_Ethernet2 | PASS | - |
| 16 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet3 | PASS | - |
| 17 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet3 | PASS | - |
| 18 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet3 | PASS | - |
| 19 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet2 | PASS | - |
| 20 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4_Ethernet1 | PASS | - |
| 21 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4_Ethernet2 | PASS | - |
| 22 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet4 | PASS | - |
| 23 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet4 | PASS | - |
| 24 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet4 | PASS | - |
| 25 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet1 | PASS | - |
| 26 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3_Ethernet1 | PASS | - |
| 27 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3_Ethernet2 | PASS | - |
| 28 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet5 | PASS | - |
| 29 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet5 | PASS | - |
| 30 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet5 | PASS | - |
| 31 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet9 -  | PASS | - |
| 32 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet2 | PASS | - |
| 33 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet3 | PASS | - |
| 34 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet3 | PASS | - |
| 35 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet3 | PASS | - |
| 36 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet3 | PASS | - |
| 37 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet4 | PASS | - |
| 38 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet4 | PASS | - |
| 39 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet4 | PASS | - |
| 40 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet4 | PASS | - |
| 41 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet5 | PASS | - |
| 42 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet5 | PASS | - |
| 43 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet5 | PASS | - |
| 44 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet5 | PASS | - |
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
| 90 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet2 | PASS | - |
| 91 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet2 | PASS | - |
| 92 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet2 | PASS | - |
| 93 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1_Ethernet1 | PASS | - |
| 94 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet2 | PASS | - |
| 95 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | PASS | - |
| 96 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | PASS | - |
| 97 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet3 | PASS | - |
| 98 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4_Ethernet1 | PASS | - |
| 99 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4_Ethernet2 | PASS | - |
| 100 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | PASS | - |
| 101 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | PASS | - |
| 102 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet4 | PASS | - |
| 103 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3_Ethernet1 | PASS | - |
| 104 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3_Ethernet2 | PASS | - |
| 105 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | PASS | - |
| 106 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | PASS | - |
| 107 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet5 | PASS | - |
| 108 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet3 | PASS | - |
| 109 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet3 | PASS | - |
| 110 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet3 | PASS | - |
| 111 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet3 | PASS | - |
| 112 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet4 | PASS | - |
| 113 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet4 | PASS | - |
| 114 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet4 | PASS | - |
| 115 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet4 | PASS | - |
| 116 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet5 | PASS | - |
| 117 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet5 | PASS | - |
| 118 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet5 | PASS | - |
| 119 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet5 | PASS | - |
| 120 | leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 121 | leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 122 | leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 123 | leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 124 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet2 | PASS | - |
| 125 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet2 | PASS | - |
| 126 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet5 - Destination: spine3_Ethernet2 | PASS | - |
| 127 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet3 | PASS | - |
| 128 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet3 | PASS | - |
| 129 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet5 - Destination: spine3_Ethernet3 | PASS | - |
| 130 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet4 | PASS | - |
| 131 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet4 | PASS | - |
| 132 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet5 - Destination: spine3_Ethernet4 | PASS | - |
| 133 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet5 | PASS | - |
| 134 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet5 | PASS | - |
| 135 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet5 - Destination: spine3_Ethernet5 | PASS | - |
| 136 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet2 - Destination: leaf1_Ethernet3 | PASS | - |
| 137 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf2_Ethernet3 | PASS | - |
| 138 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf3_Ethernet3 | PASS | - |
| 139 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf4_Ethernet3 | PASS | - |
| 140 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet2 - Destination: leaf1_Ethernet4 | PASS | - |
| 141 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf2_Ethernet4 | PASS | - |
| 142 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf3_Ethernet4 | PASS | - |
| 143 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf4_Ethernet4 | PASS | - |
| 144 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet2 - Destination: leaf1_Ethernet5 | PASS | - |
| 145 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet3 - Destination: leaf2_Ethernet5 | PASS | - |
| 146 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet4 - Destination: leaf3_Ethernet5 | PASS | - |
| 147 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet5 - Destination: leaf4_Ethernet5 | PASS | - |
| 148 | leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 149 | leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 150 | leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 151 | leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 152 | spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 153 | spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 154 | spine3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 155 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 156 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | PASS | - |
| 157 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | PASS | - |
| 158 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | PASS | - |
| 159 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 160 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | PASS | - |
| 161 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | PASS | - |
| 162 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | PASS | - |
| 163 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 164 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | PASS | - |
| 165 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | PASS | - |
| 166 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | PASS | - |
| 167 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 168 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | PASS | - |
| 169 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | PASS | - |
| 170 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | PASS | - |
| 171 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | PASS | - |
| 172 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | PASS | - |
| 173 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | PASS | - |
| 174 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | PASS | - |
| 175 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | PASS | - |
| 176 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | PASS | - |
| 177 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | PASS | - |
| 178 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | PASS | - |
| 179 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | PASS | - |
| 180 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | PASS | - |
| 181 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | PASS | - |
| 182 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | PASS | - |
| 183 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 184 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 185 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 186 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 187 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 188 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 189 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 190 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 191 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 192 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 193 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 194 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 195 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 196 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 197 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 198 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 199 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 200 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 201 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 202 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 203 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 204 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 205 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 206 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 207 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 208 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 209 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 210 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 211 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 212 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 213 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 214 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 215 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 216 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 217 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 218 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 219 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 220 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 221 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 222 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 223 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 224 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 225 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 226 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 227 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 228 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 229 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 230 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 231 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 232 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 233 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 234 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 235 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 236 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 237 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 238 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 239 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 240 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 241 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 242 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 243 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 244 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 245 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | PASS | - |
| 246 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | PASS | - |
| 247 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | PASS | - |
| 248 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | PASS | - |
| 249 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.13 | PASS | - |
| 250 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 251 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 252 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | PASS | - |
| 253 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | PASS | - |
| 254 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | PASS | - |
| 255 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | PASS | - |
| 256 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.13 | PASS | - |
| 257 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | PASS | - |
| 258 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | PASS | - |
| 259 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 260 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 261 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | PASS | - |
| 262 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | PASS | - |
| 263 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.13 | PASS | - |
| 264 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | PASS | - |
| 265 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | PASS | - |
| 266 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 267 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 268 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | PASS | - |
| 269 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | PASS | - |
| 270 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.13 | PASS | - |
