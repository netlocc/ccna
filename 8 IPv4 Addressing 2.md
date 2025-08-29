IPv4 Classes
[[ipv4classes.png]] 
[[ipv4class_sizes_and_number_of_networks.png]]


## Extrapolating Important Stuff from the IPv4 Class Table
#### Maximum Hosts per Network
	is determined by size of Host portions of IPv4 addresses
	
e.g. in a Class C (/24), the host portion is only 8 bits, therefore
	network address--->broadcast address:
		x.x.x.0 /24 -> x.x.x.255 /24
Host Portion Max = 8 bits = 2^8 = 256
Cannot use network address or broadcast address, therefore
	Class C Network Max. Hosts = 254

e.g. in a Class B (/16), the host portion is 16 bits, therefore
	





First usable address
    network address + 1, eg 192.168.1.1  /24
Last usable address
    broadcast address -  1, eg. 192.168.1.254  /24
    
First usable 

Last usable should lead to an interface on the router

show ip interface brief
    OK?:
        (ip address valid?)
        legacy feature, should always say "YES"

    Method:
        (how was the IP address assigned)

    Status:
        (layer 1 status)
        administratively down: interface disabled with 'shutdown' command
        This is the default status of cisco router interface

    Protocol:
        (layer 2 status)


To Configure A Specific Interface:
    conf t
    interface gigabitethernet0/0
            R1(config-if)#
































