# Zihin Aynası (CogniFlex) 🧠✨

**Zihin Aynası**, yapay zeka destekli bir bilişsel gelişim ve öz-yansıtma (self-reflection) uygulamasıdır. Kullanıcılara karmaşık yaşam ikilemleri sunarak, bu tercihler üzerinden psikolojik bir profil çıkarır ve bilişsel yeteneklerini "Bilinç Yaşı" ve "Zihinsel Duygu Takvimi" gibi metriklerle takip etmelerini sağlar.

## 🚀 Öne Çıkan Özellikler

* **AI Destekli Senaryo Motoru:** `Google Gemini 2.5 Flash` modeli ile her seviyede benzersiz, rasyonel ve psikolojik derinliği olan etik ikilemler oluşturur.
* **Atmosferik Senaryo Motoru:** Seviye başlangıçlarında rastgele çevresel durumlar (Sisli, Fırtınalı vb.) belirleyerek senaryolara atmosferik derinlik katar.
* **Bilişsel Profilleme:** Kararlarınıza göre (Riskli, Empatik, Stratejik) "Gezgin", "Bilge Ruh" veya "Stratejist" gibi bilişsel profillerinizi günceller.
* **Göz Konforu Modu:** `_eyeComfortMode` özelliği ile arayüzü Cyan/Turuncu tema modları arasında dinamik olarak değiştirerek kullanıcı deneyimini kişiselleştirir.
* **Zihinsel Duygu Takvimi:** Geçmiş kararlarınızı görselleştirmek için `PsychologicalCalendar` (Custom GridView) kullanır.
* **Oyunlaştırma:** Başarı sembolleri (Kriz Kristali, Mantık Asası vb.) ve `Confetti` animasyonları ile ödüllendirme sistemi.

## 🛠 Teknik Altyapı (Tech Stack)

| Kategori | Teknoloji / Kütüphane |
| :--- | :--- |
| **Framework** | Flutter (Dart) |
| **Yapay Zeka** | Google Gemini API (gemini-2.5-flash) |
| **Görsel Üretim** | Pollinations AI |
| **İstatistik & Grafik** | FL Chart & Custom GridView |
| **Metin Okuma** | Flutter TTS |
| **Oyunlaştırma** | Confetti |
| **Veri Kalıcılığı** | Shared Preferences |

## Görseller
<img width="337" height="593" alt="image" src="https://github.com/user-attachments/assets/edc4a431-3add-4fb4-a8d0-392240e091a0" />
<img width="337" height="592" alt="image" src="https://github.com/user-attachments/assets/c25f2e32-9710-4438-8586-10a935b9012a" />
<img width="336" height="596" alt="image" src="https://github.com/user-attachments/assets/4cc26fb9-6b0f-4a4c-9d3d-2e43cf1d0f5a" />
<img width="337" height="596" alt="image" src="https://github.com/user-attachments/assets/6b06cf98-22ee-4843-a98c-1901a8c5ec27" />
<img width="337" height="592" alt="image" src="https://github.com/user-attachments/assets/d3a76ee9-5fa3-47b3-a7dd-42327c69ee40" />
<img width="335" height="597" alt="image" src="https://github.com/user-attachments/assets/46fcb1de-ee15-481d-9818-055cc6f5a1c9" />
<img width="334" height="593" alt="image" src="https://github.com/user-attachments/assets/2730d67e-3bc7-43fa-92a9-5ba8a6d41919" />


## 🧠 Mimari Yapı

- **Prompt Engineering:** Gemini'ye gönderilen "System Prompt" ile ikilemler JSON formatında alınır ve görsel betimlemeleri `Pollinations AI` ile eşleştirilir.
- **Analitik Motoru:** Kullanıcının tercihleri; seviye, süre ve karar türü (tag) parametreleri ile `ScoreEntry` modeline işlenerek yerel veritabanında saklanır.
- **Veri Görselleştirme:** Kullanıcının psikolojik yolculuğu, `PsychologicalCalendar` özel widget'ı ile geçmişe dönük takvim görünümünde sunulur.

---
*CogniFlex - Kendi Zihninde Bir Yolculuğa Çık.*
