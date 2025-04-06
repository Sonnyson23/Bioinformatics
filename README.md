# Bioinformatics
Meme Kanseri Alt Tipleri Arasındaki Gen Ekspresyon Farklılıklarının Analizi
Özet
Bu analiz, 30 meme kanseri hücre hattında gen ekspresyon verilerini kullanarak ER+, HER2. ve TNBC alt tipleri arasındaki moleküler farklılıkları incelemiştir. Diferansiyel gen ekspresyon analizi, fonksiyonel analiz ve makine öğrenmesi yaklaşımları kullanılarak alt tiplere özgü gen imzaları ve potansiyel biyobelirteç adayları belirlenmiştir.

Temel Bulgular
ER+ vs. TNBC karşılaştırmasında 910 gen anlamlı diferansiyel ekspresyon göstermiştir.
HER2. vs. TNBC karşılaştırmasında 1 gen anlamlı diferansiyel ekspresyon göstermiştir.
ER+ vs. HER2. karşılaştırmasında 95 gen anlamlı diferansiyel ekspresyon göstermiştir.
Alt tiplere özgü gen imzaları belirlenmiştir: ER+ için 847 gen, HER2. için 1 gen ve TNBC için 0 gen.
GO ve KEGG analizleri, alt tipler arasındaki biyolojik farklılıkları ortaya koymuştur.
Random Forest sınıflandırıcı modeli, % 87.5 doğruluk oranı ile alt tipleri ayırt edebilmiştir.
Dosyalar
differential_expression_summary.csv: Diferansiyel ekspresyon analizi özeti
significant_genes_*.csv: Anlamlı diferansiyel eksprese olan genler
er_specific_genes.csv, her2_specific_genes.csv, tnbc_specific_genes.csv: Alt tiplere özgü gen imzaları
go_results_*.csv, kegg_results_*.csv: Fonksiyonel analiz sonuçları
random_forest_gene_importance.csv: Sınıflandırıcı model için önemli genler
biomarker_candidates_data.csv: Potansiyel biyobelirteç adayları
all_figures.pdf: Tüm analiz grafikleri
Sonuç
Bu analiz, meme kanseri alt tipleri arasındaki moleküler farklılıkları kapsamlı bir şekilde karakterize etmiş ve potansiyel biyobelirteç adayları önermiştir. Belirlenen gen imzaları, alt tiplerin moleküler temelini anlamak ve kişiselleştirilmiş tedavi yaklaşımları geliştirmek için değerli bilgiler sunmaktadır.
