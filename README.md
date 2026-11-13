<h1 align="center">GaxDPI</h1>

<p align="center"><strong>Windows için tepsi simgesinden yönetilen bir ağ aracı.</strong></p>

<p align="center">
  <a href="https://github.com/GaxCode/GaxDPI-Releases/releases/latest"><img src="https://img.shields.io/github/v/release/GaxCode/GaxDPI-Releases?style=for-the-badge&label=Son%20s%C3%BCr%C3%BCm" alt="Son sürüm"></a>
  <a href="https://github.com/GaxCode/GaxDPI-Releases/releases/latest"><img src="https://img.shields.io/github/downloads/GaxCode/GaxDPI-Releases/total?style=for-the-badge&label=Downloads" alt="Toplam indirme"></a>
  <img src="https://img.shields.io/badge/Windows-x64-0078D4?style=for-the-badge&logo=windows" alt="Windows x64">
</p>

<p align="center"><strong><a href="https://github.com/GaxCode/GaxDPI-Releases/releases/latest">Son sürümü indir</a></strong></p>

---

GaxDPI, Windows'ta bazı bağlantı ve erişim sorunlarında kullanılabilecek bir uygulamadır. VPN değildir; her ağda veya uygulamada çalışacağı garanti edilmez.

## Uygulama hakkında

GaxDPI, Windows'ta bazı site ve uygulamalardaki bağlantı sorunlarını azaltmaya yardımcı olur. HTTP ve TLS bağlantı paketlerini etkin profildeki ayarlara göre parçalara ayırır; isteğe bağlı DNS yönlendirmesi sunar. VPN tüneli kurmaz veya tüm trafiği uzak bir sunucuya taşımaz; trafiği şifrelemez ve IP adresinizi gizlemez.

- Ana pencerede çalışma durumu, uygulama sürümü ve etkin profil bilgileri gösterilir.
- Tepsi menüsünden uygulamayı başlatabilir veya durdurabilir, güncellemeleri denetleyebilirsiniz.
- Sonuçlar ağınıza ve kullandığınız hizmete göre değişebilir.

GaxDPI x64 Windows için hazırlanmıştır.

## İndirme ve başlama

1. Yukarıdaki GitHub Releases sayfasından `GaxDPI.exe` dosyasını indirin.
2. Dosyayı çalıştırın. İlk kurulumda GaxDPI hizmetini yüklemek için Windows yönetici izni ister.
3. GaxDPI bildirim alanında açılır. Ana pencereden ya da tepsi simgesine sağ tıklayıp **Başlat / Durdur** seçerek çalışmasını yönetin.

Hizmet kurulduktan sonra uygulamayı normal kısayolundan açarken yönetici izni istenmez. GaxDPI kısayolu Başlat menüsünün tüm uygulamalar listesine eklenir; Windows'un **Son eklenenler** bölümünde gösterilmesi Windows sürümüne ve bu bölümün ayarına bağlıdır. Windows oturum açılışında başlatma ilk kurulumda kapalıdır; isterseniz tepsi menüsünden açabilirsiniz. Güncellemelerden sonra bu tercihiniz korunur. Tepsi simgesine sol tıklamak pencereyi gösterir veya gizler. Pencereyi kapatmak uygulamadan çıkmaz; uygulamayı tamamen kapatmak için tepsi menüsünden **Çıkış** seçin.

Aktif profil kartında uygulama sürümünü görebilirsiniz.

## Yönetici izni

İlk kurulumda GaxDPI için Windows yönetici izni gerekir. Güncelleme ve kaldırma sırasında da yönetici onayı istenir. UAC penceresini yalnızca GaxDPI'ı resmî Releases sayfasından indirdiyseniz onaylayın. Kurulumdan sonra uygulamayı normal kısayolundan açabilirsiniz.

Yayınlanan EXE'nin Authenticode yayıncı imzası yoktur; Windows güvenlik uyarısı gösterebilir. Uyarıyı aşmak için Defender'ı kapatmayın veya klasör istisnası eklemeyin. Dosyanın kaynağından emin değilseniz çalıştırmayın.

GaxDPI, Windows ağ bağdaştırıcısının DNS adreslerini değiştirmez. Kaldırırken ayrıca DNS ayarlarını sıfırlamanız gerekmez.

## Güncellemeler

GaxDPI açılışta yeni sürüm olup olmadığını denetler. İstediğiniz zaman bildirim alanındaki GaxDPI simgesine sağ tıklayıp **Güncellemeleri denetle** seçeneğini kullanabilirsiniz. Yeni sürüm varsa sürüm bilgisi ve yayın notları gösterilir. **Yükle** seçeneğiyle güncelleme başlar; tamamlanınca uygulama yeniden açılır. Windows başlangıcında çalıştırma tercihiniz güncelleme sonrasında korunur. **Bu Sürümü Atla** seçilen sürümü gizler. **Daha Sonra Hatırlat** seçeneği veya pencereyi kapatmak, uygulama açık kaldığı sürece bildirimi 24 saat erteler. Tepsiden elle denetim yapmak bu tercihleri yok sayar.

Güncellemeler doğrulanır; kurulu sürümden eski bir sürüm yüklenmez.

## Kaldırma

Tepsi menüsünden **Uygulamayı ve Verileri Kaldır** seçeneğini kullanın. Kaldırma adımları ve uygulamanın değiştirdiği ayarlarla ilgili bilgi için [REVERT.md](./REVERT.md) dosyasına bakın.

## Lisans bilgisi

GaxDPI kaynak kodu bu yayında bulunmaz. Üçüncü taraf bileşenlerin lisans bilgileri Release dosyalarıyla birlikte sunulur.
