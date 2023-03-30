## sample output from my cisco 3750 ##
```

sw01-c3750>show mac address-table count

Mac Entries for Vlan 1:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 3:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 5:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 10:
---------------------------
Dynamic Address Count  : 8
Static  Address Count  : 0
Total Mac Addresses    : 8

Mac Entries for Vlan 15:
---------------------------
Dynamic Address Count  : 43
Static  Address Count  : 0
Total Mac Addresses    : 43

Mac Entries for Vlan 20:
---------------------------
Dynamic Address Count  : 2
Static  Address Count  : 0
Total Mac Addresses    : 2

Mac Entries for Vlan 25:
---------------------------
Dynamic Address Count  : 8
Static  Address Count  : 0
Total Mac Addresses    : 8

Mac Entries for Vlan 30:
---------------------------
Dynamic Address Count  : 6
Static  Address Count  : 0
Total Mac Addresses    : 6

Mac Entries for Vlan 35:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 40:
---------------------------
Dynamic Address Count  : 1
Static  Address Count  : 0
Total Mac Addresses    : 1

Mac Entries for Vlan 45:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 50:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 60:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 70:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Mac Entries for Vlan 80:
---------------------------
Dynamic Address Count  : 0
Static  Address Count  : 0
Total Mac Addresses    : 0

Total Mac Address Space Available: 5912

```
The end goal of this project is to dynamically be able to pull this table into the sensor, parse out the total MAC addys for each VLAN and create sensors with count of mac as state, would also need to create a total by summing up the totals from each individual vlan.  Assuming doing it that way would be easier than in HA itself.
