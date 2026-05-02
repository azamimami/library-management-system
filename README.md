# Kütüphane Yönetim Sistemi
Python ile geliştirilmiş terminal tabanlı kütüphane yönetim sistemidir. Kitap, üye ve ödünç alma işlemleri nesne yönelimli programlama (OOP) yapısı ile yönetilir.


# Özellikler

# Kitap Modülü
- Kitap ekleme
- Kitap listeleme
- Kitap durumu takibi (müsait / ödünçte)
- Kitap bilgilerini görüntüleme

# Üye Modülü
- Üye ekleme
- Üye listeleme
- Üye bilgilerini görüntüleme

# Ödünç Modülü
- Kitap ödünç alma
- Kitap iade etme
- Ödünç alma tarihi kaydı
- İade tarihi kaydı
- Ödünç geçmişi listeleme


# Kullanılan Teknolojiler

- Python 3
- Nesne Yönelimli Programlama (OOP)
- datetime modülü
- List veri yapısı
- Terminal tabanlı kullanıcı arayüzü
- In-memory veri yönetimi


# Sistem Mantığı

- Kitaplar sisteme eklenir ve durumları takip edilir
- Üyeler sisteme kayıt edilir
- Üyeler kitap ödünç alabilir
- Ödünç alınan kitap "Müsait değil" durumuna geçer
- İade edilince kitap tekrar "Müsait" olur
- Tüm işlemler ödünç geçmişinde saklanır
