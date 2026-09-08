---
title: "Savunma Sanayiinden Küresel Ölçeğe Otonomi Mimarileri"
date: 2026-09-01 12:00:00 +0300
categories: [Araştırma, Savunma Sanayii, Fiziksel Yapay Zeka]
tags: [autonomous-systems, defense-industry, edge-ai]
---


# Savunma Sanayiinden Küresel Ölçeğe Otonomi Mimarileri

<div align="center">

<img src="https://img.shields.io/badge/Status-Completed-brightgreen.svg" alt="Status">
<img src="https://img.shields.io/badge/Field-Defense_%26_Autonomous_Systems-blue.svg" alt="Field">
<img src="https://img.shields.io/badge/Author-Sueda_Zeynep_Demirtas-orange.svg" alt="Author">

</div>

## 📌 İçindekiler
1. Güncel Savunma Ekosisteminin Stratejik Odakları
2. Türk Savunma Sanayisinde Çoklu Alan Otonomisi ve Dijital Birlik
3. Taktik ve Mini Drone Sistemlerinde Çeşitlilik
4. Otonomi Felsefesi ve Seyrüsefer Algoritmaları
5. Küresel Ölçekte Paradigma Değişimi: Akıl Yürüten İHA'lar
6. Sahadaki Mühendislik Darboğazları: Model Nicelleştirme ve Sensör Füzyonu
7. Kaynakça

---

## 1. Güncel Savunma Ekosisteminin Stratejik Odakları
Bu araştırma yazısı, savunma sanayisinde fiziksel yapay zekanın insansız hava, kara ve deniz araçlarına entegrasyonunu, kullanılan yazılım mimarilerini ve küresel ölçekteki otonomi paradigmalarını incelemektedir[cite: 2]. Geleneksel kural tabanlı sistemlerden çıkarım yapabilen agentic mimarilere geçiş süreci analiz edilirken; Türkiye'nin savunma ekosistemindeki deterministik algoritma tercihleri, sensör füzyonu, GPS-bağımsız (GPS-denied) seyrüsefer ve donanım kısıtlarını aşmak için kullanılan model nicelleştirme (quantization) stratejileri detaylandırılacaktır[cite: 2].

Modern harp ortamında otonom sistemler, insan operatörlerin uzaktan kontrol ettiği platformlar olmaktan çıkıp, bizzat sahada durum farkındalığı yaratan ve karar alan bağımsız ajanlara dönüşmektedir[cite: 2]. Güncel savunma ekosistemi, yapay zekanın donanımla buluştuğu bu yeni dönemi dört ana stratejik odak etrafında şekillendirmektedir[cite: 2]:

* **Fiziksel Yapay Zeka:** Yazılım düzeyindeki derin öğrenme ve karar algoritmalarının doğrudan robotik gövdelere indirilmesidir[cite: 2]. Bu yaklaşım, GPS'in olmadığı veya karıştırıldığı ortamlarda sistemin otonom seyrüsefer yapabilmesini ve bağımsız karar alma mekanizmalarını işleterek hayatta kalmasını sağlar[cite: 2].
* **Sürü Doktrini ve Dijital Birlik:** BARKAN, SANCAR ve BAHA gibi hava, kara ve deniz otonom unsurlarının izole çalışmak yerine tek bir merkezi yapay zeka ağı üzerinden müşterek harekât icra etmesidir[cite: 2].
* **Edge AI:** Elektronik harp ortamlarında platformların dış dünya ile haberleşme (uydu veya harici sinyal) bağının kopması durumunda, cihazın kendi üzerindeki işlemci gücünü kullanarak hedef sınıflandırma ve anomali tespiti yapabilmesidir[cite: 2].
* **Küresel Ölçek ve İhracat:** Defense News Top 100 listesinde yer alan Türk savunma sanayisi şirketlerinin, sahada muharebe kanıtı (combat-proven) elde etmiş otonom sistemlerle küresel ihracat pazarındaki gücünü artırmasıdır[cite: 2].

