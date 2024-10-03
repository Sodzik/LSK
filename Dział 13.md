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
