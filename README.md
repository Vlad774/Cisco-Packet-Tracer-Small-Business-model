<h1>Cisco Packet Tracer: Small Business model</h1>

 

<h2>Description</h2>

<br />
<b>Creating Small Business Network</b>
<br />
ABC company is a fast-growing company in Canada with more than 3 million customers globally.
The company deals with selling and buying of food items, which are basically operated drom the headquaters.
The companyis intending to open a branch near the local town Kelowna. Thus, the company requires young IT graduates to design the network for the branch.
The network is intended to operate separetly from the HQ network. 


 -- <b>  Being a small network, the company has the following requirments during implementation:

 - <b>One router and one switch to be used (all CISCO products).</b>
 - <b>Three departments (Admin/IT, Finance/HR and Customer service/Reception).</b>
 - <b>Each departmnet is requered to be in defferent VLANS.</b>
 - <b>Each departament is required to have wireless network for the users.</b>
 - <b>Host devices in the network are requared to obtain IPv4 address automatically.</b>
 - <b>Devices in all the departments are required to communicate with each other. </b>

Assume the ISP gave out a base network of 192.168.1.0, you as the young network engineer who has been hired, design and implement a network considiring the above requirements.  


<h2>Languages and Utilities Used</h2>

- <b>Cisco Packet Tracer</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> 


<h2>Walk-through:</h2>

<p align="center">
Small Business Network Setup: <br/>
<img src="https://github.com/Vlad774/Cisco-Packet-Tracer-Small-Business-model/blob/main/SMALL_BUSINESS_NETWORK_SETUP.jpg"/>
<br />
<br />
Switch:VLAN:  <br/>
<img src="https://github.com/Vlad774/Cisco-Packet-Tracer-Small-Business-model/blob/main/Switch_creating_VLAN_all_departments.jpg"/>
<br />
<br />
Creating Access points for All Departments: <br/>
<img src="https://github.com/Vlad774/Cisco-Packet-Tracer-Small-Business-model/blob/main/Creating%20acces%20point%20for%20all%20departments.jpg"/>
<br />
<br />
Router: Setting up IP for each subnet:  <br/>
<img src="https://github.com/Vlad774/Cisco-Packet-Tracer-Small-Business-model/blob/main/Router%20setting%20up%20IP%20for%20each%20subnet.jpg"/>
<br />
Router: Creating DHCP Pools for All DP  <br/>
<img src="https://github.com/Vlad774/Cisco-Packet-Tracer-Small-Business-model/blob/main/Router_Creating_DHCP_pools_for_ALL_DP.jpg"/>
<br />
<br />
Test device Communications  <br/>
<img src="https://github.com/Vlad774/Cisco-Packet-Tracer-Small-Business-model/blob/main/Device%20communication.jpg"/>
<br />


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
