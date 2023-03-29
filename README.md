# Stopy i ławy w ABC

[Zakup](#zakup) | [Instalacja](#instalacja) | [Wideo](#wideo) | [Instrukcja](#instrukcja) | [Kontakt](#kontakt)

Moduł do szybkiego projektowania fundamentów bezpośrednich zgodnie z Eurokodami w
programach **ABC** firmy [PRO-SOFT](https://www.pro-soft.gliwice.pl/).

W celu zapoznania się z możliwościami modułu można obejrzeć [wideo](#wideo).
Szczegółowy opis działania zawarty jest w [instrukcji](#instrukcja).

## Zakup

Cena **600,- zł** netto za licencję wieczystą, na fakturze kwota będzie powiększona
o podatek VAT w wysokości 23%.

Wymagana aktualizacja programu **ABC** do wersji 6.23 zgodnie z
[cennikiem](https://www.pro-soft.gliwice.pl/cennik.html).
Jeden zakup dotyczy jednej licencji (jednego klucza lub użytkownika) i jest niezależny
od ilości programów. Do pobrania, aktualizacji oraz autoryzacji wymagane jest
połączenie z siecią.

W celu zakupu prosimy o [kontakt](#kontakt). Zakupy w formie grupowej prowadzi firma
[TINSERWIS](https://www.tinserwis.pl/), gdzie można uzyskać maksymalnie 50% rabatu!

```
Moduł podlega ochronie prawa autorskiego bez udzielania jakiejkolwiek gwarancji.
Jest sprzedawany jako narzędzie do wsparcia zarobkowego procesu projektowego.
Jest dostarczany "taki jaki jest" i nie ma gwarancji, że jest wolny od błędów pomimo
dołożenia wszelkich starań. Autor modułu nie ponosi odpowiedzialności za skutki powstałe
w wyniku nieumiejętnego posługiwania się oprogramowaniem, w tym związane z utratą
danych. Osoba kupująca dobrowolnie wyraża zgodę na powyższe warunki licencyjne oraz
na przetwarzanie swoich danych osobowych w celu obsługi zakupu licencji.
```

## Instalacja

Plik instalacyjny pobieramy w zależności od tego, jaki program **ABC** posiadamy na
kluczu USB.

W przypadku posiadania kilku kluczy, moduł instalujemy kilka razy w lokalizacji
programu **ABC**.

Należy kliknąć na jeden z poniższych linków, aby rozpocząć pobieranie:

- [Mam kilka programów **ABC**](https://github.com/pkpkbud/fundamenty/releases/download/3.0.0/Fundamenty-ABC6-3.0.0-win32.msi)
- [Mam tylko **ABC Płyta**](https://github.com/pkpkbud/fundamenty/releases/download/3.0.0/Fundamenty-ABC6p-3.0.0-win32.msi)
- [Mam tylko **ABC Rama3D**](https://github.com/pkpkbud/fundamenty/releases/download/3.0.0/Fundamenty-ABC6r-3.0.0-win32.msi)
- [Mam tylko **ABC Obiekt3D**](https://github.com/pkpkbud/fundamenty/releases/download/3.0.0/Fundamenty-ABC6s-3.0.0-win32.msi)
- [Mam tylko **ABC Tarcza**](https://github.com/pkpkbud/fundamenty/releases/download/3.0.0/Fundamenty-ABC6t-3.0.0-win32.msi)

Spis zmian oraz poprzednie wersje są dostępne w serwisie
[GitHub](https://github.com/pkpkbud/fundamenty/releases).

## Wideo

<iframe width="560" height="315" src="https://www.youtube.com/embed/MAA1BrUQ1LE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/dykUG6P5lk0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Instrukcja

Podczas korzystania z modułu, można uzyskać wskazówki dotyczące danej funkcji po
najechaniu na opis kursorem myszy. Jednostki, w jakich podajemy wartości są podane po
lewej stronie każdego pola. Wartości możemy zmieniać, wpisując na klawiaturze i
zatwierdzając klawiszem `Enter`, klikając na strzałki `góra`-`dół` po prawej stronie
od wartości lub wciskając strzałki `góra`-`dół` na klawiaturze.

### Uruchomienie

Moduł można uruchomić samodzielnie w formie kalkulatora. W tym celu należy uruchomić
plik `stopa.exe` lub `lawa.exe` z lokalizacji instalacji (np. *C:\ABC6\EXE*). Pierwsze
uruchomienie należy wykonać z poziomu programu **ABC**.

W każdym typie zadania, w którym wprowadzono podpory węzłowe lub typu `Słup` można
zaprojektować stopę fundamentową. W programie `ABC Płyta` dla podpór typu `Ściana`
można zaprojektować ławę fundamentową. W wynikach zadania w menu `Wymiar` dostępne
są opcje `Projektowanie stopy` oraz `Projektowanie ławy`. W przypadku, gdy ta możliwość
nie jest dostępna trzeba zaktualizować program **ABC** do wersji 6.23 lub wybrać z menu
opcję `Pokaż → Wybór wymiarowania`.

![image](https://user-images.githubusercontent.com/55211992/228655469-e4dd852d-1a4b-41f7-8c4c-1b7da20f13c9.png)

### Obciążenia

Po uruchomieniu pokaże się pytanie o obciążenia. W przypadku wariantu będzie można
zmienić mnożnik obciążenia, podpowiadany z opisu obciążeń przyjmowanych do obwiedni.
Obwiednia generalnie będzie obliczana jako `Automat EN`, chyba, że są zdefiniowane
własne kombinacje wg PN-EN, to wtedy będzie można je wybrać. Jeśli projektowanie
fundamentów było poprzedzone wymiarowaniem żelbetu, to nie będzie pytania o obciążenia,
ponieważ fundamenty będą projektowane na te same obciążenia co użyte w żelbecie. Jest
również możliwość dodania ciężaru własnego ścian i słupów do obciążeń po włączeniu
opcji `Dodaj ciężar ściany`.

![image](https://user-images.githubusercontent.com/55211992/228655573-90d33b89-6310-4e69-af37-fd3ab4dccca1.png)

### Wybór miejsca

Po zatwierdzeniu obciążeń plansza zostanie zamknięta i pokaże się rysunek modelu.
W przypadku `Projektowanie stopy` pojawią się podpory skupione (słupy) z zaznaczonym
miejscem o największej reakcji pionowej, wybieramy projektowane miejsce. W przypadku
opcji `Projektowanie ławy` pojawią się podpory liniowe typu `ściana`. Należy wybrać
dwa skrajne węzły projektowanego miejsca. Istnieje możliwość dodania długości ściany.
Jej dodanie rozkłada obciążenie na większej długości.

### Podłoże

![image](https://user-images.githubusercontent.com/55211992/228652263-0fa9d14f-8169-4cfa-9e0d-0ea5332d2e9e.png)

W oknie możemy zdefiniować `Głębokość posadowienia`, którą należy liczyć od najniższego
poziomu naziomu. W celu uwzględnienia sił wyporu spowodowanych wodą gruntową należy
określić `Poziom wody gruntowej`.

Opcja `Sprawdź podłoże na innej głębokości` służy do uwzględnienia sytuacji, gdy
warstwa o niższych parametrach geotechnicznych zalega na głębokości mniejszej niż 2B
poniżej poziomu posadowienia fundamentu według metody fundamentu zastępczego normy
*PN-81 B-03020*. Należy zdefiniować, na jakiej głębokości od naziomu znajduje się strop
warstwy gruntu oraz jaki jest rodzaj gruntu bezpośrednio pod podstawą fundamentu.
Parametr ten służy do ustalenia zasięgu poszerzania podstawy fundamentu zastępczego.
Po zatwierdzeniu przyciskiem `OK` sprawdzenie podłoża odbywa się na nowej głębokości.
Jeżeli chcemy sprawdzić inną warstwę, możemy zrzucić listę z wynikami i wprowadzić nową
głębokość oraz parametry geotechniczne.

![image](https://user-images.githubusercontent.com/55211992/228655858-e8eeb83a-e9c5-4fb1-9ac0-c54893c8fa84.png)

W celu definicji podłoża należy podać charakterystyczne wartości parametrów
geotechnicznych na podstawie badań geologicznych gruntu lub z normowych tablic.
Przycisk `PN-B` umożliwia wprowadzenie parametrów geotechnicznych według metody B
normy *PN-81 B-03020* oraz zalecane dopuszczalne naprężenia według tabeli 12-2 książki
*Zarys geotechniki* Zenona Wiłuna. Wartości te są ustalane na podstawie zależności
korelacyjnych i mogą służyć jako wskazówka. Według Eurokodu powinno się projektować na
wartościach charakterystycznych uzyskanych bezpośrednio z badań podłoża. Po wyborze z
menu rodzaju gruntu należy podać jego charakterystyczny parametr jak: stopień
zagęszczenia i wilgotność (grunty niespoiste) lub stopień plastyczności i typ
konsolidacji (grunty spoiste). Po zatwierdzeniu przyciskiem `OK` wartości parametrów
w oknie `Podłoże` są aktualizowane.

![image](https://user-images.githubusercontent.com/55211992/228655721-f8983152-7bee-40c3-b3e2-46d58f776afa.png)

Jeżeli chcemy sprawdzić warunek naprężeń krawędziowych to możemy podać ich dopuszczalną
wartość. Jeżeli chcemy sprawdzić osiadania wpisujemy `E0` edometryczny moduł ściśliwości
pierwotnej gruntu. `Wartość graniczna osiadania` definiowana jest w oknie `Opcje`.

Przycisk `Budowla wysoka lub hala z suwnicą` zmienia parametry wymiarowania nie
dopuszczając, aby siła wypadkowa wychodziła poza rdzeń podstawy oraz aby nie było za
dużej dysproporcji pomiędzy minimalnymi i maksymalnymi naprężeniami krawędziowymi.

### Projektowanie

![image](https://user-images.githubusercontent.com/55211992/228652433-8f259374-84bb-4acf-ae7e-a9d1669020ba.png)

Po wprowadzeniu danych na pierwszej planszy można przyciskiem `OK` przejść do planszy
głównej modułu. Na niej przeprowadzane jest całe projektowanie. Składa się z
następujących elementów:

**Ramka z danymi (po lewej stronie)**, gdzie podobnie jak na pierwszej planszy
podajemy wartości, tym razem dotyczące przyjętych wymiarów, materiałów, otuliny oraz
zbrojenia. Kierunek X i Y jest zgodny z układem osi przyjętym w programach **ABC**.
`Opis` można dowolnie modyfikować, domyślnie wpisany jest numer węzła.
`Wysokość` fundamentu podajemy od poziomu posadowienia (głębokości wykopu) w górę.
W celu policzenia ławy jako fundamentu pasmowego o nieskończonej długości należy
odznaczyć opcję `Długość`. W `ABC Płyta` wymiary słupa, ściany oraz dane fundamentu
są pobierane z opisu podpory. W innych przypadkach są przyjmowane wartości domyślne.

![image](https://user-images.githubusercontent.com/55211992/228462198-9d434be2-cbea-44a0-a916-e1c5ebf44b04.png)

**Ramka z wynikami (u dołu oraz rysunek w części centralnej)**, która aktualizuje
się po zmianie wartości parametrów lub po naciśnięciu przycisku `Oblicz`. Każda linijka
zawiera opis sprawdzanego warunku, wzór oraz stopień wytężenia podany w procentach.
W przypadku, gdy któryś warunek nie jest spełniony, kolor tekstu zmienia się na
czerwony. Nie są również pokazywane sprawdzenia wyników o zerowym wytężeniu. Zachowanie
to możemy zmienić w oknie `Ustawienia`. W przypadku wymiarowania na obwiednię sił, na
końcu każdego wzoru w nawiasie kwadratowym podany jest decydujący przypadek. Po
najechaniu na niego kursorem myszy wyświetlone zostaną wartości sił pobrane z ABC.
Nazwa przypadku oznacza wiodące obciążenie dla warunku.

Sprawdzane są następujące warunki nośności podłoża zgodnie z normą *PN-EN 1997-1*:
- Opór pionowy podłoża (wyparcie) obliczony metodą analityczną według załącznika D.
- Nośność na przesunięcie poziome (poślizg) obliczona zgodnie z punktem 6.5.3.
- Sprawdzenie, czy siła wypadkowa znajduje się w rdzeniu podstawy. W przypadku
większych wartości mimośrodów (> 1/6) pojawiają się naprężenia rozciągające w kontakcie
grunt-fundament, czego konsekwencją jest powstanie szczeliny, tzw. odrywanie. Możemy
dopuścić przyciskiem `Odrywanie` w przypadku, gdy obiekt budowlany nie ma wysoko
umiejscowionego środka ciężkości. Zaleca się, aby były to szczególne i wyjątkowe
sytuacje.
- Gdy dopuścimy `Odrywanie`, to znaczy, że decydujemy się na poszerzony rdzeń podstawy
fundamentu (w przybliżeniu dwa razy większy od rdzenia właściwego). Sprawdzenie zasięgu
szczeliny między podłożem i podstawą fundamentu jest przeprowadzone według normy
*PN-81 B-03020* (p. 2.3 c), gdzie wymagane jest, aby zasięg szczeliny był mniejszy niż
połowa odległości między narożem, w którym występuje odrywanie, a prostą równoległą do
osi obojętnej przeprowadzonej przez środek fundamentu.
- Dopuszczalne naprężenia krawędziowe, które są porównywane z wartością graniczną podaną
na pierwszej planszy modułu [Podłoże](#podłoże).
- Przybliżone osiadania całkowite, obliczone metodą sumowania odkształceń warstw
podłoża według punktu F.1 normy. Metoda ta jest analogiczna do zalecanych zasad normy
*PN-81 B-03020*.
- Stosunek nacisków na podłoże, który jest zaleceniem z doświadczeń praktyki projektowej
- w celu ograniczenia nierównomiernego osiadania fundamentu. Sprawdzany jest poprzez
porównanie ilorazu maksymalnych i minimalnych naprężeń krawędziowych z wartościami
dopuszczalnymi z normy *PN-93 B-03201* lub z książki dr inż. Olgierda Puły
*Projektowanie fundamentów bezpośrednich według Eurokodu 7*.

![image](https://user-images.githubusercontent.com/55211992/228576517-9490ed53-df19-418b-91c2-0f4320972e86.png)

Moduł sprawdza, czy można element można zaprojektować jako niezbrojony zgodnie z
p. 12.9.3 normy *PN-EN 1992-1-1*. Jeżeli nie jest spełniony warunek to zbrojenie jest
wymiarowane na zginanie zgodnie z normą *PN-EN 1992-1-1* w przekroju cofniętym od
krawędzi na odległość 0,15 wymiaru słupa lub ściany. Podane wartości powierzchni
zbrojenia dolnego wymaganego `As,req` oraz założonego `As,prov` dotyczą zbrojenia na
całej długości krawędzi fundamentu. W przypadku ław fundamentowych nie uwzględniono
konstrukcyjnego zbrojenia podłużnego. W przypadku stóp fundamentowych
momenty gnące są wyznaczane domyślnie *metodą wydzielonych wsporników prostokątnych*,
alternatywnie możemy wybrać *metodę wydzielonych wsporników trapezowych* w oknie
`Ustawienia`. Zakłada się też, że zbrojenie w kierunku dłuższego boku fundamentu jest
układane dołem (kierunek Y w przypadku stopy kwadratowej).

![image](https://user-images.githubusercontent.com/55211992/228656063-7a09d5d2-d63f-45d0-814c-33bc6a966aca.png)

Nośność fundamentu słupa na przebicie (przez ścinanie) jest sprawdzana na obwodach
kontrolnych leżących w odległości od 0,5d do 2d (co 0,1) od skraju słupa w myśl
p. 6.4.2 (2) *PN-EN 1992-1-1*. Odległość krytyczna podana jest w opisie warunku.
W przypadku, gdy obwód kontrolny wykracza poza obręb powierzchni stopy nie zachodzi
mechanizm przebicia.

![image](https://user-images.githubusercontent.com/55211992/228577983-d72ffe38-819a-4c1d-b30f-2008869a8a7b.png)

Rysunek w centralnej części przedstawia geometrię fundamentu w rzucie z góry w
przypadku stopy lub przekrój poprzeczny w przypadku ławy, wraz z przebiegiem i
wartościami naprężeń maksymalnych i minimalnych na każdej krawędzi. Dodatkowo na
rysunku jest układ osi, schematyczne zbrojenie oraz wartości objętości betonu i pola
powierzchni podstawy stopy. Rysunek możemy przybliżać za pomocą kółka myszy oraz
przesuwać trzymając lewy przycisk myszy. Przydaje się to w przypadku, gdy opisy są
blisko siebie i są trudne do odczytania. Optymalne położenie rysunku w oknie najłatwiej
uzyskać akceptując ponownie dowolny parametr klawiszem `Enter` lub przyciskiem `Oblicz`.

![image](https://user-images.githubusercontent.com/55211992/228580509-b5964d10-90c3-4ff4-bc28-ee5a64e5a906.png)

**Ramka przycisków (po prawej)** zawierające następujące funkcje: 
- Przycisk `Oblicz` aktualizuje część z wynikami dla zadanych wartości.
- Przycisk `Dobierz` w sposób iteracyjny szuka geometrii fundamentu, która spełnia
wszystkie warunki sprawdzenia podłoża (nie dopuszcza odrywania). Jako kryterium
optymalnej geometrii przyjęto najmniejszą powierzchnię podstawy. W przypadku stopy
fundamentowej maksymalną proporcję długości do szerokości można zmienić w oknie
`Ustawienia`. Obliczenia są przeprowadzane w tle i przy obwiedni sił,
dużych wartościach sił lub słabym podłożu mogą trwać dłuższą chwilę.
- Przycisk `Podłoże` otwiera ponownie wcześniej opisane okno [Podłoże](#podłoże).
- Przycisk `Obciążenia` otwiera okno z wartościami obliczeniowych sił skupionych i
rozłożonych. W przypadku, gdy wymiarujemy na jeden wariant wszystkie wartości możemy
dowolnie modyfikować. W przypadku, gdy wymiarujemy na obwiednię sił dopuszczalna jest
tylko modyfikacja sił rozłożonych naziomu (stałych). Przycisk z czerwonym `Z`
zeruje wszystkie obciążenia, ponowne wciśnięcie przywraca wartości przed zerowaniem.
- Przycisk `Ustawienia` zawiera dodatkowe opcje obliczeniowe oraz konfigurację wartości
parametrów takich jak dane materiałowe i częściowe współczynniki bezpieczeństwa (które
możemy przywrócić do wartości domyślnych przyciskiem `PN-EN`). W dodatkowych opcjach
obliczeniowych możemy wybrać, czy chcemy sprawdzać podłoże w warunkach pracy
`z odpływem` lub `bez odpływu`. W przypadku wybrania opcji `bez odpływu` musimy podać
wartość wytrzymałości gruntu na ścinanie. `Metoda wydzielonych wsporników` dotyczy
sposobu wyznaczania momentów gnących do wymiarowania zbrojenia. Włączenie opcji
`Pokazuj sprawdzenie zerowych warunków normowych` powoduje, że w ramce z wynikami są
pokazywane również warunki, gdzie stopień wytężenia wynosi 0% oraz zbrojenie
Osiadanie jest porównywane z wartością podaną w `Graniczna wartość osiadania`.
`Maksymalna proporcja L:B w „Dobierz”` służy do wybrania maksymalnej proporcji długości
do szerokości fundamentu szukanego funkcją `Dobierz`.
- Przycisk `Do schowka` kopiuje listę z notką obliczeniową do schowka. Po zamknięciu
modułu schowek zostaje wyczyszczony.
- Przycisk `Do Worda` otwiera nowy dokument zawierający notkę obliczeniową z rysunkiem
Ponowne naciśnięcie przycisku powoduje dopisanie wyników do otwartego dokumentu.
W przypadku posiadania innego pakietu niż *Microsoft Office*, jest tworzony i otwierany
nowy plik *Nazwa_zadania.STO.DOCX* w lokalizacji zadania.
- Przycisk `Aktualizuj` sprawdza, czy jest uruchomiona aktualna wersja modułu oraz w
razie potrzeby umożliwia pobranie i aktualizację do najnowszej wersji. Plik instalacyjny
jest pobierany w tle, trzeba poczekać na jego pobranie. Następnie moduł jest wyłączany
i uruchamia się instalacja. Moduł należy zainstalować w lokalizacji programu **ABC**
w folderze EXE (np. *C:\ABC6\EXE*).
- Przycisk `Zamknij` zapisuje wyniki i zamyka moduł, skąd możemy przejść do wyboru
kolejnego miejsca. W przypadku stóp fundamentowych miejsca zaprojektowane będą opisane
`Stopa`, a podpowiadane będzie kolejne miejsce z największą reakcją pionową.
- Zaznaczenie opcji `Domyślne` powoduje, że po zamknięciu modułu bieżące ustawienia
zostają zapisane jako domyślne do wymiarowania kolejnych miejsc.

![image](https://user-images.githubusercontent.com/55211992/228655366-15617c16-6214-4321-9291-0182c6542b2c.png)

## Kontakt

Wszelkie sugestie i ewentualne błędy w programie można zgłaszać poprzez e-mail
lub serwis [GitHub](https://github.com/pkpkbud/fundamenty/issues).

**PKPKBUD Paweł Kowalski Projektowanie Konstrukcji Budowlanych**\
NIP: 2220810920, REGON: 522155974

tel. 603 088 626\
e-mail: <pkpkbud@gmail.com>
