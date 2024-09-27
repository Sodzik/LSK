# Dział 5

## Rodzaje sieci

- sieć ***PAN*** (Personal Area Network),
- sieć ***LAN*** (Local Area Network)
- sieć ***WLAN*** (Wireless Local Area Network)
- sieć ***WMN*** (Wireless Mesh Network)
- sieć ***MAN*** (Metropolitan Area Network)
- sieć ***WAN*** (Wide Area Network)
- sieć ***VPN*** (Virual Private Network)
- sieć ***VLAN*** (Virtual Local Area Network)
___
## Urządzenia pośrednicze

- ***Przełącznik*** - łączy wiele urządzeń z siecią
- ***Router*** - przekazuje ruch między sieciami
- ***Router bezprzewodowy***- łączy wiele urządzeń bezprzewodowych z siecią i może zawierać przełącznik do łączenia przewodowych hostów
- ***Punkt dostępu (AP)*** - łączy się z routerem bezprzewodowym i służy do rozszerzenia zasięgu sieci bezprzewodowej
- ***Modem*** - łączy dom lub małe biuro z Internetem
___
## Połączenia szerokopasmowe

- ***Odbiornik satelitarny*** - Dekoduje odbierany program nadawany przez stację telewizyjną
- ***Modem DSL*** - Łączy internet za pomocą modemu i miedzinej linii telefonicznej
- ***Modem kablowy*** - Łączy się z internetem używając kabla lub światłowodu
- ***Światłowód*** - Wykorzystuje światło do przesyłania internetu itp do domu lub firmy.
- ***Tethering*** - Łączenie urządzenia z telefonem, aby podłączyć urządznie do internetu
- ***Mobilny hotspot*** - Umożliwia łączenie się z innymi urzadzniami przez Wi-Fi
___
## Protokoły Wartwy transportowej
- ***TCP*** - Korzysta z aplikacji **FTP, HTTP (www), SMTP (e-mail) oraz DNS**. Niezawodny, potwierdza dane, wysyła ponownie stracone dane, dostarcza dane po kolei
- ***UDP*** - Korzysta z aplikacji **DNS oraz TFTP**. Szybki, mały narzut, nie wysyła potwierdzenia, dostarcza dane w kolejności w jakiej je otrzymuje
___
## Porty apliakcji
- **20** -         TCP        FTP (dane)
- **21** -         TCP        FTP (sterowanie)
- **22** -         TCP        SSH
- **23** -         TCP        Telnet
- **25** -         TCP        SMTP
- **53** -         TCP/UDP    DNS
- **67** -         UDP        DHCP (serwer)
- **68** -         UDP        DHCP (klient)
- **69** -         UDP   ___     TFTP
- **80** -         TCP     ---   HTTP (www)
- **110** -        TCP    __    POP3
- **137-139** -    TCP/UDP    NetBIOS/NetBT
- **143** -        TCP        IMAP
- **161/162** -    UDP        SNMP
- **389** -        TCP/UDP    LDAP
- **427** -        TCP/UDP    SLP
- **443** -        TCP        HTTPS
- **445** -        TCP        SMB/CIFS
- **548** -        TCP        AFP
- **3389** -       TCP/UDP    RDP
___
## Standardy 802.11
- **802.11a**       54Mb/s    35m     5GHz
- **802.11b**       11Mb/s    35m     2.4GHz
- **802.11g**       54MB/s    38m     2.4GHz      802.11b
- **802.11n**       600Mb/s   70m     2.4/5GHz    802.11a/b/g
- **802.11ac**      1.4Gb/s   35m     5GHz        802.11a/n
___
## Inne technologie
- **Bluetooth** - technologia stosowana w PAN do podłączania urządzeń takich jak głośnik, słuchawki lub mikrofon
- **NFC** - zaprojektowany do zblizeniowego realizowania tranzakcji
- **Zigbee** - Charakteryzuje się niskim poborem energii oraz zasięgiem aż do 100m. Wykorzystuje się też w kontroli inteligentnego domu.
- **Z-Wave** - Wykorzystuje się do kontrolowania SMART HOME
___
## Urządzenia sieciowe
- **Wtórnik** (repeater) - regeneruje słaby sygnał wysyłany do niego
- **Koncentrator** (hub) - służy do komunikacji pomiędzy sprzętem np. komputer, serwer, drukarka itp.
- **Most** - dzieli sieć LAN na segmenty i filtruje pomiędzy nimi komunikację
- **Przełącznik** - komunikuje sprzęt ze sobą za pomoca adresów MAC
- **Router** - zbiera sygnał internetowy i łączy się z urządzeniami takimi jak komputer lub przełącznikami
___
## Zabezpieczenia
- **Zapora wewnętrzna**
- **IDS** - system do wykrywania włamań, który monitoruje ruch w sieci
- **IPS** - działa jak IDS, ale każdy ruch musi przejść przez niego
- **UTM** - posiada wszystkie funkcje IDS i IPS
- **Serwer zarządzania punktami końcowymi** - odpowiada za monitorowanie wszystkich urządzeń końcowych w sieci
___
## Inne urządzenia sieciowe
- **Panel krosowy** - stosowany jako miejsce zbierania kabli
- **PoE oraz EoP** - metody wykorzystywania zasilania do połączenia z internetem oraz na odwrót
- **Chmurowy kontroler sieci** - umożliwia administratorom sieci na zarządzanie urządzeniami sieciowymi
___
## Narzędzia
- **Kleszcze do przecinania kabli**
- **Szczypce do zdejmowania izolacji**
- **Zaciskarka**
- **Wciskarka**
- **Multimetr** - mierzy napięcie, prąd elektyczny itp.
- **Tester**
- **Pętla zwrotna** - testuje podstawową funkcjonalność portów komputera
- **Generator tonów i sonda** - testuje drut w kablu za pomocą tonów
- **Analizator Wi-Fi** - służy do audytu i naprawiania awarii w sieci bezprzewodowej
___
## Kable
- **Koncentracyjne** - jest z miedzi lub z aluminium. Używany przez stacje telewizyjne i systemy łączności satelitarnej. Ma typ BNC, typ N oraz typ F
- **Ethernet** (RJ45) -
  - T568A - Zielono-biały        Zielony        Pomarańczowo-biały      Niebieski      Niebiesko-biały      Pomarańczowy      Brązowo-biały        Brązowy
  - T568B - Pomarańczowo-biały   Pomarańczowy   Zielono-biały           Niebieski      Niebiesko-biały      Zielony           Brązowo-biały        Brązowy
- **Światłowód** - składa się ze szkła i wykorzystuję się do łączenia z internetem i przesyłania wiadomości
