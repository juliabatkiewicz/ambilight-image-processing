# ambilight-image-processing
Projekt z dziedziny przetwarzania obrazów wykonany w Pythonie. Zawiera implementację prostego algorytmu symulującego efekt ambilight oraz testowanie go na różnych mapach kolorów.

## Funkcjonalności i przebieg analizy
1. **Wczytanie obrazu testowego**: Pobranie i wyświetlenie obrazu bazowego.
2. **Analiza krawędziowa**: Wyodrębnienie pikseli z brzegów obrazu w celu obliczenia uśrednionej wartości koloru.
3. **Generowanie efektu ambilight**: Wygenerowanie jednolitych pasów kolorystycznych odpowiadających uśrednionym barwom z krawędzi.
4. **Testowanie map kolorów**: Sprawdzenie odporności i dokładności algorytmu poprzez aplikowanie różnych map kolorów na obraz testowy i obserwację wygenerowanego podświetlenia.

## Technologie i Biblioteki
Projekt został przygotowany w języku Python. W operacjach na macierzach obrazów i ich wizualizacji wykorzystano standardowe biblioteki do analizy danych i przetwarzania obrazów:
* `numpy` – do szybkich operacji matematycznych na macierzach.
* `matplotlib` – do wizualizacji obrazu, map kolorów oraz wygenerowanego efektu ambilight.

## Jak uruchomić projekt
1. Sklonuj repozytorium na swój dysk.
2. Upewnij się, że masz zainstalowane środowisko Python z pakietami wymienionymi wyżej.
3. Projekt był tworzony z myślą o środowisku Google Colab. Jeśli chcesz go tam uruchomić, wywołaj pierwszą komórkę z google.colab.files.upload() i wgraj pliki `text_image` oraz `test_image_grayscale`.
4. Aby uruchomić go lokalnie, wystarczy umieścić wyżej wymienione pliki w jednym folderze z notatnikiem i pominąć komórkę odpowiedzialną za upload.
5. Uruchamiaj kolejne komórki kodu.
