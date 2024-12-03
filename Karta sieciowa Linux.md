# Konfiguracja karty sieciowej w Linuxie
___
## Edycja pliku konfiguracyjnego interfejsu
**sudo nano /etc/network/interfaces** - do tego pliku wpisujemy poniższy tekst:<br>
  *plaintext <br>
  auto eth0 <br>
  iface eth0 inet static <br>
  address 192.168.X.XXX <br>
  netmask 255.255.255.0 <br>
  gateway 192.168.X.X* <br>
**sudo ip link set <nazwa karty> down** oraz **sudo ip link set (nowa nazwa karty> up** - wyłącza oraz włącza kartę sieciową
lub
**sudo systemctl restart networking**
## Komendy
**ip link show** - pokazuje dostępnie interfejsy sieciowe w systemie <br>
**sudo dhclient enp0s3** - włącza DHCP dla interfejsu <br>
**ip addr show** lub **ip a** - sprawdza konfigurację interfejsów <br>
**ping -c 4 192.168.2.1** - sprawdź połączenie z routerem (nie wiem po co **-c 4**) <br>
**sudo ip addr add 192.168.X.X/24 dev enp0s3** - ustaje adres IP karty sieciowej enp0s3 na 192.168.X.X o masce 255.255.255.0 <br>
**sudo ip route add default via 192.168.2.1 dev enp0s3** - dodaje bramę domyślną do karty sieciowej enp0s3 <br>
**nslookup google.com** - sprawdza połączenie DNS <br>
**ip route show** - pokazuje trasę routingu <br>
