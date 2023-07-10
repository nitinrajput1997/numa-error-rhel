# numa-error-rhel

The error message indicates that the file numa.h is not found, causing a fatal error during the compilation process of the eal_memory.c file in the DPDK (Data Plane Development Kit) library. This error is commonly encountered when the necessary development package for NUMA (Non-Uniform Memory Access) support is not installed on the system.

To resolve this issue, you can follow these steps:

Install the necessary development package: Use the package manager (dnf in RHEL 8) to install the numactl-devel package, which provides the development files required for NUMA support:

```
sudo dnf install numactl-devel
```
