# Wireshark HTTP Trafik Analizi

## 🎯 Amaç:
HTTP üzerinden gönderilen bir isteği Wireshark ile incelemek.

## 🧪 Uygulama:
- Site: http://neverssl.com
- Wireshark filtre: `http`

## 🧠 Gözlemler:
- Tarayıcı, `GET /` isteği yolladı
- Sunucudan `HTTP/1.1 200 OK` cevabı geldi
- Host: neverssl.com
- Şifreleme yok → tüm istek ve cevaplar düz metin
<img width="962" height="461" alt="dasdasdasdas" src="https://github.com/user-attachments/assets/a4bff4fc-d995-4182-9331-9e45704175b9" /> (Wireshark kaydından alınmıştır.)

## 📅 Tarih: 10.07.2025
