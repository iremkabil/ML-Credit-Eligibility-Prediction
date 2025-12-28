# Kredi Uygunluk Tahmini Projesi

Bu proje, makine öğrenmesi teknikleri kullanarak kredi başvurularının uygunluğunu tahmin etmeye yönelik bir çalışmadır. Proje kapsamında veri analizi, ön işleme, modelleme, hiperparametre optimizasyonu ve model açıklanabilirliği adımları gerçekleştirilmiştir.

---

## Proje Amacı
Kredi başvurularının onaylanıp onaylanmayacağını tahmin etmek için çeşitli makine öğrenmesi algoritmaları kullanılmıştır. Amaç, bankaların ve finans kuruluşlarının başvuruları daha hızlı ve doğru şekilde değerlendirmesini sağlamaktır.

## Veri Seti Açıklaması
 - **Ham Veri:** Başvuru sahiplerine ait demografik bilgiler, gelir, kredi geçmişi, istihdam durumu gibi değişkenler içerir.
 - **İşlenmiş Veri:** Eksik değerler doldurulmuş, kategorik değişkenler kodlanmış ve SMOTE ile dengesiz veri problemi çözülmüştür.
 - **Özellik Listesi:** Nihai modelde kullanılan en anlamlı değişkenler `final_feature_list.json` dosyasında tutulur.

## Proje Yapısı

## Proje Yapısı

```
Kredi_Uygunluk_Tahmini/
├── veri_setleri_aciklama.md
├── data/
│   ├── processed/
│   └── raw/
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing_and_feature_engineering.ipynb
│   └── 03_modeling.ipynb
```

- **data/raw/**: Ham veri dosyaları
- **data/processed/**: İşlenmiş ve özellik mühendisliği uygulanmış veri dosyaları
- **notebooks/**: Analiz, ön işleme ve modelleme adımlarını içeren Jupyter notebook dosyaları
- **veri_setleri_aciklama.md**: Veri seti ve değişken açıklamaları



## Adımlar
1. **Keşifsel Veri Analizi (EDA)**: Veri setinin incelenmesi ve ilk analizler (`01_eda.ipynb`)
2. **Ön İşleme & Özellik Mühendisliği**: Eksik değerlerin doldurulması, kategorik değişkenlerin kodlanması, SMOTE ile dengesiz veri problemi çözümü (`02_preprocessing_and_feature_engineering.ipynb`)
3. **Modelleme & Değerlendirme**: Farklı makine öğrenmesi algoritmaları ile model kurulumu, karşılaştırma ve hiperparametre optimizasyonu (`03_modeling.ipynb`)
4. **Model Açıklanabilirliği**: SHAP ile model kararlarının yorumlanması (`03_modeling.ipynb`)

## Kullanılan Kütüphaneler
 - pandas, numpy: Veri işleme ve analiz
 - scikit-learn: Makine öğrenmesi algoritmaları ve metrikler
 - matplotlib, seaborn: Görselleştirme
 - shap: Model açıklanabilirliği

## Çalıştırma
1. Gerekli Python kütüphanelerini yükleyin:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn shap
   ```
2. Notebook dosyalarını sırasıyla çalıştırın.



