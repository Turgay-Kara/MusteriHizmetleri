> # Metin Sınıflandırma Modeli 

Bu proje, metin verilerini sınıflandırmak için bir makine öğrenmesi modelinin geliştirilmesini ve uygulanmasını içermektedir.   
Kullanıcıdan alınan bir metin mesajı, önceden eğitilmiş bir modelle sınıflandırılmaktadır.   
Proje, Python'da `pandas`, `sklearn`, ve `CountVectorizer` gibi kütüphaneler kullanılarak geliştirilmiştir.  

## Özellikler:
+  **Stopword Temizleme:** Metin verisindeki anlam taşımayan kelimeler (stopwords) temizlenir.  
+  **Özellik Çıkartma:** Metinlerden en sık kullanılan 50 özellik çıkarılır.  
+  **Model Eğitimi ve Testi:** Random Forest sınıflandırıcı kullanılarak metin sınıflandırma modeli eğitilir ve doğruluk skoru hesaplanır.  
+  **Kullanıcı Girişi:** Kullanıcıdan alınan metin, model tarafından sınıflandırılır.

## Gereksinimler:
Python ortamında gerekli kütüphanelerin yüklenmesi: `pip install pandas scikit-learn`

## Kullanım:
Kullanıcıdan alınan metinle sınıflandırma yapmak için kodu çalıştırın.
