# 🗺️ Yapay Zeka Harita İşaretleri Stüdyosu
Bu proje, kullanıcıların metin açıklamaları ve stil seçenekleri kullanarak yapay zeka yardımıyla tamamen özelleştirilmiş harita işaretleri (map markers) oluşturmasını sağlayan bir web uygulamasıdır. Projeniz veya haritanız için mükemmel ikonu aramak yerine, sadece hayal edin ve saniyeler içinde oluşturun!

(Not: Bu bir yer tutucu resimdir. Projenizin gerçek bir ekran görüntüsü ile değiştirin.)

✨ Özellikler
Metin Tabanlı Üretim: İstediğiniz harita işaretini basitçe metinle açıklayarak oluşturun (Örn: "eski bir kale", "modern bir kahve dükkanı").

Stil Seçenekleri: "Minimalist", "3D", "Pixel Art" ve "Vintage" gibi çeşitli stillerle işaretinizin görünümünü zenginleştirin.

Renk ve Detay Kontrolü: "Canlı Renkler", "Pastel Tonlar" gibi renk paletleri ve "Sade Çizgiler", "Yüksek Detaylı" gibi detay seviyeleri belirleyin.

Arka Plan Temizleme: Oluşturulan görsellerin beyaz arka planı otomatik olarak kaldırılır, böylece haritanızda temiz bir şekilde kullanılabilirler.

Anında Harita Önizlemesi: Oluşturduğunuz harita işaretini Leaflet.js ile entegre edilmiş interaktif bir harita üzerinde anında görüntüleyin.

Duyarlı Tasarım: Mobil cihazlardan masaüstü bilgisayarlara kadar tüm ekran boyutlarında sorunsuz çalışır.

Kullanıcı Dostu Arayüz: Anlaşılır adımlar ve yardım menüsü ile kolay bir kullanım deneyimi sunar.

🛠️ Kullanılan Teknolojiler
Frontend: HTML5, CSS3, Vanilla JavaScript

API: Google Gemini API (gemini-2.5-flash-image-preview modeli)

Harita Kütüphanesi: Leaflet.js

🚀 Nasıl Çalışır?
Uygulama, kullanıcı tarafından girilen temel açıklamayı ve seçilen stil etiketlerini birleştirerek Google Gemini API'si için optimize edilmiş bir metin istemi (prompt) oluşturur. API'den gelen base64 formatındaki görsel, istemci tarafında işlenerek arka planı şeffaf hale getirilir. Son olarak, bu şeffaf görsel hem sonuç kartında hem de Leaflet haritası üzerinde özel bir ikon olarak görüntülenir.

🏃‍♂️ Nasıl Kullanılır?
Projeyi klonlayın veya indirin ve index.html dosyasını tarayıcınızda açın.

Google AI Studio üzerinden bir Google Gemini API Anahtarı edinin.

Uygulamadaki "Google Gemini API Key" alanına anahtarınızı girin.

Oluşturmak istediğiniz harita işaretini "Harita İşareti Açıklaması Girin" kutucuğuna yazın.

İsteğe bağlı olarak stil, renk paleti ve detay seviyesi seçin.

"🎨 Harita İşareti Oluştur" butonuna tıklayın.

Sonucun sol panelde ve harita üzerinde belirmesini izleyin!

✍️ Yazar
Bu proje ❤️ ile Emiray Kahya tarafından geliştirilmiştir.

📄 Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için LICENSE dosyasına göz atabilirsiniz.
