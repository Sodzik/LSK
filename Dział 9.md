# Wirtualizacja i przetwarzanie w chmurze
___
## Wirtualizacja
### Chmura
Model przechowywania danych i aplikacji na zdalnych serwerach udostępnianych przez internet np. Google Drive i Microsoft Drive
- **Rodzaje**
  - **Prywatna** - chmura tylko dla określonej organizacji lub osobie
  - **Publiczna** - udostępnianie wszystkim
  - **Hybrydowe** - składa się z minimum dwóch chmur
  - **Społeczniościowa**
- **Wykorzystanie**
  - **Wirtualne przesyłanie strumieniwe aplikacji** - na przykład Microsft Office365 udostępnia programy takie jak Word czy Excel
  - **Poczta e-mail w chmurze** - Office365, Gmail, iCloud Mail, Outlook, Yahoo i Exchange Online
  - **Wirtualny pulpit** - na przykład QNAP
- **Usługi**
  ![image](https://github.com/user-attachments/assets/4e716121-9b04-4050-9dc9-3674dd1bc989)
### Wirtualizacja
Technologia umożliwiająca tworzenie wirtualnych wersji zasobów komputerowych bp. serwery, systemy operacyjne lub pamięć, pozwala na efektywne zarządzanie
### Serwery dedykowane
- **Tradycyjne wdrażanie serwerów** - polega na używaniu dedykowanych serwerów do dostarczania aplikacji i usług, co wymaga dużych zasobów
- **Problemy**:
  - **Zmarnowane zasoby** - Serwery pozostają bezczynne, co prowadzi do marnowania energii.
  - **Pojedynczy punkt awarii** - Awaria jednego serwera uniemożliwia dostęp do usług, ponieważ brak serwerów zapasowych.
  - **Rozrost serwerów** - Fizyczna przestrzeń na serwery staje się niewystarczająca w związku z niewykorzystywanymi jednostkami.
### Wirtualizacja serwerów
- Technologia zmniejszająca liczbę serwerów potrzebnych do świadczenia usług, wykorzystując bezczynne zasoby
  - **Elementy**
    - **Hiperwizor** - Program zarządzający zasobami komputera i maszynami wirtualnymi, zapewniający dostęp do sprzętu fizycznego (procesor, pamięć, kontroler dysków, karta sieciowa)
      - **TYP 1**
        ![image](https://github.com/user-attachments/assets/c4036987-5f13-4787-8c11-8a5addf15bd3)
      - **TYP 2**
        ![image](https://github.com/user-attachments/assets/a5fe3a1a-d938-4ee6-841e-5efedc61cac5)
      - **Windows**
        ![image](https://github.com/user-attachments/assets/d4aa8b7d-36d4-4ba1-880c-c23cf6ea9021)
        ![image](https://github.com/user-attachments/assets/2e33f2c3-5d99-4c1d-a5df-1d087717a136)
        ![image](https://github.com/user-attachments/assets/54a2aa78-1787-44b0-8790-261af0a56d10)
    - **Maszyny wirtualne** - działają w oddzielnych systemach operacyjnych
  - **Korzyści**
    - **Konsolidacja** - na przykład konsolidacja 100 serwerów fizycznych na 10 serwerów wirtualnych
- **Zalety**
  - **Lepsze wykorzystanie zasobów** - zmneijsza ilość serwerów
  - **Mniej zużywanej energii** - obniża koszty zasilania i chłodzenia
  - **Szybsze udostępnianie serwerów** - zdecydowanie szybsze jest stworzenie serwera wirtualnego
  - **Ulepszone odzyskiwanie po awarii** - latwiejsze tworzenie kopii maszyny wirtualnej
  - **Wymagana jest mniejsza ilość miejsca** - serwery wirtualne nie zajmują fizycznego miejsca
  - **Redukcja kosztów** - zużywa mniej energii i potrzeba mniej sprzętu
  - **Maksymalizacja czasu pracy serwera**
  - **Wsparcie dla starszych systemów** - wirutalizacja wydłuża żywotność SO i aplikacji
### Diagram logicznej maszyny wirtualnej
![image](https://github.com/user-attachments/assets/16ccffca-f5bf-41ed-aba4-f41c060d65a9)
