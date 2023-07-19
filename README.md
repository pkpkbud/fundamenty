# Stopy i ławy w ABC

[Zakup](#zakup) | [Instalacja](#instalacja) | [Wideo](#wideo) | [Instrukcja](#instrukcja) | [Kontakt](#kontakt)

Moduł do szybkiego projektowania fundamentów bezpośrednich zgodnie z Eurokodami w
programach **ABC** firmy [PRO-SOFT](https://www.pro-soft.gliwice.pl/).

W celu zapoznania się z możliwościami modułu można obejrzeć [wideo](#wideo)
lub go [zainstalować](#instalacja). Przed [zakupem](#zakup) działa w trybie DEMO,
gdzie nie można zmieniać parametrów podłoża.
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
[TINSERWIS](https://www.tinserwis.pl/), gdzie można uzyskać maksymalnie 50% rabatu.

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

Wybieramy jeden z poniższych linków, aby rozpocząć pobieranie:

- [Mam kilka programów **ABC**](https://github.com/pkpkbud/fundamenty/releases/download/5.0.0/Fundamenty-ABC6-5.0.0-win32.msi)
- [Mam tylko **ABC Płyta**](https://github.com/pkpkbud/fundamenty/releases/download/5.0.0/Fundamenty-ABC6p-5.0.0-win32.msi)
- [Mam tylko **ABC Rama3D**](https://github.com/pkpkbud/fundamenty/releases/download/5.0.0/Fundamenty-ABC6r-5.0.0-win32.msi)
- [Mam tylko **ABC Obiekt3D**](https://github.com/pkpkbud/fundamenty/releases/download/5.0.0/Fundamenty-ABC6s-5.0.0-win32.msi)
- [Mam tylko **ABC Tarcza**](https://github.com/pkpkbud/fundamenty/releases/download/5.0.0/Fundamenty-ABC6t-5.0.0-win32.msi)

Moduł instalujemy w lokalizacji programu **ABC** w folderze *EXE*
(np. *C:\ABC6\EXE*).

Spis zmian oraz poprzednie wersje są dostępne w serwisie
[GitHub](https://github.com/pkpkbud/fundamenty/releases).

## Wideo

<iframe width="560" height="315" src="https://www.youtube.com/embed/MAA1BrUQ1LE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/dykUG6P5lk0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Instrukcja

Podczas korzystania z modułu, można uzyskać wskazówki dotyczące danej funkcji po
najechaniu na opis kursorem myszy. Jednostki, w jakich podane są wartości są po
lewej stronie każdego pola. Wartości można zmieniać, wpisując na klawiaturze i
zatwierdzając klawiszem `Enter`, klikając na znaki `góra`-`dół` po prawej stronie
pola lub wciskając klawisze strzałek `↑`-`↓` na klawiaturze.

### Uruchomienie

Moduł można uruchomić samodzielnie w trybie kalkulatora. W tym celu należy uruchomić
skrót z pulpitu albo odpowiedni plik `stopa.exe` lub `lawa.exe` z lokalizacji instalacji
(np. *C:\ABC6\EXE*). Przy uruchamianiu można wybrać plik zadania z końcówką *.STO*
w celu wczytania wcześniej zapisanych wyników. Przy zamykaniu można zapisać wyniki do
pliku z końcówką *.STO*. Pierwsze uruchomienie należy wykonać z poziomu programu **ABC**.

W każdym typie zadania, w którym wprowadzono podpory węzłowe lub typu `Słup` można
zaprojektować stopę fundamentową. W programie **ABC Płyta** dla podpór typu `Ściana`
można zaprojektować ławę fundamentową. W wynikach zadania w menu `Wymiar` dostępne
są opcje `Projektowanie stopy` oraz `Projektowanie ławy`. W przypadku, gdy ta możliwość
nie jest dostępna trzeba zaktualizować program **ABC** do wersji 6.23, włączyć pełny
zakres menu w **ABC** przyciskiem "M" lub wybrać z menu opcję `Pokaż → Wybór wymiarowania`.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/775bd5e1-657d-4b8f-a272-fb3ec5c52b8e)

### Obciążenia

Po uruchomieniu pokaże się pytanie o obciążenia. W przypadku wariantu będzie można
zmienić mnożnik obciążenia, podpowiadany z opisu obciążeń przyjmowanych do obwiedni.
Obwiednia generalnie będzie obliczana jako `Automat EN`, chyba, że są zdefiniowane
własne kombinacje wg PN-EN, to wtedy będzie można je wybrać. Jeśli projektowanie
fundamentów było poprzedzone wymiarowaniem żelbetu, to nie będzie pytania o obciążenia,
ponieważ fundamenty będą projektowane na te same obciążenia co użyte w żelbecie. Jest
również możliwość dodania ciężaru własnego ścian i słupów do obciążeń po włączeniu
opcji `Dodaj ciężar ściany`. Przycisk `Usuń` usuwa wcześniej zadane miejsca.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/4722f4d9-9307-4c1b-a887-4f82979e7ef5)

### Wybór miejsca

Po zatwierdzeniu obciążeń plansza zostanie zamknięta i pokaże się rysunek modelu. W
przypadku opcji `Projektowanie stopy` pojawią się podpory skupione (słupy) z zaznaczonym
miejscem o największej reakcji pionowej, należy wybrać projektowane miejsce. W przypadku
opcji `Projektowanie ławy` pojawią się podpory liniowe typu `Ściana`, należy wybrać dwa
skrajne węzły projektowanego miejsca. Istnieje możliwość dodania długości ściany.
Jej dodanie rozkłada obciążenie na większej długości.

### Podłoże

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/b1ed0afd-03fd-4ddf-b856-fb7109b879c1)

W oknie można zdefiniować `Głębokość posadowienia`, którą należy liczyć od najniższego
poziomu naziomu. W celu uwzględnienia sił wyporu spowodowanych wodą gruntową należy
określić `Poziom wody gruntowej`.

Opcja `Sprawdź podłoże na innej głębokości` służy do uwzględnienia sytuacji, gdy
warstwa o niższych parametrach geotechnicznych zalega na głębokości mniejszej niż 2B
poniżej poziomu posadowienia fundamentu według metody fundamentu zastępczego normy
*PN-81 B-03020*. Należy zdefiniować, na jakiej głębokości od naziomu znajduje się strop
warstwy gruntu oraz jaki jest rodzaj gruntu bezpośrednio pod podstawą fundamentu.
Parametr ten służy do ustalenia zasięgu poszerzania podstawy fundamentu zastępczego.
Po zatwierdzeniu przyciskiem `OK` sprawdzenie podłoża odbywa się na nowej głębokości.
W celu sprawdzenia kolejnej warstwy gruntu, można skopiować listę z wynikami
`Do schowka` lub `Do Worda` i wprowadzić nową głębokość oraz parametry geotechniczne.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/a3d827cb-d974-4a27-92d6-dce7b5996865)

W celu definicji podłoża należy podać charakterystyczne wartości parametrów
geotechnicznych na podstawie badań geologicznych gruntu lub z normowych tablic.
Przycisk `Metoda B normy PN-81 B-03020` umożliwia wprowadzenie parametrów geotechnicznych
na podstawie zależności korelacyjnych z normy `PN-81 B-03020` oraz zalecane dopuszczalne
naprężenia według tabeli 12-2 książki *Zarys geotechniki* Zenona Wiłuna.
Po wyborze z menu rodzaju gruntu należy podać jego charakterystyczny parametr jak:
stopień zagęszczenia i wilgotność (grunty niespoiste) lub stopień plastyczności
i typ konsolidacji (grunty spoiste). Po zatwierdzeniu przyciskiem `OK` wartości
parametrów w oknie `Podłoże` są aktualizowane oraz blokowane.
W celu ich zmiany należy odznaczyć opcję `Metoda B normy PN-81 B-03020`.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/d0b79951-9061-4781-8a0f-c965f7e330a0)

W celu sprawdzenia warunku naprężeń krawędziowych należy włączyć i podać
`Dopuszczalne naprężenia`. W celu sprawdzenia osiadania należy włączyć
`Sprawdź osiadanie` i podać `M0`, edometryczny moduł ściśliwości pierwotnej gruntu.
`Wartość graniczna osiadania` definiowana jest w oknie `Ustawienia`.

Przycisk `Budowla wysoka lub hala z suwnicą` zmienia parametry wymiarowania nie
dopuszczając, aby siła wypadkowa wychodziła poza rdzeń podstawy oraz aby nie było za
dużej dysproporcji pomiędzy minimalnymi i maksymalnymi naprężeniami krawędziowymi.

### Projektowanie

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/f9b94c64-3765-417b-ba85-700093ab4b17)

Po wprowadzeniu danych na pierwszej planszy można przyciskiem `OK` przejść do planszy
głównej modułu. Na niej przeprowadzane jest całe projektowanie. Składa się z opisanych
poniżej elementów.

**Ramka z danymi po lewej stronie**, gdzie podobnie jak na pierwszej planszy należy
podać wartości, tym razem dotyczące przyjętych wymiarów, materiałów, otuliny oraz
zbrojenia. Kierunek X i Y jest zgodny z układem osi przyjętym w programach **ABC**.
`Opis` można dowolnie modyfikować, domyślnie wpisany jest numer węzła. Zaznaczenie opcji
`Okrągła` pozwala na projektowanie niezbrojonych, pionowo obciążonych stóp o podstawie
kołowej o promieniu R według normy *PN-81 B-03020*, gdzie przyjmuje się B = L = 1,77 R.
Przycisk `Obróć` umożliwia obracanie stopy o 90 stopni, podmieniana jest wartość X z Y.
`Wysokość` fundamentu to wartość od poziomu posadowienia (głębokości wykopu) w górę.
Przycisk `Centruj` umożliwia zerowanie mimośrodów, czyli centralne ustawienie środka
słupa względem środka fundamentu. Ponowne wciśnięcie przywraca wartości przed centrowaniem.
W celu policzenia ławy jako fundamentu pasmowego o nieskończonej długości należy
odznaczyć opcję `Długość`. W **ABC Płyta** wymiary słupa, ściany oraz dane fundamentu
są pobierane z opisu podpory z wyjątkiem słupów okrągłych. Aby je zadać, należy
zaznaczyć opcję `Okrągły`. W innych przypadkach są przyjmowane wartości domyślne.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/7c280982-7f00-4da0-ae3f-20141f9460d6)

**Ramka z wynikami u dołu**, która aktualizuje się po zmianie wartości parametrów
lub po naciśnięciu przycisku `Oblicz`. Każda linijka zawiera opis sprawdzanego warunku,
wzór oraz stopień wytężenia podany w procentach. W przypadku, gdy któryś warunek nie
jest spełniony, kolor tekstu zmienia się na czerwony. Nie są również pokazywane
sprawdzenia wyników o zerowym wytężeniu. Zachowanie to można zmienić w oknie
`Ustawienia`. W przypadku wymiarowania na obwiednię sił, na końcu każdego wzoru w
nawiasie kwadratowym podany jest decydujący przypadek. Po najechaniu na niego kursorem
myszy wyświetlone zostaną wartości sił pobrane z programu **ABC**. Nazwa przypadku
oznacza wiodące obciążenie dla warunku.

Sprawdzane są następujące warunki nośności podłoża zgodnie z normą *PN-EN 1997-1*:
- Opór pionowy podłoża (wyparcie) obliczony metodą analityczną według załącznika D.
- Nośność na przesunięcie poziome (poślizg) obliczona zgodnie z punktem 6.5.3.
- Sprawdzenie, czy siła wypadkowa znajduje się w rdzeniu podstawy. W przypadku
większych wartości mimośrodów (> 1/6) pojawiają się naprężenia rozciągające w kontakcie
grunt-fundament, czego konsekwencją jest powstanie szczeliny, tzw. odrywanie. Można
dopuścić przyciskiem `ODRYWANIE` w przypadku, gdy obiekt budowlany nie ma wysoko
umiejscowionego środka ciężkości. Zaleca się, aby były to szczególne i wyjątkowe
sytuacje.
- Gdy włączono opcję `ODRYWANIE`, to znaczy, że sprawdzany jest poszerzony rdzeń podstawy
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
w celu ograniczenia nierównomiernego osiadania fundamentu. Sprawdzany jest poprzez
porównanie ilorazu maksymalnych i minimalnych naprężeń krawędziowych z wartościami
dopuszczalnymi z normy *PN-93 B-03201* lub z książki dr inż. Olgierda Puły
*Projektowanie fundamentów bezpośrednich według Eurokodu 7*.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/12fea5d2-468b-417d-9edc-57d692889516)

Moduł sprawdza, czy można element można zaprojektować jako niezbrojony zgodnie z
p. 12.9.3 normy *PN-EN 1992-1-1*. Wynik koloru pomarańczowego oznacza, że wysokość
fundamentu jest mniejsza niż zalecany podwójny wysięg odsadzki.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/ac9f895b-6243-441d-9c1e-51a6bbfad34a)

Jeżeli nie jest spełniony warunek to zbrojenie jest wymiarowane na zginanie zgodnie
z normą *PN-EN 1992-1-1* w przekroju cofniętym od krawędzi na odległość 0,15 wymiaru
słupa lub ściany. Podane wartości powierzchni zbrojenia wymaganego `As,req`
oraz założonego `As,prov` dotyczą zbrojenia na całej długości krawędzi fundamentu.
W przypadku ław fundamentowych nie uwzględniono konstrukcyjnego zbrojenia podłużnego.
W przypadku stóp fundamentowych momenty gnące są wyznaczane domyślnie
*metodą wydzielonych wsporników prostokątnych*, alternatywnie można wybrać
*metodę wydzielonych wsporników trapezowych* w oknie `Ustawienia`.
Przyjęto, że zbrojenie w kierunku dłuższego boku stopy jest układane dołem
(kierunek Y w przypadku stopy kwadratowej).

Nośność fundamentu na przebicie (przez ścinanie) jest sprawdzana: dla stopy na
obwodach kontrolnych leżących w odległości od 0,5d do 2d (co 0,1) od skraju słupa w
myśl p. 6.4.2 (2) *PN-EN 1992-1-1*, a dla ławy w odległości 1d od skraju ściany.
Odległość krytyczna podana jest w opisie warunku. W przypadku, gdy obwód kontrolny
wykracza poza obręb powierzchni stopy nie zachodzi mechanizm przebicia.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/432e1286-f110-488b-94ca-0fb1fe01c588)

**Rysunek w centralnej części** przedstawia geometrię fundamentu w rzucie z góry w
przypadku stopy lub przekrój poprzeczny w przypadku ławy, wraz z przebiegiem i
wartościami naprężeń maksymalnych i minimalnych na każdej krawędzi. Dodatkowo na
rysunku jest układ osi, schematyczne zbrojenie oraz poziomy w przypadku ławy.
Rysunek można przybliżać za pomocą kółka myszy oraz przesuwać trzymając lewy
przycisk myszy. Przydaje się to w przypadku, gdy opisy są blisko siebie i są trudne
do odczytania. Optymalne położenie rysunku w oknie najłatwiej uzyskać akceptując
ponownie dowolny parametr klawiszem `Enter` lub przyciskiem `Oblicz`.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/dc16b0ac-c4fb-4cc5-8e7b-e8ca68ddb243)

