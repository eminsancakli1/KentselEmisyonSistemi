Kentsel Emisyon Dedektifi (Green-Audit)
Mevcut şehir kameralarını, çevre sensörlerini ve NASA uydu görüntülerini yapay zeka ile eşzamanlı işleyerek kentsel alanlardaki çevre suçlarını ve özellikle gizlice yapılan kaçak moloz/hafriyat dökümlerini anlık tespit eden otonom kentsel takip platformu.

Bu proje, geleneksel denetim mekanizmalarının ve kameraların yetersiz kaldığı kör noktalarda bile uydu teknolojilerini ve bilgisayarlı görüyü birleştirerek yasadışı dökümleri engellemeyi amaçlar.

Benim Katkım ve Rolüm (Yapay Zeka & Veri Mühendisliği)
Bu ekip projesinde Makine Öğrenmesi Geliştiricisi ve Bilgisayarlı Görü (Computer Vision) Uzmanı olarak görev aldım. Çoklu veri kaynaklarından (Kamera, Sensör ve NASA Uydu Verileri) gelen girdileri işleyen, analiz eden ve çevre ihlallerini otonom olarak saptayan hibrit yapay zeka motorunu sıfırdan tasarladım, kodladım ve eğittim.

Neler Yaptım?
 Yapay Zeka ve Model Eğitimi: Projenin karar alma mekanizmasını oluşturmak adına Python kullanarak ham verileri işledim, anomali tespiti ve sınıflandırma yapabilen makine öğrenmesi modellerini sıfırdan eğitip optimize ettim.

 Bilgisayarlı Görü (OpenCV): Canlı şehir kamera akışları üzerinde nesne tespiti ve hareket analizi yaparak, yasadışı moloz/hafriyat dökmeye çalışan şüpheli araçları ve çevre kirliliği odaklarını anlık yakalayan algoritmalar geliştirdim.

 NASA Uydu Verisi Analizi ve Ar-Ge: Kameraların açısı dışında kalan gizli ve kırsal alanlardaki dökümleri yakalamak amacıyla NASA uydu görüntülerini yapay zeka boru hattına (pipeline) entegre ettim. Zaman serisi analizleriyle yüzeydeki ani topoğrafik değişimleri saptayan Ar-Ge süreçlerini yürüttüm.

 Hibrit Veri Entegrasyonu: Sensörlerden gelen metrik veriler ile bilgisayarlı görü çıktılarının eşzamanlı çalışmasını sağlayan hibrit veri analizi mimarisini kurdum.

Kullanılan Teknolojiler: Python, OpenCV, Scikit-learn, Pandas, NumPy, Google Colab

 Projenin Genel Amacı ve Çözdüğü Problem
Modern şehirlerde kaçak moloz ve hafriyat dökümleri genellikle denetimin az olduğu kırsal alanlarda, orman sınırlarında veya kameraların görmediği kör noktalarda gizlice gerçekleştirilmektedir.

Green-Audit, bu problemi çözmek için üç katmanlı bir hibrit ağ kurar:

Anlık Takip (Kamera): Şehir kameralarından gelen canlı yayınlar üzerinden yasadışı döküm yapmaya çalışan araçları bilgisayarlı görüyle saptar.

Emisyon Analizi (Sensör): Çevreye yerleştirilen sensör verileriyle hava kalitesindeki ani değişimleri ve kaçak emisyon odaklarını yakalar.

Kör Nokta Denetimi (NASA Uydu): Kameraların tamamen dışında kalan gizli bölgelerdeki topoğrafik değişimleri ve kaçak dolgu alanlarını NASA uydu görüntüleri üzerinden otonom olarak tespit eder.

 Dosya Yapısı
KentselEmisyonDemo02_1.ipynb: Geliştirdiğim yapay zeka model mimarisinin, veri işleme boru hatlarının (pipeline) ve çok katmanlı analiz sisteminin çalıştığı ana notebook dosyası.



 Nasıl Çalıştırılır?
Sistemi test etmek ve analiz süreçlerini incelemek için aşağıdaki adımları takip edebilirsiniz:

Depoda bulunan KentselEmisyonDemo02_1.ipynb dosyasını Google Colab veya Jupyter Notebook üzerinde açın.

Gerekli bağımlılıkların ortamınızda yüklü olduğundan emin olun:

Bash
pip install opencv-python scikit-learn pandas numpy
Proje içinde kullanılan API entegrasyonları veya veri havuzu bağlantıları mevcutsa, gerekli kimlik doğrulama anahtarlarını çalışma ortamınıza tanımlayın.

Tüm kod hücrelerini sırasıyla çalıştırarak hibrit yapay zeka modelinin çevre ihlallerini nasıl raporladığını gözlemleyin.

(Not: Bu proje, Nisan 2026'da düzenlenen Marmara Impacthon kapsamında "Kentsel Emisyon Sistemi" adısıyla ekip olarak geliştirilmiştir. Bu repository, projenin yapay zeka ve makine öğrenmesi katmanlarına yaptığım kişisel katkıları sergilemek amacıyla oluşturulmuş bağımsız bir kopyadır.)
