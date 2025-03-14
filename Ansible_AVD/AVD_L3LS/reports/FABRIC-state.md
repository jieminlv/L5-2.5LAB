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
| 456 | 456 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| borderleaf1 |  59 | 59 | 0 | - |
| borderleaf2 |  58 | 58 | 0 | - |
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
| Interface State |  144 | 144 | 0 |
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
| 21 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2_Ethernet1 | PASS | - |
| 22 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2_Ethernet2 | PASS | - |
| 23 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet2 | PASS | - |
| 24 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet2 | PASS | - |
| 25 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet2 | PASS | - |
| 26 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet1 | PASS | - |
| 27 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1_Ethernet1 | PASS | - |
| 28 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1_Ethernet2 | PASS | - |
| 29 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet3 | PASS | - |
| 30 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet3 | PASS | - |
| 31 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet3 | PASS | - |
| 32 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet2 | PASS | - |
| 33 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4_Ethernet1 | PASS | - |
| 34 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4_Ethernet2 | PASS | - |
| 35 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet4 | PASS | - |
| 36 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet4 | PASS | - |
| 37 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet4 | PASS | - |
| 38 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet1 | PASS | - |
| 39 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3_Ethernet1 | PASS | - |
| 40 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3_Ethernet2 | PASS | - |
| 41 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet5 | PASS | - |
| 42 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet5 | PASS | - |
| 43 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet5 | PASS | - |
| 44 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet2 | PASS | - |
| 45 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet3 | PASS | - |
| 46 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet3 | PASS | - |
| 47 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet3 | PASS | - |
| 48 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet3 | PASS | - |
| 49 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1_Ethernet3 | PASS | - |
| 50 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2_Ethernet3 | PASS | - |
| 51 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet4 | PASS | - |
| 52 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet4 | PASS | - |
| 53 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet4 | PASS | - |
| 54 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet4 | PASS | - |
| 55 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1_Ethernet4 | PASS | - |
| 56 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2_Ethernet4 | PASS | - |
| 57 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet5 | PASS | - |
| 58 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet5 | PASS | - |
| 59 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet5 | PASS | - |
| 60 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet5 | PASS | - |
| 61 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1_Ethernet5 | PASS | - |
| 62 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2_Ethernet5 | PASS | - |
| 63 | borderleaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf2_Po1 | PASS | - |
| 64 | borderleaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf1_Po1 | PASS | - |
| 65 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2_Po1 | PASS | - |
| 66 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | PASS | - |
| 67 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1_Po1 | PASS | - |
| 68 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | PASS | - |
| 69 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4_Po1 | PASS | - |
| 70 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | PASS | - |
| 71 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3_Po1 | PASS | - |
| 72 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | PASS | - |
| 73 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 74 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 75 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 76 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 77 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 78 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 79 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 80 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 81 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 82 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 83 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 84 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 85 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 86 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 87 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 88 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 89 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 90 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 91 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 92 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 93 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 94 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 95 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 96 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 97 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 98 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 99 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 100 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 101 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 102 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 103 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 104 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 105 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 106 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 107 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 108 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 109 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 110 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 111 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 112 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 113 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 114 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 115 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 116 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 117 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 118 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 119 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 120 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 121 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 122 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 123 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 124 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 125 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ-1 | PASS | - |
| 126 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal-1 | PASS | - |
| 127 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Staging-1 | PASS | - |
| 128 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 129 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - DMZ-2 | PASS | - |
| 130 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan50 - Internal-2 | PASS | - |
| 131 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan60 - Staging-2 | PASS | - |
| 132 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf VRF_B | PASS | - |
| 133 | borderleaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 134 | borderleaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 135 | leaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 136 | leaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 137 | leaf3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 138 | leaf4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 139 | borderleaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 140 | borderleaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 141 | borderleaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 142 | borderleaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 143 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 144 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 145 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 146 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 147 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 148 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 149 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 150 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 151 | spine1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 152 | spine2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 153 | spine3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 154 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf2_Ethernet1 | PASS | - |
| 155 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf2_Ethernet2 | PASS | - |
| 156 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet6 | PASS | - |
| 157 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet6 | PASS | - |
| 158 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet6 | PASS | - |
| 159 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf1_Ethernet1 | PASS | - |
| 160 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf1_Ethernet2 | PASS | - |
| 161 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet7 | PASS | - |
| 162 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet7 | PASS | - |
| 163 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet7 | PASS | - |
| 164 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2_Ethernet1 | PASS | - |
| 165 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2_Ethernet2 | PASS | - |
| 166 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet2 | PASS | - |
| 167 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet2 | PASS | - |
| 168 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet2 | PASS | - |
| 169 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1_Ethernet1 | PASS | - |
| 170 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet2 | PASS | - |
| 171 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | PASS | - |
| 172 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | PASS | - |
| 173 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet3 | PASS | - |
| 174 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4_Ethernet1 | PASS | - |
| 175 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4_Ethernet2 | PASS | - |
| 176 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | PASS | - |
| 177 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | PASS | - |
| 178 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet4 | PASS | - |
| 179 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3_Ethernet1 | PASS | - |
| 180 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3_Ethernet2 | PASS | - |
| 181 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | PASS | - |
| 182 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | PASS | - |
| 183 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet5 | PASS | - |
| 184 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet3 | PASS | - |
| 185 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet3 | PASS | - |
| 186 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet3 | PASS | - |
| 187 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet3 | PASS | - |
| 188 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet3 | PASS | - |
| 189 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet3 | PASS | - |
| 190 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet4 | PASS | - |
| 191 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet4 | PASS | - |
| 192 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet4 | PASS | - |
| 193 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet4 | PASS | - |
| 194 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet4 | PASS | - |
| 195 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet4 | PASS | - |
| 196 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet5 | PASS | - |
| 197 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet5 | PASS | - |
| 198 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet5 | PASS | - |
| 199 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet5 | PASS | - |
| 200 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet5 | PASS | - |
| 201 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet5 | PASS | - |
| 202 | borderleaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 203 | borderleaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 204 | leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 205 | leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 206 | leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 207 | leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 208 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet3 - Destination: spine1_Ethernet6 | PASS | - |
| 209 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet4 - Destination: spine2_Ethernet6 | PASS | - |
| 210 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet5 - Destination: spine3_Ethernet6 | PASS | - |
| 211 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet3 - Destination: spine1_Ethernet7 | PASS | - |
| 212 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet4 - Destination: spine2_Ethernet7 | PASS | - |
| 213 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet5 - Destination: spine3_Ethernet7 | PASS | - |
| 214 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet2 | PASS | - |
| 215 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet2 | PASS | - |
| 216 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet5 - Destination: spine3_Ethernet2 | PASS | - |
| 217 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet3 | PASS | - |
| 218 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet3 | PASS | - |
| 219 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet5 - Destination: spine3_Ethernet3 | PASS | - |
| 220 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet4 | PASS | - |
| 221 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet4 | PASS | - |
| 222 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet5 - Destination: spine3_Ethernet4 | PASS | - |
| 223 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet5 | PASS | - |
| 224 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet5 | PASS | - |
| 225 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet5 - Destination: spine3_Ethernet5 | PASS | - |
| 226 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet2 - Destination: leaf1_Ethernet3 | PASS | - |
| 227 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf2_Ethernet3 | PASS | - |
| 228 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf3_Ethernet3 | PASS | - |
| 229 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf4_Ethernet3 | PASS | - |
| 230 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet6 - Destination: borderleaf1_Ethernet3 | PASS | - |
| 231 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet7 - Destination: borderleaf2_Ethernet3 | PASS | - |
| 232 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet2 - Destination: leaf1_Ethernet4 | PASS | - |
| 233 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf2_Ethernet4 | PASS | - |
| 234 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf3_Ethernet4 | PASS | - |
| 235 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf4_Ethernet4 | PASS | - |
| 236 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet6 - Destination: borderleaf1_Ethernet4 | PASS | - |
| 237 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet7 - Destination: borderleaf2_Ethernet4 | PASS | - |
| 238 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet2 - Destination: leaf1_Ethernet5 | PASS | - |
| 239 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet3 - Destination: leaf2_Ethernet5 | PASS | - |
| 240 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet4 - Destination: leaf3_Ethernet5 | PASS | - |
| 241 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet5 - Destination: leaf4_Ethernet5 | PASS | - |
| 242 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet6 - Destination: borderleaf1_Ethernet5 | PASS | - |
| 243 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet7 - Destination: borderleaf2_Ethernet5 | PASS | - |
| 244 | borderleaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 245 | borderleaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 246 | leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 247 | leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 248 | leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 249 | leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 250 | spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 251 | spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 252 | spine3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 253 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 254 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.24 | PASS | - |
| 255 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.26 | PASS | - |
| 256 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.28 | PASS | - |
| 257 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 258 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.30 | PASS | - |
| 259 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.32 | PASS | - |
| 260 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.34 | PASS | - |
| 261 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 262 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | PASS | - |
| 263 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | PASS | - |
| 264 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | PASS | - |
| 265 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 266 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | PASS | - |
| 267 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | PASS | - |
| 268 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | PASS | - |
| 269 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 270 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | PASS | - |
| 271 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | PASS | - |
| 272 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | PASS | - |
| 273 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 274 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | PASS | - |
| 275 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | PASS | - |
| 276 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | PASS | - |
| 277 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | PASS | - |
| 278 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | PASS | - |
| 279 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | PASS | - |
| 280 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | PASS | - |
| 281 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.25 | PASS | - |
| 282 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.31 | PASS | - |
| 283 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | PASS | - |
| 284 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | PASS | - |
| 285 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | PASS | - |
| 286 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | PASS | - |
| 287 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.27 | PASS | - |
| 288 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.33 | PASS | - |
| 289 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | PASS | - |
| 290 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | PASS | - |
| 291 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | PASS | - |
| 292 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | PASS | - |
| 293 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.29 | PASS | - |
| 294 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.35 | PASS | - |
| 295 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 296 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 297 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 298 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 299 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 300 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 301 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 302 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 303 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 304 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 305 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 306 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 307 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 308 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 309 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 310 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 311 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 312 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 313 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 314 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 315 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 316 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 317 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 318 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 319 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 320 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 321 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 322 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 323 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 324 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 325 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 326 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 327 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 328 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 329 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 330 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 331 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 332 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 333 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 334 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 335 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 336 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 337 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 338 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 339 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 340 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 341 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 342 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 343 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 344 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 345 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 346 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 347 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 348 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 349 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 350 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 351 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 352 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 353 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 354 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 355 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 356 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 357 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 358 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 359 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 360 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 361 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 362 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 363 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 364 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 365 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 366 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 367 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 368 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 369 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 370 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 371 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 372 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 373 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 374 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 375 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 376 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 377 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 378 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 379 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 380 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 381 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 382 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 383 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 384 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 385 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 386 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 387 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 388 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 389 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 390 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 391 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 392 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 393 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 394 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 395 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 396 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 397 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 398 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 399 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 400 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 401 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 402 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 403 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.5 | PASS | - |
| 404 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.6 | PASS | - |
| 405 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.1 | PASS | - |
| 406 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.2 | PASS | - |
| 407 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.3 | PASS | - |
| 408 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.4 | PASS | - |
| 409 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.11 | PASS | - |
| 410 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.12 | PASS | - |
| 411 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.13 | PASS | - |
| 412 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.5 | PASS | - |
| 413 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.6 | PASS | - |
| 414 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.1 | PASS | - |
| 415 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.2 | PASS | - |
| 416 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.3 | PASS | - |
| 417 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.4 | PASS | - |
| 418 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.11 | PASS | - |
| 419 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.12 | PASS | - |
| 420 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.13 | PASS | - |
| 421 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.5 | PASS | - |
| 422 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.6 | PASS | - |
| 423 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 424 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 425 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | PASS | - |
| 426 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | PASS | - |
| 427 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | PASS | - |
| 428 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | PASS | - |
| 429 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.13 | PASS | - |
| 430 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.5 | PASS | - |
| 431 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.6 | PASS | - |
| 432 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 433 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 434 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | PASS | - |
| 435 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | PASS | - |
| 436 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | PASS | - |
| 437 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | PASS | - |
| 438 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.13 | PASS | - |
| 439 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.5 | PASS | - |
| 440 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.6 | PASS | - |
| 441 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | PASS | - |
| 442 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | PASS | - |
| 443 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 444 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 445 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | PASS | - |
| 446 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | PASS | - |
| 447 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.13 | PASS | - |
| 448 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.5 | PASS | - |
| 449 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.6 | PASS | - |
| 450 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | PASS | - |
| 451 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | PASS | - |
| 452 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 453 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 454 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | PASS | - |
| 455 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | PASS | - |
| 456 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.13 | PASS | - |
