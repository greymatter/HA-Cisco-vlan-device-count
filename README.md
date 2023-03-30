# HA-Cisco-vlan-device-count
Integration to get count of devices per vlan

Starting to put this together for personal testing as I would love an easy way of getting a fairly accurate count of physical devices on the various vlans of my network.  I already am able to get an accurate count of my wireless devices via SNMP from the WLC, however at least on cisco ios 12.2 I have not been able to find a way via SNMP to gather the same info as provided from running ```show mac address-table count``` directly on the console of the switch.  So the I am trying to leverage the original cisco_ios device tracker code to make this a reality or at least attempt to.



The end goal of this project is to dynamically be able to pull this table into the sensor, parse out the total MAC addys for each VLAN and create sensors with count of mac as state, would also need to create a total by summing up the totals from each individual vlan.  Assuming doing it that way would be easier than in HA itself.
