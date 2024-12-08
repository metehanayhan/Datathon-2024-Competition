[EN]
# Datathon 2024 - Evaluation Score Prediction Project

This project was developed as part of the Datathon 2024 competition hosted by the Entrepreneurship Foundation. The goal is to predict the Evaluation Score of candidates based on provided data, using machine learning models to achieve the best accuracy.

## Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [EDA (Exploratory Data Analysis)](#eda-exploratory-data-analysis)
- [Results](#results)


## About the Project

This competition aims to predict the Evaluation Scores of candidates who have applied to the Entrepreneurship Foundation. The data underwent various cleaning and transformation processes, filling missing values, and converting features like birthdate into useful formats. The project’s final performance was measured using the RMSE (Root Mean Squared Error) metric.

## Dataset

The project involves two main datasets:
- **train.csv**: Training data containing candidates' personal information and their evaluation scores.
- **test_x.csv**: Test data containing only personal information; scores need to be predicted.

## EDA (Exploratory Data Analysis)

Key steps taken during data analysis:
- **Missing Data Handling**: Missing values were filled using techniques like KNN and Simple Imputer.
- **Data Cleaning**: Text fields were processed and converted into numeric formats.


## Results

The model with the lowest RMSE was selected as the final model. Detailed performance metrics are provided in the results section of the project.


[TR]

# Datathon 2024 - Evaluation Score Prediction Project

Bu proje, BTK Akademi, Google ve Girişimcilik Vakfı tarafından düzenlenen Datathon 2024 yarışması kapsamında geliştirilmiştir. Projenin amacı, adayların Evaluation Score (Değerlendirme Puanı) değerlerini, sağlanan veri setleri üzerinden makine öğrenimi modelleri kullanarak tahmin etmektir.

---

## İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Veri Seti](#veri-seti)
- [EDA (Keşifsel Veri Analizi)](#eda-keşifsel-veri-analizi)
- [Sonuçlar](#sonuçlar)
- [İletişim](#iletişim)

---

## Proje Hakkında

Bu yarışmada amaç, Girişimcilik Vakfı'na başvuran adayların değerlendirme puanlarını tahmin etmektir. Veri seti çeşitli temizlik ve dönüşüm işlemlerinden geçirilmiş, eksik değerler doldurulmuş ve doğum tarihi gibi özellikler daha faydalı formatlara dönüştürülmüştür. Projenin nihai performansı **RMSE (Root Mean Squared Error)** metriği ile değerlendirilmiştir.

---

## Veri Seti

Proje, iki ana veri setini içermektedir:
- **train.csv**: Adayların kişisel bilgilerini ve değerlendirme puanlarını içeren eğitim verisi.
- **test_x.csv**: Yalnızca kişisel bilgileri içeren ve puanların tahmin edilmesi gereken test verisi.

---

## EDA (Keşifsel Veri Analizi)

Veri analizi sırasında izlenen temel adımlar:
- **Eksik Veri Yönetimi:** Eksik değerler, **KNN Imputer** ve **Simple Imputer** gibi yöntemlerle doldurulmuştur.
- **Veri Temizliği:** Metinsel alanlar işlenmiş ve sayısal formatlara dönüştürülmüştür.

---

## Sonuçlar

En düşük **RMSE** değerine sahip model, nihai model olarak seçilmiştir. Model performansıyla ilgili detaylı metrikler projenin sonuç bölümünde paylaşılmıştır.

---
