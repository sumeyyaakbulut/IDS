# Intrusion Detection System (IDS) – Log Analizi
Bu proje, basit bir Saldırı Tespit Sistemi (IDS) simülasyonudur.
Log dosyası parse etme → IP, zaman, HTTP method, URL, status code ve response size bilgilerini ayrıştırır.

🔎 Kural tabanlı analiz:

Dakikada 10’dan fazla istek atan IP’ler

Art arda 3 kez hatalı giriş yapan IP’ler (401/403)

Hassas sayfalara erişim girişimleri (/admin, /login, /wp-login)

✅ Pandas DataFrame ile tablo bazlı analiz

⏱️ Zaman bilgisi datetime tipine dönüştürülür

