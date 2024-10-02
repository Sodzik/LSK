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
    
