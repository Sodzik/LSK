# Instalacja systemu Windows
___
## Nowoczesne SO
### SO
- *Jest to Interfejs między użytkownikiem a sprzętem zarządzającym*:
  - **Zasobami oprogramowania**
  - **Alokacją pamięci**
  - **Usługami dla aplikacji**
- *Kluczowe terminy*:
- **Wielozadniowość** - umożliwia wielu użytkownikom jednoczesne korzystanie z kont
- **Wieloprocesorowość** - obsługuje wiele aplikacji procesorów
- **Wielowątkowość** - dzieli programy na mniejsze części do równoczesnego uruchamiania
### Funkcje
- **Dostęp do sprzętu**
- **Zarządzanie plikami i folderami**
- **Interfejs użytkownika**
  - **Interfejs wiersza poleceń (CLI)** - użytkownik wpisuje komendę w wierszu poleceń
  - **Graficzny interfejs użytkownika (GUI)** - użytkownik korzysta z menu i ikon
- **Zarządzanie aplikacjami**
### Wymagania systemowe Windowsa
![image](https://github.com/user-attachments/assets/ba7a4762-2642-4479-a2ca-80f6090f2f64)
### Architektura proesorów 32/64 bitowych
![image](https://github.com/user-attachments/assets/60aa293c-a7ee-4465-a449-7901f684adfc)
### Aktualizacje
- **Asystent aktualizacji** - narzędzie instalowane na komputerze z systemem Windows
- **Narzędzia migracji stanu użytkownika** - narzędzie wiersza poleceń przeznaczone do przechwytywania kont użytkowników, plików, ustawień SO i aplikacji oraz migrowania ich do nowej instalacji systemu Windows
- **Łatwy transfer systemu Windows** - narzędzie do migrowania ustawień i plików z systemu 7 i 8 do systemu 8.1
- **PCmover Express - narzędzie do przesyłania plików, folderów, profili i apliakcji ze starego komputera na nowy z systemem Windows 10
___
## Zarządzanie dyskami
### Partycjonowanie
- **MBR** - Master Boot Record
- **GPT** - GUID Particion Table
![image](https://github.com/user-attachments/assets/6432987f-9343-4149-b479-0b86b88dd983)
### Partycje
- **Podstawowa** - zawiera pliki SO i zwykle jest pierwszą partycją
- **Aktywna** - przechowuje i uruchamia SO, znajduje się na dysku MBR
- **Rozszerzona** - jest to partycja *Podstawowa* wyznaczona na rozszerzoną
### Dyski
- **Logiczny** - sekcja partycji rozszerzonej, może służyć do oddzielania informacji w celach administracyjnych
- **Podstawowy** - zawiera partycje (podstawowe i rozszerzone oraz dyski *Logiczne*
- **Dynamiczny** - zapewniają nieobsługiwane funkcje przez dyski *Podstawowwe*
- **Formatowanie** - proces tworzy system plików na partycji do przechowywania plików
___
## Inne terminy
- **Zaawansowane opcje uruchamiania** - zestaw narzędzi pozwalający użytkownikom rozwiązywanie problemów, odzyskiwanie lub przywracanie SO, gdy nie można go uruchomić
- **PXE** - środowisko używane do uruchamiania komputera, łączenia się z siecią i komunikacji z serwerem w celu rozpoczęcia instalacji SO
- **Partycja odzyskiwania** - zawiera obraz, którego można użyć do przywróceni komputera do jego oryginalnej konfuguracji
- **Sysprep** - program używany do przygotowania SO z różnymi konfiguracjami sprzętu zainstalowania i skonfigurowania tego samego SO na wielu komputerach
- **Odśwież komputer** - przywraca oprogramowanie systemowe komputera do stanu fabrycznego bez usuwania danych
- **Obraz** - plik zawierający wszystkie dane z partycji
- **RIS** - pakiet oprogramowania używany do komunikacji z klientem i zapewniający klientowi niezbędne instrukcje dotycząse pobierania plików instalacyjnych SO i rozpoczęcia instalacji
