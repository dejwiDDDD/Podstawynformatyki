+---------------------+------------------------------------------------------------+
| Nazwa warstwy       | Opis                                                       |
+---------------------+------------------------------------------------------------+
| Warstwa aplikacji   | Odpowiada za komunikację między aplikacjami użytkowników.  |
|                     | Przykłady protokołów: HTTP, FTP, SMTP, DNS.                |
+---------------------+------------------------------------------------------------+
| Warstwa transportowa| Zapewnia niezawodny przesył danych między hostami.         |
|                     | Protokół TCP (Transmission Control Protocol) zapewnia      |
|                     | kontrolę błędów i przesyłanie w odpowiedniej kolejności.   |
|                     | Protokół UDP (User Datagram Protocol) jest mniej niezawodny,|
|                     | ale szybszy.                                               |
+---------------------+------------------------------------------------------------+
| Warstwa internetowa | Odpowiada za adresowanie i przesyłanie danych w sieci.     |
|                     | Protokół IP (Internet Protocol) umożliwia adresowanie i    |
|                     | trasowanie pakietów między różnymi sieciami.               |
+---------------------+------------------------------------------------------------+
| Warstwa łącza danych| Zapewnia fizyczną transmisję danych przez medium transmisyjne|
|                     | (np. Ethernet, Wi-Fi). Protokół ARP (Address Resolution    |
|                     | Protocol) mapuje adresy IP na adresy MAC.                  |
+---------------------+------------------------------------------------------------+
| Warstwa fizyczna    | Odpowiada za przesyłanie surowych bitów przez medium       |
|                     | transmisyjne, takie jak kabel miedziany, światłowód lub    |
|                     | fale radiowe (w przypadku sieci bezprzewodowych).          |
+---------------------+------------------------------------------------------------+

##Porównanie modelu OSI i TCP/IP 

 TCP/IP łączy warstwy łącza danych i fizyczną modelu OSI w jednej warstwie. TCP/IP wydaje się prostszy, 
 ponieważ ma mniej warstw. Model odniesienia OSI jest mniej skomplikowany; ma więcej warstw, a to pozwala 
 na szybszą współpracę i rozwiązywanie problemów.

##Najpopularniejsze protokoły TCP/IP:
 
 -http-Używany do przesyłania stron internetowych i innych zasobów w sieci. Protokół bazowy dla WWW.
 -https-Szyfrowana wersja HTTP, zapewniająca bezpieczeństwo komunikacji poprzez SSL/TLS.
 -ftp-Służy do przesyłania plików między komputerami w sieci. Wspiera zarówno pobieranie, jak i wysyłanie plików.
 -smtp-Używany do wysyłania wiadomości e-mail między serwerami pocztowymi.
 -pop3-Używany do pobierania poczty e-mail z serwera pocztowego na komputer użytkownika.
 -imap-Umożliwia dostęp do poczty e-mail przechowywanej na serwerze, zachowując wiadomości na serwerze, zamiast pobierać je na urządzenie.
 -ip-Odpowiada za adresowanie i trasowanie pakietów w sieci. Istnieją dwie wersje: IPv4 i IPv6.
