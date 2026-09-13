# Symulator Polskiego Bezrobocia 3.0.13

Wydanie Windows z 13 września 2026. Gotowa gra znajduje się w samodzielnym `Updater.exe`; muzyka, modele i pozostałe zasoby są w środku. Można przenieść sam plik. Przy aktualizacji zachowaj istniejące foldery `Saves` i `PlayerMusic`.

## Dostawca Jedzenia

| Zasada | Działanie |
| --- | --- |
| Włączenie | Ustawienia → Rozrywka → Dostawca Jedzenia; domyślnie wyłączony |
| Częstotliwość | Losowo co 4–8 minut aktywnej gry; po zakończeniu lub anulowaniu ponowne oczekiwanie |
| Wynagrodzenie | 5,00–15,00 zł za ukończone zamówienie |
| Przyjmowanie | Klawisz **1**, dokładnie 5 sekund od pojawienia się powiadomienia |
| Limit | Jedna oczekująca oferta albo jedno przyjęte zlecenie |
| Panel | Kwota, mapa trasy, miejsce odbioru, adres, mieszkanie, piętro i zawartość paczki |
| Odbiór | Widoczna paczka w Groszku, Delikatesach albo u Pana Zdzisia; podejdź i użyj **E** |
| Transport | Paczka widoczna w rękach; po wejściu do samochodu znajduje się na siedzeniu |
| Doręczenie | Wejdź drzwiami i schodami do bloku, otwórz mieszkanie i użyj **E** przy właściwym lokatorze |
| Zasięg | Wszystkie 14 bloków, losowe piętro i mieszkanie; budynki rotują |
| Mapa | Pomarańczowy punkt: odbiór; zielony kwadrat: adres dostawy; biały punkt: gracz |
| Szczegóły/anulowanie | **TAB → Dostawa • szczegóły zlecenia**; pełna mapa pod **M** |

Menu i pauza zatrzymują czas oferty. Pościg blokuje przyjmowanie nowych zleceń. Wyłączenie trybu nie kasuje przyjętej paczki. Zapis zachowuje zlecenie i terminy, więc restart nie losuje natychmiast nowej pracy. Starszy już przyjęty kurs Ubera można dokończyć; nowe oferty dotyczą jedzenia. Klawisz 1 nie otwiera telefonu.

## Samochody i policja

- Kradzież rozpoczyna **3 z 5 gwiazdek**. Mocne uderzenie w patrol podnosi poziom, maksymalnie do pięciu.
- Policjanci ścigają pieszego pieszo, a kierowcę radiowozem. Radiowóz korzysta z dróg; jego dwóch funkcjonariuszy może wysiąść, gdy gracz opuści samochód. Cztery dodatkowe patrole chodzą po osiedlu.
- Gubienie pościgu wymaga braku widoczności i oddalenia się ponad **18 m pieszo / 32 m autem**. Czas nieprzerwanego ukrycia wynosi **12 + 4 × liczba gwiazdek sekund**: 20 sekund przy dwóch gwiazdkach. Miganie gwiazdek i pasek pokazują postęp. Na oczach policji pościg się nie kończy.
- Po utracie widoczności policja sprawdza ostatnią widzianą pozycję. Po zgubieniu otrzymujesz 40 sekund osłony przed ponownym rozpoznaniem. Nierozliczona kradzież może ponownie ujawnić się z bliska przy patrolu.
- Zatrzymanie następuje po 1,5 sekundy bliskiego kontaktu. W aucie policja musi zbliżyć się do powoli jadącego lub zatrzymanego pojazdu.
- **Za kradzież nie ma więzienia.** Niesprzedane kradzione auto zostaje skonfiskowane. Policja odbiera wyłącznie zapisany zarobek ze sprzedaży kradzionych aut, najwyżej do dostępnego salda. Każdy taki zarobek rozlicza raz.
- Przykład: sprzedaż za **200 zł** oznacza odebranie **200 zł**; jeśli pozostało 80 zł, policja odbierze 80 zł. Saldo nie spada poniżej zera. Za niesprzedane auto nie pobiera ceny sklepowej.
- Mirek skupuje kradzione auta za **5%** wartości, a legalne za **20%**. Każde auto musi dodatkowo odczekać **180 sekund aktywnej gry** od zakupu lub kradzieży. Pięć cen zakupu: 1000, 1800, 2500, 3500 i 5000 zł. Sprzedaż wymaga przyprowadzenia auta, zgubienia pościgu i zakończenia oczekiwania.

