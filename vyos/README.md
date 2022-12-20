
# initial configuration
set system hostname vyos-0
set interface ethernet eth0 address 172.12.105.200/24
set protocols static route 0.0.0.0/0 next-hop 172.21.105.1

set system hostname vyos-1
set interface ethernet eth0 address 172.12.105.201/24
set protocols static route 0.0.0.0/0 next-hop 172.21.105.1

set system hostname vyos-2
set interface ethernet eth0 address 172.12.105.202/24
set protocols static route 0.0.0.0/0 next-hop 172.21.105.1
