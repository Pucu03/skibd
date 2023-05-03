# Ćwiczenie nr 2

## 1
* Korzytsamy z komendy `ipconfig` na komputerze lokalnym
![image](https://user-images.githubusercontent.com/92114245/235941069-23d98e70-c81d-41d2-b687-763adcb979ab.png)
* Następnie korzytsamy z komendy `ip address` dla komputera sieciowego
![image](https://user-images.githubusercontent.com/92114245/235942208-be0919e7-d5a6-4fff-8b9d-6575fe7757a7.png)

## 2
* Adres fizyczny - adres pamięci pojawiający się w postaci liczby binarnej na szynie adresowej procesora w momencie odwoływania się do pamięci operacyjnej lub przestrzeni adresowej urządzeń wejścia-wyjścia.
* Serwer DHCP - (Dynamic Host Configuration Protocol) to protokół zarządzania siecią wymagany w sieciach IP. DHCP Server dynamicznie przypisuje adres IP i inne parametry konfiguracji sieci każdemu urządzeniu w tej samej sieci, a wszystkie urządzenia w tej sieci komunikują się ze sobą z adresami IP z serwera.
* Adres IP - skrót od angielskiego terminu Internet Protocol address, który oznacza „adres protokołu internetowego”. Jest to unikalny numer nadawany wszystkim urządzeniom elektronicznym podłączonym do sieci komputerowej.
* Maska podsieci -  liczba służąca do wyodrębnienia w adresie IP części będącej adresem podsieci i części, która jest adresem hosta w tej podsieci.
* Brama domyślna - maszyna podłączona do sieci komputerowej, za pośrednictwem której komputery z sieci lokalnej komunikują się z komputerami w innych sieciach.
* Serwer DNS - usługa zapewniająca powiązanie domeny z adresem IP danego serwera. Pozwala on internaucie na dostęp do danej strony internetowej bez konieczności znania jej dokładnego adresu IP

## 3
* Komenda `netstat` wyświetla w postaci symbolicznej zawartość różnego rodzaju struktur danych sieciowych dotyczących aktywnych połączeń.

* Dla komputera lokalnego
![image](https://user-images.githubusercontent.com/92114245/235946980-f149521d-2f2f-47de-9030-d242f3eeae7c.png)

* Dla komputera sieciowego
![image](https://user-images.githubusercontent.com/92114245/235947393-b605e194-8496-4536-b25b-60ff1e64990d.png)

## 4
* Komenda `ping` wysyła jeden datagram na sekundę i drukuje po jednym wierszu na każdą otrzymaną odpowiedź. Komenda ping oblicza czas obiegu w obie strony oraz statystyki strat pakietów, a także wyświetla krótkie podsumowanie po zakończeniu działania.

![image](https://user-images.githubusercontent.com/92114245/235948550-d47667cb-417b-43d1-bb79-80b3626b0092.png)
![image](https://user-images.githubusercontent.com/92114245/235949014-650d7ab3-a95f-4d3c-b61f-bdc9e4e069ea.png)
![image](https://user-images.githubusercontent.com/92114245/235954738-ff961831-c34b-407b-a251-4201b07a5f16.png)
![image](https://user-images.githubusercontent.com/92114245/235955017-fa727780-0052-4250-b636-186e96315fa7.png)
![image](https://user-images.githubusercontent.com/92114245/235955151-ad447e55-7fb8-4d68-b567-cb08adf0c681.png)

* Można wyciągnąć wnioski, że im dłuższy czas tym dalej znajdujemy się od pingowanego serwera.

## 5
* Komenda `nslookup` pozwalaja sprawdzić poprawność konfiguracji dla danej domeny. Dzięki tej komendzie jesteś w stanie zweryfikować poprawność konfiguracji rekordów ustawionych na serwerach.

![image](https://user-images.githubusercontent.com/92114245/235956417-05997223-a57e-4d57-9a64-b297e205ea33.png)
![image](https://user-images.githubusercontent.com/92114245/235956528-72526e2d-7263-444a-b3eb-e9a0c7bfccfd.png)
![image](https://user-images.githubusercontent.com/92114245/235956638-1489b783-09ca-48df-be06-08276c50b614.png)
![image](https://user-images.githubusercontent.com/92114245/235956754-ff1f9194-b80a-46d6-9dc5-58fde881951f.png)
![image](https://user-images.githubusercontent.com/92114245/235956844-95ee81e1-d85a-47f1-8a72-38c884e8f174.png)

## 6
* Komenda `tracert` to narzędzie służące do śledzenia trasy pakietów IP w sieciach. Polecenie tracert wykorzystuje pole czasu IP TTL i komunikaty o błędach protokołu ICMP do określania trasy między poszczególnymi hostami w sieci.

![image](https://user-images.githubusercontent.com/92114245/235957389-c10c97b7-c2b3-4783-989e-bb3b0e9c9603.png)
![image](https://user-images.githubusercontent.com/92114245/235957952-4c7f62c8-da39-495d-9b51-ef71aba3e9e4.png)
![image](https://user-images.githubusercontent.com/92114245/235958874-fdf2dd57-3ad5-4353-a6e5-d55cb0a029f4.png)
![image](https://user-images.githubusercontent.com/92114245/235959168-89016900-2c50-4402-ac3b-45b82ebd7d89.png)
![image](https://user-images.githubusercontent.com/92114245/235960557-ca0741ee-3c5f-4bf3-b044-a2108a4ea43f.png)

## 7
* "Wireshark" jest to program lub sprzęt komputerowy służący do przechwytywania i zapisywania ruchu sieciowego. Pozwala szczegółowo zapoznać się z zawartością przesyłanych pakietów poprzez ich dekodowanie. Wykorzystywany jest głównie do diagnostyki niezawodności i wydajności sieci.
