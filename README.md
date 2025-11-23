# 5-Storey Building Hot Water Delivery System Design 💧

Bu proje, 5 katlı bir bina için optimize edilmiş sıcak su dağıtım sisteminin tasarımını, hidrolik hesaplamalarını ve maliyet analizini kapsar. Akışkanlar mekaniği prensipleri kullanılarak boru çapları, pompa seçimi ve vana ayarları belirlenmiştir.

## 🎯 Proje Amacı
Binanın her katına şu şartları sağlayacak bir sistem tasarlamak:
* **Sıcaklık:** 50°C
* **Debi:** Her kat için 0.3 m³/h
* **Hız Sınırı:** Borularda 0.5 - 1 m/s arası akış hızı
* **Hedef:** Minimum yük kaybı ve maliyet optimizasyonu.

## ⚙️ Metodoloji ve Tasarım Süreci

### 1. Sistem Şeması ve Borulama
Sistem; kazan, pompa, farklı çaplarda borular ve radyatörlerden oluşmaktadır. Fırat Boru (PPRC PN25) kataloğu kullanılarak ticari boru çapları seçilmiştir.

<img width="450" height="703" alt="image" src="https://github.com/user-attachments/assets/465c603c-192b-4d12-8843-02927ce754ad" />

### 2. Hidrolik Hesaplamalar (Excel)
Tüm hesaplamalar Excel kullanılarak yapılmıştır.
* **Reynolds Sayısı ve Akış Rejimi:** Her boru hattı için hız ve Re sayısı hesaplandı.
* **Yük Kayıpları (Head Loss):**
    * *Majör Kayıplar:* Haaland denklemi ve Darcy-Weisbach formülü ile hesaplandı.
    * *Minör Kayıplar:* Dirsekler, T-bağlantılar ve radyatör kayıpları eklendi.
* **Junction Analysis (Düğüm Analizi):** Her kattaki basınç düşüşünü eşitlemek için "Loop Metodu" kullanıldı ve gerekli vana katsayıları belirlendi.

### 3. Pompa Seçimi
Toplam sistem yük kaybı **7.2 metre** olarak hesaplandı. Bu ihtiyacı karşılamak ve enerji verimliliğini sağlamak için **Mars MRS 25/6-130** sirkülasyon pompası seçildi.

### 4. Maliyet Analizi
Kazan ve radyatörler hariç; boru, fitings, vana ve pompa maliyetleri hesaplandı.
* **Toplam Sistem Maliyeti:** ~6,691 TL (Proje tarihindeki birim fiyatlarla).

## 📊 Sonuç
Tasarlanan sistem, hız sınırlarını (0.5-1 m/s) aşmadan, her kata eşit debide (0.3 m³/h) su iletimini başarıyla sağlamaktadır. Loop analizi sayesinde sistemin hidrolik dengesi sağlanmıştır.

---
*Bu proje, Marmara Üniversitesi Makine Mühendisliği Akışkanlar Mekaniği dersi kapsamında hazırlanmıştır.*
