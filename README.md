# Teknik-Servis-Ve-r-n-Takip-Sistemi
Proje Tanımı

Bu veritabanı, bir işletmenin temel operasyonlarını desteklemek üzere tasarlanmıştır. Aşağıdaki iş süreçlerini kapsayan tablolar içerir:

Kullanıcı Yönetimi: Kullanıcı giriş bilgileri (kullanıcı adı ve şifre) güvenli bir şekilde TBlKULLANICIADI tablosunda saklanır.
Müşteri Yönetimi: TBLMUSTERI tablosu, müşteri bilgilerini (ad, soyad, iletişim bilgileri, adres vb.) içerir.
Departman Yönetimi: Şirket departmanlarının isimleri ve açıklamaları TBLDEPARTMAN tablosunda saklanır.
Gider Takibi: Şirketin giderlerini takip etmek için TBLGIDER tablosu kullanılır.
Ürün Yönetimi:
Ürün bilgileri (isim, marka, fiyat, stok durumu) TBLURUN tablosunda tutulur.
Ürün kategorileri TBLKATEGORI tablosunda yönetilir.
Ürün hareketleri (müşteri, personel, tarih vb.) TBLURUNHAREKET tablosunda kaydedilir.
Ürün kabul ve takip bilgileri TBLURUNKABUL ve TBLURUNTAKIP tablolarında saklanır.
Fatura Yönetimi:
Fatura bilgileri (seri, sıra, tarih, müşteri) TBLFaturabilgi tablosunda saklanır.
Fatura detayları (ürün, adet, fiyat) TBLFaturadetay tablosunda tutulur.
Notlar ve İş Takibi: TBLNOTLARIM tablosu, kullanıcıların önemli notlarını ve durumlarını yönetmelerine olanak tanır.
Personel Yönetimi: TBLPERSONEL tablosu, personelin ad, soyad, departman, iletişim bilgileri ve fotoğrafını içerir.
Projenin Temel Amaçları
Veri Organizasyonu: İş süreçlerini desteklemek için düzenli ve yapılandırılmış veri saklama.
Veri Bütünlüğü: Birincil ve yabancı anahtarlar aracılığıyla tablolar arasında güçlü ilişkiler oluşturulması.
Gelişmiş Analiz: Gider, gelir ve müşteri davranışları hakkında raporlar oluşturulmasına olanak tanır.
Normalizasyon: Veritabanı tasarımı 3. Normal Form’a (3NF) uygun olarak tasarlanmıştır, böylece veri tekrarları minimize edilmiştir.
Projenin Kullanım Alanları
CRM (Müşteri İlişkileri Yönetimi): Müşteri bilgilerini ve geçmişlerini takip etmek.
Fatura ve Muhasebe Yönetimi: Fatura, gider ve gelir takibi.
Envanter Yönetimi: Ürün stoklarını, hareketlerini ve kategorilerini yönetmek.
Personel Yönetimi: Çalışanların bilgilerini düzenli bir şekilde saklamak.
İş Süreçleri Takibi: Notlar ve iş durumlarıyla günlük operasyonları takip etmek.
Veritabanı İlişkileri
Müşteri - Fatura: Her müşteri birden fazla fatura oluşturabilir.
Fatura - Detaylar: Her fatura, birden fazla ürün içerebilir.
Ürün - Hareketler: Ürün hareketleri müşteriler ve personel ile ilişkilidir.
Personel - Departman: Her personel bir departmana bağlıdır.
