Proje Detayları:

Kullandığım veri seti veri seti, 18.000'den fazla şarkıya ait ses özellikleri ve şarkı sözleri içermektedir. Hayata geçirmeye çalıştığım fikir ; Müzik platformlarından elde edilen kullanıcı dinleme verileri ile kullanıcıları analiz edip müzik tercihlerini kümeleyebilmekti.Bu projede müziğe olan ilgilere göre kullanıcıları gruplandırarak (Unsupervised) ve onlara öneriler sunacak modeller geliştirmeyi hedeflemiştim (Supervised).

Gözetimli öğrenme algoritması olarak kNN sınıflandırıcısını kullandım.

Gözetimsiz öğrenme algoritması olarak KMeans kümelemesini kullandım. 


Sonuç Gözlemleri ve Verileri: 

Gözlemlerim doğrultusunda Gözetimli öğrenme algoritmam görece iyi çalışırken Gözetimsiz algoritmamın çalışması yetersiz kalmış oldu.
Cross-Validation Accuracy Scores: [0.18489672 0.19607179 0.19031493 0.18224932 0.18699187]
Mean Accuracy: 0.18810492659616743 ( En son olarak %18 e accuracy değerimi çıkarabilmiş oldum.)
Best Parameters: {'max_depth': 3, 'min_samples_leaf': 2, 'min_samples_split': 2}
Başta Decition Tree algoritmasının benim için en doğru algoritma tercihi olacağını düşünüyordum fakat kodu yazarken çok fazla hata aldım ve değerlerimde değişiklikler gerçekleştiremedim. Bu sebeple kNN metoduna geçtim.KMeans algoritmasının en uygun algoritma olduğunu düşündüğüm için bu algoritmadan yana şansımı kullandım.
https://www.kaggle.com/code/tueslaylmaz/aygaz-mlbootcamp-spotifyprojefinal
