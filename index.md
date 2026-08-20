---
title: Mikrobat Gizlilik Politikasi
---

# Mikrobat — Gizlilik Politikası

_Son güncelleme: 20 Ağustos 2026_

Mikrobat, laboratuvar analiz raporlarının (Certificate of Analysis) doğruluğunu kontrol etmeye yarayan bir doğrulama uygulamasıdır. Bu politika, uygulamanın hangi verileri işlediğini açıklar.

## 1. İşlenen veriler

### Rapor doğrulama (giriş gerektirmez)

Uygulamayı yalnızca bir raporu doğrulamak için kullanıyorsanız hesap açmanız gerekmez ve sizden **hiçbir kişisel veri toplanmaz**. Girdiğiniz rapor numarası ve doğrulama anahtarı yalnızca ilgili raporu getirmek için sunucuya iletilir; kimliğinizle ilişkilendirilmez ve saklanmaz.

### Laboratuvar yöneticisi girişi

Yalnızca laboratuvar personeline ait yönetici hesapları için:

- **E-posta adresi** — hesabı tanımlamak ve giriş yapmak için.
- **Şifre** — şifreler asla düz metin olarak saklanmaz; kimlik doğrulama sağlayıcısı tarafından tek yönlü şifrelenerek (hash) tutulur ve tarafımızca görülemez.

Yönetici hesapları uygulama içinden açılmaz; laboratuvar tarafından oluşturulur ve verilir.

### Rapor içerikleri

Yöneticiler tarafından oluşturulan raporlar madde adı, CAS numarası, parti/lot numarası, analiz sonuçları, test tarihleri ve analist adı gibi laboratuvara ait teknik verileri içerir. Bunlar laboratuvarın iş verisidir; uygulamayı doğrulama için kullanan kişilerden toplanan veriler değildir.

## 2. Toplanmayan veriler

- Konum verisi toplanmaz.
- Kişi rehberi, fotoğraf, kamera veya mikrofon verisine erişilmez.
- Reklam kimliği (IDFA) kullanılmaz, reklam gösterilmez.
- Üçüncü taraf analitik veya izleme (tracking) araçları kullanılmaz.
- Hiçbir veri reklam amacıyla satılmaz veya paylaşılmaz.

## 3. Veriler nerede saklanıyor

Veriler, altyapı sağlayıcımız **Supabase** (PostgreSQL veritabanı, kimlik doğrulama ve REST API) üzerinde barındırılır. Uygulama ile sunucu arasındaki tüm iletişim HTTPS/TLS ile şifrelenir. Erişim, veritabanı düzeyinde satır bazlı güvenlik (Row Level Security) kurallarıyla sınırlandırılmıştır: doğrulama ekranı yalnızca doğru rapor numarası *ve* doğrulama anahtarının birlikte girildiği tek bir raporu döndürebilir, rapor listesine erişemez.

## 4. Saklama süresi ve silme

Raporlar, laboratuvar tarafından silinene kadar saklanır. Yönetici hesabınızın ve ilgili verilerin silinmesini istiyorsanız aşağıdaki e-posta adresinden talep edebilirsiniz; talebiniz 30 gün içinde yerine getirilir.

## 5. Çocuklar

Uygulama 13 yaş altındaki çocuklara yönelik değildir ve bilerek onlardan veri toplamaz.

## 6. Değişiklikler

Bu politika güncellenirse, yukarıdaki "Son güncelleme" tarihi değiştirilir.

## 7. İletişim

Gizlilikle ilgili tüm sorular ve veri silme talepleri için: **m.hsyngl@gmail.com**

---

# Mikrobat — Privacy Policy

_Last updated: 20 August 2026_

Mikrobat is a verification app that lets anyone check the authenticity of a laboratory Certificate of Analysis. This policy explains what data the app processes.

## 1. Data we process

### Report verification (no sign-in)

If you use the app only to verify a report, no account is required and **no personal data is collected from you**. The report number and verification key you type are sent to the server solely to retrieve that one report; they are not linked to your identity and are not stored.

### Laboratory administrator sign-in

For laboratory staff accounts only:

- **Email address** — to identify the account and sign in.
- **Password** — never stored in plain text; stored as a one-way hash by our authentication provider and not visible to us.

Administrator accounts cannot be created inside the app; they are provisioned by the laboratory.

### Report content

Reports created by administrators contain laboratory technical data such as substance name, CAS number, batch/lot number, analytical results, test dates and analyst name. This is the laboratory's business data, not data collected from people who use the app to verify a report.

## 2. Data we do NOT collect

- No location data.
- No access to contacts, photos, camera or microphone.
- No advertising identifier (IDFA); no ads.
- No third-party analytics or tracking SDKs.
- No data is ever sold or shared for advertising purposes.

## 3. Where data is stored

Data is hosted on **Supabase** (PostgreSQL database, authentication and REST API). All traffic between the app and the server is encrypted with HTTPS/TLS. Access is restricted at the database level with Row Level Security: the public verification screen can only return a single report when the correct report number *and* verification key are supplied together, and cannot list reports.

## 4. Retention and deletion

Reports are retained until deleted by the laboratory. To request deletion of an administrator account and its associated data, contact us at the address below; requests are fulfilled within 30 days.

## 5. Children

The app is not directed at children under 13 and does not knowingly collect data from them.

## 6. Changes

If this policy changes, the "Last updated" date above will be revised.

## 7. Contact

For any privacy question or data deletion request: **m.hsyngl@gmail.com**
