# Proje Başlığı

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          	       | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 5200505059 | Arzuv Hudaynazarova  | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/arzuv-hudaynazarova)  |
| 1180505810 | Yusuf Gürcan         | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/Joseph0grcn)          |
| 1200505039 | Barış Gönenç         | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/balfatih)             |
| 1200505034 | Baran Kılıç          | Yazılım Mühendisliği     | PROJE_9       | [Github](https://github.com/balfatih)             |


---

## Proje Açıklaması

Bu proje, Kırklareli Üniversitesi Mühendislik Fakültesi Yazılım Mühendisliği Bölümü'nün YAZ20411 - Derin Öğrenme dersi için geliştirilmiş bir uygulamadır. Ana hedefimiz, muz meyvesinin farklı gelişim evrelerini tanımlayarak tarım sektörüne katkıda bulunmaktır. Bu amaçla, geniş bir veri seti kullanarak derin öğrenme modellerini eğitip, bu modellerin tarım alanında nasıl uygulanabileceğini araştırdık.

#### Kullanılan Teknolojiler:

Convolutional Neural Networks (CNN): Projemizde, muz meyvesinin gelişim evrelerini sınıflandırmak için özel bir CNN modeli tasarladım. Bu model, görüntü işleme ve sınıflandırma konusunda etkili sonuçlar vermektedir.
Transfer Learning: Mevcut eğitilmiş modelleri kullanarak, zaman ve kaynak tasarrufu sağladık. Bu yöntem, projemizin verimliliğini artırdı.
Yapay Sinir Ağları: Özgün bir Yapay Sinir Ağı modeli geliştirerek, veri setimiz üzerinde daha spesifik sonuçlar elde etmeyi amaçladık.

#### Proje Kapsamı ve Çalıştırılması:

Projemiz, muz meyvesinin gelişim evrelerinin doğru bir şekilde sınıflandırılmasını hedefler. Bu süreçte, veri setimizi öncelikle eğitim, test ve doğrulama (validation) için uygun oranlarda böldük. Her bir modeli Python programlama dili ve TensorFlow, Keras gibi kütüphaneleri kullanarak geliştirdik. Modelleri, belirlenen veri setleri üzerinde eğittim ve test ederek, her birinin performansını Accuracy, Precision, Recall ve F1 skoru gibi metriklerle değerlendirdim. Ayrıca, Karmaşıklık Matrisi ve Classification Report aracılığıyla her modelin sınıflandırma başarısını ayrıntılı bir şekilde inceledim.

#### Projenin Çalıştırılması:

Proje, Python programlama dili ve TensorFlow, Keras, Scikit-learn gibi kütüphaneler kullanılarak geliştirildi. Projenin çalıştırılması için aşağıdaki adımlar takip edildi:

Veri Seti Hazırlığı: Öncelikle, veri seti indirildi ve eğitim, test ve validation olarak ayrıldı.
Model Geliştirme ve Eğitimi: CNN, Transfer Learning ve Yapay Sinir Ağı modelleri geliştirildi ve eğitildi.
Test ve Değerlendirme: Her model, ayrılan test seti üzerinde değerlendirildi ve performansları karşılaştırıldı.

Sonuç olarak, bu proje ile hem teorik bilgilerimi pekiştirdik hem de pratik beceriler kazandık. Derin öğrenme ve yapay zeka alanlarındaki güncel teknik ve yaklaşımları kullanarak tarım sektörü için potansiyel çözümler sunmayı başardık. Projemiz, bu teknolojilerin gerçek dünya sorunlarına nasıl uygulanabileceğini gösteren önemli bir örnek teşkil ediyor.Bu proje, derin öğrenme ve yapay zeka teknolojilerinin tarım alanında nasıl uygulanabileceğini gösteren bir örnek teşkil etmektedir. Hem teorik bilgilerin pekiştirilmesi hem de pratik uygulama becerilerinin geliştirilmesi açısından bizim için değerli bir deneyim oldu.


---

## Proje Dosya Yapısı

Projemizin dosya yapısı, projenin organizasyonunu ve her bir dosyanın amacını açıkça göstermektedir. Projemizin dosya yapısı aşağıdaki gibidir:

- **/deep_learning**
  - **/CNN**
    - `CNN_8020.ipynb`
    - `CNN_7030.ipynb`
  - **/transfer_learning**
    - `Transfer_Learning_8020.ipynb`
    - `Transfer_Learning_7030.ipynb`
  - **/ANN**
    - `ANN_8020.ipynb`
    - `ANN_7030.ipynb`
- **/data_set**
  - `data_set.txt`
- `README.md`
- `requirements.txt`  


---

## Kurulum


Projeyi yerel bir ortamda çalıştırmak için aşağıdaki adımları izleyin:

### Projeyi Klonlama:

1. **GitHub'dan Projenin Klonlanması:**
   - Terminal veya komut istemcisini açın.
   - Projenin GitHub deposuna gidin: `https://github.com/arzuv-hudaynazarova/Deep_Learning_Project`.
   - `git clone https://github.com/arzuv-hudaynazarova/Deep_Learning_Project.git` komutunu kullanarak projeyi bilgisayarınıza klonlayın.

### Bağımlılıkların Kurulumu:

1. **Gerekli Kütüphanelerin Yüklenmesi:**
   - Klonlanan projenin kök dizinine gidin.
   - Terminal veya komut istemcisinde `pip install -r requirements.txt` komutunu çalıştırarak projenin ihtiyaç duyduğu kütüphaneleri yükleyin.

### Veri Setinin Hazırlanması:

1. **Veri Setinin İndirilmesi:**
   - Veri setini [bu bağlantıdan](https://drive.google.com/drive/folders/1mNSh6bzizCfcnuurP1jsIbWmnhN984Ue?usp=drive_link) indirin.
   - İndirdiğiniz veri setini projenin ilgili klasörüne yerleştirin (örneğin, `/datasets` klasörüne).

### Ortamın Konfigürasyonu:

1. **Ortam Ayarlarının Doğrulanması:**
   - İndirilen veri setinin ve kütüphanelerin doğru yüklenip yüklenmediğini kontrol edin.
   - Eğer bir hata ile karşılaşırsanız, dosya yollarını ve isimlerini kontrol edin.

### Jupyter Notebook ile Çalışma:

1. **Jupyter Notebook'un Başlatılması:**
   - Terminal veya komut istemcisinde projenin kök dizinindeyken `jupyter notebook` komutunu çalıştırarak Jupyter Notebook ortamını başlatın.
   - Açılan web arayüzünde, projenin içerdiği Jupyter Notebook dosyalarını bulun ve sırasıyla çalıştırın.

Bu adımları tamamladıktan sonra, projeyi yerel ortamınızda başarıyla çalıştırabilir ve derin öğrenme modellerinin eğitimini ve testlerini 
gerçekleştirebilirsiniz. Herhangi bir teknik sorunla veya soruyla karşılaşırsanız, lütfen GitHub sayfası üzerinden veya e-posta yoluyla iletişime geçin.


---

## Kullanım

Projeyi başarıyla yerel ortamınızda çalıştırmak için aşağıdaki adımları takip edin:

#### Google Colab Kullanımı:

Google Hesabı ile Giriş Yapma:
Google Colab web sitesine gidin ve Google hesabınızla giriş yapın.

Yeni Notebook Oluşturma:
Yeni bir Colab notebook oluşturun. Bunu yapmak için, "File" menüsünden "New notebook" seçeneğini tıklayın.

Projenin Klonlanması:
Oluşturduğunuz notebook'ta, aşağıdaki komutu çalıştırarak projeyi klonlayın:
!git clone [Projenizin GitHub Linki]

Örneğin: !git clone https://github.com/arzuv-hudaynazarova/Deep_Learning_Project.git

Veri Setinin İndirilmesi ve Yüklenmesi:
Veri setini bu linkten indirin.
Google Colab'da, sol taraftaki menüden "Files" sekmesine tıklayın ve "Upload to session storage" seçeneğini kullanarak indirdiğiniz veri setini yükleyin.
Ortamın Konfigürasyonu:

Veri setinin doğru yolda olduğundan ve tüm dosyaların düzgün bir şekilde yüklendiğinden emin olun.
Notebook içerisindeki kod hücrelerini sırasıyla çalıştırarak projenin kurulum ve konfigürasyon işlemlerini tamamlayın.
Jupyter Notebook Kullanımı:
Jupyter Notebook Kurulumu:

Eğer Jupyter Notebook yüklü değilse, Jupyter'in resmi web sitesinden Jupyter Notebook'u indirip kurun.
Projenin Klonlanması ve Ortamın Hazırlanması:

Terminal veya komut istemi aracılığıyla, git clone https://github.com/arzuv-hudaynazarova/Deep_Learning_Project.git komutu ile projeyi klonlayın.
Klonlanan projenin dizinine gidin ve pip install -r requirements.txt komutu ile gerekli kütüphaneleri yükleyin.
Veri Setinin Eklenmesi:

Projeye ait veri setini indirin ve projenin ilgili klasörüne (örneğin /datasets) yerleştirin.
Jupyter Notebook'ların Çalıştırılması:

Terminal veya komut istemcisinde jupyter notebook komutunu çalıştırarak Jupyter Notebook ortamını başlatın.
Açılan web arayüzünde, projenin içerdiği Jupyter Notebook'ları bulun ve sırasıyla çalıştırın.
Bu adımları takip ederek projeyi Google Colab ve Jupyter Notebook üzerinde başarıyla çalıştırabilir ve derin öğrenme modellerini eğitip test edebilirsiniz. Herhangi bir teknik sorunla karşılaşırsanız, GitHub sayfası üzerinden ya da e-posta yoluyla iletişime geçmekten çekinmeyin.


---

## Katkılar

Bu projeyi hayata geçirirken, çok sayıda değerli kaynaktan faydalandık. Temel olarak, TensorFlow, Scikit-learn ve Keras kütüphanelerinin resmi dokümantasyonları, derin öğrenme modellerini anlamak ve uygulamak için ana kaynağım oldu. 

Ayrıca, YouTube ve Udemy gibi online eğitim platformlarındaki derin öğrenme ve yapay zeka kursları, öğrenim sürecimde temel taşlar olarak yer aldı. Udemy'den aldığımız "Python for Computer Vision & Image Recognition - Deep Learning Convolutional Neural Network (CNN) - Keras & TensorFlow" kursu bu proje sürecinde bize çok destek oldu. Ayrıca Andrew Ng'un "Deep Learning Specialization" kursu, derin öğrenme alanındaki temel prensipleri ve uygulamaları kapsamlı bir şekilde anlatıyor. TensorFlow'un resmi YouTube kanalındaki eğitim videoları da, karmaşık konseptleri anlamamda ve uygulamalarda bize rehberlik etti.

Karşılaştığım zorlukları aşmada, Stack Overflow ve GitHub gibi platformlar vazgeçilmezim oldu. Açık kaynak kodlar ve bu platformlardaki tartışma forumları, problemlere pratik çözümler bulmamda yardımcı oldu. Özellikle [bu GitHub reposu](https://github.com/balfatih/YAZ20411_Derin_Ogrenme), projemin çeşitli aşamalarında referans aldığımız önemli kaynaklardan biridir. Bu repo, benzer projelerde kullanılan kod örneklerini ve algoritmaları içeriyor, bu da uygulamalı öğrenim sürecimizde bizim için büyük bir avantaj sağladı. 


---

## İletişim

Proje hakkında herhangi bir sorunuz veya öneriniz varsa, benimle iletişime geçmekten çekinmeyin. Sorularınızı doğrudan e-posta yoluyla gönderebilirsiniz: [erdemliasena@gmail.com](mailto:erdemliasena@gmail.com). Ayrıca, projenin ilerlemesini takip etmek ve güncel bilgilere ulaşmak için LinkedIn ve Gitub hesaplarımı ziyaret edebilirsiniz:

- LinkedIn: [www.linkedin.com/in/arzuv-hudaynazarova-97995924a/](https://www.linkedin.com/in/arzuv-hudaynazarova-97995924a/)
- GitHub: [arzuv-hudaynazarova/Deep_Learning_Project](https://github.com/arzuv-hudaynazarova/Deep_Learning_Project)

Her türlü geri bildirim ve işbirliği tekliflerine açığım ve projemi daha da geliştirmek için topluluktan gelen katkıları değerlendiriyorum. Bu projede elde ettiğim bilgileri ve deneyimleri paylaşmaktan ve bu alanda çalışmalarınızda size yardımcı olmaktan mutluluk duyarım.
