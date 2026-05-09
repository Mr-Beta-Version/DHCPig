# DHCPig
DHCP exhaustion

find connected inetface
```
sudo ip link
```

Select UP

download requirements
```
sudo pip install scapy
```

check working or not
```
from scapy.all import *
print(get_if_list())
```
should return a list of interface



run tools
```
sudo python3 pig.py <interface>
```
e.g. sudo python3 pig.py eth0
