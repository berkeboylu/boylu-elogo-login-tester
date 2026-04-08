# E-Logo API Login Test Aracı

Bu proje, E-Logo API'sine bağlanarak kullanıcı girişini test etmek için basit bir PHP web uygulamasıdır. SOAP protokolü kullanarak login işlemini gerçekleştirir ve sonucu görsel bir arayüzde gösterir.

## Özellikler

- Kullanıcı dostu web arayüzü
- Karanlık/Aydınlık mod desteği
- SOAP ile E-Logo API entegrasyonu
- Hata yakalama ve detaylı yanıt gösterimi
- Responsive tasarım (Tailwind CSS)

## Gereksinimler

- PHP 8.0 veya üzeri
- SOAP extension (PHP'de etkinleştirilmiş olmalı)
- Web sunucusu (örneğin Apache, Nginx)
- Composer (opsiyonel, bağımlılık yönetimi için)

## Kurulum

1. Projeyi klonlayın veya dosyaları sunucunuza yükleyin:
   ```bash
   git clone https://github.com/berkeboylu/boylu-elogo-login-tester/
   cd boylu-elogo-login-tester
   ```

2. Web sunucusunun document root'una yerleştirin (örneğin `htdocs/` veya `www/` klasörü).

3. Tarayıcınızda `index.php` dosyasına erişin.

## Kullanım

1. Web tarayıcınızda uygulamayı açın.
2. Kullanıcı adı ve şifre alanlarını doldurun.
3. "Bağlantıyı Sına" butonuna tıklayın.
4. Sonuç raporunu inceleyin:
   - Başarılı giriş durumunda Session ID gösterilir.
   - Hata durumunda detaylı hata mesajı ve ham yanıt görüntülenir.

## Yapılandırma

Uygulama kendi kendine çalışacak şekilde yapılandırılmıştır. Sabit değerler kod içinde tanımlanmıştır:

- API URL: `https://pb.elogo.com.tr/PostBoxService.svc?wsdl`
- Varsayılan kullanıcı adı ve şifre: Boş (formdan girilir)

## Güvenlik Notları

- Bu uygulama test amaçlıdır. Üretim ortamında kullanmadan önce güvenlik önlemleri alın.
- Şifreler açık metin olarak gönderilir (SOAP üzerinden).
- HTTPS kullanın.

## Lisans

Bu proje açık kaynak kodludur. Lisans bilgilerini kontrol edin.

## Destek

Sorularınız için [destek e-posta] ile iletişime geçin.
