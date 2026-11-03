# HMM Servis — Android APK dağıtımı

Bu depo yalnızca **HMM Servis** Android uygulamasının APK dosyalarını dağıtmak için kullanılır. Kaynak kod bu depoda bulunmaz.

## Kurulum

1. [Releases](https://github.com/Methdemir/hmm-servis/releases/latest) sayfasından son sürümün `.apk` dosyasını indirin.
2. Android sorarsa tarayıcıya veya dosya yöneticisine "bilinmeyen uygulamaları yükle" izni verin.
3. APK'yı açıp **Yükle** / **Güncelle**'ye dokunun.

Mevcut kurulumun üzerine güncelleme yapıldığında veriler ve oturum korunur.

## Uygulama içi güncelleme

`0.7.1` ve sonraki sürümler, uygulama açıldığında bu depodaki son kararlı sürümü denetler. Yeni sürüm varsa güncelleme önerilir; güncelleme isteğe bağlıdır. İndirilen dosya kurulmadan önce boyut, SHA-256 özeti, paket adı ve imza sertifikasıyla doğrulanır.

`0.7.0` ve öncesinde güncelleyici yoktur; bu sürümlerden geçerken APK bir kez elle kurulmalıdır.

## Doğrulama

- Paket adı: `com.sarperstudios.hmm`
- İmza sertifikası SHA-256: `767b21af25df755c59a2650d00c9fcf80f125a6c437d8f86e2c08eebb61184e7`
- Her APK'nın SHA-256 özeti Releases sayfasında dosyanın yanında görünür.
