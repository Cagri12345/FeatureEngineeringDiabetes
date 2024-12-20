# Diyabet Tahmini ve Özellik Mühendisliği

Bu proje, diyabet tahmini yapmak için Python kullanılarak veri ön işleme, özellik mühendisliği ve makine öğrenimi modellerinin uygulanmasını kapsamaktadır. Diyabet veri seti kullanılarak çeşitli özellik mühendisliği teknikleriyle veriler işlenmiş ve makine öğrenimi algoritmaları ile tahmin modeli oluşturulmuştur.

## Proje Amaçları
- Diyabet hastalığının tahmini için etkili bir özellik seti oluşturmak.
- Makine öğrenimi algoritmaları kullanarak doğru tahminler yapmak.

## Veri Seti
Proje, [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) kullanılmaktadır. Veri seti, hamilelik sayısı, glikoz seviyesi, kan basıncı, vücut kitle indeksi gibi biyometrik özelliklerden oluşmakta ve diyabet sonucu (1: Pozitif, 0: Negatif) içermektedir.

- **Satır Sayısı:** 768
- **Sütun Sayısı:** 9
- **Sütunlar:**
  - `Pregnancies`: Hamilelik sayısı
  - `Glucose`: Glikoz seviyesi
  - `BloodPressure`: Kan basıncı
  - `SkinThickness`: Cilt kalınlığı
  - `Insulin`: İnsülin seviyesi
  - `BMI`: Vücut kitle indeksi
  - `DiabetesPedigreeFunction`: Ailede diyabet öyküsü fonksiyonu
  - `Age`: Yaş
  - `Outcome`: Diyabet sonucu (1: Pozitif, 0: Negatif)

## Kullanılan Yöntemler
- **Veri Ön İşleme:**
  - Eksik değerlerin kontrol edilmesi.
  - Veri ölçeklendirme ve normalizasyon.
- **Özellik Mühendisliği:**
  - Yeni özelliklerin oluşturulması.
  - Anlamlı olmayan özelliklerin çıkarılması.
- **Makine Öğrenimi Modelleri:**
  - Lojistik Regresyon
  - Karar Ağaçları (Decision Trees)
  - Random Forest