**Ramka przycisków po prawej** stronie zawierająca następujące funkcje: 
- Przycisk `Oblicz` aktualizuje rysunek i część z wynikami dla zadanych wartości.
- Przycisk `Dobierz` w sposób iteracyjny szuka geometrii fundamentu, która spełnia
wszystkie warunki sprawdzenia podłoża (nie dopuszcza odrywania). Jako kryterium
optymalnej geometrii przyjęto najmniejszą powierzchnię podstawy. W przypadku stopy
fundamentowej maksymalną proporcję długości do szerokości można zmienić w oknie
`Ustawienia`. Obliczenia są przeprowadzane w tle i przy obwiedni sił,
dużych wartościach sił lub słabym podłożu mogą trwać dłuższą chwilę.
- Przycisk `Podłoże` otwiera ponownie wcześniej opisane okno [Podłoże](#podłoże).
- Przycisk `Obciążenia` otwiera okno z wartościami obliczeniowych sił skupionych i
rozłożonych. Po włączeniu opcji `Własne` wszystkie wartości obciążeń można
dowolnie modyfikować oraz można wybrać wariant z obwiedni sił. Przycisk `Zeruj`
zeruje wszystkie obciążenia. Ponowne wciśnięcie przywraca wartości przed zerowaniem.
- Przycisk `Ustawienia` zawiera dodatkowe opcje obliczeniowe oraz konfigurację wartości
parametrów takich jak dane materiałowe i częściowe współczynniki bezpieczeństwa (które
można przywrócić do wartości normowych przyciskiem `NA.2`). W dodatkowych opcjach
obliczeniowych można wybrać, czy podłoże sprawdzane jest w warunkach pracy
`z odpływem` czy `bez odpływu`. W przypadku wybrania opcji `bez odpływu` należy podać
wartość wytrzymałości gruntu na ścinanie. `Metoda wydzielonych wsporników` dotyczy
sposobu wyznaczania momentów gnących do wymiarowania zbrojenia stopy. Włączenie opcji
`Pokazuj sprawdzenie zerowych warunków i minimalne zbrojenie` powoduje, że w ramce z
wynikami są pokazywane również warunki, gdy stopień wytężenia wynosi 0% oraz sprawia,
że fundament jest liczony jako żelbetowy. Osiadanie jest porównywane z wartością
podaną w `Graniczna wartość osiadania`. `Maksymalna proporcja L:B w "Dobierz"` służy
do wybrania maksymalnej proporcji długości do szerokości stopy fundamentowej
szukanej funkcją `Dobierz`. Wybranie `1:1` sprawia, że stopa w rzucie jest kwadratowa.
- Przycisk `Do schowka` kopiuje listę z notką obliczeniową do schowka. Po zamknięciu
modułu schowek zostaje wyczyszczony.
- Przycisk `Do Worda` otwiera nowy dokument zawierający notkę obliczeniową z rysunkiem
Ponowne naciśnięcie przycisku powoduje dopisanie wyników do otwartego dokumentu.
W przypadku posiadania innego pakietu niż *Microsoft Office*, jest tworzony i otwierany
nowy plik *Nazwa_zadania.STO.DOCX* w lokalizacji zadania.
- Przycisk `Aktualizuj` sprawdza, czy jest uruchomiona aktualna wersja modułu oraz w
razie potrzeby umożliwia pobranie i aktualizację do najnowszej wersji. Plik instalacyjny
jest pobierany w tle, trzeba poczekać na jego pobranie. Następnie moduł jest wyłączany
i uruchamia się instalacja. Zaleca się zamknięcie programu **ABC** przed instalacją.
- Przycisk `Zamknij` zapisuje wyniki i zamyka moduł, skąd można przejść do wyboru
kolejnego miejsca. W przypadku stóp fundamentowych miejsca zaprojektowane będą opisane
*Stopa*, a podpowiadane będzie kolejne miejsce z największą reakcją pionową.
- Zaznaczenie opcji `Domyślne` powoduje, że po zamknięciu modułu bieżące ustawienia
zostają zapisane jako domyślne do wymiarowania kolejnych miejsc.

![image](https://github.com/pkpkbud/fundamenty/assets/55211992/e88f781a-19ab-42cf-b5f1-507f2f21484c)

## Kontakt

Wszelkie sugestie i ewentualne błędy w programie można zgłaszać poprzez e-mail
lub serwis [GitHub](https://github.com/pkpkbud/fundamenty/issues).

**PKPKBUD Paweł Kowalski Projektowanie Konstrukcji Budowlanych**\
NIP: 2220810920, REGON: 522155974

tel. 603 088 626\
e-mail: <pkpkbud@gmail.com>
