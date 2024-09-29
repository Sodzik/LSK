# Konfiguracja systemu Windows
___
## Menedżer zadań systemu Windows 10
- **Procesy** - zakładka pokazująca listę procesów aktualnie działających na komputerze
- **Wydajność** - zakładka zawierająca dynamiczne wykresy wydajności systemu
- **Historia aplikacji** - wyświetla wykorzystanie zasobów historycznych np. czas procesora albo wykorzystanie danych sieciowych
- **Uruchamianie** - pokazuje jakie procesy są automatycznie uruchamiane podczas uruchamiania systemu Windows
- **Użytkownicy** - wyświetla użytkowników, którzy mają aktualne połaczenie z komputer i zasobami systemowymi
- **Szczegóły** - dzięki niej mkożna dostosować poziom priorytetu dla danego procesu
- **Usługi** - ta karta wyświetla wszystkie dostępne usługi i ich stan, pozwana na ich łatwe zatrzymanie, uruchamianie oraz restertowanie
___
## Pliki
### Rozszerzenia
- **pliki tekstowe**: TXT, DOC, DOCX, PDF, HTML
- **pliki graficzne**: JPEG, BMP, GIF, PNG
- **pliki muzyczne**: MP3
- **pliki filmowe**: MP4, MPEG.
- **pliki zarchiwizowane/skompresowane**: RAR, ZIP
### Atrybuty
- **R** - plik jest tylko do odczytu (Read-only)
- **A** - plik będzie archiwizowany podczas tworzenia kopii zapasowej danych (Archive)
- **S** - oznaczenie dla plików systemowych (System)
- **H** - plik ukryty w oknie katalogu (Hidden)
___
## Panel sterowania
- **System i bezpieczeństwo**
- **Sieć i internet**
- **Sprzęt i dźwięk**
- **Programy**
- **Konta użytkownika**
- **Ułatwienia dostępu**
- **Zegar i region**
- **Wygląd i personalizacja**
___
## Panel sterowania kont i użytkowników
- **Kontrola konta użytkownika (UAC)** - monitoruje programy na komputerze i ostrzega użytkowmników, gdy działanie może stanowić zagrożenie dla komputera
- **Menedżer poświadczeń** - pomaga zarządzać hasłami używanymi do witryn internetowych i aplikacji Windows
- **Centrum synchronizacji** - umożliwia edytowanie plików z wielu urządzeń z systemem Windows
___
## Rejestr systemu Windows
![image](https://github.com/user-attachments/assets/dde825bf-ba71-440a-b32c-a83b014d44ae)
___
## Narzędzia systemowe
- **DCDiag** - narzędzie diagnostyczne DirectX
- **Microsoft Management Console (MMC)** - aplikacja umożliwiająca tworzenie konsol zarządzających dla kolekcji narzędzi i narzędzi firmy Microsoft
- **Regedit** - edytor rejestru pozwala administratorowi przeglądać i wprowadzać zmiany w rejestrze systemu Windows
- **Konfiguracja systemu** - narzędzie służące do identyfikowania problemów, które uniemożliwiają poprawne uruchomienie systemu
___
## Wiersz poleceń
- **chkdsk** - sprawdza dysk pod kątem błędów. /f - naprawia błędy (odzyskuje), /r - naprawia błędy fizyczne
- **format** - tworzy nowy system plików. /q - szybki format, /v - podaj nazwę woluminu, /fs - określ system plików
- **diskpart** - uruchamia oddzielny interpreter poleceń z poleceniami. *create* -tworzy partycje, *extend* - zwiększa rozmiar woluminu/partycji, *shrink* - zmniejsza rozmiar partycji
- **tasklist** - wyświetla listę procesów
- **taskkill** - zabija działającego procesu
- **dism** - służy do pracy z obrazami systemowymi przed ich wdrożeniem
- **sfc** - sprawdza i naprawia pliki systemu Windows
- **shutdown** - wyłącz komputer lokalny lub zdalny
- **gpupdate** - Group Policy Update. /target:computer - wymusza aktualizacje *computera*, /force - wymuś aktualizacje, /boot - uruchamia ponownie komputer po aktualizacji
- **gpresuit** - wyświetla informacje o wynikowym zestawie zasad grupy. /s - system do podglądu wyniku, nazwy lub adresu IP, /r - wyświetla dane podsumowujące
- **net use** - wyświetla i łączy się z zasobami sieciowymi
- **net user**
- **ping** - testuje połączenie
- **tracert** - polecenie śledzi trasę, którą pokonują pakiety z komputera do hosta docelowego
- **nslookup** - testuje serwery DNS
- **ipconfig**
![image](https://github.com/user-attachments/assets/e40b5bdb-d0f9-447c-ab9b-83599483a43e)
___
## Sieci systemu Windows
### telnet lub SSH
- **Telnet** - protokjół i program emulacji CLI
- **Secure Shell (SSH)** - bezpieczna alternatywa dla Telnet
___
## Proces rozwiązywania problemów
![image](https://github.com/user-attachments/assets/8c35692a-e4b1-4365-8173-ba5b94e501ed)
![image](https://github.com/user-attachments/assets/f60ee9a1-2627-4ca2-824d-5b72c21c77f2)
![image](https://github.com/user-attachments/assets/5fda497f-422c-4558-a155-dc26b30823d2)
![image](https://github.com/user-attachments/assets/e2b5bb47-b931-4c5e-858b-e6bacac71545)
![image](https://github.com/user-attachments/assets/3e2a9f8d-de8c-4367-b453-4b82e201088b)
![image](https://github.com/user-attachments/assets/c8be51da-b7fe-4394-b595-b2ad49b18c12)
___
## Problemy
![image](https://github.com/user-attachments/assets/7f7e1f90-5bc3-4345-b84f-27313148de3f)
![image](https://github.com/user-attachments/assets/659c860a-8f57-4901-b214-8620ca6b2de9)
![image](https://github.com/user-attachments/assets/55d550ef-0ea8-4b3e-babc-3cf8b62c7178)
![image](https://github.com/user-attachments/assets/0b94e5a6-4477-4aef-bc2b-99f2ced80aaf)
![image](https://github.com/user-attachments/assets/e4bf4200-5868-402a-a4cf-d613cafd39e7)
![image](https://github.com/user-attachments/assets/5d3992d0-96b0-496d-9615-1d016e03414b)
![image](https://github.com/user-attachments/assets/f4649139-6f78-406a-9d49-b6316527a5b5)
![image](https://github.com/user-attachments/assets/49bfc3b9-7e40-4d1c-8f28-dc2de78c15c9)
![image](https://github.com/user-attachments/assets/72b5e586-2cdd-4136-8bd5-a0243dbd8b37)
