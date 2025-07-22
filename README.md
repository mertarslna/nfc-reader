# NFC Reader

Android cihazlar için geliştirilmiş, NFC kartlarının UID bilgisini kolayca okumanızı sağlayan açık kaynaklı bir uygulamadır. Modern Android (Kotlin + Jetpack Compose) teknolojileriyle yazılmıştır.

## Özellikler

- NFC desteği olan Android cihazlarda çalışır.
- Kart okutulduğunda UID bilgisini ekranda gösterir.
- NFC kapalıysa kullanıcıyı uyarır ve ayarlara yönlendirir.
- Basit ve modern kullanıcı arayüzü.

## Kurulum

### Yöntem 1: Kaynak Koddan Derleme

1. Bu repoyu klonlayın:
   ```bash
   git clone https://github.com/mertarslna/nfc-reader.git
   ```
2. Android Studio ile açın.
3. Gerçek bir cihazda (NFC destekli) veya uygun bir emülatörde çalıştırın.

### Yöntem 2: Hazır APK ile Kurulum

- Ana klasöre yüklenen `NFC-Reader.apk` dosyasını Android cihazınıza aktarın.
- Cihazınızda APK dosyasını açarak uygulamayı yükleyin.
- (Gerekirse) Ayarlardan "Bilinmeyen kaynaklara izin ver" seçeneğini aktif edin.

## Gereksinimler

- Android Studio (Arctic Fox veya üzeri) [Kaynak koddan derleme için]
- NFC destekli Android cihaz
- Minimum SDK: 21 (Android 5.0 Lollipop)

## Kullanım

1. Uygulamayı başlatın.
2. NFC özelliğinin açık olduğundan emin olun.
3. Bir NFC kartını cihazınıza yaklaştırın.
4. Kartın UID bilgisi ekranda görünecektir.

## İzinler

Uygulama, yalnızca NFC donanımına erişim izni ister:
```xml
<uses-permission android:name="android.permission.NFC" />
```

## Katkıda Bulunma

Katkılarınızı memnuniyetle karşılıyoruz! Lütfen bir pull request gönderin veya bir issue açın.

## Lisans

MIT Lisansı. Ayrıntılar için LICENSE dosyasına bakınız.
