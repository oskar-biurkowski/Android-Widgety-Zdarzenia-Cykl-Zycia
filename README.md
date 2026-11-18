# Projekt: BmiApp (Android M02 – Widgety, zdarzenia, cykl życia)

Kalkulator BMI stworzony w Android Studio przy użyciu języka Java (minimum SDK 26).

## Struktura projektu
- `MainActivity.java`: Obsługa formularza, walidacji (`setError`), obliczeń BMI, oraz zachowania stanu przy obrocie ekranu (`onSaveInstanceState`).
- `activity_main.xml`: Układ `LinearLayout` z polami `EditText`, `CheckBox`, przyciskami oraz dynamicznym `TextView`.
- `strings.xml`: Zbiór tekstów oraz komunikatów błędów interfejsu.

## Uruchomienie
1. Otwórz folder projektu w Android Studio.
2. Poczekaj na zakończenie synchronizacji Gradle.
3. Uruchom aplikację na emulatorze lub fizycznym urządzeniu (zielony trójkąt ▶).
