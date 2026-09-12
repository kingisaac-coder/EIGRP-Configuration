# EIGRP-Configuration
Cisco Packet Tracer lab focused on configuring EIGRP for dynamic routing, route discovery, and network connectivity between multiple routers.

# EIGRP Configuration

## 📖 Overview

This lab focused on configuring Enhanced Interior Gateway Routing Protocol (EIGRP) on Cisco routers to enable dynamic routing between multiple networks.

The lab provided hands-on experience with configuring EIGRP, advertising connected networks, establishing neighbor relationships, and verifying dynamically learned routes.

## 🎯 Objectives

The lab was designed to:

* Configure IP addressing on router interfaces.
* Enable EIGRP on multiple routers.
* Configure the appropriate EIGRP networks.
* Establish EIGRP neighbor relationships.
* Advertise connected networks through EIGRP.
* Examine dynamically learned routes.
* Verify end-to-end connectivity.
* Troubleshoot EIGRP configuration and routing issues.

## 🧠 Concepts Practiced

* Dynamic routing
* EIGRP
* EIGRP neighbor relationships
* Autonomous System (AS) numbers
* Network statements
* Routing tables
* Dynamic route advertisement
* Administrative distance
* EIGRP metric
* Successor and feasible successor concepts
* Network troubleshooting

## 🛠️ Tools Used

* Cisco Packet Tracer
* Cisco IOS CLI

## ⚙️ Configuration

EIGRP was configured on the participating routers using Cisco IOS.

The appropriate EIGRP autonomous system number was configured, and the connected networks were advertised using EIGRP network statements.

Once configured, the routers exchanged routing information and dynamically learned routes to remote networks.

## 🧪 Verification & Testing

The EIGRP configuration was verified using commands such as:

```text
show ip eigrp neighbors
show ip route
show ip protocols
show ip eigrp topology
```

Connectivity was tested using:

```text
ping
traceroute
```

These tests were used to confirm that routers successfully formed EIGRP neighbor relationships and that remote networks were reachable through dynamically learned routes.

## 🔍 Troubleshooting

Common EIGRP issues investigated during the lab included:

* Incorrect network statements.
* Incorrect IP addressing.
* Interfaces being down.
* Routers using different EIGRP AS numbers.
* Missing network advertisements.
* Incorrect subnet masks.
* Missing or incorrect routes.
* Failed EIGRP neighbor relationships.

Troubleshooting involved examining EIGRP neighbors, routing tables, protocol configuration, and the EIGRP topology table.

## 🚀 Advanced Routing Concepts

EIGRP can select routes based on its composite metric, which considers factors such as bandwidth and delay.

The protocol can also maintain backup paths through feasible successors, allowing it to adapt when a preferred route becomes unavailable.

These concepts provide a foundation for understanding more advanced dynamic-routing behavior and route selection.

## ✅ Outcome

Successfully configured EIGRP across multiple Cisco routers, established dynamic routing relationships, verified dynamically learned routes, and tested end-to-end connectivity across the network.

## 📚 Skills Demonstrated

* Cisco IOS CLI
* EIGRP configuration
* Dynamic routing
* Routing-table analysis
* EIGRP neighbor verification
* Route advertisement
* Network troubleshooting
* Connectivity testing
* Enterprise routing fundamentals
