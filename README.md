Global AI Hub Derin Öğrenme Proje Kampı'nın bitirme projesini bugün itibariyle tamamladım. Projenin amacı ANN kullanarak 9 farklı balık türünden oluşan birçok fotoğraftaki balıkların hangi türler olduğunu tahmin etmekti. Projeyi yaparken izlediğim adımları şöyle sıralayabilirim:
- Kütüphaneleri import etmek.
- Verideki balıkların olduğu fotoğrafların pathlerini ve isimlerini alarak onları bir dataframede birleştirmek.
- Veri hakkında bazı bilgileri (boş değer vs.) ve her bir balık türünden birer tane fotoğraf göstermek.
- Veriyi öncelikle train ve test olarak, daha sonra da train, validasyon ve test olarak ölçekleyerek bölmek.
- Veriden Sequential model oluşturarak bu modele 1028 nöronlu giriş katmanı, 512 ve 256 nöronlu gizli katmanları ve 9 nöronlu çıkış katmanı eklemek.
- Modeli fit etmeden önce overfittingi önlemek amacıyla earlystopping eklemek ve sonrasında compile etmek.
- Modelin sonuçlarını görmek için train ve validasyon verilerinin loss ve accuracy değerlerini görselleştirmek.
- Bunlardan sonra modeli modelin daha önce görmediği veri olan test verisi ile fit etmek ve loss, accuracy, confusion_matrix gibi metrikler ve classification_report kullanarak sonularını analiz etmek.

-- Proje içeriğine ulaşmak için [tıklayınız](https://www.kaggle.com/code/abdurrahmangulmez46/notebook39b8249c95/notebook).
