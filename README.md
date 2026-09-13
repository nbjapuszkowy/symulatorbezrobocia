# Symulator Polskiego Bezrobocia — kod źródłowy 3.0.13

Rozpakuj cały ZIP. Edytuj `Game/*.gd` albo otwórz `Game/project.godot` w dołączonym Godocie (`Tools/Godot/Godot_v4.5.1-stable_win64.exe`). Kliknij `Zbuduj.bat`. Gotowa gra: `Build/Updater.exe`.

Dołączono Godot 4.5.1, konsolę i szablon eksportu Windows x64. Systemowy .NET Framework kompiluje małe narzędzia C#. BAT nie uruchamia testów. Zachowuje `Build/Saves` i `Build/PlayerMusic`.

Główne pliki: `Game/main.gd` — interfejs i rozgrywka; `world.gd` — mapa i modele pieszych; `state.gd` — postępy i ekonomia; `vehicle_system.gd` — samochody; `jobs.gd` — dostawy; `delivery_card.gd` — panel oferty; `pursuit_hud.gd` — gwiazdki; `surface_materials.gd` — tekstury; `update_check.gd` — aktualizacje. `Tools/DiscordBridge.cs` — Discord.

Kod własny jest na MIT (LICENSE). Silnik, font i modele mają licencje w Licenses i Game/assets/cars/CREDITS.txt. MIT nie obejmuje nagrań muzycznych, logo ani materiałów innych autorów.

Prywatny klucz podpisu nie jest dołączony. Na koncie autora BAT podpisze EXE istniejącym certyfikatem. Bez klucza powstanie niepodpisany EXE. Gra zachowuje manifest UAC.

Aktualizacje: numer wydania ustaw w `Game/project.godot`, `Game/export_presets.cfg`, `Game/main.gd` i `Game/update_check.gd`. Zbuduj EXE i dodaj `Updater.exe` do nowego wydania w https://github.com/nbjapuszkowy/symulatorbezrobocia/releases. Po publikacji zmień `version` w `SPB-aktualizacje.json` w głównej gałęzi repozytorium. Od 3.0.12 gra sprawdza ten plik przy zwykłym starcie i proponuje otwarcie najnowszego wydania GitHub. W edytorze i diagnostyce nie odpytuje internetu. Gracze 3.0.12 i starszych muszą pobrać 3.0.13 ręcznie. Aktualizacja polega na zastąpieniu samego EXE z zachowaniem `Saves` i `PlayerMusic`.

Zmiany i wymagania wydania: SPECYFIKACJA.md. Pełna historia: CHANGELOG.txt.
