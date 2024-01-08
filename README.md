# Deep_Learning_Project

# Proje Başlığı

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          	       | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 5200505059 | Arzuv Hudaynazarova  | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/arzuv-hudaynazarova)  |
| 1180505810 | Yusuf Gürcan         | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/Joseph0grcn)  |
| 1200505039 | Barış Gönenç         | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/balfatih)     |
| 1200505034 | Baran Kılıç          | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/balfatih)     |

---

## Proje Açıklaması

Buraya proje ile ilgili genel bir açıklama ekleyin. Projenizin amacı, kapsamı, kullanılan teknolojiler ve belki de projenin nasıl çalıştırılacağı gibi önemli bilgileri içermelidir.

Bu proje, Kırklareli Üniversitesi Mühendislik Fakültesi Yazılım Mühendisliği Bölümü'nün YAZ20411 - Derin Öğrenme dersi için geliştirilmiş bir uygulamadır. Ana hedefimiz, muz meyvesinin farklı gelişim evrelerini tanımlayarak tarım sektörüne katkıda bulunmaktır. Bu amaçla, geniş bir veri seti kullanarak derin öğrenme modellerini eğitip, bu modellerin tarım alanında nasıl uygulanabileceğini araştırdık.

Kullanılan Teknolojiler:

Convolutional Neural Networks (CNN): Projemizde, muz meyvesinin gelişim evrelerini sınıflandırmak için özel bir CNN modeli tasarladım. Bu model, görüntü işleme ve sınıflandırma konusunda etkili sonuçlar vermektedir.
Transfer Learning: Mevcut eğitilmiş modelleri kullanarak, zaman ve kaynak tasarrufu sağladık. Bu yöntem, projemizin verimliliğini artırdı.
Yapay Sinir Ağları: Özgün bir Yapay Sinir Ağı modeli geliştirerek, veri setimiz üzerinde daha spesifik sonuçlar elde etmeyi amaçladık.
Proje Kapsamı ve Çalıştırılması:
Projemiz, muz meyvesinin gelişim evrelerinin doğru bir şekilde sınıflandırılmasını hedefler. Bu süreçte, veri setimizi öncelikle eğitim, test ve doğrulama (validation) için uygun oranlarda böldük. Her bir modeli Python programlama dili ve TensorFlow, Keras gibi kütüphaneleri kullanarak geliştirdik. Modelleri, belirlenen veri setleri üzerinde eğittim ve test ederek, her birinin performansını Accuracy, Precision, Recall ve F1 skoru gibi metriklerle değerlendirdim. Ayrıca, Karmaşıklık Matrisi ve Classification Report aracılığıyla her modelin sınıflandırma başarısını ayrıntılı bir şekilde inceledim.

Projenin Çalıştırılması:
Proje, Python programlama dili ve TensorFlow, Keras,scikit-learn gibi kütüphaneler kullanılarak geliştirildi. Projenin çalıştırılması için aşağıdaki adımlar takip edildi:

Veri Seti Hazırlığı: Öncelikle, veri seti indirildi ve eğitim, test ve validation olarak ayrıldı.
Model Geliştirme ve Eğitimi: CNN, Transfer Learning ve Yapay Sinir Ağı modelleri geliştirildi ve eğitildi.
Test ve Değerlendirme: Her model, ayrılan test seti üzerinde değerlendirildi ve performansları karşılaştırıldı.

Sonuç olarak, bu proje ile hem teorik bilgilerimi pekiştirdik hem de pratik beceriler kazandık. Derin öğrenme ve yapay zeka alanlarındaki güncel teknik ve yaklaşımları kullanarak tarım sektörü için potansiyel çözümler sunmayı başardık. Projemiz, bu teknolojilerin gerçek dünya sorunlarına nasıl uygulanabileceğini gösteren önemli bir örnek teşkil ediyor.Bu proje, derin öğrenme ve yapay zeka teknolojilerinin tarım alanında nasıl uygulanabileceğini gösteren bir örnek teşkil etmektedir. Hem teorik bilgilerin pekiştirilmesi hem de pratik uygulama becerilerinin geliştirilmesi açısından bizim için değerli bir deneyim oldu.
---

## Proje Dosya Yapısı

Projenizin dosya yapısını açıklayan bir bölüm ekleyebilirsiniz. Örneğin:
- **/src**
  - **/components**
    - `Component1.js`
    - `Component2.js`
  - **/utils**
    - `utility.js`
- **/public**
  - `index.html`
- `README.md`
- `LICENSE`  


---

## Kurulum

Projeyi yerel bilgisayarınıza klonlamak ve çalıştırmak için adımları buraya ekleyin.  
Gerekli bağımlılıkların nasıl yükleneceği (veri seti, kullanılan kütüphanelerin sürümleri vs.), konfigürasyon adımları vb. bu bölümde bulunabilir.

---

## Kullanım

Projenin nasıl kullanılacağına dair bilgileri ekleyin. Örneğin, projenizi bir kişi bilgisayarına indirdiğinde sorunsuz bir şekilde çalıştırması için yapması gereken adımları listeleyin.

Projeyi başarıyla yerel ortamınızda çalıştırmak için aşağıdaki adımları takip edin:

Google Colab Kullanımı:

