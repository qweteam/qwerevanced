# ReVanced Magisk Modülü
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/qweteamrevanced)
[![Build Modules](https://github.com/qweteam/qwerevanced/actions/workflows/build.yml/badge.svg?event=release)](https://github.com/qweteam/qwerevanced/actions/workflows/build.yml)
[![CI](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml)

> **Orijinal Proje Sahibi:** Bu repo, [j-hc/revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module) projesinin altyapısı kullanılarak oluşturulmuştur. Emekleri için orijinal geliştiriciye teşekkürler.

Kapsamlı ReVanced Derleyicisi  

En son [CI sürümünü indirin](https://github.com/j-hc/revanced-magisk-module/releases).

Eğer Magisk modülleri kullanıyorsanız, YouTube'u ve YT Music'i Play Store güncellemelerinden ayırmak için [**zygisk-detach**](https://github.com/zygisk-detach/zygisk-detach) kullanın.

<details><summary><big>Özellikler</big></summary>
<ul>
 <li> Mevcut ve gelecekteki tüm ReVanced uygulamalarını destekler (aynı API'yi uygulayan projeler dahil)</li>
 <li> Magisk modülleri ve root gerektirmeyen (non-root) APK'lar oluşturabilir</li>
 <li> En son uygulama ve yama sürümleriyle günlük olarak güncellenir</li>
 <li> APK'ları ve modülleri boyut açısından optimize eder</li>
 <li> Modüller;</li>
    <ul>
     <li> Daha hızlı kullanım için geçersiz kılınan odex dosyalarını yeniden derler</li>
     <li> Magisk uygulamasından güncelleme alabilir</li>
     <li> SafetyNet'i bozmaz veya root tespitini tetiklemez</li>
     <li> Orijinal uygulamanın doğru sürümünün kurulumunu ve her şeyi yönetir</li>
     <li> Magisk ve KernelSU'yu destekler</li>
    </ul>
</ul>
</details>

## Modüllerin klasik bağlama (mount) yöntemiyle ilgili sorun yaşıyorsanız
Örneğin;
- Yeniden başlatmalardan sonra **"Yeniden flaşlama gerekiyor"** hatası
- Root tespiti yapan uygulamalardan gelen **"Şüpheli bağlama tespit edildi"** uyarıları

[rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount) kullanmayı değerlendirebilirsiniz.

## Yerel Olarak Derleme
### Termux Üzerinde
```console
bash <(curl -sSf [https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh](https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh))
# ReVanced Magisk Modülü
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/qweteamrevanced)
[![Build Modules](https://github.com/qweteam/qwerevanced/actions/workflows/build.yml/badge.svg?event=release)](https://github.com/qweteam/qwerevanced/actions/workflows/build.yml)