---

## 2. Türk Savunma Sanayisinde Çoklu Alan Otonomisi ve Dijital Birlik
Türk savunma sanayisinin otonomi vizyonu, tekil platformların ötesine geçerek farklı fiziksel alanlardaki sistemleri birbirine bağlayan "Dijital Birlik" konseptine dayanmaktadır[cite: 2].

### BARKAN 3 ve Çevresel Farkındalık
HAVELSAN tarafından geliştirilen BARKAN 3 İnsansız Kara Aracı (İKA), kara otonomisinin ulaştığı ileri noktayı temsil etmektedir[cite: 2]. 
* Sistemin sensör kapasitesi dört katına çıkarılarak tam durumsal farkındalık ve 360 derece çevresel algılama yeteneği kazandırılmıştır[cite: 2].
* GNSS sinyallerinin yoğun olarak karıştırıldığı (jamming/spoofing) elektronik harp ortamlarında bağımsız olarak eve dönüş yeteneğine sahip olup, engelleri aşarak dinamik rota çizebilmektedir[cite: 2].
* Modüler silah kulesi sayesinde üzerine entegre edilen füze ve makineli tüfek sistemleri, otonom hedef tespiti ve angajman desteği ile çalışabilmektedir[cite: 2]. Bu sistemlerin EFES ve SAHA gibi saha testleri tamamlanmış olup, TSK envanterine giriş protokolleri aktif olarak yürütülmektedir[cite: 2].

<p align="center">
  <img width="700" alt="BARKAN 3 İnsansız Kara Aracı" src="https://github.com/user-attachments/assets/SS-1.jpg">
</p>

### Müşterek Dijital Birlik Mimarisi
Hava, kara ve deniz sistemlerinin koordinasyonu, dağıtık konsensüs (distributed consensus) ve kombinatorik optimizasyon algoritmalarıyla sağlanmaktadır[cite: 2]. 
* BAHA (Dikey İniş Kalkışlı İHA), BARKAN ve SANCAR (SİDA) platformları, merkezi bir lider mimari yerine telsiz ağı üzerinden dağıtık olarak haberleşerek tek platform gibi hareket eder[cite: 2].
* Havadan BAHA'nın yaptığı otonom keşif ve tespit ettiği tehdit verileri, anlık olarak karadaki robotik unsura (BARKAN) aktarılarak insansız keşiften insansız taarruza geçiş sağlanır[cite: 2].
* Tüm sensör füzyonu verileri, deniz ve kara harp yönetim sistemleriyle entegre olan merkezi ADVENT sistemi üzerinden işlenir, bu sayede karar verme süresi dakikalardan saniyelere indirilir[cite: 2].
* Otonomi yazılımı arka planda "Macar Algoritması (Hungarian Algorithm)" gibi matris hesaplamaları yürüterek; platformların hedefe olan geometrik mesafesini, anlık batarya/yakıt durumlarını ve mühimmat kapasitelerini hesaplar[cite: 2]. Bu sayede görev dağılımı insan müdahalesi olmadan otonom olarak gerçekleştirilir[cite: 2].

---

