# Jak zbudować APK z telefonu

1. Załóż konto GitHub i utwórz nowe repozytorium, np. FreeRepairAlert.
2. Wgraj CAŁĄ zawartość tego projektu do repozytorium (razem z folderem .github).
3. Wejdź w zakładkę Actions.
4. Uruchom workflow „Build Android APK” przez „Run workflow”.
5. Po zakończeniu otwórz zakończony workflow.
6. Na dole znajdziesz „Artifacts” → „FreeRepairAlert-debug”.
7. Pobierz ZIP z artefaktem i wypakuj go. W środku będzie plik APK.
8. Otwórz APK na telefonie i zezwól na instalację z tego źródła, jeśli Android o to poprosi.

Uwaga:
- To buduje APK debug, nie podpisaną wersję sklepową.
- Aplikacja nadal korzysta z okresowego sprawdzania w tle; Android może opóźniać takie zadania.
- Struktura stron Adverts/DoneDeal może się zmieniać i wtedy parser może wymagać aktualizacji.
