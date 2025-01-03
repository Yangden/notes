# overview
* layer2 switching and layer3 routing
# layer 3 routing
* SVI

# steps
## layer2
1. configuration mode : vlan  ID    
2. naming
3. configure ports </br>
```
// access port
interface INTERFACE
switch mode access
switchport access vlan-id
```
## layer 3
1. enter interface : interface vlan-ID
2. ip address
3. no shutdown : explanation of this command - set up the interface preventing default down 