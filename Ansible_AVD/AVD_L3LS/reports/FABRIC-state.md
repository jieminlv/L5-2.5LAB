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
| 457 | 457 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| borderleaf1 |  59 | 59 | 0 | - |
| borderleaf2 |  59 | 59 | 0 | - |
| leaf1 |  60 | 60 | 0 | - |
| leaf2 |  60 | 60 | 0 | - |
| leaf3 |  60 | 60 | 0 | - |
| leaf4 |  60 | 60 | 0 | - |
| spine1 |  33 | 33 | 0 | - |
| spine2 |  33 | 33 | 0 | - |
| spine3 |  33 | 33 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  9 | 9 | 0 |
| Interface State |  145 | 145 | 0 |
| LLDP Topology |  48 | 48 | 0 |
| MLAG |  6 | 6 | 0 |
| IP Reachability |  36 | 36 | 0 |
| BGP |  87 | 87 | 0 |
| Routing Table |  72 | 72 | 0 |
| Loopback0 Reachability |  54 | 54 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | borderleaf1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | borderleaf2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | leaf1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | leaf2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | leaf3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | leaf4 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | spine1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | spine2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 9 | spine3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 10 | borderleaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf2_Ethernet1 | PASS | - |
| 11 | borderleaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf2_Ethernet2 | PASS | - |
| 12 | borderleaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet6 | PASS | - |
| 13 | borderleaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet6 | PASS | - |
| 14 | borderleaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet6 | PASS | - |
| 15 | borderleaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet9 -  | PASS | - |
| 16 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf1_Ethernet1 | PASS | - |
| 17 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf1_Ethernet2 | PASS | - |
| 18 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet7 | PASS | - |
| 19 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet7 | PASS | - |
| 20 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet7 | PASS | - |
| 21 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet9 -  | PASS | - |
| 22 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2_Ethernet1 | PASS | - |
| 23 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2_Ethernet2 | PASS | - |
| 24 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet2 | PASS | - |
| 25 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet2 | PASS | - |
| 26 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet2 | PASS | - |
| 27 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet1 | PASS | - |
| 28 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1_Ethernet1 | PASS | - |
| 29 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1_Ethernet2 | PASS | - |
| 30 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet3 | PASS | - |
| 31 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet3 | PASS | - |
| 32 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet3 | PASS | - |
| 33 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet2 | PASS | - |
| 34 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4_Ethernet1 | PASS | - |
| 35 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4_Ethernet2 | PASS | - |
| 36 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet4 | PASS | - |
| 37 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet4 | PASS | - |
| 38 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet4 | PASS | - |
| 39 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet1 | PASS | - |
| 40 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3_Ethernet1 | PASS | - |
| 41 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3_Ethernet2 | PASS | - |
| 42 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet5 | PASS | - |
| 43 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet5 | PASS | - |
| 44 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet5 | PASS | - |
| 45 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet2 | PASS | - |
| 46 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet3 | PASS | - |
| 47 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet3 | PASS | - |
| 48 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet3 | PASS | - |
| 49 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet3 | PASS | - |
| 50 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1_Ethernet3 | PASS | - |
| 51 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2_Ethernet3 | PASS | - |
| 52 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet4 | PASS | - |
| 53 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet4 | PASS | - |
| 54 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet4 | PASS | - |
| 55 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet4 | PASS | - |
| 56 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1_Ethernet4 | PASS | - |
| 57 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2_Ethernet4 | PASS | - |
| 58 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet5 | PASS | - |
| 59 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet5 | PASS | - |
| 60 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet5 | PASS | - |
| 61 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet5 | PASS | - |
| 62 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1_Ethernet5 | PASS | - |
| 63 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2_Ethernet5 | PASS | - |
| 64 | borderleaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf2_Po1 | PASS | - |
| 65 | borderleaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf1_Po1 | PASS | - |
| 66 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2_Po1 | PASS | - |
| 67 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | PASS | - |
| 68 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1_Po1 | PASS | - |
| 69 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | PASS | - |
| 70 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4_Po1 | PASS | - |
| 71 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | PASS | - |
| 72 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3_Po1 | PASS | - |
| 73 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | PASS | - |
| 74 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 75 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 76 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 77 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 78 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 79 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 80 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 81 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 82 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 83 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 84 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 85 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 86 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 87 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 88 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 89 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 90 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 91 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 92 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 93 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 94 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 95 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 96 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 97 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 98 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 99 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 100 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 101 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 102 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 103 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 104 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 105 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 106 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 107 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 108 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 109 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 110 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 111 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 112 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 113 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 114 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 115 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 116 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 117 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 118 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 119 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 120 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 121 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 122 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 123 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 124 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 125 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 126 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 127 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 128 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 129 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 130 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 131 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 132 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 133 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 134 | borderleaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 135 | borderleaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 136 | leaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 137 | leaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 138 | leaf3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 139 | leaf4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 140 | borderleaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 141 | borderleaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 142 | borderleaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 143 | borderleaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 144 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 145 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 146 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 147 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 148 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 149 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 150 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 151 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 152 | spine1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 153 | spine2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 154 | spine3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 155 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf2_Ethernet1 | PASS | - |
| 156 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf2_Ethernet2 | PASS | - |
| 157 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet6 | PASS | - |
| 158 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet6 | PASS | - |
| 159 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet6 | PASS | - |
| 160 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf1_Ethernet1 | PASS | - |
| 161 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf1_Ethernet2 | PASS | - |
| 162 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet7 | PASS | - |
| 163 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet7 | PASS | - |
| 164 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet7 | PASS | - |
| 165 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2_Ethernet1 | PASS | - |
| 166 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2_Ethernet2 | PASS | - |
| 167 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet2 | PASS | - |
| 168 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet2 | PASS | - |
| 169 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet2 | PASS | - |
| 170 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1_Ethernet1 | PASS | - |
| 171 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet2 | PASS | - |
| 172 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | PASS | - |
| 173 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | PASS | - |
| 174 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet3 | PASS | - |
| 175 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4_Ethernet1 | PASS | - |
| 176 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4_Ethernet2 | PASS | - |
| 177 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | PASS | - |
| 178 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | PASS | - |
| 179 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet4 | PASS | - |
| 180 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3_Ethernet1 | PASS | - |
| 181 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3_Ethernet2 | PASS | - |
| 182 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | PASS | - |
| 183 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | PASS | - |
| 184 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet5 | PASS | - |
| 185 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet3 | PASS | - |
| 186 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet3 | PASS | - |
| 187 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet3 | PASS | - |
| 188 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet3 | PASS | - |
| 189 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet3 | PASS | - |
| 190 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet3 | PASS | - |
| 191 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet4 | PASS | - |
| 192 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet4 | PASS | - |
| 193 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet4 | PASS | - |
| 194 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet4 | PASS | - |
| 195 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet4 | PASS | - |
| 196 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet4 | PASS | - |
| 197 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet5 | PASS | - |
| 198 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet5 | PASS | - |
| 199 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet5 | PASS | - |
| 200 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet5 | PASS | - |
| 201 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet5 | PASS | - |
| 202 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet5 | PASS | - |
| 203 | borderleaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 204 | borderleaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 205 | leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 206 | leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 207 | leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 208 | leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 209 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet3 - Destination: spine1_Ethernet6 | PASS | - |
| 210 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet4 - Destination: spine2_Ethernet6 | PASS | - |
| 211 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet5 - Destination: spine3_Ethernet6 | PASS | - |
| 212 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet3 - Destination: spine1_Ethernet7 | PASS | - |
| 213 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet4 - Destination: spine2_Ethernet7 | PASS | - |
| 214 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet5 - Destination: spine3_Ethernet7 | PASS | - |
| 215 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet2 | PASS | - |
| 216 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet2 | PASS | - |
| 217 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet5 - Destination: spine3_Ethernet2 | PASS | - |
| 218 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet3 | PASS | - |
| 219 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet3 | PASS | - |
| 220 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet5 - Destination: spine3_Ethernet3 | PASS | - |
| 221 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet4 | PASS | - |
| 222 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet4 | PASS | - |
| 223 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet5 - Destination: spine3_Ethernet4 | PASS | - |
| 224 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet5 | PASS | - |
| 225 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet5 | PASS | - |
| 226 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet5 - Destination: spine3_Ethernet5 | PASS | - |
| 227 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet2 - Destination: leaf1_Ethernet3 | PASS | - |
| 228 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf2_Ethernet3 | PASS | - |
| 229 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf3_Ethernet3 | PASS | - |
| 230 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf4_Ethernet3 | PASS | - |
| 231 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet6 - Destination: borderleaf1_Ethernet3 | PASS | - |
| 232 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet7 - Destination: borderleaf2_Ethernet3 | PASS | - |
| 233 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet2 - Destination: leaf1_Ethernet4 | PASS | - |
| 234 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf2_Ethernet4 | PASS | - |
| 235 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf3_Ethernet4 | PASS | - |
| 236 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf4_Ethernet4 | PASS | - |
| 237 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet6 - Destination: borderleaf1_Ethernet4 | PASS | - |
| 238 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet7 - Destination: borderleaf2_Ethernet4 | PASS | - |
| 239 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet2 - Destination: leaf1_Ethernet5 | PASS | - |
| 240 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet3 - Destination: leaf2_Ethernet5 | PASS | - |
| 241 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet4 - Destination: leaf3_Ethernet5 | PASS | - |
| 242 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet5 - Destination: leaf4_Ethernet5 | PASS | - |
| 243 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet6 - Destination: borderleaf1_Ethernet5 | PASS | - |
| 244 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet7 - Destination: borderleaf2_Ethernet5 | PASS | - |
| 245 | borderleaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 246 | borderleaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 247 | leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 248 | leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 249 | leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 250 | leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 251 | spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 252 | spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 253 | spine3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 254 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 255 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.24 | PASS | - |
| 256 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.26 | PASS | - |
| 257 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.28 | PASS | - |
| 258 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 259 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.30 | PASS | - |
| 260 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.32 | PASS | - |
| 261 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.34 | PASS | - |
| 262 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 263 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | PASS | - |
| 264 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | PASS | - |
| 265 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | PASS | - |
| 266 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 267 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | PASS | - |
| 268 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | PASS | - |
| 269 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | PASS | - |
| 270 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 271 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | PASS | - |
| 272 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | PASS | - |
| 273 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | PASS | - |
| 274 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 275 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | PASS | - |
| 276 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | PASS | - |
| 277 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | PASS | - |
| 278 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | PASS | - |
| 279 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | PASS | - |
| 280 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | PASS | - |
| 281 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | PASS | - |
| 282 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.25 | PASS | - |
| 283 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.31 | PASS | - |
| 284 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | PASS | - |
| 285 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | PASS | - |
| 286 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | PASS | - |
| 287 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | PASS | - |
| 288 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.27 | PASS | - |
| 289 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.33 | PASS | - |
| 290 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | PASS | - |
| 291 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | PASS | - |
| 292 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | PASS | - |
| 293 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | PASS | - |
| 294 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.29 | PASS | - |
| 295 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.35 | PASS | - |
| 296 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 297 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 298 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 299 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 300 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 301 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 302 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 303 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 304 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 305 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 306 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 307 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 308 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 309 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 310 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 311 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 312 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 313 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 314 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 315 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 316 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 317 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 318 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 319 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 320 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 321 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 322 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 323 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 324 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 325 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 326 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 327 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 328 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 329 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 330 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 331 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 332 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 333 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 334 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 335 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 336 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 337 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 338 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 339 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 340 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 341 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 342 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 343 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 344 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 345 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 346 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 347 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 348 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 349 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 350 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 351 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 352 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 353 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 354 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 355 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 356 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 357 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 358 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 359 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 360 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 361 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 362 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 363 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 364 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 365 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 366 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 367 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 368 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 369 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 370 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 371 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 372 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 373 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 374 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 375 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 376 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 377 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 378 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 379 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 380 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 381 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 382 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 383 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 384 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 385 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 386 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 387 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 388 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 389 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 390 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 391 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 392 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 393 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 394 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 395 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 396 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 397 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 398 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 399 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 400 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 401 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 402 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 403 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 404 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.5 | PASS | - |
| 405 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.6 | PASS | - |
| 406 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.1 | PASS | - |
| 407 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.2 | PASS | - |
| 408 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.3 | PASS | - |
| 409 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.4 | PASS | - |
| 410 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.11 | PASS | - |
| 411 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.12 | PASS | - |
| 412 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.13 | PASS | - |
| 413 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.5 | PASS | - |
| 414 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.6 | PASS | - |
| 415 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.1 | PASS | - |
| 416 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.2 | PASS | - |
| 417 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.3 | PASS | - |
| 418 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.4 | PASS | - |
| 419 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.11 | PASS | - |
| 420 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.12 | PASS | - |
| 421 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.13 | PASS | - |
| 422 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.5 | PASS | - |
| 423 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.6 | PASS | - |
| 424 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 425 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 426 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | PASS | - |
| 427 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | PASS | - |
| 428 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | PASS | - |
| 429 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | PASS | - |
| 430 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.13 | PASS | - |
| 431 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.5 | PASS | - |
| 432 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.6 | PASS | - |
| 433 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 434 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 435 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | PASS | - |
| 436 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | PASS | - |
| 437 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | PASS | - |
| 438 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | PASS | - |
| 439 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.13 | PASS | - |
| 440 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.5 | PASS | - |
| 441 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.6 | PASS | - |
| 442 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | PASS | - |
| 443 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | PASS | - |
| 444 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 445 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 446 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | PASS | - |
| 447 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | PASS | - |
| 448 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.13 | PASS | - |
| 449 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.5 | PASS | - |
| 450 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.6 | PASS | - |
| 451 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | PASS | - |
| 452 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | PASS | - |
| 453 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 454 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 455 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | PASS | - |
| 456 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | PASS | - |
| 457 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.13 | PASS | - |
