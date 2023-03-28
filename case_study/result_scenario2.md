# Cost Estimate Result for Scenario 2

To obtain the estimate, run:

```sh
cccm_prototype.py --case-study-scenario-2
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
[9]    Resource:       information_system_server.day_1.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[10]   Resource:       information_system_server.day_1.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[11]   Resource:       information_system_server.day_1.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[12]   Resource:       information_system_server.day_1.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[13]   Resource:       information_system_server.day_1.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[14]   Resource:       information_system_server.day_1.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[15]   Resource:       information_system_server.day_1.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[16]   Resource:       information_system_server.day_1.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[17]   Resource:       information_system_server.day_1.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[18]   Resource:       information_system_server.day_1.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[19]   Resource:       information_system_server.day_1.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[20]   Resource:       information_system_server.day_1.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[21]   Resource:       information_system_server.day_1.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[22]   Resource:       information_system_server.day_1.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[23]   Resource:       information_system_server.day_1.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[24]   Resource:       information_system_server.day_1.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[25]   Resource:       information_system_server.day_2.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[26]   Resource:       information_system_server.day_2.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[27]   Resource:       information_system_server.day_2.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[28]   Resource:       information_system_server.day_2.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[29]   Resource:       information_system_server.day_2.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[30]   Resource:       information_system_server.day_2.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[31]   Resource:       information_system_server.day_2.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[32]   Resource:       information_system_server.day_2.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[33]   Resource:       information_system_server.day_2.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[34]   Resource:       information_system_server.day_2.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[35]   Resource:       information_system_server.day_2.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[36]   Resource:       information_system_server.day_2.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[37]   Resource:       information_system_server.day_2.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[38]   Resource:       information_system_server.day_2.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[39]   Resource:       information_system_server.day_2.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[40]   Resource:       information_system_server.day_2.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[41]   Resource:       information_system_server.day_3.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[42]   Resource:       information_system_server.day_3.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[43]   Resource:       information_system_server.day_3.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[44]   Resource:       information_system_server.day_3.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[45]   Resource:       information_system_server.day_3.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[46]   Resource:       information_system_server.day_3.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[47]   Resource:       information_system_server.day_3.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[48]   Resource:       information_system_server.day_3.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[49]   Resource:       information_system_server.day_3.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[50]   Resource:       information_system_server.day_3.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[51]   Resource:       information_system_server.day_3.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[52]   Resource:       information_system_server.day_3.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[53]   Resource:       information_system_server.day_3.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[54]   Resource:       information_system_server.day_3.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[55]   Resource:       information_system_server.day_3.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[56]   Resource:       information_system_server.day_3.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[57]   Resource:       information_system_server.day_4.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[58]   Resource:       information_system_server.day_4.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[59]   Resource:       information_system_server.day_4.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[60]   Resource:       information_system_server.day_4.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[61]   Resource:       information_system_server.day_4.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[62]   Resource:       information_system_server.day_4.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[63]   Resource:       information_system_server.day_4.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[64]   Resource:       information_system_server.day_4.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[65]   Resource:       information_system_server.day_4.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[66]   Resource:       information_system_server.day_4.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[67]   Resource:       information_system_server.day_4.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[68]   Resource:       information_system_server.day_4.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[69]   Resource:       information_system_server.day_4.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[70]   Resource:       information_system_server.day_4.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[71]   Resource:       information_system_server.day_4.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[72]   Resource:       information_system_server.day_4.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[73]   Resource:       information_system_server.day_5.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[74]   Resource:       information_system_server.day_5.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[75]   Resource:       information_system_server.day_5.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[76]   Resource:       information_system_server.day_5.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[77]   Resource:       information_system_server.day_5.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[78]   Resource:       information_system_server.day_5.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[79]   Resource:       information_system_server.day_5.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[80]   Resource:       information_system_server.day_5.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[81]   Resource:       information_system_server.day_5.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[82]   Resource:       information_system_server.day_5.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[83]   Resource:       information_system_server.day_5.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[84]   Resource:       information_system_server.day_5.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[85]   Resource:       information_system_server.day_5.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[86]   Resource:       information_system_server.day_5.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[87]   Resource:       information_system_server.day_5.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[88]   Resource:       information_system_server.day_5.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[89]   Resource:       information_system_server.day_6.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[90]   Resource:       information_system_server.day_6.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[91]   Resource:       information_system_server.day_6.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[92]   Resource:       information_system_server.day_6.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[93]   Resource:       information_system_server.day_6.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[94]   Resource:       information_system_server.day_6.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[95]   Resource:       information_system_server.day_6.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[96]   Resource:       information_system_server.day_6.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[97]   Resource:       information_system_server.day_6.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[98]   Resource:       information_system_server.day_6.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[99]   Resource:       information_system_server.day_6.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[100]  Resource:       information_system_server.day_6.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[101]  Resource:       information_system_server.day_6.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[102]  Resource:       information_system_server.day_6.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[103]  Resource:       information_system_server.day_6.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[104]  Resource:       information_system_server.day_6.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[105]  Resource:       information_system_server.day_7.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[106]  Resource:       information_system_server.day_7.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[107]  Resource:       information_system_server.day_7.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[108]  Resource:       information_system_server.day_7.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[109]  Resource:       information_system_server.day_7.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[110]  Resource:       information_system_server.day_7.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[111]  Resource:       information_system_server.day_7.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[112]  Resource:       information_system_server.day_7.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[113]  Resource:       information_system_server.day_7.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[114]  Resource:       information_system_server.day_7.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[115]  Resource:       information_system_server.day_7.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[116]  Resource:       information_system_server.day_7.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[117]  Resource:       information_system_server.day_7.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[118]  Resource:       information_system_server.day_7.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[119]  Resource:       information_system_server.day_7.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[120]  Resource:       information_system_server.day_7.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[121]  Resource:       information_system_server.day_8.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[122]  Resource:       information_system_server.day_8.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[123]  Resource:       information_system_server.day_8.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[124]  Resource:       information_system_server.day_8.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[125]  Resource:       information_system_server.day_8.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[126]  Resource:       information_system_server.day_8.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[127]  Resource:       information_system_server.day_8.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[128]  Resource:       information_system_server.day_8.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[129]  Resource:       information_system_server.day_8.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[130]  Resource:       information_system_server.day_8.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[131]  Resource:       information_system_server.day_8.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[132]  Resource:       information_system_server.day_8.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[133]  Resource:       information_system_server.day_8.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[134]  Resource:       information_system_server.day_8.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[135]  Resource:       information_system_server.day_8.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[136]  Resource:       information_system_server.day_8.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[137]  Resource:       information_system_server.day_9.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[138]  Resource:       information_system_server.day_9.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[139]  Resource:       information_system_server.day_9.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[140]  Resource:       information_system_server.day_9.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[141]  Resource:       information_system_server.day_9.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[142]  Resource:       information_system_server.day_9.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[143]  Resource:       information_system_server.day_9.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[144]  Resource:       information_system_server.day_9.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[145]  Resource:       information_system_server.day_9.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[146]  Resource:       information_system_server.day_9.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[147]  Resource:       information_system_server.day_9.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[148]  Resource:       information_system_server.day_9.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[149]  Resource:       information_system_server.day_9.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[150]  Resource:       information_system_server.day_9.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[151]  Resource:       information_system_server.day_9.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[152]  Resource:       information_system_server.day_9.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[153]  Resource:       information_system_server.day_10.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[154]  Resource:       information_system_server.day_10.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[155]  Resource:       information_system_server.day_10.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[156]  Resource:       information_system_server.day_10.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[157]  Resource:       information_system_server.day_10.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[158]  Resource:       information_system_server.day_10.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[159]  Resource:       information_system_server.day_10.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[160]  Resource:       information_system_server.day_10.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[161]  Resource:       information_system_server.day_10.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[162]  Resource:       information_system_server.day_10.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[163]  Resource:       information_system_server.day_10.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[164]  Resource:       information_system_server.day_10.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[165]  Resource:       information_system_server.day_10.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[166]  Resource:       information_system_server.day_10.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[167]  Resource:       information_system_server.day_10.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[168]  Resource:       information_system_server.day_10.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[169]  Resource:       information_system_server.day_11.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[170]  Resource:       information_system_server.day_11.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[171]  Resource:       information_system_server.day_11.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[172]  Resource:       information_system_server.day_11.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[173]  Resource:       information_system_server.day_11.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[174]  Resource:       information_system_server.day_11.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[175]  Resource:       information_system_server.day_11.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[176]  Resource:       information_system_server.day_11.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[177]  Resource:       information_system_server.day_11.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[178]  Resource:       information_system_server.day_11.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[179]  Resource:       information_system_server.day_11.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[180]  Resource:       information_system_server.day_11.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[181]  Resource:       information_system_server.day_11.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[182]  Resource:       information_system_server.day_11.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[183]  Resource:       information_system_server.day_11.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[184]  Resource:       information_system_server.day_11.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[185]  Resource:       information_system_server.day_12.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[186]  Resource:       information_system_server.day_12.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[187]  Resource:       information_system_server.day_12.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[188]  Resource:       information_system_server.day_12.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[189]  Resource:       information_system_server.day_12.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[190]  Resource:       information_system_server.day_12.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[191]  Resource:       information_system_server.day_12.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[192]  Resource:       information_system_server.day_12.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[193]  Resource:       information_system_server.day_12.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[194]  Resource:       information_system_server.day_12.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[195]  Resource:       information_system_server.day_12.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[196]  Resource:       information_system_server.day_12.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[197]  Resource:       information_system_server.day_12.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[198]  Resource:       information_system_server.day_12.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[199]  Resource:       information_system_server.day_12.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[200]  Resource:       information_system_server.day_12.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[201]  Resource:       information_system_server.day_13.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[202]  Resource:       information_system_server.day_13.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[203]  Resource:       information_system_server.day_13.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[204]  Resource:       information_system_server.day_13.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[205]  Resource:       information_system_server.day_13.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[206]  Resource:       information_system_server.day_13.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[207]  Resource:       information_system_server.day_13.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[208]  Resource:       information_system_server.day_13.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[209]  Resource:       information_system_server.day_13.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[210]  Resource:       information_system_server.day_13.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[211]  Resource:       information_system_server.day_13.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[212]  Resource:       information_system_server.day_13.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[213]  Resource:       information_system_server.day_13.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[214]  Resource:       information_system_server.day_13.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[215]  Resource:       information_system_server.day_13.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[216]  Resource:       information_system_server.day_13.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[217]  Resource:       information_system_server.day_14.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[218]  Resource:       information_system_server.day_14.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[219]  Resource:       information_system_server.day_14.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[220]  Resource:       information_system_server.day_14.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[221]  Resource:       information_system_server.day_14.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[222]  Resource:       information_system_server.day_14.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[223]  Resource:       information_system_server.day_14.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[224]  Resource:       information_system_server.day_14.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[225]  Resource:       information_system_server.day_14.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[226]  Resource:       information_system_server.day_14.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[227]  Resource:       information_system_server.day_14.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[228]  Resource:       information_system_server.day_14.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[229]  Resource:       information_system_server.day_14.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[230]  Resource:       information_system_server.day_14.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[231]  Resource:       information_system_server.day_14.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[232]  Resource:       information_system_server.day_14.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[233]  Resource:       information_system_server.day_15.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[234]  Resource:       information_system_server.day_15.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[235]  Resource:       information_system_server.day_15.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[236]  Resource:       information_system_server.day_15.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[237]  Resource:       information_system_server.day_15.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[238]  Resource:       information_system_server.day_15.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[239]  Resource:       information_system_server.day_15.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[240]  Resource:       information_system_server.day_15.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[241]  Resource:       information_system_server.day_15.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[242]  Resource:       information_system_server.day_15.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[243]  Resource:       information_system_server.day_15.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[244]  Resource:       information_system_server.day_15.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[245]  Resource:       information_system_server.day_15.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[246]  Resource:       information_system_server.day_15.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[247]  Resource:       information_system_server.day_15.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[248]  Resource:       information_system_server.day_15.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[249]  Resource:       information_system_server.day_16.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[250]  Resource:       information_system_server.day_16.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[251]  Resource:       information_system_server.day_16.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[252]  Resource:       information_system_server.day_16.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[253]  Resource:       information_system_server.day_16.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[254]  Resource:       information_system_server.day_16.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[255]  Resource:       information_system_server.day_16.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[256]  Resource:       information_system_server.day_16.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[257]  Resource:       information_system_server.day_16.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[258]  Resource:       information_system_server.day_16.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[259]  Resource:       information_system_server.day_16.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[260]  Resource:       information_system_server.day_16.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[261]  Resource:       information_system_server.day_16.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[262]  Resource:       information_system_server.day_16.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[263]  Resource:       information_system_server.day_16.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[264]  Resource:       information_system_server.day_16.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[265]  Resource:       information_system_server.day_17.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[266]  Resource:       information_system_server.day_17.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[267]  Resource:       information_system_server.day_17.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[268]  Resource:       information_system_server.day_17.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[269]  Resource:       information_system_server.day_17.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[270]  Resource:       information_system_server.day_17.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[271]  Resource:       information_system_server.day_17.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[272]  Resource:       information_system_server.day_17.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[273]  Resource:       information_system_server.day_17.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[274]  Resource:       information_system_server.day_17.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[275]  Resource:       information_system_server.day_17.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[276]  Resource:       information_system_server.day_17.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[277]  Resource:       information_system_server.day_17.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[278]  Resource:       information_system_server.day_17.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[279]  Resource:       information_system_server.day_17.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[280]  Resource:       information_system_server.day_17.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[281]  Resource:       information_system_server.day_18.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[282]  Resource:       information_system_server.day_18.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[283]  Resource:       information_system_server.day_18.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[284]  Resource:       information_system_server.day_18.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[285]  Resource:       information_system_server.day_18.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[286]  Resource:       information_system_server.day_18.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[287]  Resource:       information_system_server.day_18.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[288]  Resource:       information_system_server.day_18.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[289]  Resource:       information_system_server.day_18.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[290]  Resource:       information_system_server.day_18.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[291]  Resource:       information_system_server.day_18.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[292]  Resource:       information_system_server.day_18.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[293]  Resource:       information_system_server.day_18.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[294]  Resource:       information_system_server.day_18.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[295]  Resource:       information_system_server.day_18.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[296]  Resource:       information_system_server.day_18.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[297]  Resource:       information_system_server.day_19.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[298]  Resource:       information_system_server.day_19.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[299]  Resource:       information_system_server.day_19.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[300]  Resource:       information_system_server.day_19.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[301]  Resource:       information_system_server.day_19.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[302]  Resource:       information_system_server.day_19.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[303]  Resource:       information_system_server.day_19.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[304]  Resource:       information_system_server.day_19.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[305]  Resource:       information_system_server.day_19.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[306]  Resource:       information_system_server.day_19.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[307]  Resource:       information_system_server.day_19.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[308]  Resource:       information_system_server.day_19.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[309]  Resource:       information_system_server.day_19.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[310]  Resource:       information_system_server.day_19.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[311]  Resource:       information_system_server.day_19.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[312]  Resource:       information_system_server.day_19.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[313]  Resource:       information_system_server.day_20.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[314]  Resource:       information_system_server.day_20.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[315]  Resource:       information_system_server.day_20.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[316]  Resource:       information_system_server.day_20.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[317]  Resource:       information_system_server.day_20.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[318]  Resource:       information_system_server.day_20.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[319]  Resource:       information_system_server.day_20.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[320]  Resource:       information_system_server.day_20.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[321]  Resource:       information_system_server.day_20.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[322]  Resource:       information_system_server.day_20.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[323]  Resource:       information_system_server.day_20.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[324]  Resource:       information_system_server.day_20.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[325]  Resource:       information_system_server.day_20.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[326]  Resource:       information_system_server.day_20.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[327]  Resource:       information_system_server.day_20.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[328]  Resource:       information_system_server.day_20.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[329]  Resource:       information_system_server.day_21.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[330]  Resource:       information_system_server.day_21.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[331]  Resource:       information_system_server.day_21.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[332]  Resource:       information_system_server.day_21.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[333]  Resource:       information_system_server.day_21.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[334]  Resource:       information_system_server.day_21.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[335]  Resource:       information_system_server.day_21.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[336]  Resource:       information_system_server.day_21.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[337]  Resource:       information_system_server.day_21.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[338]  Resource:       information_system_server.day_21.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[339]  Resource:       information_system_server.day_21.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[340]  Resource:       information_system_server.day_21.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[341]  Resource:       information_system_server.day_21.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[342]  Resource:       information_system_server.day_21.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[343]  Resource:       information_system_server.day_21.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[344]  Resource:       information_system_server.day_21.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[345]  Resource:       information_system_server.day_22.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[346]  Resource:       information_system_server.day_22.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[347]  Resource:       information_system_server.day_22.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[348]  Resource:       information_system_server.day_22.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[349]  Resource:       information_system_server.day_22.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[350]  Resource:       information_system_server.day_22.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[351]  Resource:       information_system_server.day_22.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[352]  Resource:       information_system_server.day_22.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[353]  Resource:       information_system_server.day_22.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[354]  Resource:       information_system_server.day_22.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[355]  Resource:       information_system_server.day_22.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[356]  Resource:       information_system_server.day_22.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[357]  Resource:       information_system_server.day_22.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[358]  Resource:       information_system_server.day_22.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[359]  Resource:       information_system_server.day_22.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[360]  Resource:       information_system_server.day_22.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[361]  Resource:       information_system_server.day_23.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[362]  Resource:       information_system_server.day_23.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[363]  Resource:       information_system_server.day_23.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[364]  Resource:       information_system_server.day_23.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[365]  Resource:       information_system_server.day_23.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[366]  Resource:       information_system_server.day_23.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[367]  Resource:       information_system_server.day_23.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[368]  Resource:       information_system_server.day_23.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[369]  Resource:       information_system_server.day_23.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[370]  Resource:       information_system_server.day_23.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[371]  Resource:       information_system_server.day_23.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[372]  Resource:       information_system_server.day_23.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[373]  Resource:       information_system_server.day_23.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[374]  Resource:       information_system_server.day_23.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[375]  Resource:       information_system_server.day_23.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[376]  Resource:       information_system_server.day_23.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[377]  Resource:       information_system_server.day_24.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[378]  Resource:       information_system_server.day_24.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[379]  Resource:       information_system_server.day_24.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[380]  Resource:       information_system_server.day_24.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[381]  Resource:       information_system_server.day_24.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[382]  Resource:       information_system_server.day_24.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[383]  Resource:       information_system_server.day_24.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[384]  Resource:       information_system_server.day_24.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[385]  Resource:       information_system_server.day_24.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[386]  Resource:       information_system_server.day_24.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[387]  Resource:       information_system_server.day_24.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[388]  Resource:       information_system_server.day_24.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[389]  Resource:       information_system_server.day_24.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[390]  Resource:       information_system_server.day_24.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[391]  Resource:       information_system_server.day_24.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[392]  Resource:       information_system_server.day_24.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[393]  Resource:       information_system_server.day_25.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[394]  Resource:       information_system_server.day_25.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[395]  Resource:       information_system_server.day_25.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[396]  Resource:       information_system_server.day_25.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[397]  Resource:       information_system_server.day_25.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[398]  Resource:       information_system_server.day_25.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[399]  Resource:       information_system_server.day_25.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[400]  Resource:       information_system_server.day_25.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[401]  Resource:       information_system_server.day_25.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[402]  Resource:       information_system_server.day_25.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[403]  Resource:       information_system_server.day_25.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[404]  Resource:       information_system_server.day_25.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[405]  Resource:       information_system_server.day_25.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[406]  Resource:       information_system_server.day_25.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[407]  Resource:       information_system_server.day_25.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[408]  Resource:       information_system_server.day_25.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[409]  Resource:       information_system_server.day_26.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[410]  Resource:       information_system_server.day_26.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[411]  Resource:       information_system_server.day_26.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[412]  Resource:       information_system_server.day_26.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[413]  Resource:       information_system_server.day_26.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[414]  Resource:       information_system_server.day_26.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[415]  Resource:       information_system_server.day_26.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[416]  Resource:       information_system_server.day_26.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[417]  Resource:       information_system_server.day_26.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[418]  Resource:       information_system_server.day_26.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[419]  Resource:       information_system_server.day_26.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[420]  Resource:       information_system_server.day_26.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[421]  Resource:       information_system_server.day_26.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[422]  Resource:       information_system_server.day_26.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[423]  Resource:       information_system_server.day_26.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[424]  Resource:       information_system_server.day_26.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[425]  Resource:       information_system_server.day_27.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[426]  Resource:       information_system_server.day_27.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[427]  Resource:       information_system_server.day_27.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[428]  Resource:       information_system_server.day_27.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[429]  Resource:       information_system_server.day_27.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[430]  Resource:       information_system_server.day_27.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[431]  Resource:       information_system_server.day_27.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[432]  Resource:       information_system_server.day_27.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[433]  Resource:       information_system_server.day_27.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[434]  Resource:       information_system_server.day_27.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[435]  Resource:       information_system_server.day_27.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[436]  Resource:       information_system_server.day_27.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[437]  Resource:       information_system_server.day_27.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[438]  Resource:       information_system_server.day_27.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[439]  Resource:       information_system_server.day_27.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[440]  Resource:       information_system_server.day_27.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[441]  Resource:       information_system_server.day_28.scaling_0.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[442]  Resource:       information_system_server.day_28.scaling_0.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[443]  Resource:       information_system_server.day_28.scaling_0.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[444]  Resource:       information_system_server.day_28.scaling_1.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[445]  Resource:       information_system_server.day_28.scaling_1.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[446]  Resource:       information_system_server.day_28.scaling_1.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[447]  Resource:       information_system_server.day_28.scaling_2.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[448]  Resource:       information_system_server.day_28.scaling_2.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[449]  Resource:       information_system_server.day_28.scaling_2.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[450]  Resource:       information_system_server.day_28.scaling_2.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[451]  Resource:       information_system_server.day_28.scaling_2.instance_4
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[452]  Resource:       information_system_server.day_28.scaling_3.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[453]  Resource:       information_system_server.day_28.scaling_3.instance_1
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[454]  Resource:       information_system_server.day_28.scaling_3.instance_2
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[455]  Resource:       information_system_server.day_28.scaling_3.instance_3
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[456]  Resource:       information_system_server.day_28.scaling_4.instance_0
  Selected offer: azure.compute.germany-north.standard_e64is_v3
[457]  Resource:       support_application_server
  Selected offer: Azure, Compute, Standard F8s v2, Azure Region: North Germany
[458]  Resource:       support_application_storage
  Selected offer: Azure, Disk Storage, Standard SSD, E15, Local Redundant Storage (LRS), Azure Region: North Germany
Initialized resources in 0.20 seconds.
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

[9]    Resource: information_system_server.day_1.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[10]   Resource: information_system_server.day_1.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[11]   Resource: information_system_server.day_1.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[12]   Resource: information_system_server.day_1.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[13]   Resource: information_system_server.day_1.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[14]   Resource: information_system_server.day_1.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[15]   Resource: information_system_server.day_1.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[16]   Resource: information_system_server.day_1.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[17]   Resource: information_system_server.day_1.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[18]   Resource: information_system_server.day_1.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[19]   Resource: information_system_server.day_1.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[20]   Resource: information_system_server.day_1.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[21]   Resource: information_system_server.day_1.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[22]   Resource: information_system_server.day_1.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[23]   Resource: information_system_server.day_1.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[24]   Resource: information_system_server.day_1.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[25]   Resource: information_system_server.day_2.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[26]   Resource: information_system_server.day_2.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[27]   Resource: information_system_server.day_2.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[28]   Resource: information_system_server.day_2.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[29]   Resource: information_system_server.day_2.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[30]   Resource: information_system_server.day_2.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[31]   Resource: information_system_server.day_2.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[32]   Resource: information_system_server.day_2.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[33]   Resource: information_system_server.day_2.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[34]   Resource: information_system_server.day_2.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[35]   Resource: information_system_server.day_2.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[36]   Resource: information_system_server.day_2.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[37]   Resource: information_system_server.day_2.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[38]   Resource: information_system_server.day_2.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[39]   Resource: information_system_server.day_2.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[40]   Resource: information_system_server.day_2.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[41]   Resource: information_system_server.day_3.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[42]   Resource: information_system_server.day_3.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[43]   Resource: information_system_server.day_3.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[44]   Resource: information_system_server.day_3.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[45]   Resource: information_system_server.day_3.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[46]   Resource: information_system_server.day_3.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[47]   Resource: information_system_server.day_3.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[48]   Resource: information_system_server.day_3.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[49]   Resource: information_system_server.day_3.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[50]   Resource: information_system_server.day_3.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[51]   Resource: information_system_server.day_3.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[52]   Resource: information_system_server.day_3.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[53]   Resource: information_system_server.day_3.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[54]   Resource: information_system_server.day_3.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[55]   Resource: information_system_server.day_3.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[56]   Resource: information_system_server.day_3.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[57]   Resource: information_system_server.day_4.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[58]   Resource: information_system_server.day_4.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[59]   Resource: information_system_server.day_4.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[60]   Resource: information_system_server.day_4.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[61]   Resource: information_system_server.day_4.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[62]   Resource: information_system_server.day_4.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[63]   Resource: information_system_server.day_4.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[64]   Resource: information_system_server.day_4.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[65]   Resource: information_system_server.day_4.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[66]   Resource: information_system_server.day_4.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[67]   Resource: information_system_server.day_4.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[68]   Resource: information_system_server.day_4.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[69]   Resource: information_system_server.day_4.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[70]   Resource: information_system_server.day_4.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[71]   Resource: information_system_server.day_4.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[72]   Resource: information_system_server.day_4.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[73]   Resource: information_system_server.day_5.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[74]   Resource: information_system_server.day_5.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[75]   Resource: information_system_server.day_5.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[76]   Resource: information_system_server.day_5.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[77]   Resource: information_system_server.day_5.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[78]   Resource: information_system_server.day_5.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[79]   Resource: information_system_server.day_5.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[80]   Resource: information_system_server.day_5.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[81]   Resource: information_system_server.day_5.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[82]   Resource: information_system_server.day_5.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[83]   Resource: information_system_server.day_5.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[84]   Resource: information_system_server.day_5.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[85]   Resource: information_system_server.day_5.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[86]   Resource: information_system_server.day_5.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[87]   Resource: information_system_server.day_5.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[88]   Resource: information_system_server.day_5.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[89]   Resource: information_system_server.day_6.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[90]   Resource: information_system_server.day_6.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[91]   Resource: information_system_server.day_6.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[92]   Resource: information_system_server.day_6.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[93]   Resource: information_system_server.day_6.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[94]   Resource: information_system_server.day_6.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[95]   Resource: information_system_server.day_6.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[96]   Resource: information_system_server.day_6.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[97]   Resource: information_system_server.day_6.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[98]   Resource: information_system_server.day_6.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[99]   Resource: information_system_server.day_6.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[100]  Resource: information_system_server.day_6.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[101]  Resource: information_system_server.day_6.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[102]  Resource: information_system_server.day_6.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[103]  Resource: information_system_server.day_6.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[104]  Resource: information_system_server.day_6.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[105]  Resource: information_system_server.day_7.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[106]  Resource: information_system_server.day_7.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[107]  Resource: information_system_server.day_7.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[108]  Resource: information_system_server.day_7.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[109]  Resource: information_system_server.day_7.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[110]  Resource: information_system_server.day_7.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[111]  Resource: information_system_server.day_7.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[112]  Resource: information_system_server.day_7.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[113]  Resource: information_system_server.day_7.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[114]  Resource: information_system_server.day_7.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[115]  Resource: information_system_server.day_7.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[116]  Resource: information_system_server.day_7.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[117]  Resource: information_system_server.day_7.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[118]  Resource: information_system_server.day_7.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[119]  Resource: information_system_server.day_7.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[120]  Resource: information_system_server.day_7.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[121]  Resource: information_system_server.day_8.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[122]  Resource: information_system_server.day_8.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[123]  Resource: information_system_server.day_8.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[124]  Resource: information_system_server.day_8.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[125]  Resource: information_system_server.day_8.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[126]  Resource: information_system_server.day_8.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[127]  Resource: information_system_server.day_8.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[128]  Resource: information_system_server.day_8.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[129]  Resource: information_system_server.day_8.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[130]  Resource: information_system_server.day_8.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[131]  Resource: information_system_server.day_8.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[132]  Resource: information_system_server.day_8.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[133]  Resource: information_system_server.day_8.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[134]  Resource: information_system_server.day_8.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[135]  Resource: information_system_server.day_8.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[136]  Resource: information_system_server.day_8.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[137]  Resource: information_system_server.day_9.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[138]  Resource: information_system_server.day_9.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[139]  Resource: information_system_server.day_9.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[140]  Resource: information_system_server.day_9.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[141]  Resource: information_system_server.day_9.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[142]  Resource: information_system_server.day_9.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[143]  Resource: information_system_server.day_9.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[144]  Resource: information_system_server.day_9.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[145]  Resource: information_system_server.day_9.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[146]  Resource: information_system_server.day_9.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[147]  Resource: information_system_server.day_9.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[148]  Resource: information_system_server.day_9.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[149]  Resource: information_system_server.day_9.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[150]  Resource: information_system_server.day_9.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[151]  Resource: information_system_server.day_9.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[152]  Resource: information_system_server.day_9.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[153]  Resource: information_system_server.day_10.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[154]  Resource: information_system_server.day_10.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[155]  Resource: information_system_server.day_10.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[156]  Resource: information_system_server.day_10.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[157]  Resource: information_system_server.day_10.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[158]  Resource: information_system_server.day_10.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[159]  Resource: information_system_server.day_10.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[160]  Resource: information_system_server.day_10.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[161]  Resource: information_system_server.day_10.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[162]  Resource: information_system_server.day_10.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[163]  Resource: information_system_server.day_10.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[164]  Resource: information_system_server.day_10.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[165]  Resource: information_system_server.day_10.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[166]  Resource: information_system_server.day_10.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[167]  Resource: information_system_server.day_10.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[168]  Resource: information_system_server.day_10.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[169]  Resource: information_system_server.day_11.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[170]  Resource: information_system_server.day_11.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[171]  Resource: information_system_server.day_11.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[172]  Resource: information_system_server.day_11.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[173]  Resource: information_system_server.day_11.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[174]  Resource: information_system_server.day_11.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[175]  Resource: information_system_server.day_11.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[176]  Resource: information_system_server.day_11.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[177]  Resource: information_system_server.day_11.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[178]  Resource: information_system_server.day_11.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[179]  Resource: information_system_server.day_11.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[180]  Resource: information_system_server.day_11.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[181]  Resource: information_system_server.day_11.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[182]  Resource: information_system_server.day_11.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[183]  Resource: information_system_server.day_11.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[184]  Resource: information_system_server.day_11.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[185]  Resource: information_system_server.day_12.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[186]  Resource: information_system_server.day_12.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[187]  Resource: information_system_server.day_12.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[188]  Resource: information_system_server.day_12.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[189]  Resource: information_system_server.day_12.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[190]  Resource: information_system_server.day_12.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[191]  Resource: information_system_server.day_12.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[192]  Resource: information_system_server.day_12.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[193]  Resource: information_system_server.day_12.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[194]  Resource: information_system_server.day_12.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[195]  Resource: information_system_server.day_12.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[196]  Resource: information_system_server.day_12.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[197]  Resource: information_system_server.day_12.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[198]  Resource: information_system_server.day_12.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[199]  Resource: information_system_server.day_12.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[200]  Resource: information_system_server.day_12.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[201]  Resource: information_system_server.day_13.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[202]  Resource: information_system_server.day_13.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[203]  Resource: information_system_server.day_13.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[204]  Resource: information_system_server.day_13.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[205]  Resource: information_system_server.day_13.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[206]  Resource: information_system_server.day_13.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[207]  Resource: information_system_server.day_13.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[208]  Resource: information_system_server.day_13.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[209]  Resource: information_system_server.day_13.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[210]  Resource: information_system_server.day_13.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[211]  Resource: information_system_server.day_13.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[212]  Resource: information_system_server.day_13.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[213]  Resource: information_system_server.day_13.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[214]  Resource: information_system_server.day_13.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[215]  Resource: information_system_server.day_13.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[216]  Resource: information_system_server.day_13.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[217]  Resource: information_system_server.day_14.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[218]  Resource: information_system_server.day_14.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[219]  Resource: information_system_server.day_14.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[220]  Resource: information_system_server.day_14.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[221]  Resource: information_system_server.day_14.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[222]  Resource: information_system_server.day_14.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[223]  Resource: information_system_server.day_14.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[224]  Resource: information_system_server.day_14.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[225]  Resource: information_system_server.day_14.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[226]  Resource: information_system_server.day_14.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[227]  Resource: information_system_server.day_14.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[228]  Resource: information_system_server.day_14.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[229]  Resource: information_system_server.day_14.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[230]  Resource: information_system_server.day_14.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[231]  Resource: information_system_server.day_14.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[232]  Resource: information_system_server.day_14.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[233]  Resource: information_system_server.day_15.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[234]  Resource: information_system_server.day_15.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[235]  Resource: information_system_server.day_15.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[236]  Resource: information_system_server.day_15.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[237]  Resource: information_system_server.day_15.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[238]  Resource: information_system_server.day_15.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[239]  Resource: information_system_server.day_15.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[240]  Resource: information_system_server.day_15.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[241]  Resource: information_system_server.day_15.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[242]  Resource: information_system_server.day_15.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[243]  Resource: information_system_server.day_15.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[244]  Resource: information_system_server.day_15.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[245]  Resource: information_system_server.day_15.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[246]  Resource: information_system_server.day_15.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[247]  Resource: information_system_server.day_15.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[248]  Resource: information_system_server.day_15.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[249]  Resource: information_system_server.day_16.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[250]  Resource: information_system_server.day_16.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[251]  Resource: information_system_server.day_16.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[252]  Resource: information_system_server.day_16.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[253]  Resource: information_system_server.day_16.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[254]  Resource: information_system_server.day_16.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[255]  Resource: information_system_server.day_16.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[256]  Resource: information_system_server.day_16.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[257]  Resource: information_system_server.day_16.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[258]  Resource: information_system_server.day_16.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[259]  Resource: information_system_server.day_16.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[260]  Resource: information_system_server.day_16.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[261]  Resource: information_system_server.day_16.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[262]  Resource: information_system_server.day_16.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[263]  Resource: information_system_server.day_16.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[264]  Resource: information_system_server.day_16.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[265]  Resource: information_system_server.day_17.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[266]  Resource: information_system_server.day_17.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[267]  Resource: information_system_server.day_17.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[268]  Resource: information_system_server.day_17.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[269]  Resource: information_system_server.day_17.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[270]  Resource: information_system_server.day_17.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[271]  Resource: information_system_server.day_17.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[272]  Resource: information_system_server.day_17.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[273]  Resource: information_system_server.day_17.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[274]  Resource: information_system_server.day_17.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[275]  Resource: information_system_server.day_17.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[276]  Resource: information_system_server.day_17.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[277]  Resource: information_system_server.day_17.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[278]  Resource: information_system_server.day_17.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[279]  Resource: information_system_server.day_17.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[280]  Resource: information_system_server.day_17.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[281]  Resource: information_system_server.day_18.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[282]  Resource: information_system_server.day_18.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[283]  Resource: information_system_server.day_18.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[284]  Resource: information_system_server.day_18.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[285]  Resource: information_system_server.day_18.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[286]  Resource: information_system_server.day_18.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[287]  Resource: information_system_server.day_18.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[288]  Resource: information_system_server.day_18.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[289]  Resource: information_system_server.day_18.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[290]  Resource: information_system_server.day_18.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[291]  Resource: information_system_server.day_18.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[292]  Resource: information_system_server.day_18.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[293]  Resource: information_system_server.day_18.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[294]  Resource: information_system_server.day_18.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[295]  Resource: information_system_server.day_18.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[296]  Resource: information_system_server.day_18.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[297]  Resource: information_system_server.day_19.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[298]  Resource: information_system_server.day_19.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[299]  Resource: information_system_server.day_19.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[300]  Resource: information_system_server.day_19.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[301]  Resource: information_system_server.day_19.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[302]  Resource: information_system_server.day_19.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[303]  Resource: information_system_server.day_19.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[304]  Resource: information_system_server.day_19.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[305]  Resource: information_system_server.day_19.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[306]  Resource: information_system_server.day_19.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[307]  Resource: information_system_server.day_19.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[308]  Resource: information_system_server.day_19.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[309]  Resource: information_system_server.day_19.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[310]  Resource: information_system_server.day_19.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[311]  Resource: information_system_server.day_19.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[312]  Resource: information_system_server.day_19.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[313]  Resource: information_system_server.day_20.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[314]  Resource: information_system_server.day_20.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[315]  Resource: information_system_server.day_20.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[316]  Resource: information_system_server.day_20.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[317]  Resource: information_system_server.day_20.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[318]  Resource: information_system_server.day_20.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[319]  Resource: information_system_server.day_20.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[320]  Resource: information_system_server.day_20.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[321]  Resource: information_system_server.day_20.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[322]  Resource: information_system_server.day_20.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[323]  Resource: information_system_server.day_20.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[324]  Resource: information_system_server.day_20.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[325]  Resource: information_system_server.day_20.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[326]  Resource: information_system_server.day_20.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[327]  Resource: information_system_server.day_20.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[328]  Resource: information_system_server.day_20.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[329]  Resource: information_system_server.day_21.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[330]  Resource: information_system_server.day_21.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[331]  Resource: information_system_server.day_21.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[332]  Resource: information_system_server.day_21.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[333]  Resource: information_system_server.day_21.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[334]  Resource: information_system_server.day_21.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[335]  Resource: information_system_server.day_21.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[336]  Resource: information_system_server.day_21.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[337]  Resource: information_system_server.day_21.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[338]  Resource: information_system_server.day_21.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[339]  Resource: information_system_server.day_21.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[340]  Resource: information_system_server.day_21.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[341]  Resource: information_system_server.day_21.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[342]  Resource: information_system_server.day_21.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[343]  Resource: information_system_server.day_21.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[344]  Resource: information_system_server.day_21.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[345]  Resource: information_system_server.day_22.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[346]  Resource: information_system_server.day_22.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[347]  Resource: information_system_server.day_22.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[348]  Resource: information_system_server.day_22.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[349]  Resource: information_system_server.day_22.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[350]  Resource: information_system_server.day_22.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[351]  Resource: information_system_server.day_22.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[352]  Resource: information_system_server.day_22.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[353]  Resource: information_system_server.day_22.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[354]  Resource: information_system_server.day_22.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[355]  Resource: information_system_server.day_22.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[356]  Resource: information_system_server.day_22.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[357]  Resource: information_system_server.day_22.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[358]  Resource: information_system_server.day_22.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[359]  Resource: information_system_server.day_22.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[360]  Resource: information_system_server.day_22.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[361]  Resource: information_system_server.day_23.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[362]  Resource: information_system_server.day_23.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[363]  Resource: information_system_server.day_23.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[364]  Resource: information_system_server.day_23.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[365]  Resource: information_system_server.day_23.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[366]  Resource: information_system_server.day_23.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[367]  Resource: information_system_server.day_23.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[368]  Resource: information_system_server.day_23.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[369]  Resource: information_system_server.day_23.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[370]  Resource: information_system_server.day_23.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[371]  Resource: information_system_server.day_23.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[372]  Resource: information_system_server.day_23.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[373]  Resource: information_system_server.day_23.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[374]  Resource: information_system_server.day_23.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[375]  Resource: information_system_server.day_23.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[376]  Resource: information_system_server.day_23.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[377]  Resource: information_system_server.day_24.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[378]  Resource: information_system_server.day_24.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[379]  Resource: information_system_server.day_24.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[380]  Resource: information_system_server.day_24.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[381]  Resource: information_system_server.day_24.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[382]  Resource: information_system_server.day_24.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[383]  Resource: information_system_server.day_24.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[384]  Resource: information_system_server.day_24.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[385]  Resource: information_system_server.day_24.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[386]  Resource: information_system_server.day_24.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[387]  Resource: information_system_server.day_24.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[388]  Resource: information_system_server.day_24.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[389]  Resource: information_system_server.day_24.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[390]  Resource: information_system_server.day_24.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[391]  Resource: information_system_server.day_24.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[392]  Resource: information_system_server.day_24.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[393]  Resource: information_system_server.day_25.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[394]  Resource: information_system_server.day_25.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[395]  Resource: information_system_server.day_25.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[396]  Resource: information_system_server.day_25.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[397]  Resource: information_system_server.day_25.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[398]  Resource: information_system_server.day_25.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[399]  Resource: information_system_server.day_25.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[400]  Resource: information_system_server.day_25.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[401]  Resource: information_system_server.day_25.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[402]  Resource: information_system_server.day_25.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[403]  Resource: information_system_server.day_25.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[404]  Resource: information_system_server.day_25.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[405]  Resource: information_system_server.day_25.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[406]  Resource: information_system_server.day_25.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[407]  Resource: information_system_server.day_25.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[408]  Resource: information_system_server.day_25.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[409]  Resource: information_system_server.day_26.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[410]  Resource: information_system_server.day_26.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[411]  Resource: information_system_server.day_26.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[412]  Resource: information_system_server.day_26.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[413]  Resource: information_system_server.day_26.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[414]  Resource: information_system_server.day_26.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[415]  Resource: information_system_server.day_26.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[416]  Resource: information_system_server.day_26.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[417]  Resource: information_system_server.day_26.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[418]  Resource: information_system_server.day_26.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[419]  Resource: information_system_server.day_26.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[420]  Resource: information_system_server.day_26.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[421]  Resource: information_system_server.day_26.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[422]  Resource: information_system_server.day_26.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[423]  Resource: information_system_server.day_26.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[424]  Resource: information_system_server.day_26.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[425]  Resource: information_system_server.day_27.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[426]  Resource: information_system_server.day_27.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[427]  Resource: information_system_server.day_27.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[428]  Resource: information_system_server.day_27.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[429]  Resource: information_system_server.day_27.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[430]  Resource: information_system_server.day_27.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[431]  Resource: information_system_server.day_27.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[432]  Resource: information_system_server.day_27.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[433]  Resource: information_system_server.day_27.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[434]  Resource: information_system_server.day_27.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[435]  Resource: information_system_server.day_27.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[436]  Resource: information_system_server.day_27.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[437]  Resource: information_system_server.day_27.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[438]  Resource: information_system_server.day_27.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[439]  Resource: information_system_server.day_27.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[440]  Resource: information_system_server.day_27.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[441]  Resource: information_system_server.day_28.scaling_0.instance_0
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[442]  Resource: information_system_server.day_28.scaling_0.instance_1
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[443]  Resource: information_system_server.day_28.scaling_0.instance_2
       - component: instance_time ......................................       14400.00 units USD      22.76
                                                                                             ---------------
         resource cost ...................................................................... USD      22.76

[444]  Resource: information_system_server.day_28.scaling_1.instance_0
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[445]  Resource: information_system_server.day_28.scaling_1.instance_1
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[446]  Resource: information_system_server.day_28.scaling_1.instance_2
       - component: instance_time ......................................       66600.00 units USD     105.28
                                                                                             ---------------
         resource cost ...................................................................... USD     105.28

[447]  Resource: information_system_server.day_28.scaling_2.instance_0
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[448]  Resource: information_system_server.day_28.scaling_2.instance_1
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[449]  Resource: information_system_server.day_28.scaling_2.instance_2
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[450]  Resource: information_system_server.day_28.scaling_2.instance_3
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[451]  Resource: information_system_server.day_28.scaling_2.instance_4
       - component: instance_time ......................................       59400.00 units USD      93.90
                                                                                             ---------------
         resource cost ...................................................................... USD      93.90

[452]  Resource: information_system_server.day_28.scaling_3.instance_0
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[453]  Resource: information_system_server.day_28.scaling_3.instance_1
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[454]  Resource: information_system_server.day_28.scaling_3.instance_2
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[455]  Resource: information_system_server.day_28.scaling_3.instance_3
       - component: instance_time ......................................       48600.00 units USD      76.83
                                                                                             ---------------
         resource cost ...................................................................... USD      76.83

[456]  Resource: information_system_server.day_28.scaling_4.instance_0
       - component: instance_time ......................................       37800.00 units USD      59.76
                                                                                             ---------------
         resource cost ...................................................................... USD      59.76

[457]  Resource: support_application_server
       - component: instance_time ......................................     2419200.00 units USD     338.69
                                                                                             ---------------
         resource cost ...................................................................... USD     338.69

[458]  Resource: support_application_storage
       - component: storage ............................................     2419200.00 units USD      24.96
       - component: iops ...............................................       18412.80 units USD      36.83
                                                                                             ---------------
         resource cost ...................................................................... USD      61.79

                                                                                             ===============
Total cost (for interval: 2023-02-01 00:00:00 to 2023-03-01 00:00:00) ....................... USD   65175.44

Total usage units:
instance_time...........................................................    43394400.00 units
iops....................................................................       18412.80 units
storage.................................................................     2419200.00 units
Warning: This is the sum of usage units for each component across all offers, e.g., also across different VM types. The
unit of one usage unit depends on the component and the adjustment by the cloud provider, e.g., it is GB * seconds for
the component storage and Azure's IOPS units (10,000 IOPS) for the component iops.
Computed costs in 5.32 seconds.
########################################################################################################################
```
