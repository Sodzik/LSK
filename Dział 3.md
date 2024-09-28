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
___
## Urządzenia ochrony zasilania
- **Listwy przeciprzepięciowe** - ochrania przed przepięciami i skokami napięcia
- **UPS** - chroni przed problemami z zasilaniem przez dostarczanie zasilania
- **SPS** - chroni przed problemami z zasilaniem przez użycie zapasowej baterii dostarczającej zasilanie
___
## Architektura procesora
- **Reduced Instriction Set Computer (RISC)** - zapewnia szybkie wykonywanie operacji dzięki prostemu zestawu instrukcji
- **Complex Instruction Set Computer (CISK)** - dzięki złożonemu zestawowi instrukcji ta architektura pozwala na wykonywanie wielu operacji w jednej instrukcji
___
## Moc i rdzenie procesora
- **Przetaktowanie (overclocking)** - zwiększenie wydajności zegara procesora powyżej jego fabryczne ustawienia
![image](https://github.com/user-attachments/assets/85458bae-10c1-4dbe-8272-7331dfb8adc6)
___
## Chłodzenie procesora
- **Wentylator obudowy** - wentylator dołączony do obudowy już przy jej zakupie
- **Radiator (pasywny)** - montowany na procesor, służy do rozprowadzania ciepła generowanego przez CPU za pomocą swoich metalowych żeber
- **Wentylator CPU (aktywny)** - montowany na radiator, służy do przemieszczania ciepłego powietrza z dala od żeber radiatora
- **Chłodzenie GPU** - w każdą karte graficzną sa już wmontowany przynajmniej jeden wentylator
- **Wodne** - montowana jest na procesorze płytka metalowa przez którą jest pompowana woda która odprowadza ciepło
___
## RAID
![image](https://github.com/user-attachments/assets/f2b8d3ce-d540-4f6d-ac80-b33d145620c6)
___
## Starsze porty
- **Szeregowy** - używane do łączenia urządzeń peryferyjnych np. drukarki albo skanery. Ma 9 lub 25 styków
- **Równoległy** - wysyła informacje wiele bitów jednocześnie, ponieważ były stosowane do drukarek
- **Port gier** - 15-pinowy port do wejścia joysticka
- **PS/2** - dwa 6-pinowe porty służące do podłączenia myszy (zielony) oraz klawiatury (fioletowy)
- **Porty audio** - porty zawierające wejście liniowe (line in) dla np. systemu stereo oraz wyjście liniowe (line out) dla np. głośników i słuchawek
- 