## 3. Taktik ve Mini Drone Sistemlerinde Çeşitlilik
Büyük ölçekli İHA'ların yanı sıra, asimetrik harpte dengeleri değiştiren taktik ve mini drone sistemleri yapay zeka ile donatılmaktadır[cite: 2]. STM firması bu alanda geniş bir yelpazede otonom çözümler sunmaktadır[cite: 2]: 
* **STM KARGU (Kamikaze):** Görüntü işleme ve yapay zeka algoritmalarını kullanarak hareketli hedefleri tespit edip imha edebilen bu sistem, aynı zamanda sürüler halinde operasyon icra etme kabiliyetine sahiptir[cite: 2].
* **STM BOYGA (Mühimmat Bırakan):** Otonom uçuş dinamiklerini rüzgar ve irtifa hesaplamalarıyla birleştiren hassas balistik algoritması sayesinde, 81mm havan mühimmatını doğrudan hedefin üzerine bırakabilmektedir[cite: 2].
* **STM KUZGUN (Dolanıp Duran Mühimmat):** 1.000 kilometrenin üzerinde menzile ve 180 km/s seyir hızına sahip olan sistem, stratejik hedeflerin imhası için derin harekât yeteneği sunar[cite: 2].
* **DASAL PUHU C75 (Lojistik Kargo İHA):** Zorlu coğrafyalarda görev yapan birliklere otonom olarak ikmal, erzak ve mühimmat transferi yapabilen 75 kg faydalı yük taşıma kapasiteli sistemdir[cite: 2].
* **TOGAN & TUNGA-X (Taktik Keşif / Hedefleme):** Optik güdüm teknolojileri ve Edge AI algoritmaları ile donatılmış olan bu dronlar, otomatik hedef sınıflandırması yaparak sınır ve üs bölgelerinin güvenliğini sağlar[cite: 2].

<p align="center">
  <img width="700" alt="TUNGA-X Avcı Drone Sistemi" src="https://github.com/user-attachments/assets/SS-2.jpg">
</p>

* **BARAN & Anti-Drone Sistemleri:** Mikro İHA ve kamikaze drone tehditlerini yapay zeka ile otomatik olarak algılayıp imha eden otonom hava savunma önleme konseptleridir[cite: 2]. 

Bununla birlikte ASELSAN tarafından geliştirilen İHTAR sistemi, TV ve termal kameralardan gelen verileri sensör füzyonu ile birleştirip geliştirilmiş bilgisayarlı görü (computer vision) ile uzak mesafeden drone tehditlerini teşhis, tespit ve takip eden yapay zeka destekli bir karar verme algoritması sunmaktadır[cite: 2].

<p align="center">
  <img width="700" alt="ASELSAN İHTAR Anti-Drone Sistemi" src="https://github.com/user-attachments/assets/SS-3.jpg">
</p>

---

## 4. Otonomi Felsefesi ve Seyrüsefer Algoritmaları
Savunma sanayisinde karşılaşılan en büyük problemlerden biri donanımın kısıtlı kaynakları ve ortamdaki elektronik karıştırmadır[cite: 2]. Türkiye'nin savunma sanayisindeki yapay zeka felsefesi, halüsinasyon riski taşıyan büyük dil modelleri yerine, doğrudan "Görselden ve Veriden Eyleme" giden, deterministik matematiksel hesaplamaları temel alan modellere dayanır[cite: 2]. 

Bu felsefenin en başarılı örneği STM'nin KERKES (Görsel Navigasyon) projesidir[cite: 2]. 
* **Çalışma Prensibi:** KERKES, bilgisayarlı görü ve özellik eşleştirme algoritmalarını kullanır[cite: 2]. 
* **GPS Bağımsızlığı:** GPS sinyallerinin tamamen kesildiği senaryolarda, İHA'nın altındaki kameradan gelen canlı video akışı milisaniyeler içerisinde işlenir[cite: 2]. 
* **Öznitelik Çıkarımı ve Haritalama:** Algoritma, yer yüzeyindeki doğal veya yapay işaretçileri (köşe noktaları, yol kavşakları) birer öznitelik olarak kaydeder ve haritalandırır[cite: 2]. 
* **Konum Doğrulama:** Elde edilen bu anlık görüntü verileri, uçağın belleğinde bulunan Sayısal Yükseklik Haritası (DTM - Digital Terrain Model) ile matematiksel olarak eşleştirilerek İHA'nın uzaysal konumu GPS olmadan sıfır sapmayla hesaplanır[cite: 2]. 

Bu tür yaklaşımlarda KERKES, Macar Algoritması ve Mikro-Doppler Sinyal Analizi gibi nokta atışı çalışan derin öğrenme mimarileri tercih edilmektedir[cite: 2]. Bu sayede %100 güvenilirlik ve tam otonom elektronik harp bağışıklığı garanti altına alınmaktadır[cite: 2].

