Repozytorium zawiera skrypty z kodem użytem do analizy przedstawionej w pracy inżynierskiej o tytule "Identyfikacja oddziaływań neutrin w detektorach ciekłoargonowych metodami uczenia maszynowego".
- plik eskport_danych.ipynb służy do wyeksportowania danych z generatora GENIE do pliku .csv w formie w jakiej są używane w dalszej analizie
- plik statystyka.ipynb służy do tworzenia wykresów i histogramów charakteryzujących dane zebrane w pliku .csv w tym histogram krotności cząstek w oddziaływanaich, korelacje między parametrami oraz porównanie rozkładów każdego z parametrów dla sygnału i tła
- plik model.ipynb zawiera funkcje służące do selekcji danych, przygotowania zbiorów treningowych i testowych oraz samego treningu modelu i analizy wyników (krzywa ROC, confusion matrix i rozkład czystości oraz efektywności)

Dodatkowo w repozytorium zawarto pliki otrzymane w wyniku generacji 1 000 000 oddziaływań kwazielastycznych neutrin taonowych i mionowych w zakresie energii 0.1-50 GeV w detektorze ciekłoargonowym
