# Tytuł Projektu: Klasyfikacja Samochodów za pomocą Głębokiego Uczenia - Porzucone

## Status
Przerwany - Muszę znaleźć innego dataseta, bo ten (od Stanforda) jest źle ustrukturyzowany. Konwencja nazewnictwa do odpowiednich plików graficznych jest kompletnie inna w pliku .mat aniżeli w realnych ścieżkach na dysku. Próbowałem zmienić konwencję nazewnictwa odpowiednich plików poprzez augmentację danych. Niestety wygląda na to iż ten sposób również nie działa ponieważ klasy (modele) samochodów są podpięte pod złe zdjęcia.

## Opis
Celem tego projektu jest stworzenie modelu uczenia maszynowego, który jest w stanie automatycznie klasyfikować różne marki i modele samochodów na podstawie zdjęć. Projekt wykorzystuje techniki głębokiego uczenia i jest zbudowany na bazie konwolucyjnych sieci neuronowych (CNN).

## Dane
Zestaw danych składa się z tysięcy zdjęć samochodów, pogrupowanych według marki i modelu. Każde zdjęcie jest etykietowane, co umożliwia nadzorowane uczenie modelu. **Uwaga**: Aktualne wyniki nie są adekwatne ze względu na błędną strukturę pliku .mat dostarczonego przez Stanford. Ścieżki do plików są źle przypisane, co wymaga znalezienia innego zestawu danych lub naprawienia obecnego.

## Technologie
- Python
- TensorFlow/Keras
- OpenCV (dla przetwarzania obrazów)

## Zrealizowane Funkcje
- **Przetwarzanie Danych**: Obróbka i przygotowanie zdjęć do treningu i testowania modelu.
- **Augmentacja Danych**: Zastosowanie różnych technik augmentacji danych w celu zwiększenia różnorodności zestawu treningowego.
- **Budowa Modelu**: Projekt i implementacja architektury CNN.

## Planowane Funkcje
- Optymalizacja Modelu: Dalsze dostosowanie i tuninguje parametrów modelu.
- Walidacja i Testowanie: Ocena wydajności modelu na zestawie danych testowych.
- Interfejs Użytkownika: Prosty interfejs użytkownika, który pozwala na przesyłanie zdjęć do klasyfikacji.

## Wyzwania
- Poprawa dokładności modelu
- Znalezienie optymalnej architektury sieci
- Zapewnienie efektywnego przetwarzania danych w czasie rzeczywistym

## Wyniki
Projekt ma na celu osiągnięcie jak najwyższej dokładności w klasyfikacji samochodów, co zostanie zmierzone za pomocą różnych metryk, takich jak dokładność, precyzja, czułość i F1-score (planowane).

## Zastosowania
Model może być używany w różnych aplikacjach, od automatycznej klasyfikacji zdjęć w bazach danych po zastosowania w branży motoryzacyjnej, takie jak automatyczne rozpoznawanie pojazdów na parkingach czy w systemach monitoringu ruchu drogowego.
