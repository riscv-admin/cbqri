# Cache and Memory Control QoS Register Interface (CMQRI) Task Group Charter

The CMQRI Task Group shall develop a memory-mapped register interface to cache and memory controllers for:

1. Configuring cache capacity allocation
2. Configuring memory bandwidth allocation
3. Monitoring cache occupancy statistics\n4.Monitoring memory bandwidth usage

The CMQRI specification shall complement the QoS Identifiers extension proposal that defines the sqoscfg CSR to associate a resource-control-ID (RCID) and a monitoring-counter-ID (MCID) with software execution on hart.

The CMQRI specification shall not prescribe:

- The level of QoS in the system
- Methods for resource usage metering or enforcement of allocated resource limits
- Behavior of components in the system that choose not to implement CMQRI

The CMQRI TG shall validate its specification by prototyping the behavior using QEMU and demonstrate integration with Linux resource control framework with CMQRI.