Projeyi Google Colab üzerinde çalıştırmayı tercih ettiyseniz, öncelikle Google hesabınız ile giriş yapın.
Yeni bir Colab notebook oluşturun ve bu notebook'a projenin GitHub linkini kullanarak klonlama komutunu yazın, örneğin: !git clone [Projenizin GitHub Linki].
Veri Setinin İndirilmesi ve Yüklenmesi:

Veri setini bu linkten indirin: Veri Seti Linki.
Google Colab'da, sol taraftaki menüden "Files" sekmesine tıklayın ve "Upload to session storage" seçeneğini kullanarak indirdiğiniz veri setini yükleyin.
Ortamın Konfigürasyonu:

Veri setinin doğru yolda olduğundan ve tüm dosyaların düzgün bir şekilde yüklendiğinden emin olun. Eğer bir hata ile karşılaşırsanız, dosya yollarını ve isimlerini kontrol edin.
Notebook içerisindeki kod hücrelerini sırasıyla çalıştırarak projenin kurulum ve konfigürasyon işlemlerini tamamlayın.
Bu adımları takip ederek projeyi sorunsuz bir şekilde Google Colab üzerinde çalıştırabilirsiniz.
---

## Katkılar

Projeyi yaparken hangi kaynaklardan bilgi edindiğinizi belirtin.

Bu projeyi hayata geçirirken, çok sayıda değerli kaynaktan faydalandım. Temel olarak, TensorFlow ve Keras kütüphanelerinin resmi dokümantasyonları, derin öğrenme modellerini anlamak ve uygulamak için ana kaynağım oldu. Bu dokümantasyonlar, karmaşık konuları basitleştirmede ve pratik örneklerle teorik bilgileri somutlaştırmada büyük rol oynadı.

Ayrıca, Coursera ve Udemy gibi online eğitim platformlarındaki derin öğrenme ve yapay zeka kursları, öğrenim sürecimde temel taşlar olarak yer aldı. Özellikle Andrew Ng'un "Deep Learning Specialization" kursu, derin öğrenme alanındaki temel prensipleri ve uygulamaları kapsamlı bir şekilde anlatıyor. TensorFlow'un resmi YouTube kanalındaki eğitim videoları da, karmaşık konseptleri anlamamda ve uygulamalarda bana rehberlik etti.

Karşılaştığım zorlukları aşmada, Stack Overflow ve GitHub gibi platformlar vazgeçilmezim oldu. Açık kaynak kodlar ve bu platformlardaki tartışma forumları, problemlere pratik çözümler bulmamda yardımcı oldu. Özellikle [bu GitHub reposu](https://github.com/balfatih/YAZ20411_Derin_Ogrenme), projemin çeşitli aşamalarında referans aldığım önemli kaynaklardan biriydi. Bu repo, benzer projelerde kullanılan kod örneklerini ve algoritmaları içeriyor, bu da uygulamalı öğrenim sürecimde benim için büyük bir avantaj sağladı. 

Bu kaynakların her biri, projemin başarılı bir şekilde tamamlanmasında büyük rol oynadı ve derin öğrenme alanındaki bilgi ve becerilerimi genişletmeme yardımcı oldu.

---

## İletişim

Proje ile ilgili iletişim bilgileri veya bağlantılarınızı ekleyin. Örneğin, e-posta adresleri, sosyal medya hesapları vb.

## Katkılar

Bu projeyi gerçekleştirirken birçok değerli kaynaktan yararlandım. Öncelikle, TensorFlow ve Keras kütüphanelerinin resmi dokümantasyonları, derin öğrenme modellerinin anlaşılması ve uygulanmasında temel rehberim oldu. Ayrıca, Coursera ve Udemy gibi çevrimiçi eğitim platformlarında yer alan derin öğrenme ve yapay zeka kursları, teorik bilgileri pratik uygulamalarla pekiştirmeme yardımcı oldu.

Özel olarak, Andrew Ng'un "Deep Learning Specialization" kursu ve TensorFlow'un resmi YouTube kanalındaki eğitici videolar, konseptleri anlamamda ve uygulamalarda bana yol gösterdi. Ayrıca, Stack Overflow ve GitHub gibi platformlarda yer alan açık kaynak kodlar ve tartışma forumları, karşılaştığım zorlukların üstesinden gelmekte önemli bir rol oynadı.

## İletişim

Proje hakkında herhangi bir sorunuz veya öneriniz varsa, benimle iletişime geçmekten çekinmeyin. Sorularınızı doğrudan e-posta yoluyla gönderebilirsiniz: [erdemliasena@gmail.com](mailto:erdemliasena@gmail.com). Ayrıca, projenin ilerlemesini takip etmek ve güncel bilgilere ulaşmak için LinkedIn ve Twitter hesaplarımı ziyaret edebilirsiniz:

- LinkedIn: [www.linkedin.com/in/arzuv-hudaynazarova-97995924a/](https://www.linkedin.com/in/arzuv-hudaynazarova-97995924a/)
- GitHub: [arzuv-hudaynazarova/Deep_Learning_Project](https://github.com/arzuv-hudaynazarova/Deep_Learning_Project)]

Her türlü geri bildirim ve işbirliği tekliflerine açığım ve projemi daha da geliştirmek için topluluktan gelen katkıları değerlendiriyorum. Bu projede elde ettiğim bilgileri ve deneyimleri paylaşmaktan ve bu alanda çalışmalarınızda size yardımcı olmaktan mutluluk duyarım.
