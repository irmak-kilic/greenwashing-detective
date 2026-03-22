# 🌿 Greenwashing Dedektifi

**AI destekli şirket sürdürülebilirlik analiz aracı**

🔗 **Canlı Demo:** [greenwashing-detective.netlify.app](https://greenwashing-detective.netlify.app)

---

## Nedir?

Greenwashing Dedektifi, şirketlerin sürdürülebilirlik iddialarını **Gemini AI** kullanarak gerçek zamanlı analiz eden ve manipülasyon taktiklerini tespit eden bir web uygulamasıdır.

Bir şirket adı yaz → AI internette araştırsın → greenwashing skoru ve detaylı analiz al.

---

## Özellikler

- **5 Adımlı AI Agent** — Web araştırması, sektör tespiti, taktik analizi, skor hesaplama, rapor üretimi
- **10 Sektöre Özel Analiz** — Tekstil, enerji, finans, otomotiv, gıda ve daha fazlası
- **50+ Şirket Demo** — API kotası olmadan anında sonuç (Shell, Zara, Tüpraş, THY, ExxonMobil...)
- **Manipülasyon Skoru** — 0-100 arası, güven seviyeleriyle
- **Sektör Kırmızı Çizgileri** — Her sektörün kendine özgü kriterleri
- **Şirket Karşılaştırma** — İki şirketi yan yana analiz et
- **Analiz Geçmişi** — Son 20 analiz kaydedilir
- **Kaynakça** — Gemini'nin başvurduğu web kaynakları listelenir
- **PDF Rapor** — Analizi indir
- **QR Kod** — Sonucu paylaş
- **Router** — 5 sayfalı navigasyon (/, /analiz, /sonuc, /karsilastir, /gecmis)

---

## Tespit Edilen Greenwashing Taktikleri

| Taktik | Açıklama |
|---|---|
| Vague Language | Ölçülemeyen, belirsiz iddialar |
| Cherry-Picked Metrics | Sadece iyi verileri öne çıkarma |
| Carbon Offset Overreliance | Gerçek azaltım yerine offset satın alma |
| Missing Baselines | Referans yıl olmadan yüzde değişim |
| Scope 3 Omissions | Tedarik zinciri emisyonlarını gizleme |
| Future-Tense Promises | Hesap sorulmayan uzak vadeli hedefler |
| Relative vs Absolute Targets | Yoğunluk hedefleriyle mutlak artışı gizleme |
| Third-Party Verification Absent | Bağımsız denetim olmadan öz-beyan |
| Misleading Framing | Teknik doğru ama yanıltıcı çerçeveleme |

---

## Teknoloji

- **Frontend:** React 18 (CDN), Babel Standalone
- **AI:** Google Gemini API (gemini-2.5-flash) + Web Grounding
- **Deploy:** Netlify
- **Mimari:** Tek dosya (`index.html`) — sıfır build adımı

---

## Kullanım

1. [aistudio.google.com](https://aistudio.google.com) → ücretsiz Gemini API key al
2. Uygulamaya gir, API key'i gir
3. Şirket adını yaz → Analiz Et

> Demo şirketler API key olmadan da çalışır.

---

## Proje Hakkında

Bu proje **Future Talent Program 201 — Yapay Zeka Bitirme Projesi** kapsamında geliştirilmiştir.

Geliştirici: [Irmak Kılıç](https://github.com/irmak-kilic) — Bahçeşehir Üniversitesi, Endüstri Mühendisliği
