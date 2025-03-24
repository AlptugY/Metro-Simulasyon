Bu proje, metro ağı üzerinde BFS (Breadth-First Search) ve A\* (A-star)
algoritmalarını kullanarak en uygun rotayı bulmayı amaçlamaktadır.

BFS (Breadth-First Search) Amacı : En az aktarmalı rotayı bulmak.
Çalışma Mantığı : 1-Başlangıç istasyonundan başlayarak, komşu
istasyonlar sırayla keşfedilir. 2-Her bir istasyon ziyaret edilip, hangi
rotada hangi aktarmalar yapıldığı izlenir. 3-En az aktarmayı içeren rota
bulunduğunda, o rota döndürülür. 4-BFS, her istasyonun yalnızca bir kez
ziyaret edilmesini sağlar, bu da onu efektif ve hızlı yapar.

A\* (A-star) Amacı : En hızlı rotayı bulmak Çalışma Mantığı :
1-Başlangıçtan hedefe doğru, her adımda toplam süreyi hesaplar. 2-Ayrıca
her istasyonun hedefe olan mesafesini (heuristic) de göz önünde
bulundurur. 3-Heuristic kullanarak, hedefe en hızlı ulaşan yol
belirlenir. 4-A\*, öncelik kuyruğu (priority queue) kullanarak en uygun
rotayı seçer.
