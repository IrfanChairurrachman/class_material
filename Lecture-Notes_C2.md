
# Summary Naive Bayes

- Menghitung peluang kejadian dependen -> P(A|B)
    + A → Target
    + B → Prediktor
  
- Karakteristik Naive Bayes:
    + Antara prediktor dengan target dependen
    + Antar prediktor independen
    + Cocok untuk prediktor yang kategorik, karena mengitung peluang / frekuensi kemunculan
    
- Kelebihan:
    + Komputasi cepat, hanya menghitung peluang dari tabel frekuensi
    
- Kekurangan:
    + **Skewness due to scarcity**, ketika salah satu level di prediktor tidak/jarang muncul di salah satu kelas target
    + Solusi: **Laplace Smoothing**, tambah 1 frekuensi di tiap kelas prediktor (sebaiknya selalu dilakukan)