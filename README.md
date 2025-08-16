# PCOS-prediction-hypotheses
Testing hypotheses on health and lifestyle factors influencing PCOS in R. (Badanie hipotez dotyczących czynników zdrowotnych i stylu życia wpływających na ryzyko wystąpienia zespołu polistycznych jajników PCOS w R.)

## Opis projektu:
Celem badania była analiza danych medycznych dotyczących zespołu policystycznych jajników (PCOS) oraz sprawdzenie zależności pomiędzy czynnikami zdrowotnymi a występowaniem choroby.  

Projekt został zrealizowany w języku **R** na podstawie zbioru danych [PCOS Dataset (Kaggle)](https://www.kaggle.com/datasets/shreyasvedpathak/pcos-dataset). [Czerwiec 2023]

Projekt wykonany we współpracy.

---

## Hipotezy badawcze:
1. Wyższy wskaźnik BMI jest istotnie związany z występowaniem PCOS.  
2. Niewłaściwe wyniki hormonów (FSH, LH, prolaktyna, TSH) zwiększają prawdopodobieństwo rozpoznania PCOS.  
3. Nieregularne cykle menstruacyjne częściej występują u pacjentek z PCOS.  

Celem analizy było sprawdzenie, czy parametry zdrowotne mogą być pomocne w diagnostyce PCOS.  

---

## Etapy analizy:
1. **Wstępne czyszczenie danych:**  
   - usunięcie braków i błędów w danych
   - zmiana typów zmiennych 
   - przygotowanie danych do analizy

2. **Podstawowe statystyki opisowe:**  
   - charakterystyka populacji (wiek, BMI, regularność cykli)
   - rozkłady podstawowych parametrów hormonalnych 

3. **Analiza hipotez badawczych:**  
   - wizualizacje danych (histogramy, wykresy pudełkowe, wykresy punktowe) 
   - porównania pomiędzy grupami pacjentek z PCOS i bez PCOS

4. **Budowa modeli regresji:**  
   - **Model 1**: zależność pomiędzy BMI a występowaniem PCOS
   - **Model 2**: wpływ hormonów na ryzyko PCOS 
   - **Model 3**: związek nieregularności cyklu z PCOS 

5. **Wnioski:**  
   - BMI jest jednym z czynników powiązanych z PCOS. 
   - Parametry hormonalne mają istotny wpływ na diagnozę. 
   - Nieregularne cykle są częstsze u pacjentek z PCOS.
