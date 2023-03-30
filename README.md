# HA-Cisco-vlan-device-count
Integration to get count of devices per vlan

The end goal of this project is to dynamically be able to pull this table into the sensor, parse out the total MAC addys for each VLAN and create sensors with count of mac as state, would also need to create a total by summing up the totals from each individual vlan.  Assuming doing it that way would be easier than in HA itself.
