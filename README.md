# 5-Storey Building Hot Water Delivery System Design 💧

Bu proje, 5 katlı bir bina için optimize edilmiş sıcak su dağıtım sisteminin tasarımını, hidrolik hesaplamalarını ve maliyet analizini kapsar. Akışkanlar mekaniği prensipleri kullanılarak boru çapları, pompa seçimi ve vana ayarları belirlenmiştir.

## 🎯 Proje Amacı
[cite_start]Binanın her katına şu şartları sağlayacak bir sistem tasarlamak[cite: 1887]:
* **Sıcaklık:** 50°C
* **Debi:** Her kat için 0.3 m³/h
* **Hız Sınırı:** Borularda 0.5 - 1 m/s arası akış hızı
* **Hedef:** Minimum yük kaybı ve maliyet optimizasyonu.

## ⚙️ Metodoloji ve Tasarım Süreci

### 1. Sistem Şeması ve Borulama
Sistem; kazan, pompa, farklı çaplarda borular ve radyatörlerden oluşmaktadır. [cite_start]Fırat Boru (PPRC PN25) kataloğu kullanılarak ticari boru çapları seçilmiştir.

<img width="450" height="703" alt="image" src="https://github.com/user-attachments/assets/465c603c-192b-4d12-8843-02927ce754ad" />

### 2. Hidrolik Hesaplamalar (Excel)
[cite_start]Tüm hesaplamalar Excel kullanılarak yapılmıştır.
* [cite_start]**Reynolds Sayısı ve Akış Rejimi:** Her boru hattı için hız ve Re sayısı hesaplandı[cite: 1997].
* **Yük Kayıpları (Head Loss):**
    * [cite_start]*Majör Kayıplar:* Haaland denklemi ve Darcy-Weisbach formülü ile hesaplandı[cite: 1999, 2007].
    * [cite_start]*Minör Kayıplar:* Dirsekler, T-bağlantılar ve radyatör kayıpları eklendi[cite: 2053].
* [cite_start]**Junction Analysis (Düğüm Analizi):** Her kattaki basınç düşüşünü eşitlemek için "Loop Metodu" kullanıldı ve gerekli vana katsayıları belirlendi.

### 3. Pompa Seçimi
[cite_start]Toplam sistem yük kaybı **7.2 metre** olarak hesaplandı[cite: 2113]. [cite_start]Bu ihtiyacı karşılamak ve enerji verimliliğini sağlamak için **Mars MRS 25/6-130** sirkülasyon pompası seçildi.

### 4. Maliyet Analizi
Kazan ve radyatörler hariç; boru, fitings, vana ve pompa maliyetleri hesaplandı.
* [cite_start]**Toplam Sistem Maliyeti:** ~6,691 TL (Proje tarihindeki birim fiyatlarla).

## 📊 Sonuç
Tasarlanan sistem, hız sınırlarını (0.5-1 m/s) aşmadan, her kata eşit debide (0.3 m³/h) su iletimini başarıyla sağlamaktadır. [cite_start]Loop analizi sayesinde sistemin hidrolik dengesi sağlanmıştır[cite: 2159].

---
[cite_start]*Bu proje, Marmara Üniversitesi Makine Mühendisliği Akışkanlar Mekaniği dersi kapsamında hazırlanmıştır[cite: 1874, 1875].*
