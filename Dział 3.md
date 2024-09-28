# Dział 3
___
## POST
![image](https://github.com/user-attachments/assets/7e390b54-f5ec-4b79-9963-ffbce8bcfb94)
___
## BIOS, wykrywa:
- **dostępne urządzenia**
- **które napędy pozwalają na uruchomienie systemu**
- **jak skonfigurowana jest pamięć i kiedy może być użyta**
- **jak skonfigurować gniazda PCI i PCIe**
- **jak skonfigurowac porty SATA i USB**
- **właściwości płyty głownej dotyczące zarządzania energią**
- **CMOS** - BIOS zapisuje swoje ustawienia w pamięci CMOS
___
## UEFI
- **Zastępca** - działa tak samo jak tradycyjny BIOS, ale posiada dodatkowe funkcje takie jak obsługa interfejsu myszką zamiast ekranów BIOS
- **Obsługa** - obsługuje większe dyski i systemy 32/64-bitowe
___
## Dostęp i ochrona BIOS/UEFI
- **Pełny dostęp** - dostęp do wszystkich zakładek i ustawień z wyjątkiem ustawień hasła administratora
- **Ograniczony dostęp** - zmiany można dokonywac tylko do pewnych ustawień
- **Tylko podgląd** - można przeglądac wszytkie zakładki, ale nie można ich zmieniać
- **Brak dostępu** - nie ma dostępu do podglądu i konfiguracji BIOSu
- **LoJack** - funkcja składająca się z 2 programów modułu Persistance i agenta aplikacji. Zgłasza informacje o urządzeniu i lokalizację do centrum monitorowania
- **Trusted Platform Module (TPM)** - przechowuje klucze szyfrujące, certyfikatów danych, haseł i danych
- **Secure boot** - umożliwia bezpieczne uruchamianie systemu
___
## Moc i napięcie
- **Napięcie (U)** - mierzy się w woltach (V)
- **Rezystancja (R)** - mierzy się w omach (Om)
- **Natężenie prądu (I)** - mierzy się w amperach (A)
- **Moc (P)** - mierzy się w watach (W), zasilacze się klasyfikuje w nich
___
## Wahania
- **Zanik** - całkowita utrata zasilania AC
- **Spadek napięcia** - obniżony poziom napięcia zasilania AC
- **Szum** - zakłócenia pochodzące od generatorów i wyładowań atmosferycznych
- **Przepięcie** - nagły wzrost napięcia
- **Skok mocy** - gwałtowny wzrost napięcia
