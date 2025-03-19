
## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus) : jest to jedna z topologii fizycznych sieci komputerowych charakteryzująca się tym, że wszystkie elementy sieci są podłączone do jednej magistrali (zazwyczaj w postaci kabla koncentrycznego).
  - Wady: minimalna odporność na awarie
  - Zalety: małe użycie kabla. niska cena sieci.
  - Gdzie stosowane: Obecnie stosowana do łączenia urządzeń w topologii punkt-punkt
- **Topologia pierścienia** (Ring): jest to układ, w którym każde urządzenie (węzeł) jest połączone z dwoma sąsiednimi węzłami, tworząc zamkniętą pętlę komunikacyjną.
  - Wady: awaria pojedynczego przewodu lub komputera powoduje unieruchomienie całej sieci,
  - Zalety: mała ilości kabli
  - Gdzie stosowane: w sieciach komputerowych, gdzie każde urządzenie jest połączone z dwoma sąsiednimi urządzeniami, tworząc zamknięty pierścień.
- **Topologia gwiazdy** (Star): są to Komputery są podłączone do jednego punktu centralnego, koncentratora lub przełącznika
  - Wady: ograniczona liczba komputerów. duża liczba połączeń (duże zużycie kabli) gdy awarii ulegnie punkt centralny (koncentrator lub przełącznik), to cała sieć przestaje funkcjonować
  - Zalety: wysoka przepustowość · łatwa lokalizacja uszkodzeń ze względu na centralne sterowanie
  - Gdzie stosowane: W średnich i dużych sieciach lokalnych, w których pracuje wiele urządzeń (serwerów, komputerów, drukarek)



## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point):W topologii typu punkt-punkt dane przesyłane są tylko od jednego urządzenia do drugiego. 
  - Zastosowanie:  Jest to logiczna topologia często stosowana w sieciach lokalnych, w których wykorzystuje się fizyczną topologie gwiazdy.
- **Przekazywanie żetonu** (Token Passing): W topologii przekazywania żetonu, dane przekazywane są kolejno do urządzeń połączonych w sieć. Urządzenie, które otrzyma porcję danych, analizuje czy są one kierowane do niego czy też nie. Jeśli dane nie są do niego adresowane, przekazuje je dalej, do sąsiedniego urządzenia.
  - Zastosowanie: topologie pirscienia
- **Wielodostępowa** (Multiple Access): Topologia wielodostępowa (czasami zwana również logiczną topologią rozgłaszania lub magistrali) umożliwia komunikację urządzeń w sieci poprzez jedno fizyczne medium transmisyjne.
  - Zastosowanie: ethernet



