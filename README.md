Merhaba, ben Mesut 👋

Karabük Üniversitesi Bilgisayar Mühendisliği öğrencisiyim. Aktif olarak canlı ortamda (production) çalışan mobil uygulamalar ve bu sistemlerin arka uç (backend) servisleri üzerinde çalışıyorum.

Projelerim aktif bir kullanıcı kitlesine sahip olduğu ve sistem/kullanıcı güvenliği en büyük önceliğim olduğu için depolarım (repository) dış erişime kapalıdır. Aşağıda mimari yaklaşımlarım ve mühendislik prensiplerim hakkında genel bir fikir edinebilirsiniz.

🚀 PomoKampüs — Çalışma ve Odaklanma Uygulaması
Öğrenciler için geliştirilmiş, Google Play ve App Store'da aktif olarak yer alan; zamanlayıcı, istatistik ve ortak çalışma odaları içeren mobil uygulama.

Teknolojiler: React Native, Expo, TypeScript, Firebase, RevenueCat, Sentry.

Mimari Yaklaşım: Karmaşık iş mantıklarını modüler ve bağımsız yapılara ayırarak test edilebilirliği en üst düzeye çıkarıyorum. Sistemde koşan yüzlerce birim testi ile uçtan uca veri bütünlüğünü güvence altına alıyorum.

Mahremiyet ve Topluluk Güvenliği: Kullanıcı veri mahremiyeti tasarımın merkezinde yer alıyor. Riskleri mimari seviyede minimize etmek adına, kontrolsüz veri girişleri yerine izole asset'ler kullanıyor; arka planda kapsamlı bir şikayet ve moderasyon akışı işletiyorum.

🛡️ Kale — Özel Sunucu ve API Mimarisi (Geliştirme Aşamasında)
İstemci (client) tarafına hiçbir koşulda güvenmemek ilkesiyle tasarladığım, kimlik doğrulama ve veri akışlarını yönetecek olan arka uç (backend) servisi. Şu an aktif olarak geliştirme sürecindedir.

Teknolojiler: Node.js, Fastify, PostgreSQL, Docker.

Güvenlik Yaklaşımı:

Kısıtlanmış Altyapı: Konteyner mimarisinde "en az yetki" (least privilege) prensibiyle izole ağlar ve kısıtlanmış sistem erişimleri kullanıyorum.

Mimari Güvenlik: Yetkilendirme (authorization) kontrollerini doğrudan veritabanı sorgu katmanına entegre ederek yatay ve dikey yetki yükseltme (BOLA/IDOR) zafiyetlerini tasarım aşamasında engelliyorum.

Güvenli Veri İşleme: Hassas verilerin sunucu günlüklerine (log) yansımasını engelleyen sıkı filtrelemeler ve modern oturum yönetimi standartları uyguluyorum.

🧠 Nasıl Çalışıyorum?
Gerçekçi Doğrulama: Sistemin çalıştığını sadece içeriden izole bir şekilde değil, dışarıdan gerçek bir kullanıcının erişim noktalarından (end-to-end) doğrulamayı tercih ediyorum.

Kök Neden Analizi: Geliştirme sürecinde karşılaşılan önemli mimari darboğazların ve hataların kök nedenlerini analiz edip dokümante ederek kalıcı çözümler üretiyorum.

📬 İletişim
E-posta: ozkokmesut2005@gmail.com
