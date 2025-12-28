# Veri Setleri Hakkında

Bu projede iki ana veri klasörü bulunmaktadır: `raw` ve `processed`.

## 1. raw Klasörü
- Bu klasör, sisteme yüklenen orijinal (ham) veri setlerini içerir.
- Ödev gereği, veri setinin silinmiş (kişisel bilgilerden arındırılmış) hali bu klasöre eklenir.
- Örnek dosyalar:
  - `train_u6lujuX_CVtuZ9i.csv`: Eğitim veri seti
  - `test_Y3wMUE5_7gLdaTN.csv`: Test veri seti

## 2. processed Klasörü
- Bu klasör, ham veri setleri üzerinde çeşitli ön işleme ve özellik mühendisliği adımlarından sonra oluşturulan dosyaları içerir.
- Buradaki dosyalar, modelleme ve analiz için hazırlanmış veri setleridir.
- Örnek dosyalar:
  - `X_train_selected.csv`: Seçilen özelliklerle eğitim veri seti
  - `X_train_smote.csv`: SMOTE ile dengelenmiş eğitim veri seti
  - `X_val_encoded.csv`: Kodlanmış doğrulama veri seti
  - `final_feature_list.json`: Son özellik listesini içerir
  - Diğer ilgili dosyalar

## Klasörlerin Kullanımı
- Ham veri setleri ilk olarak `raw` klasörüne yüklenir.
- Veri işleme ve özellik mühendisliği adımlarından sonra elde edilen yeni veri setleri ve dosyalar `processed` klasöründe saklanır.
- Her iki klasör de veri yönetimi ve projenin izlenebilirliği açısından önemlidir.
