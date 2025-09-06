# 🗺️ Yapay Zeka Harita İşaretleri Stüdyosu

Bu proje, kullanıcıların **metin açıklamaları** ve **stil seçenekleri** kullanarak yapay zeka yardımıyla tamamen özelleştirilmiş **harita işaretleri (map markers)** oluşturmasını sağlayan bir web uygulamasıdır.  
Artık projeniz veya haritanız için mükemmel ikonu aramak zorunda değilsiniz,sadece hayal edin ve saniyeler içinde oluşturun! 🚀

---

<img width="1517" height="862" alt="image" src="https://github.com/user-attachments/assets/9d256a5c-335c-4755-bba9-5e4da1509e1a" />


---

## ✨ Özellikler
- **Metin Tabanlı Üretim:**  
  Basit açıklamalarla işaret oluşturun.  
  Örn: `"eski bir kale"`, `"modern bir kahve dükkanı"`  

- **Stil Seçenekleri:**  
  "Minimalist", "3D", "Pixel Art", "Vintage" vb.  

- **Renk & Detay Kontrolü:**  
  "Canlı Renkler", "Pastel Tonlar", "Sade Çizgiler", "Yüksek Detaylı"  

- **Arka Plan Temizleme:**  
  Beyaz arka plan otomatik kaldırılır → şeffaf PNG ikonları hazır.  

- **Anında Harita Önizlemesi:**  
  Leaflet.js entegrasyonu sayesinde üretilen işareti haritada canlı görün.  

- **Duyarlı Tasarım:**  
  Mobil & masaüstü uyumluluk.  

- **Kullanıcı Dostu Arayüz:**  
  Yardım menüsü ve basit adımlarla kolay kullanım.  

---

## 🛠️ Kullanılan Teknolojiler
- **Frontend:** HTML5, CSS3, Vanilla JavaScript  
- **API:** Google Gemini API (`gemini-2.5-flash-image-preview`)  
- **Harita Kütüphanesi:** Leaflet.js  

---

## 🚀 Nasıl Çalışır?
1. Kullanıcının girdiği açıklama + seçilen stil etiketleri → **Google Gemini API prompt’u** oluşturulur.  
2. API’den gelen **base64 görsel**, istemci tarafında işlenir.  
3. **Arka plan şeffaf hale getirilir**.  
4. Sonuç:  
   - Sol panelde görüntülenir.  
   - Leaflet.js haritasında özel ikon olarak işaretlenir.  

---

## 🏃‍♂️ Nasıl Kullanılır?
1. Projeyi **klonlayın veya indirin**.  
2. `index.html` dosyasını tarayıcıda açın.  
3. [Google AI Studio](https://aistudio.google.com/) üzerinden bir **Gemini API Key** edinin.  
4. API anahtarınızı uygulamadaki **Google Gemini API Key** alanına girin.  
5. Açıklamanızı yazın → stil, renk, detay seçin.  
6. **🎨 "Harita İşareti Oluştur"** butonuna basın.  
7. Sonuçları hem panelde hem de haritada görün. 🎉  

---

