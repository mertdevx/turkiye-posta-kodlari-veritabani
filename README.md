# Türkiye Posta Kodu Veritabanı

Bu proje, Türkiye'deki tüm posta kodlarını içeren bir veritabanını sağlar. Veritabanı, plaka kodu, il, ilçe, semt/bucak/belde, mahalle ve posta kodu gibi bilgilerle birlikte gelir. Bu, çeşitli projelerinizde kullanabileceğiniz kapsamlı bir kaynaktır.

## Veritabanı Detayları

- **Tablo Adı:** `posta_kodlari`
- **Sütunlar:**
  - `veri_id`: Benzersiz veri kimliği
  - `plaka`: İlin plaka kodu
  - `il`: İlin adı
  - `ilce`: İlçenin adı
  - `semt_bucak_belde`: Semt, bucak veya belde adı
  - `mahalle`: Mahallenin adı
  - `posta_kodu`: Posta kodu

## Kullanım

Bu veritabanını projelerinize entegre ederek, Türkiye'nin herhangi bir bölgesine ait posta kodu bilgilerini kolayca sorgulayabilirsiniz.

## Lisans

Bu proje [GNU Genel Kamu Lisansı](LICENSE) ile lisanslanmıştır.

---

# Turkey Postal Code Database

This project provides a comprehensive database of postal codes across Turkey. The database includes information such as license plate code, province, district, neighborhood/village/town, and postal code. It is a valuable resource that can be integrated into various projects.

## Database Details

- **Table Name:** `posta_kodlari`
- **Columns:**
  - `veri_id`: Unique data identifier
  - `plaka`: Province license plate code
  - `il`: Province name
  - `ilce`: District name
  - `semt_bucak_belde`: Neighborhood, village, or town name
  - `mahalle`: Neighborhood name
  - `posta_kodu`: Postal code

## Usage

You can integrate this database into your projects to easily query postal code information for any region in Turkey.

## License

This project is licensed under the [GNU General Public License](LICENSE).