---

## 5. Küresel Ölçekte Paradigma Değişimi: Akıl Yürüten İHA'lar
Geleneksel savunma sistemlerindeki deterministik yapıların yanında, küresel drone ekosisteminde Akıl Yürüten otonomi mimarilerine doğru köklü bir paradigma değişimi yaşanmaktadır[cite: 2]. 

Yeni nesil akıl yürüten İHA'lar, klasik SLAM ve PID kontrolcü mimarilerinden ayrıldığı gibi, doğrudan girdi-çıktı eşlemesi yapan salt reaktif VLA modellerinden de yapısal olarak farklılaşır[cite: 2]. 
* **Embodied CoT (Fizikselleştirilmiş Akıl Yürütme):** Bu yeni sistemler, OpenAI'ın o1/o3 serisi veya DeepSeek-R1 gibi büyük modellerde rüştünü ispatlayan Chain-of-Thought mantığını fiziksel dünyaya ve aerodinamik platformlara uyarlamaktadır[cite: 2]. 

**Tarihsel Gelişim ve Farklar:**
* **Geleneksel Sistemler:** Çevresel engelleri algılayan sensörler ve engel sakınma kontrolcüleriyle sadece "görür ve kaçar" prensibiyle çalışır[cite: 2]. 
* **1. Nesil VLA Modelleri:** Ortamı anlamsal olarak kavrar ancak planlama yapmadan uçtan uca eşlemeyle "anlar ve reaktif olarak uçar"[cite: 2]. 
* **Agentic / Reasoning Modeller:** Sistemi tamamen değiştirerek; dronun çevresini "görmesini", nihai amaca giden ara adımları kendi zihninde planlamasını, olası hatalarını uçuş esnasında fark edip kararını değiştirmesini ve fiziksel aksiyonu en son aşamada almasını sağlar[cite: 2].

---

## 6. Sahadaki Mühendislik Darboğazları: Model Nicelleştirme ve Sensör Füzyonu
Havacılık ve uzay projelerinde otonomi yazılımlarının karşılaştığı en büyük engel, uçan platformların sahip olduğu katı "Boyut, Ağırlık ve Güç" (SWaP) kısıtlamalarıdır[cite: 2]. Milyarlarca parametreye sahip devasa LLM, VLM veya gelişmiş YOLO gibi bilgisayarlı görü modellerinin, sınırlı batarya kapasitesine sahip bir donanım üzerinde çalıştırılabilmesi için Nicelleştirme adı verilen model sıkıştırma teknolojisi kullanılmaktadır[cite: 2]. 

### Model Nicelleştirme Stratejisi
* **Veri Tipi Dönüşümü:** Standart yapay zeka modelleri, ağırlıklarını yüksek hassasiyetli 32-bit ondalıklı sayı (FP32) formatında tutar[cite: 2]. Nicelleştirme işlemi, bu devasa veri havuzunu INT8 (8-bit Integer) formatına, yani -128 ile +127 arasındaki tam sayılara indirgeyerek sıkıştırır[cite: 2]. 
* **Donanım Avantajları:** Bu sıkıştırma işlemi drone'un kısıtlı RAMini rahatlatırken, çıkarım hızını devasa oranda artırır[cite: 2]. 
* **Güç Tüketimi ve Batarya:** Yapılan analizlerde, standart bir YOLO modeli FP32 formatında koşturulurken edge kartının anlık 33.67 Watt güç tükettiği ölçülmüştür[cite: 2]. Model INT8 seviyesine nicelleştirildiğinde ise bu tüketim 13.85 Watt'a kadar düşerek sistemde net %59 enerji tasarrufu sağlamıştır[cite: 2]. Gücünü tamamen pillerden alan bir drone platformu için bu durum, havada kalma süresinin (endurance) doğrudan iki katına çıkması anlamına gelmektedir[cite: 2]. 

