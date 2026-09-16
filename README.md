# Python Data Analysis Notes

Uporządkowany zbiór notatników Jupyter dokumentujących naukę analizy danych w Pythonie — od podstaw języka i NumPy, przez pełne API pandas (`Series`, `DataFrame`, `MultiIndex`, `groupby`, łączenie tabel), po wizualizację, szeregi czasowe i biblioteki modelujące.

70 notatników ułożonych w spójną, numerowaną ścieżkę nauki (01–70), z jednym tematem na plik. Każdy notatnik łączy działający kod z krótkim, własnym komentarzem wyjaśniającym *dlaczego* dana metoda działa tak, a nie inaczej — nie jest to transkrypcja żadnego konkretnego kursu.

## Zakres materiału

- **Podstawy** — Python, wbudowane struktury danych, NumPy
- **Pandas Series** — tworzenie, indeksowanie, sortowanie, filtrowanie, modyfikacja
- **Pandas DataFrame** — pełny zestaw operacji: czyszczenie, typy danych, filtrowanie, edycja, przebudowa indeksu
- **MultiIndex i tabele przestawne** — hierarchiczne indeksy, `pivot_table()`, `stack()`/`unstack()`, `melt()`
- **Grupowanie i agregacja** — `groupby()`, `agg()`, operacje na obiekcie grupującym
- **Łączenie danych** — `concat()`, `join()`, `merge()` (wszystkie warianty `how=`)
- **Wizualizacja** — `plot()` i jego parametry, wykresy kołowe, słupkowe, pudełkowe, histogramy, scatter
- **Zagadnienia zaawansowane** — szeregi czasowe, biblioteki modelujące (`patsy`, `statsmodels`), zaawansowany NumPy, iPython

## Spis treści

### Część I – Podstawy Pythona i NumPy

- [Podstawy Pythona](01_podstawy_pythona.ipynb)
- [Wbudowane struktury danych, funkcje i pliki](02_wbudowane_struktury_danych.ipynb)
- [NumPy – tablice i wektory](03_numpy_tablice_i_wektory.ipynb)

### Część II – Pandas: Series

- [Wprowadzenie do Pandas (Series i DataFrame)](04_pandas_wprowadzenie.ipynb)
- [Pierwsze kroki w Pandas](05_pandas_pierwsze_kroki.ipynb)
- [Series – podstawy](06_series_podstawy.ipynb)
- [Filtrowanie danych w Series](07_series_filtrowanie.ipynb)
- [Import danych do Series](08_series_import_danych.ipynb)
- [Sortowanie Series](09_series_sortowanie.ipynb)
- [Sprawdzanie obecności elementu w Series](10_series_sprawdzanie_elementu.ipynb)
- [Pobieranie danych po indeksie](11_series_pobieranie_po_indeksie.ipynb)
- [Pobieranie danych po wartości/etykiecie](12_series_pobieranie_po_wartosci.ipynb)
- [reindex() i intersection()](13_series_reindex_intersection.ipynb)
- [Określanie indeksu podczas importu](14_series_indeks_podczas_importu.ipynb)
- [Więcej metod Series](15_series_wiecej_metod.ipynb)
- [Modyfikacja Series](16_series_modyfikacja.ipynb)
- [Metoda map()](17_series_metoda_map.ipynb)

### Część III – Pandas: DataFrame

- [DataFrame – wprowadzenie](18_dataframe_wprowadzenie.ipynb)
- [Metody i atrybuty DataFrame](19_dataframe_metody_i_atrybuty.ipynb)
- [Pobieranie danych z DataFrame](20_dataframe_pobieranie_danych.ipynb)
- [Dodawanie i usuwanie kolumn](21_dataframe_dodawanie_usuwanie_kolumn.ipynb)
- [Czyszczenie danych – dropna()](22_dataframe_czyszczenie_dropna.ipynb)
- [Czyszczenie danych – fillna()](23_dataframe_czyszczenie_fillna.ipynb)
- [Sortowanie danych w DataFrame](24_dataframe_sortowanie.ipynb)
- [Kontrola typów w DataFrame](25_dataframe_kontrola_typow.ipynb)
- [Ranking](26_dataframe_ranking.ipynb)
- [Filtrowanie danych w DataFrame](27_dataframe_filtrowanie.ipynb)
- [Metody where() i query()](28_dataframe_where_query.ipynb)
- [isin(), isnull(), notnull(), between()](29_dataframe_isin_isnull_between.ipynb)
- [Duplikaty w DataFrame](30_dataframe_duplikaty.ipynb)
- [Edycja nazw kolumn/indeksu, kopiowanie DataFrame](31_dataframe_edycja_nazw_kopiowanie.ipynb)
- [Modyfikacja danych w DataFrame](32_dataframe_modyfikacja_danych.ipynb)
- [Dodawanie i usuwanie wierszy](33_dataframe_wiersze_dodawanie_usuwanie.ipynb)
- [Przebudowa indeksu](34_dataframe_przebudowa_indeksu.ipynb)
- [Operacje na kolumnach tekstowych](35_dataframe_operacje_tekstowe.ipynb)
- [Przygotowanie danych po imporcie](36_dataframe_przygotowanie_po_imporcie.ipynb)

