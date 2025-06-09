# HumanBone-YOLOv8-YOLOV11

 🔔 İnsan Kemik Kırıklarının Tespiti - Yolov8-Yolov11 Karşılaştırılması

Bu projede İnsan Kemik Kırıklarının Tespit Edilmesi ile ilgili bir çalışma gerçekleştirdim. Çalışmada Kaggle'den elde ettiğim "Human Bone Fractures Image Dataset" veri setini kullandım. Veri setinde;

🔹 Comminuted – Parçalı kırık

 🔹 Greenstick – Yeşil ağaç (çocuk) kırığı

 🔹 Healthy – Sağlam kemik

 🔹 Linear – Doğrusal kırık

 🔹 Oblique Displaced – Yer değiştirmiş oblik kırık

 🔹 Oblique – Oblik kırık

 🔹 Segmental – Segmental (çok parçalı) kırık

 🔹 Spiral – Spiral (burulma) kırık

 🔹 Transverse Displaced – Yer değiştirmiş enine kırık

 🔹 Transverse – Enine kırık

olmak üzere  toplam10 farklı sınıf bulunmaktadır.  

❗ Neden Önemli

Kemik kırıkları, özellikle doğru teşhis edilmediğinde ciddi komplikasyonlara yol açabiliyor. Derin öğrenme tabanlı tespit sistemleri, sağlık alanında doktorlara destek olarak hem hız hem de doğruluk kazandırıyor.

🦴 Model

Model olarak Yolov8 ve Yolov11 modelleri kullanılmıştır.

Çalışma sonucunda ise;

➡️ Yolov8 -->  Ortalama IoU: 0.681  -F1 Score: 0.968

➡️ Yolov11 --> Ortalama IoU: 0.669 - F1 Score: 0.960

sonuçları elde edilmiştir.