Ruch obejmuje dziesięć stale symulowanych aut. Hamują według przeszkód na swoim pasie i odstępu, pokazują światła hamowania oraz kolejno opuszczają skrzyżowania. Gracz na chodniku i samochód na przeciwnym pasie nie blokują ich jazdy. Piesi przechodzą po pasach. Nadal nie ma sygnalizacji ani mandatów za czerwone światło.

## Grafika i pozostałe funkcje

Asfalt, płyty chodnikowe, tynki i trawa mają mapy koloru, normalnych i chropowatości 1K z Poly Haven. Użyte zasoby CC0: **Asphalt 01** (Charlotte Baglioni, Dario Barresi), **Concrete Pavement** (Charlotte Baglioni), **Plastered Wall** i **Sparse Grass** (Amal Kumar). Mipmapy, filtrowanie anizotropowe i mapowanie trójpłaszczyznowe ograniczają migotanie oraz rozciąganie. Mniejszy bias cieni ogranicza ich widoczne odsunięcie od obiektów. Modele PSX Style Cars autorstwa **GGBotNet** zachowują styl gry; tekstury aut mają mipmapy i gładszy filtr. Piesi używają modelu **Man** autorstwa Polygonal Mind z Poly Pizza, CC0, z `Game/assets/people/CREDITS.txt`. Autorzy są w przewijanych creditsach i plikach licencji.

Nowy układ HUD rozdziela dostawę, gwiazdki, prędkościomierz, minimapę i cel fabularny. Zachowane są: butelkomaty z przeciąganiem i sekundową animacją, kaucja 1 zł za szkło / 0,50 zł za PET i puszki, przeszukiwanie koszy, ulepszenia, dzień i noc, radio z `PlayerMusic`, Lotto, wnętrza i schody, zadania, osiągnięcia oraz zapis postępów. Areszt po spaniu na ławce pozostaje osobną mechaniką.

Gra sprawdza numer wersji przy zwykłym uruchomieniu. Brak internetu nie blokuje rozgrywki. Pytanie o zaufanie certyfikatowi developera zachowuje odpowiedzi Tak i Nie; wybór Nie nie zmienia zaufanych certyfikatów. Sam EXE ma manifest UAC.

## Orientacyjne wymagania sprzętowe

| Element | Podstawowa konfiguracja | Zalecana konfiguracja |
| --- | --- | --- |
| System | Windows 10/11, 64-bit | Windows 10/11, 64-bit |
| Procesor | x64, SSE4.2, 2 rdzenie | x64, SSE4.2, 4 rdzenie |
| RAM | 4 GB | 8 GB |
| Grafika | OpenGL 3.3, około 1 GB pamięci graficznej | Dedykowana, OpenGL 3.3, 2 GB pamięci graficznej |
| Miejsce | 500 MB wolnego | 1 GB wolnego, SSD |
| Punkt wyjścia ustawień | 1280 × 720, niskie | 1920 × 1080, średnie |

To szacunki dla gry, a nie potwierdzone progi płynności lub obietnica FPS. Własne MP3 wymagają dodatkowego miejsca. Wymóg SSE4.2 dla eksportu x64 i obsługa OpenGL 3.3 wynikają z [dokumentacji silnika Godot 4.5](https://docs.godotengine.org/en/4.5/about/system_requirements.html#exported-godot-project). Pozostałe wartości są założeniami tego wydania. Informacje o wymaganiach są również w menu gry.

## Zapis i źródła

Postępy: `Saves/progress.sav`; ustawienia: `Saves/settings.json`; kopie poprzednich plików: `.bak`. Jeśli folder EXE jest niezapisywalny, gra używa `%APPDATA%\Godot\app_userdata\Symulator Polskiego Bezrobocia`. Zapis automatyczny działa co 30 sekund oraz po ważnych akcjach. **F5** zapisuje ręcznie.

Migracja zachowuje dotychczasowe pieniądze, przedmioty, osiągnięcia, auta i przyjętą pracę. Stary timer pościgu zastępują gwiazdki. W starszych zapisach, które nie odróżniały sprzedaży od konfiskaty, gra nie wymyśla historycznego zarobku do odebrania.

Kod do edycji znajduje się w `SPB-Gra-OpenSource/Game`. `SPB-Gra-OpenSource/Zbuduj.bat` buduje `Build/Updater.exe`. Klucz prywatny certyfikatu nie jest dołączony do źródeł. Pełna historia wydań jest w `CHANGELOG.txt` i w menu gry.