### Część IV – MultiIndex i tabele przestawne

- [MultiIndex – wprowadzenie](37_multiindex_wprowadzenie.ipynb)
- [Wyszukiwanie danych za pomocą MultiIndex](38_multiindex_wyszukiwanie.ipynb)
- [Transpozycja](39_multiindex_transpozycja.ipynb)
- [Metoda swaplevel()](40_multiindex_swaplevel.ipynb)
- [Metody stack() i unstack()](41_multiindex_stack_unstack.ipynb)
- [Pivot table – część 1](42_pivot_table_czesc_1.ipynb)
- [Pivot table – część 2](43_pivot_table_czesc_2.ipynb)
- [Pivot table – część 3](44_pivot_table_czesc_3.ipynb)
- [Konwersja pivot table do DataFrame metodą melt()](45_pivot_table_melt.ipynb)
- [Metadane MultiIndex](46_multiindex_metadane.ipynb)

### Część V – Grupowanie i agregacja

- [Grupowanie danych](47_groupby_grupowanie_danych.ipynb)
- [Metoda groupby()](48_groupby_metoda.ipynb)
- [Agregacja danych](49_groupby_agregacja_danych.ipynb)
- [Grupowanie a MultiIndex](50_groupby_a_multiindex.ipynb)
- [Metoda agg()](51_groupby_metoda_agg.ipynb)
- [Przetwarzanie obiektu groupby](52_groupby_przetwarzanie_obiektu.ipynb)

### Część VI – Łączenie danych

- [Łączenie tabel – join() i merge()](53_laczenie_tabel_join_merge.ipynb)

### Część VII – Odczyt, zapis i przetwarzanie danych

- [Odczyt i zapis plików, formaty plików](54_odczyt_i_zapis_plikow.ipynb)
- [Czyszczenie i przygotowywanie danych](55_czyszczenie_i_przygotowywanie_danych.ipynb)
- [Przetwarzanie i łączenie danych](56_przetwarzanie_i_laczenie_danych.ipynb)

### Część VIII – Wizualizacja danych

- [Wizualizacja danych – wprowadzenie](57_wizualizacja_danych_wprowadzenie.ipynb)
- [Metoda plot()](58_wykresy_metoda_plot.ipynb)
- [Parametry metody plot()](59_wykresy_parametry_plot.ipynb)
- [Formatowanie wykresu](60_wykresy_formatowanie.ipynb)
- [Wykres kołowy](61_wykresy_kolowy.ipynb)
- [Wykres słupkowy, pudełkowy i histogram](62_wykresy_slupkowy_pudelkowy_histogram.ipynb)
- [Wykresy scatter, hexbin i area](63_wykresy_scatter_hexbin_area.ipynb)

### Część IX – Zagadnienia zaawansowane

- [Agregacje danych i operacje na grupach](64_agregacje_i_operacje_na_grupach.ipynb)
- [Szeregi czasowe](65_szeregi_czasowe.ipynb)
- [Biblioteki modelujące](66_biblioteki_modelujace.ipynb)
- [Przykłady analizy danych](67_przyklady_analizy_danych.ipynb)
- [Zaawansowane zagadnienia w NumPy](68_numpy_zagadnienia_zaawansowane.ipynb)
- [iPython](69_ipython.ipynb)
- [Import danych z URL (dodatek)](70_import_danych_z_url_dodatek.ipynb)

## Struktura repozytorium

Płaska struktura — 70 notatników (`01_...ipynb`–`70_...ipynb`) w jednym katalogu, numerowanych zgodnie z kolejnością nauki (patrz spis treści wyżej), nie z kolejnością powstawania plików.

## Jak z tego korzystać

Notatniki powstawały w Google Colab i część z nich wczytuje dane z `/content/...` (lokalny dysk sesji Colab) lub z zamontowanego Google Drive. Żeby uruchomić je samodzielnie:

- **Google Colab** — wgraj notatnik i plik danych (CSV wymieniony w pierwszych komórkach) do sesji Colab, albo podmień ścieżkę `read_csv(...)` na własną.
- **Lokalnie** — potrzebne `pandas`, `numpy`, `matplotlib` (`pip install pandas numpy matplotlib`); ścieżki do plików CSV trzeba dopasować do lokalizacji na dysku.

Same pliki danych (CSV) nie są częścią repozytorium — to publicznie dostępne zbiory ćwiczeniowe (m.in. Pokemon, McDonald's menu, Northwind, dane pogodowe), używane wyłącznie do nauki.

## Uwaga o materiałach źródłowych

To notatki własne, pisane w trakcie nauki na podstawie różnych źródeł (kursów online, dokumentacji pandas/NumPy, książki *Python for Data Analysis*). Repozytorium zawiera wyłącznie własny kod i własne opisy — bez zrzutów ekranu, materiałów wideo ani innych treści objętych prawami autorskimi kursów, z których korzystano w trakcie nauki.

## Licencja

Kod i notatki własne — [MIT](LICENSE). Nie dotyczy to zewnętrznych zbiorów danych używanych w przykładach — te podlegają licencjom swoich źródeł.