### GPS-Denied Ortamlar ve Sensör Füzyonu
Projelerin asıl katma değerli kısmı, cihazın aerodinamik ve mekanik tasarımından ziyade, elektronik harp altında hayatta kalmasını sağlayan yazılım mimarisidir[cite: 2]. GPS sinyallerinin tamamen köreltildiği harekât alanlarında otonomi, cihazın üzerindeki tüm donanımların ortaklaşa çalışmasını gerektirir[cite: 2]. 

Geliştirilen milli yazılım mimarileri; İHA üzerindeki kızılötesi termal kameralardan, optik sensörlerden ve ataletsel ölçüm birimlerinden (IMU) gelen ham verileri "Sensör Füzyonu (Sensor Fusion)" algoritmalarıyla tek bir doğru veride birleştirir[cite: 2]. INT8 seviyesinde nicelleştirilerek hızlandırılmış YOLO ve VLA modelleri bu füzyon verisiyle beslenerek, İHA'nın aynı anda hem görsel algılamayı, hem mantıksal akıl yürütmeyi hem de otonom rota planlamasını bir bütün olarak yapabilmesine olanak tanır[cite: 2].

---

## 7. Kaynakça
[1] STM, "TUNGA-X Avcı Drone Sistemi ve Teknik Özellikleri," STM Ürün Katalogları, 2026. [Çevrimiçi]. Erişim: stm.com.tr[cite: 2]

[2] SavunmaSanayiST, "STM'nin Avcı Drone'u TUNGA-X İlk Kez Sergilendi," SavunmaSanayiST Savunma Haberleri, 2024. [Çevrimiçi]. Erişim: savunmasanayist.com[cite: 2]

[3] STM, "TOGAN Otonom Döner Kanatlı Gözcü İHA Sistemi," STM Ürün Sayfası, 2024. [Çevrimiçi]. Erişim: stm.com.tr[cite: 2]

[4] STM, "KUZGUN Akıllı Mühimmat ve Drone Entegrasyon Çözümleri," STM Savunma Projeleri, 2025. [Çevrimiçi]. Erişim: stm.com.tr[cite: 2]

[5] STM, "Savunma Havacılığında Bilgisayarlı Görü Teknolojileri," STM Akıllı Sistemler Bülteni, 2025. [Çevrimiçi]. Erişim: stm.com.tr[cite: 2]

[6] STM, "GNSS Bağımsız Seyrüsefer Çözümleri: KERKES Projesi Akış Yapısı," STM Teknoloji Sayfaları, 2023. [Çevrimiçi]. Erişim: stm.com.tr[cite: 2]

[7] STM, "İHA'lar Artık GPS Yokken de Görev Yapabilecek: KERKES Projesinde Sahada Teslimat Aşaması," STM Haber Arşivi, 2022. [Çevrimiçi]. Erişim: stm.com.tr[cite: 2]

[8] STM, "Çoklu Alan (Multi-Domain) Operasyon Yetkinliği ve Robotik Entegrasyon Mimarisi," STM Stratejik Raporlar, 2024. [Çevrimiçi]. Erişim: stm.com.tr[cite: 2]

[9] Baykar Technology, "Unmanned Aerial Vehicle Systems: AKINCI, KIZILELMA and TB3 Tactical AI Platforms," Baykartech Official Product Repository, 2026. [Çevrimiçi]. Erişim: baykartech.com[cite: 2]

[10] Envanter Medya, "HAVELSAN Dijital Birlik Mimarisi ve Otonom Vizyon Çözümleri," Envanter Medya İnceleme Raporu, 2024. [Çevrimiçi]. Erişim: envantermedya.com[cite: 2]

[11] ASELSAN, "İHTAR Anti-Drone ve Mini-İHA Önleme Sistemi Teknik İsterleri," ASELSAN Savunma Sistemleri Kataloğu, 2024. [Çevrimiçi]. Erişim: aselsan.com[cite: 2]

