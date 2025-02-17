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
| 426 | 422 | 4 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| borderleaf1 |  53 | 53 | 0 | - |
| borderleaf2 |  53 | 53 | 0 | - |
| leaf1 |  55 | 54 | 1 | Interface State |
| leaf2 |  55 | 54 | 1 | Interface State |
| leaf3 |  55 | 54 | 1 | Interface State |
| leaf4 |  56 | 55 | 1 | Interface State |
| spine1 |  33 | 33 | 0 | - |
| spine2 |  33 | 33 | 0 | - |
| spine3 |  33 | 33 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  9 | 9 | 0 |
| Interface State |  114 | 110 | 4 |
| LLDP Topology |  48 | 48 | 0 |
| MLAG |  6 | 6 | 0 |
| IP Reachability |  36 | 36 | 0 |
| BGP |  87 | 87 | 0 |
| Routing Table |  72 | 72 | 0 |
| Loopback0 Reachability |  54 | 54 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 66 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 68 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 70 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 72 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |

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
| 15 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf1_Ethernet1 | PASS | - |
| 16 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf1_Ethernet2 | PASS | - |
| 17 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet7 | PASS | - |
| 18 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet7 | PASS | - |
| 19 | borderleaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet7 | PASS | - |
| 20 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2_Ethernet1 | PASS | - |
| 21 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2_Ethernet2 | PASS | - |
| 22 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet2 | PASS | - |
| 23 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet2 | PASS | - |
| 24 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet2 | PASS | - |
| 25 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet1 | PASS | - |
| 26 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1_Ethernet1 | PASS | - |
| 27 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1_Ethernet2 | PASS | - |
| 28 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet3 | PASS | - |
| 29 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet3 | PASS | - |
| 30 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet3 | PASS | - |
| 31 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet2 | PASS | - |
| 32 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4_Ethernet1 | PASS | - |
| 33 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4_Ethernet2 | PASS | - |
| 34 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet4 | PASS | - |
| 35 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet4 | PASS | - |
| 36 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet4 | PASS | - |
| 37 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet1 | PASS | - |
| 38 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3_Ethernet1 | PASS | - |
| 39 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3_Ethernet2 | PASS | - |
| 40 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet5 | PASS | - |
| 41 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet5 | PASS | - |
| 42 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet5 | PASS | - |
| 43 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet9 -  | PASS | - |
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
| 66 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 67 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1_Po1 | PASS | - |
| 68 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 69 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4_Po1 | PASS | - |
| 70 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 71 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3_Po1 | PASS | - |
| 72 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host2_PortChannel host2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 73 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 74 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 75 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 76 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 77 | borderleaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 78 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 79 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 80 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 81 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 82 | borderleaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 83 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 84 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 85 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 86 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 87 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 88 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 89 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 90 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 91 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 92 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 93 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 94 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 95 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 96 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 97 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 98 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 99 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 100 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 101 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 102 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 103 | borderleaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 104 | borderleaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 105 | leaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 106 | leaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 107 | leaf3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 108 | leaf4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 109 | borderleaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 110 | borderleaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 111 | borderleaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 112 | borderleaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 113 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 114 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 115 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 116 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 117 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 118 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 119 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 120 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 121 | spine1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 122 | spine2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 123 | spine3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 124 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf2_Ethernet1 | PASS | - |
| 125 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf2_Ethernet2 | PASS | - |
| 126 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet6 | PASS | - |
| 127 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet6 | PASS | - |
| 128 | borderleaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet6 | PASS | - |
| 129 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf1_Ethernet1 | PASS | - |
| 130 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf1_Ethernet2 | PASS | - |
| 131 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet7 | PASS | - |
| 132 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet7 | PASS | - |
| 133 | borderleaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet7 | PASS | - |
| 134 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2_Ethernet1 | PASS | - |
| 135 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2_Ethernet2 | PASS | - |
| 136 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet2 | PASS | - |
| 137 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet2 | PASS | - |
| 138 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet2 | PASS | - |
| 139 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1_Ethernet1 | PASS | - |
| 140 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet2 | PASS | - |
| 141 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | PASS | - |
| 142 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | PASS | - |
| 143 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet3 | PASS | - |
| 144 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4_Ethernet1 | PASS | - |
| 145 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4_Ethernet2 | PASS | - |
| 146 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | PASS | - |
| 147 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | PASS | - |
| 148 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet4 | PASS | - |
| 149 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3_Ethernet1 | PASS | - |
| 150 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3_Ethernet2 | PASS | - |
| 151 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | PASS | - |
| 152 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | PASS | - |
| 153 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet5 | PASS | - |
| 154 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet3 | PASS | - |
| 155 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet3 | PASS | - |
| 156 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet3 | PASS | - |
| 157 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet3 | PASS | - |
| 158 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet3 | PASS | - |
| 159 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet3 | PASS | - |
| 160 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet4 | PASS | - |
| 161 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet4 | PASS | - |
| 162 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet4 | PASS | - |
| 163 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet4 | PASS | - |
| 164 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet4 | PASS | - |
| 165 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet4 | PASS | - |
| 166 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet5 | PASS | - |
| 167 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet5 | PASS | - |
| 168 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet5 | PASS | - |
| 169 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet5 | PASS | - |
| 170 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1_Ethernet5 | PASS | - |
| 171 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2_Ethernet5 | PASS | - |
| 172 | borderleaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 173 | borderleaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 174 | leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 175 | leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 176 | leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 177 | leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 178 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet3 - Destination: spine1_Ethernet6 | PASS | - |
| 179 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet4 - Destination: spine2_Ethernet6 | PASS | - |
| 180 | borderleaf1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1_Ethernet5 - Destination: spine3_Ethernet6 | PASS | - |
| 181 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet3 - Destination: spine1_Ethernet7 | PASS | - |
| 182 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet4 - Destination: spine2_Ethernet7 | PASS | - |
| 183 | borderleaf2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2_Ethernet5 - Destination: spine3_Ethernet7 | PASS | - |
| 184 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet2 | PASS | - |
| 185 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet2 | PASS | - |
| 186 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet5 - Destination: spine3_Ethernet2 | PASS | - |
| 187 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet3 | PASS | - |
| 188 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet3 | PASS | - |
| 189 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet5 - Destination: spine3_Ethernet3 | PASS | - |
| 190 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet4 | PASS | - |
| 191 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet4 | PASS | - |
| 192 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet5 - Destination: spine3_Ethernet4 | PASS | - |
| 193 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet5 | PASS | - |
| 194 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet5 | PASS | - |
| 195 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet5 - Destination: spine3_Ethernet5 | PASS | - |
| 196 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet2 - Destination: leaf1_Ethernet3 | PASS | - |
| 197 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf2_Ethernet3 | PASS | - |
| 198 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf3_Ethernet3 | PASS | - |
| 199 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf4_Ethernet3 | PASS | - |
| 200 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet6 - Destination: borderleaf1_Ethernet3 | PASS | - |
| 201 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet7 - Destination: borderleaf2_Ethernet3 | PASS | - |
| 202 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet2 - Destination: leaf1_Ethernet4 | PASS | - |
| 203 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf2_Ethernet4 | PASS | - |
| 204 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf3_Ethernet4 | PASS | - |
| 205 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf4_Ethernet4 | PASS | - |
| 206 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet6 - Destination: borderleaf1_Ethernet4 | PASS | - |
| 207 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet7 - Destination: borderleaf2_Ethernet4 | PASS | - |
| 208 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet2 - Destination: leaf1_Ethernet5 | PASS | - |
| 209 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet3 - Destination: leaf2_Ethernet5 | PASS | - |
| 210 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet4 - Destination: leaf3_Ethernet5 | PASS | - |
| 211 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet5 - Destination: leaf4_Ethernet5 | PASS | - |
| 212 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet6 - Destination: borderleaf1_Ethernet5 | PASS | - |
| 213 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet7 - Destination: borderleaf2_Ethernet5 | PASS | - |
| 214 | borderleaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 215 | borderleaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 216 | leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 217 | leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 218 | leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 219 | leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 220 | spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 221 | spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 222 | spine3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 223 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 224 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.24 | PASS | - |
| 225 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.26 | PASS | - |
| 226 | borderleaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.28 | PASS | - |
| 227 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 228 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.30 | PASS | - |
| 229 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.32 | PASS | - |
| 230 | borderleaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.34 | PASS | - |
| 231 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 232 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | PASS | - |
| 233 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | PASS | - |
| 234 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | PASS | - |
| 235 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 236 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | PASS | - |
| 237 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | PASS | - |
| 238 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | PASS | - |
| 239 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 240 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | PASS | - |
| 241 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | PASS | - |
| 242 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | PASS | - |
| 243 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 244 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | PASS | - |
| 245 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | PASS | - |
| 246 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | PASS | - |
| 247 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | PASS | - |
| 248 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | PASS | - |
| 249 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | PASS | - |
| 250 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | PASS | - |
| 251 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.25 | PASS | - |
| 252 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.31 | PASS | - |
| 253 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | PASS | - |
| 254 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | PASS | - |
| 255 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | PASS | - |
| 256 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | PASS | - |
| 257 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.27 | PASS | - |
| 258 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.33 | PASS | - |
| 259 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | PASS | - |
| 260 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | PASS | - |
| 261 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | PASS | - |
| 262 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | PASS | - |
| 263 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.29 | PASS | - |
| 264 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.35 | PASS | - |
| 265 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 266 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 267 | borderleaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 268 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 269 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 270 | borderleaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 271 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 272 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 273 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 274 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 275 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 276 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 277 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 278 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 279 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 280 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 281 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 282 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 283 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 284 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 285 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 286 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 287 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 288 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 289 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 290 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 291 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 292 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 293 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 294 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 295 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 296 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 297 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 298 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 299 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 300 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 301 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 302 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 303 | borderleaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 304 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 305 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 306 | borderleaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 307 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 308 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 309 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 310 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 311 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 312 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 313 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 314 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 315 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 316 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 317 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 318 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 319 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 320 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 321 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 322 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 323 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 324 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 325 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 326 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 327 | borderleaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 328 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 329 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 330 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 331 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 332 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 333 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 334 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 335 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 336 | borderleaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 337 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 338 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 339 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 340 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 341 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 342 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 343 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 344 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 345 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 346 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 347 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 348 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 349 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 350 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 351 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 352 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 353 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 354 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 355 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 356 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 357 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 358 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 359 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 360 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 361 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 362 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 363 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 364 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 365 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 366 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 367 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 368 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 369 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 370 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 371 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 372 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 373 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.5 | PASS | - |
| 374 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.6 | PASS | - |
| 375 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.1 | PASS | - |
| 376 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.2 | PASS | - |
| 377 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.3 | PASS | - |
| 378 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.4 | PASS | - |
| 379 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.11 | PASS | - |
| 380 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.12 | PASS | - |
| 381 | borderleaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1 - 192.168.101.5 Destination: 192.168.101.13 | PASS | - |
| 382 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.5 | PASS | - |
| 383 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.6 | PASS | - |
| 384 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.1 | PASS | - |
| 385 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.2 | PASS | - |
| 386 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.3 | PASS | - |
| 387 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.4 | PASS | - |
| 388 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.11 | PASS | - |
| 389 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.12 | PASS | - |
| 390 | borderleaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2 - 192.168.101.6 Destination: 192.168.101.13 | PASS | - |
| 391 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.5 | PASS | - |
| 392 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.6 | PASS | - |
| 393 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 394 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 395 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | PASS | - |
| 396 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | PASS | - |
| 397 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | PASS | - |
| 398 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | PASS | - |
| 399 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.13 | PASS | - |
| 400 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.5 | PASS | - |
| 401 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.6 | PASS | - |
| 402 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 403 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 404 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | PASS | - |
| 405 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | PASS | - |
| 406 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | PASS | - |
| 407 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | PASS | - |
| 408 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.13 | PASS | - |
| 409 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.5 | PASS | - |
| 410 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.6 | PASS | - |
| 411 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | PASS | - |
| 412 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | PASS | - |
| 413 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 414 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 415 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | PASS | - |
| 416 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | PASS | - |
| 417 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.13 | PASS | - |
| 418 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.5 | PASS | - |
| 419 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.6 | PASS | - |
| 420 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | PASS | - |
| 421 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | PASS | - |
| 422 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 423 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 424 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | PASS | - |
| 425 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | PASS | - |
| 426 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.13 | PASS | - |
