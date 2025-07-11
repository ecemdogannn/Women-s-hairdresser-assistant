Kuaför Randevu Asistanı Otomasyonu (n8n Workflow)
Bu proje, n8n otomasyon platformu kullanılarak oluşturulmuş, Telegram üzerinden kuaför salonu randevularını yönetmeye yarayan bir asistan botudur.

Ana Özellikler:
Telegram Bot Trigger: Kullanıcılardan gelen mesajları tetikler ve komutları algılar.

Yapay Zeka Destekli Chat: LangChain ile entegre edilen AI Agent, samimi ve profesyonel bir kadın kuaförü asistanı olarak kullanıcılarla etkileşime geçer.

Google Takvim Entegrasyonu: Randevuları Google Takvim’den çeker (RandevuAl) ve yeni randevuları takvime kaydeder (Takvimle).

PostgreSQL Veritabanı: Randevu detaylarını randevular tablosuna kaydeder ve yönetir.

Zaman ve Gün Kısıtlamaları: Kuaförün çalışma saatlerine ve kapalı günlerine göre randevu taleplerini otomatik olarak kontrol eder ve uygunsa onaylar.

Güncel Saat Dilimi Desteği: Tüm tarih ve saat işlemleri Europe/Istanbul (GMT+3) zaman dilimine göre yapılır.

Teknik Detaylar:
Kullanıcıdan isim, soyisim, randevu tarihi ve saati bilgileri alınır.

Google Takvim’e randevu eklenir, mevcut takvim kayıtları kontrol edilir.

Randevu verileri PostgreSQL’e kaydedilir.

LangChain AI Agent, doğal dil işleme ile kullanıcının sorularına yanıt verir ve randevu sürecini yönetir.

Neden Bu Proje?
Kadın kuaförlerine özel olarak tasarlanmış, müşteri deneyimini kolaylaştıran ve randevu yönetimini otomatikleştiren pratik bir çözüm sunar. Böylece hem işletme sahipleri hem de müşteriler zaman kaybetmeden hızlı ve etkili randevu işlemi gerçekleştirebilir.
