# Bezpieczeństwo
___
## Zagrożenie bezpieczeństwa
### Złośliwe oprogramowanie
- **może**
  - Zmienić konfigurację komputera
  - Usunąć pliki lub uszkodzić dyski twarde
  - Zbierać informacje przechowywane na komputerze bez zgody użytkownika
  - Otworzyć dodatkowe okna na komputerze lub przekierować przeglądarkę
- **Rodzaje**
  - **Adware** - wyświetla niechcące reklamy jako wyskakujące okienka przeglądarki
  - **Spyware** - monitorują aktywność użytkownika i wysyłają informacje do cyberprzestępcy
  - **rootkit** - używane do uzyskania dostępu na poziomie konta administratora, w celu zdalnego sterowania
  - **Ransomware** - szyfruje pliki w miejscu docelowym, a następnie ząda zapłaty za klucz odszyfrujący
  - **Wirus** - polega na rozprzestrzenianiu się i zarażaniu hostów, tworzy kopie siebie
    ![image](https://github.com/user-attachments/assets/6408e82a-5696-43cd-a8ed-b067c8cfb71a)
  - **Worm** - wykorzystuje aplikacje sieciowe do zużywania przepustowości, awarii urządzenia lub innego *Złośliwego oprogramowania*
  - **Koń Trojański** - dostarczane z legalnym oprogramowaniem i jest aktywowany przy instalacji legalnej aplikacji
  - ![image](https://github.com/user-attachments/assets/c97c74c2-a7fa-40db-b09f-6881fab6f32d)
- **Źródła**
  - **Strony** - odwiedzanie zainfekowanych stron
  - **Oprogramowanie** - użytkownik ma przestarzałe oprogramowanie antywirusowe
  - **Pliki** - pobieranie *darmowego* programu
  - **Mail** - otwieranie linków i pobieranie plików z wiadomości e-mail oraz innych komunikatorów
  - **Infekcja** - komputer został zainfekowany przez hosta
  - **Pendrive** - odczytywanie znalezionych pamięci USB
___
### Zapobieganie złośliwemu oprogramowaniu
- **Procedura**
  - Zidentyfikuj i zbadaj objawy złośliwego oprogramowania
  - Ustaw kwarantanna zainfekowanych systemów
  - Wyłącz przywracanie systemu (w systemie Windows)
  - Napraw zainfekowane systemy
  - Zaplanuj skanowanie i uruchamiaj aktualizacje
  - Włącz przywracanie systemu i utwórz punkty przywracania (w systemie Windows)
  - Poinformuj użytkownika końcowego
- **Program antywirusowy**
  - Otwórz program antywirusowy
  - Sprawdź czy jest dostępna aktualizacja (jeśli jest aktualizuj)
  - Przeskanuj komputer
___
### Ataki sieciowe
- **Rodzaje ataków TCP/IP**
  - **Odmowa usługi (Denial of Service, DoS)**
    - przytłacza urządzenie fałszywymi żądaniami, aby stworzyć odmowę usługi dla legalnych użytkowników
    - atakujący może przeciąć lub odłączyć kabel sieciowy do krytycznego urządzenia sieciowego, aby spowodować awarię sieci
    - ataki mogą być spowodowane złośliwym oprogramowaniem
    - **Distributed DoS, DDoS** - rodzaj DoS
      - działa jak DoS, ale używa zainfekowanych hostów (zombie), aby przytłoczyć cel
      - atakujący kontroluje zombie uzywając komputera obsługująceto
      - Botnet - armia zainfekoweanych hostów
      - Botnety są uśpione zanim przewodnik nie wyda polecenia, mogą być również wykorzystywane do ataku SPAM
    - **SYN Flood** - rodzaj DoS
      - wykorzystuje TCP trójdrożny uścisk dłoni
      - atakujący wysyła do celu ciągłe fałszywe żądania SYN
      - cel zostaje przytłoczony i nie jest w stanie ustnaowić prawidłowych żądań SYN, tworząc atak  DoS
  - **Zatruwanie DNS**
    - atakujący akceptuje falszywe rekordy DNS wskazujące na złośliwe serwery, przy użyciu już zainfekowanego hosta
    - serwery służą do przechwytywania poufnych informacji
    - atakujący może pobrać dane z serwera
  - **Man-in-the-Middle, MitM**
    - atakujący przechwytuje komunikację między dwoma hostami
    - atakujący może przechwycić pakiety i przeglądać ich zawartość
    - ataki MitM są tworzone przy ataku zatruwającego tablicę ARP (Address Resolution Protocol)
  - **Fałszowanie, Spoofing**
    - komputer atakują sfałszowane adresy IP
    - atakujący fałszuje adres, aby otrzymać dostęp do zasobów
    - **Atak powtórzeniowy**  - rodzaj Spoofingu, w którym atakujący:
      - przechwytuje uwierzytelniony pakiet
      - zmienia zawartość pakietu i wysyła go do pierwotnego miejsca przeznaczenia
  - **Zero-day** - dzień, w którym nieznana luka została odkryta przez dostawcę, termin ten odnosi się do czasu naprawy luki w zabezpieczeniach przez dostawcę.
  - **Zero-godzina** - moment, w którym odkryto exploit
- **Socjotechnika** - czynność wykorzystywana do uzyskania informacji lub dostępu do systemu poprzez oszukanie ofiary
  - **Przynęta** - polega na zostawianiu zainfekowanych dysków flash z złośliwym oprogramowaniem
  - **Nurkowanie w śmietniku** - polega naprzeszukiwaniu śmietników w celu znalezienia paufnych dokumentów lub starych media
  - **Personifikacja** - atakujący udaje kogoś kim nie jest (np. współpracownik)
  - **Wyłudzenie informacji** - atakujący wysyła fałszywą wiadomość e-mail udającą wiadomość pochodzącą z zaufanego źródła, aby zakłonić ofiare
  - **Pretekst, Pretexting** - atakujący udaje, że potrzebuje danych osobistych lub finansowych
  - **Podglądanie, shoulder surfing** - osoba atakująca niepozornie spogląda kmuś przez ramie, aby ukraść hasło
  - **Coś za coś** - Quid pro Quo, atakujący żąda od ofiary danych w zamian za coś
  - **Spam** - wysyła niechciane wiadomości na pocztę
  - **Phishing profilowy, spear phishing** - atak ukierunkowany na konkretne osoby/organizacje
  - **Śledzenie, piggybacking** - atak mający na celu uzyskania dostępu do zabezpieczonego obszaru
___
## Procedury bezpieczeństwa
### Polityka zabezpieczeń
Zestaw celów bezpieczeństwa zapewniających bezpieczeństwo sieci, danych i komputerów w organizacji
- **Kategorie zasad bezpieczeństwa**
  - **Polityka identyfikacji i uwierzytelniania** - określa upoważnione osoby, które mogą mieć dostęp do zasobów sieciowych i określa procedury weryfikacji
  - **Polityka haseł** - zapewnia spełnianie minimalnych wymagań przez hasła oraz regularne zmiany haseł
  - **Polityka dopuszczalnego użycia** - identyfikuje zasoby i sposoby użycia sieci akceptowane przez organizacje, może wskazywać konsekwencje naruszenia tej zasady
  - **Polityka zdalnego dostępu** - wskazuje jak zdalni użytkownicy mogą uzyskać dostęp do sieci i co jest dostepne przez zdalne połączenie
  - **Zasady konserwacji sieci** - określa SO urządzeń sieciowych i procedury aktualizacji zaplikacji użytkownika końcowego
  - **Zasady obsługi incydentów** - opisuje sposób obsługi incydentów bezpieczeństwa
___
### Zabezpieczenia fizyczne
- **Polegają na zabezpieczeniu:**
  - Dostępu do terenu organizacji
  - Dostępu do obszarów zastrzeżonych
  - Infrastruktury komputerowej i sieciowej
- **Rodzaje**
  - **Zamek konwencjonalny** - odblokowywany przez klucz
  - **Zamek zasuwkowy** odblokowywany kluczem, oddzielony od mechanizmu klamki
  - **Zamek elektroniczny** - odblokowywany PINem lub kodem
  - **Tokeny** - odblokowywany przez przesuwanie bezpiecznej karty lub za pomocą czytnika
  - **Biometryczna** - odblokowywany za pomocą skanera biometrycznego np. skaner siatkówki, odcisku lub głosu
  - **Blokada wieloczynnikowa** - blokadqa wykorzystująca kilka mechanizmów, np. odcisk kciuka oraz kod PIN
___
### Ochrona danych
- **Skutki**
  - Uszkodzenie marki/Utrata reputacji
  - Utrata przewagi konkurencyjnej
  - Znaczne koszty i wysiłki, aby odzyskać dane
  - Działania prawne skutkujące grzywnami i sankcjami
  - Utrata przychodów
  - Utrata klientów
- **Uwagi tworzenia kopii zapasowych**
  - **Częstotliwość**
     - Wykonuj regularnie kopie zapasowe (comiesięczne lub cotygodniowe z częściowymi kopiami zapasowymi)
  - **Bezpieczeństwo**
    - Kopie powinny byc transportowane do zatwierdzonego miejsca przechowywania poza siedzibą
  - **Walidacja**
    - Ochrona kopii za pomocą silnych haseł
    - Wymaganie hasła przy przywróceniu danych
  - **Pamięć masowa**
    - Sprawdzaj poprawność kopii, aby zapewnić integralność danych
- **Uprawnienia do plików i folderów**
![image](https://github.com/user-attachments/assets/f9a8c950-bc75-42d3-830e-1c2eb215162d)
- **Szyfrowanie dysków twardych**
  - **Krok 1**
    - **Włącz moduł TPM**
    ![image](https://github.com/user-attachments/assets/20de52de-31a2-4280-90ab-d8708e4f001c)
  - **Krok 2**
    - **Włącz funkcje BitLocker**
    ![image](https://github.com/user-attachments/assets/826a3cb9-26a1-494e-ad1a-532c41d0c2a5)
___
### Niszczenie danych
- **Z dysku twardego**
![image](https://github.com/user-attachments/assets/d6f4255d-edcf-43cb-b771-fcf794351805)
- **Recykling i niszczenie dysków twardych**
  - **Recykling**
    - **Kroki**
      - Wyczyszczenie dysku
      - Formatowanie dysku
      ![image](https://github.com/user-attachments/assets/d2728bda-0297-4ac1-a20a-843f26561741)
  - **Niszczenie**
    - gwarantuje nie odzyskanie danych z dysku twardego
    - **Sposoby**
      - Niszczarka
      - Uszkodzenie napędu młotkiem
- **Narzędzia**
  - **Różdżka do rozmagnesowania** - emituje zmienne pole magnetyczne, używane do rozmagnesowania przedmiotów
  - **Urządzenie do rozmagnesowania elektromagnetycznego** - wykorzystuje zmienne pole elektromagnetyczne do rozmagnesowania metalowych obiektów
___
### Zabezpieczanie stacji roboczych systemu Windows
- **Zabezpieczanie stacji roboczej**
  - **Komputer i BIOS**
    - **BIOS** - zapobiega uruchomieniu SO i zmianie ustawień BIOS
    - **Logowanie** - zapobiega nieautoryzowanemu dostępowi do komputera
    - **Sieć** - uniemożliwia dostęp do zasobów sieciowych nieupoważnionym
- **SO Windows**
  - **Windows Hello** - funkcja rozpoznywania twarzy lub odcisku palca
  - **PIN**
  - **Dynamiczna blokada** - blokada sięga poza zasięg komputera po sparowaniu urządzenia
  - **Silne hasło**
    - **Minimalna długość** - co najmniej 8 znaków
    - **Złożoność** - musi zawierać litery, cyfry i symbole, unikaj haseł opartych na dostępnych informacjach np. dane osobiste
    - **Różnorodność** - używaj różnych haseł do różnych witryn
    - **Wygaśnięcie** - regularnie zmieniaj hasło
___
### Zasady zabezpieczeń lokalnych systemu Windows
- **Zasady**
  - **W7 i Vista** - *Start> Panel sterowania > Narzędzia administracyjne > Zasady zabezpieczeń lokalnych*
  - **W8, W8.1, W10** - *Wyszukaj > secpol.msc* następnie kliknij *secpol*
  - **Udostępnianie** - do replikacji listy zasad zabezpieczeń należy użyc funkcji *Akcja > Eksportuj listę*
___
### Zarządzanie użytkownikami i grupami
- **Zarządzanie kontami i ich obsługa**
  - **Śledź czasy logowania** - umożliwianie logowania tylko w wybranych porach
  - **Limit czasu bezczynności i blokada ekranu** - skonfiguruj aby wylogowywało użytkownika po danym czasie
  - **Narzędzia konta użytkownika
![image](https://github.com/user-attachments/assets/6f243b71-cabd-4256-8daf-fbba12a163b0)
  - **Menedżer grup** - *Panelu sterowania > Narzędzia administracyjne > Zarządzanie komputerem > Użytkownicy i grupy lokalne*
___
### Zapora systemu Windows
- **Rodzaje**
  - **Zapora oparta na hoście** - korzystanie z oprogramowania takiego jak Windows Defender
  - **Małe biuro domowe (SOHO)** - rozwiązanie sieciowa za pomocą routera bezprzewodowego
  - **Mała i średnia organizacja** - rozwiązanie przy użyciu dedykowanego urządzenia
- **Ustawienia zapory**
  - **Translacja adresów portu (NAT)** – pozwala na przekazywanie publicznego adresu IP routera do prywatnych hostów, umożliwiając im komunikację z Internetem. Ruch powrotny jest tłumaczony na prywatne adresy IP.
  - **Kontrola rodzicielska* – filtrowanie treści internetowych na podstawie niedozwolonych słów kluczowych według oceny stron.
  - **Przekierowanie portów** – nazywane też NATem docelowym (DNAT). Ruch internetowy jest kierowany do określonego hosta i portu na routerze.
  - **Adresy URL białej/czarnej listy** – czarna lista blokuje niebezpieczne witryny, biała pozwala na identyfikację dozwolonych.
  - **Wyłącz porty** – selektywne wyłączanie dostępu do określonych portów TCP/UDP.
  - **Filtrowanie adresów MAC** – pozwala na dodanie znanych adresów MAC do listy i zezwolenie na połączenia tylko z białej listy.
___
### Przeglądarka internetowa
- **Zabezpieczenia**
  - **Tryb prywatny**
  - **Blokada Pop-up** - blkuje wyskakujące okna przeglądarki
  - **Filtr SmartScreen** - wykrywa witryny wyłudzające informacje
  - **Filtrowanie ActiveX** - umożliwia uruchamianie stron bez uruchamiania formatów ActiveX
___
### Utrzymanie bezpieczeństwa
  
