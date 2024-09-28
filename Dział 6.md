# Dział 6
___
## MAC i IP i inne adresy
- **IP** - identyfikuje urządzenie w sieci
- **Maska podsieci** - używana do identyfikacji sieci, w której urządzenie się znajduje
- **Brama domyślna** - identyfikuje router z którego korzysta urządzenie, aby uzyskać dostęp do Internetu
- **Opcjonalne wartości** - preferowany adres DNS oraz alternatywny adres DNS  <br></br>
![image](https://github.com/user-attachments/assets/349579a0-328e-414f-abe6-0d8bfc80fb81)
![image](https://github.com/user-attachments/assets/348de10a-8c20-4350-be33-500e8c64c175)
![image](https://github.com/user-attachments/assets/07350254-56bf-49aa-b905-78b88647f593)
![image](https://github.com/user-attachments/assets/5f84661f-1862-495d-950a-13f57e4496eb)
___
## Skrót IPv6
2001:0db8:0000:1111:0000:0000:0000:0200 <br></br>
2001:0db8:0:1111:0:0:0:200 <br></br>
2001:0db8::1111::200
___
## Projekt sieci
- **Komponent sieci** - zawiera karty sieciowe i bezprzewodowe i urządzenia sieciowe np. przełączniki, bezprzewodowe punkty dostępu, routery, urządzenia wielofunkcyjne itp.
- **Projekt sieci** - Wymaga znajomości sposobu, w jaki sieci są ze sobą połączone, aby wspierać potrzeby firmy
- ___
- ## Podstawowa konfiguracja routera
- **Krok 1** - Zaloguje się do router używając adresu, loginu oraz hasła z routera
- **Krok 2** - Zmień domyślne hasło
- **Krok 3** - Zaloguj się za pomocą nowego hasła
- **Krok 4** -  Zmień adresy DHCP IPv4
- **Krok 5** - Odnów adres IP używając komendy **ipconfig /renew**
- **Krok 6** - Zaloguj się na nowy adres IP
  ___
## Podstawowe ustawienia bezprzewodowe
- **Krok 1** - Wyświetl ustawienia domyślne siecio WLAN
- **Krok 2** - Zmień tryb sieci
- **Krok 3** - Skonfiguruj SSID (nazwę sieci)
- **Krok 4** - Skonfiguruj kanał
- **Krok 5** - Skonfiguruj tryb bezpieczeństwa
- **Krok 6** - Skonfiguruj hasło do sieci
  ___
  ## Ustawienia QoS
  Ustawia poziom priorytetu jakości audio i wideo dla danych Zasad <br></br>
  np. <br></br>
  ![image](https://github.com/user-attachments/assets/250b0884-c32d-4055-b5fd-f4d908723934)
  ![image](https://github.com/user-attachments/assets/f55051d6-babe-47cd-b6d0-11005eef46d4)
___
## Ustawienia zapory
- **UPnP (Universal Plug and Play)** to protokół służący do umożliwiania urządzeniom dynamiczne dodawanie się do sieci bez interwencji użytkownika lub konfiguracji
- **DMZ (Strefa zdemilitaryzowana)** - sieć świadcząca usługi dla niezaufanej sieci, w tej strefie często są umieszczone serwery WWWW, e-mail, FTP
- **Przekierowanie portów** - zapory sprzętowe mogą służyć do blokowania portów TCP i UDP
- **Filtrowanie adresów MAC** - określa dokładnie które adresy MAC mają pozwolenie na wysyłanie danych w Twojej sieci lub nie mogą wysyłać
- **Biała i czarna lista** - decyduje jakie adresy IP są dozwolone lub odmawiane w sieci
