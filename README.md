# Statystyczna Analiza Danych II (SAD 2) 📊

Repozytorium zawiera materiały, skrypty R oraz opracowania zadań realizowanych w ramach przedmiotu **Statystyczna Analiza Danych II**. Projekt ma na celu praktyczne wykorzystanie metod statystyki wielowymiarowej do eksploracji i interpretacji rzeczywistych zbiorów danych.

## 📁 Zawartość repozytorium

### 🔹 Lekcja 1: Analiza korespondencji (CA)
Pierwszy moduł skupia się na badaniu zależności między zmiennymi kategorycznymi na przykładzie danych dotyczących koloru oczu i włosów.

**Zakres analizy:**
* Budowa macierzy kontyngencji.
* Test niezależności $\chi^2$ (poziom istotności $\alpha = 0,05$).
* Obliczanie mas wierszy i kolumn oraz profili brzegowych.
* Wizualizacja za pomocą mapy korespondencji (biplot).

**Kluczowe wnioski:**
* Odrzucenie hipotezy $H_0$ o niezależności cech ($p < 2.2 \times 10^{-16}$).
* Silna asocjacja cech jasnych (Blond/Niebieskie) oraz ciemnych (Brunatne/Ciemne).



---

## 🛠️ Wymagane pakiety R
Aby uruchomić skrypty zawarte w repozytorium, należy zainstalować następujące biblioteki:
```r
install.packages(c("vcd", "ca", "MASS", "psych", "ggplot2", "readxl"))
