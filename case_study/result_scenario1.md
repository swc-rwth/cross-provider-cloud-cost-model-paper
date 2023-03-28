# Cost Estimate Result for Scenario 1

To obtain the estimate, run:

```sh
cccm_prototype.py --case-study-scenario-1 
```

This results in the following output:

```
## Cloud Infrastructure Costs ##########################################################################################
Initializing scenario (this may take a while as this is not optimized for efficiency)...
** Infrastructure ******************************************************************************************************
Time interval: 2023-02-01 00:00:00 to 2023-03-01 00:00:00
Resources:
[1]    Resource:       information_system_server.0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[2]    Resource:       information_system_server.1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[3]    Resource:       information_system_server.2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[4]    Resource:       information_system_server.3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[5]    Resource:       information_system_server.4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[6]    Resource:       information_system_server.5
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[7]    Resource:       information_system_server.6
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[8]    Resource:       information_system_server.7
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[9]    Resource:       information_system_server.8
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[10]   Resource:       information_system_server.9
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[11]   Resource:       information_system_server.10
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[12]   Resource:       information_system_server.11
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[13]   Resource:       information_system_server.12
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[14]   Resource:       information_system_server.13
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[15]   Resource:       information_system_server.14
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[16]   Resource:       information_system_server.15
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[17]   Resource:       information_system_server.16
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[18]   Resource:       information_system_server.17
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[19]   Resource:       information_system_server.18
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[20]   Resource:       information_system_server.19
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[21]   Resource:       information_system_server.20
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[22]   Resource:       information_system_server.21
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[23]   Resource:       information_system_server.22
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[24]   Resource:       information_system_server.23
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[25]   Resource:       information_system_server.24
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[26]   Resource:       information_system_server.25
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[27]   Resource:       information_system_server.26
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[28]   Resource:       information_system_server.27
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[29]   Resource:       information_system_server.28
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[30]   Resource:       information_system_server.29
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[31]   Resource:       information_system_server.30
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[32]   Resource:       information_system_server.31
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[33]   Resource:       support_application_server
  Selected offer: Azure, Compute, Standard F8s v2, Azure Region: North Germany
[34]   Resource:       support_application_storage
  Selected offer: Azure, Disk Storage, Standard SSD, E15, Local Redundant Storage (LRS), Azure Region: North Germany
Initialized resources in 0.23 seconds.
Computing costs for cloud infrastructure...
** Costs ***************************************************************************************************************
[1]    Resource: information_system_server.0
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[2]    Resource: information_system_server.1
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[3]    Resource: information_system_server.2
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[4]    Resource: information_system_server.3
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[5]    Resource: information_system_server.4
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[6]    Resource: information_system_server.5
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[7]    Resource: information_system_server.6
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[8]    Resource: information_system_server.7
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[9]    Resource: information_system_server.8
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[10]   Resource: information_system_server.9
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[11]   Resource: information_system_server.10
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[12]   Resource: information_system_server.11
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[13]   Resource: information_system_server.12
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[14]   Resource: information_system_server.13
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[15]   Resource: information_system_server.14
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[16]   Resource: information_system_server.15
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[17]   Resource: information_system_server.16
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[18]   Resource: information_system_server.17
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[19]   Resource: information_system_server.18
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[20]   Resource: information_system_server.19
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[21]   Resource: information_system_server.20
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[22]   Resource: information_system_server.21
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[23]   Resource: information_system_server.22
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[24]   Resource: information_system_server.23
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[25]   Resource: information_system_server.24
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[26]   Resource: information_system_server.25
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[27]   Resource: information_system_server.26
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[28]   Resource: information_system_server.27
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[29]   Resource: information_system_server.28
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[30]   Resource: information_system_server.29
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[31]   Resource: information_system_server.30
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[32]   Resource: information_system_server.31
       - component: instance_time ......................................     2419200.00 units USD    3824.35
                                                                                             ---------------
         resource cost ...................................................................... USD    3824.35

[33]   Resource: support_application_server
       - component: instance_time ......................................     2419200.00 units USD     338.69
                                                                                             ---------------
         resource cost ...................................................................... USD     338.69

[34]   Resource: support_application_storage
       - component: storage ............................................     2419200.00 units USD      24.96
       - component: iops ...............................................       18412.80 units USD      36.83
                                                                                             ---------------
         resource cost ...................................................................... USD      61.79

                                                                                             ===============
Total cost (for interval: 2023-02-01 00:00:00 to 2023-03-01 00:00:00) ....................... USD  122779.74

Total usage units:
instance_time...........................................................    79833600.00 units
iops....................................................................       18412.80 units
storage.................................................................     2419200.00 units
Warning: This is the sum of usage units for each component across all offers, e.g., also across different VM types. The
unit of one usage unit depends on the component and the adjustment by the cloud provider, e.g., it is GB * seconds for
the component storage and Azure's IOPS units (10,000 IOPS) for the component iops.
Computed costs in 7.99 seconds.
########################################################################################################################
```