[12] T.C. Cumhurbaşkanlığı Savunma Sanayii Başkanlığı (SSB), "Savunma Sanayii Yapay Zeka Algoritmaları ve Veri Stratejisi Raporu," SSB Yayınları, Ankara, 2024. [Çevrimiçi]. Erişim: defenceturk.net[cite: 2]

[13] H. Yılmaz, "Yapay Zeka Destekli Savunma Teknolojileri ve Taktik İHA Sahasındaki Algoritmik Gelişmeler," Anadolu Ajansı Bilim ve Teknoloji Raporu, Temmuz 2024.[cite: 2]

[14] STM Savunma Teknolojileri, "Yapay Zeka Destekli Avcı Drone Teknolojilerinde Sosyal Medya Teknik Tanıtım Serisi," STM Resmi Instagram Hesabı, Makaralar (Reels), Ocak 2025. [Çevrimiçi]. Erişim: instagram.com[cite: 2]

[15] HAVELSAN A.Ş., "HAVELSAN Fusion Core: Multi-Sensor Data and Track Fusion Architecture," Academia Research Repository, 2016. [Çevrimiçi]. Erişim: academia.edu[cite: 2]

[16] M. B. Uzun et al., "Handling of Sensor Registration Errors in Track-Level Fusion," ResearchGate Technical Papers, vol. 12, pp. 45-51, Nov. 2016. doi: 10.13140/RG.2.2.31130.40331[cite: 2]

[17] A. T. Serkan ve E. Çetin, "Çoklu Sensör İz Füzyonu Yöntemlerinin Simülasyon Yoluyla Değerlendirilmesi (Evaluation of Multi-Sensor Track Fusion Methodologies by Simulation)," ResearchGate Akademik Yayınlar, ss. 112-120, Aralık 2016. doi: 10.13140/RG.2.2.31130.47325[cite: 2]

[18] Google DeepMind, Stanford University, and UC Berkeley, "OpenVLA: An Open-Source Vision-Language-Action Model for Generalist Robotic Manipulation," arXiv preprint arXiv:2406.09246, 2024. [Çevrimiçi]. Erişim: huggingface.co[cite: 2]

[19] W. Azder et al., "CognitiveDrone: A Vision-Language-Action Architecture for High-Level Cognitive Decision Making in Unmanned Aerial Vehicles," arXiv preprint arXiv:2503.01378, 2025. [Çevrimiçi]. Erişim: github.com[cite: 2]

[20] J. Smith and A. Taylor, "Vision-Language-Action (VLA) Models for Unmanned Aerial Robotics and Bimanual Manipulation: A Comprehensive Review," Journal of Robotics and Automated Systems, vol. 42, no. 3, pp. 204-219, 2026.[cite: 2]

[21] DeepLearning.AI, "The Reasoning Revolution: How Chain-of-Thought Models Like o1 and DeepSeek-R1 Transformed Embodied AI," The Batch, Jan. 2025.[cite: 2]

[22] L. Zhang et al., "COMPASS: A 7-Layer Semantic Reference Architecture for AI-Powered Autonomous Drone Systems in Smart Cities," IEEE Transactions on Intelligent Transportation Systems, vol. 27, no. 2, pp. 1102-1115, 2026.[cite: 2]

[23] R. Khanna, "Action Chunking with Transformers (ACT) and Diffusion Policies in High-DoF Bimanual Harvesting and Aerial Manipulation," Robotics Center AI Research Report, 2026.[cite: 2]

[24] Defence Turk, "İngiltere Hava Savunma Sistemlerine Karşı Sürü Drone Kullanacak," DefenceTurk Haber Portalı, 2025. [Çevrimiçi]. Erişim: defenceturk.net[cite: 2]

[25] S. Boddu and A. Mukherjee, "Lightweight Object Detection Using Quantized YOLOv4-Tiny for Emergency Response in Aerial Imagery," arXiv preprint arXiv:2506.09299v1, Jun. 2025. [Çevrimiçi]. Erişim: https://arxiv.org/html/2506.09299v1[cite: 2]

</div>
