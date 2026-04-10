EEG Tabanlı Epilepsi Tespiti - TCN Modeli
Bu proje, Makine Öğrenmesi dersi kapsamında Bonn Üniversitesi EEG veri seti kullanılarak "Sağlıklı" ve "Nöbet (Seizure)" durumlarını ayırt etmeyi hedefleyen bir zaman serisi sınıflandırma (time series classification) çalışmasıdır. Model olarak Temporal Convolutional Network (TCN) kullanılmıştır.

Proje Özeti ve Teknik Strateji
Veri Sızıntısı (Data Leakage) Önlemi: Veri sızıntısını engellemek için veri önce %80-20 oranında eğitim ve test seti olarak ayrılmış, ardından parçalama işlemine geçilmiştir.

Veri Çoğaltma (Augmentation): Eğitim setinde örtüşmeli pencereler (Stride: 512) kullanılarak modelin genelleme yeteneği artırılmıştır.

Kritik Karar Mekanizması: Hastalık tespitinde nöbet yakalama hassasiyetini artırmak büyük önem taşıdığından, test aşamasında karar eşik değeri (threshold) 0.3 olarak optimize edilmiştir.
