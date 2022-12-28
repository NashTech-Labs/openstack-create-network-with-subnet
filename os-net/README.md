# OpenStack network
A network is an isolated Layer 2 networking segment. There are two types of networks, project and provider networks. 
Project networks are fully isolated and are not shared with other projects. 
Provider networks map to existing networks in the data center and provide external network access for servers. 

Creating custom network in openstack with subnet.
* providing subnet range.
* add subnet to the network name.
* show all the available network.
* And shaow the create network.

# Execute:
change permission:
* chmod +x demo-network
Run:
* ./demo-network

# delete network:
microstack.openstack network delete net-id or name

# Network list:
microstack.openstack network list
