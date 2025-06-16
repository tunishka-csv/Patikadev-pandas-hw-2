# 🚢 Kız Başına Patika.dev Veri Analizi Bootcamp Ödevleri - Pandas ile Titanik Veri Seti (hw-2)
Kız Başına - Patika.dev Veri Analizi Bootcamp'i kapsamında, Titanik veri seti ile çeşitli analizlerin yapıldığı bir projedir. Analizlerin açıklaması ve ödev kapsamı aşağıda açıklanmıştır.

## 📌Notlar
Analizler Jupyter Notebook (Colab) üzerinde yapılmıştır. Kodun lokalde doğru çalışması için Titanic_dataset.csv dosyasının uygun path'inin eklenmesi gerekmektedir.

## Odev 2 pandas ödevi

Titanic veri seti altında aşağıdaki soruları çözmenizi istiyoruz. Her sorunun markdown olarak yazılması ve altına da kodunun yazılması daha okunaklı kılar kodlarınızı.
1.	Kazada ölenlerin yaş ortalamasını bulunuz
2.	Kazada ölenlerin bilet fiyatlarının ortalamasını ve medyanını bulunuz
3.	Kazada ölen erkeklerin yaş ortalamasını bulunuz
4.	Kazada ölen Kadınların yaş ortalamasını bulunuz

5.	Kazadan kurtulanların yaş ortalamasını bulunuz
6.	Kazadan kurtulanların bilet fiyatlarının ortalamasını bulunuz
7.	Kazadan kurtulan toplam kişi sayısını bulunuz… 
(tüyo: len(df_titanic[(df_titanic.Survived==1)]   kodu ile de bu sayıya ulaşabilirsiniz.)

8.	10 yaşından küçüklerin bilet fiyatlarının medyan değerini bulunuz

9.	1.sınıf, 2.sınıf ve 3.sınıf bilet fiyatlarının ortalama ve medyanlarını karşılaştırınız. (Pclass değişkeni sınıfları barındırmaktadır.)

10.	Kazada ölen kadınların oranı ile erkeklerin oranını karşılaştırınız. (Örnek: erkekler için; ölen erkeklerin, erkek sayısına bölümü bu oranı vermektedir.

Veriseti üzerine:
Titanic veri seti üzerinden soruları çözeceğiz. Aşağıdaki tabloda sütunların açıklamaları mevcut.
Link: https://www.kaggle.com/c/titanic/data

