Proje Tanımı
Bu veritabanı, bir işletmenin temel operasyonlarını desteklemek üzere tasarlanmıştır. Aşağıdaki iş süreçlerini kapsayan tablolar içerir:
1.	Kullanıcı Yönetimi: Kullanıcı giriş bilgileri (kullanıcı adı ve şifre) güvenli bir şekilde TBlKULLANICIADI tablosunda saklanır.
2.	Müşteri Yönetimi: TBLMUSTERI tablosu, müşteri bilgilerini (ad, soyad, iletişim bilgileri, adres vb.) içerir.
3.	Departman Yönetimi: Şirket departmanlarının isimleri ve açıklamaları TBLDEPARTMAN tablosunda saklanır.
4.	Gider Takibi: Şirketin giderlerini takip etmek için TBLGIDER tablosu kullanılır.
5.	Ürün Yönetimi:
o	Ürün bilgileri (isim, marka, fiyat, stok durumu) TBLURUN tablosunda tutulur.
o	Ürün kategorileri TBLKATEGORI tablosunda yönetilir.
o	Ürün hareketleri (müşteri, personel, tarih vb.) TBLURUNHAREKET tablosunda kaydedilir.
o	Ürün kabul ve takip bilgileri TBLURUNKABUL ve TBLURUNTAKIP tablolarında saklanır.
6.	Fatura Yönetimi:
o	Fatura bilgileri (seri, sıra, tarih, müşteri) TBLFaturabilgi tablosunda saklanır.
o	Fatura detayları (ürün, adet, fiyat) TBLFaturadetay tablosunda tutulur.
7.	Notlar ve İş Takibi: TBLNOTLARIM tablosu, kullanıcıların önemli notlarını ve durumlarını yönetmelerine olanak tanır.
8.	Personel Yönetimi: TBLPERSONEL tablosu, personelin ad, soyad, departman, iletişim bilgileri ve fotoğrafını içerir.
________________________________________
Projenin Temel Amaçları
•	Veri Organizasyonu: İş süreçlerini desteklemek için düzenli ve yapılandırılmış veri saklama.
•	Veri Bütünlüğü: Birincil ve yabancı anahtarlar aracılığıyla tablolar arasında güçlü ilişkiler oluşturulması.
•	Gelişmiş Analiz: Gider, gelir ve müşteri davranışları hakkında raporlar oluşturulmasına olanak tanır.
•	Normalizasyon: Veritabanı tasarımı 3. Normal Form’a (3NF) uygun olarak tasarlanmıştır, böylece veri tekrarları minimize edilmiştir.
________________________________________
Projenin Kullanım Alanları
•	CRM (Müşteri İlişkileri Yönetimi): Müşteri bilgilerini ve geçmişlerini takip etmek.
•	Fatura ve Muhasebe Yönetimi: Fatura, gider ve gelir takibi.
•	Envanter Yönetimi: Ürün stoklarını, hareketlerini ve kategorilerini yönetmek.
•	Personel Yönetimi: Çalışanların bilgilerini düzenli bir şekilde saklamak.
•	İş Süreçleri Takibi: Notlar ve iş durumlarıyla günlük operasyonları takip etmek.
________________________________________
Veritabanı İlişkileri
•	Müşteri - Fatura: Her müşteri birden fazla fatura oluşturabilir.
•	Fatura - Detaylar: Her fatura, birden fazla ürün içerebilir.
•	Ürün - Hareketler: Ürün hareketleri müşteriler ve personel ile ilişkilidir.
•	Personel - Departman: Her personel bir departmana bağlıdır.

