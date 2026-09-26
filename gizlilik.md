---
title: Gizlilik Politikası
---


Son güncelleme: 26 Eylül 2026

Bu politika, Atenso tarafından geliştirilen Growia Android uygulamasının ("Uygulama") hangi verileri, hangi amaçla ve nasıl işlediğini açıklar. Sorularınız için atensostudio@gmail.com adresine yazabilirsiniz.

## Özet

- Uygulamayı hesap açmadan kullanabilirsiniz. Bu durumda verileriniz yalnızca telefonunuzda saklanır.
- Google hesabıyla giriş isteğe bağlıdır. Giriş yaparsanız bitki, bakım geçmişi ve hatırlatıcı bilgileriniz Google Firebase üzerinde hesabınıza yedeklenir.
- Fotoğraflarınız hiçbir zaman sunucuya yüklenmez.
- Akıllı Araçlar'daki ışık ölçümü, sulama ölçümü ve bitki sağlığı analizi ile kamerayla bitki tanıma tamamen telefonunuzda çalışır; kamera görüntüleri hiçbir yere gönderilmez. Tanıma internet bağlantısı gerektirmez.
- Uygulamanın ana ekranlarının altında Google AdMob reklamları gösterilir. Bunun için Google, reklam kimliği gibi cihaz bilgilerini işleyebilir. Bitkileriniz, notlarınız ve fotoğraflarınız reklam için kullanılmaz.
- Uygulamada analiz aracı yoktur. Verileriniz satılmaz.

## Telefonunuzda saklanan veriler

- Eklediğiniz bitkiler, bitkilere verdiğiniz takma adlar ve notlar
- Bakım geçmişi (sulama, gübreleme gibi kayıtlar) ve hatırlatıcılar
- Oluşturduğunuz kurtarma planları ve adımların tamamlanma durumu (bulut yedeğine eklenmez)
- Kamerayla çektiğiniz veya galeriden seçtiğiniz bitki fotoğrafları ve fotoğraf notları
- Yazı boyutu ve "Evimde yaşayanlar" (kedi, köpek, küçük çocuk) gibi uygulama ayarları. Evinizdekilerle ilgili seçim yalnızca zehirli bitki uyarıları için kullanılır ve hiçbir yere gönderilmez.
- Ana ekran widget'ı ve rozetler ayrı bir veri tutmaz; telefondaki bitki ve bakım kayıtlarınızdan hesaplanır.

Akıllı Araçlar'da (Işık Ölçer, Sulama Ölçer, Saksı Kontrolü, Sağlık Analizi) çektiğiniz ya da seçtiğiniz fotoğraflar yalnızca analiz için geçici olarak kullanılır ve araçtan çıkınca silinir. Sağlık analizinin fotoğrafını bir bitkinizin günlüğüne eklemeyi ya da kurtarma planı oluşturmayı seçerseniz fotoğraf ve kısa analiz notu diğer günlük fotoğraflarınız gibi saklanır. Pencere Pusulası telefonun yön sensörünü kullanır; izin gerektirmez ve konum bilgisi alınmaz.

Bu veriler uygulamanın telefondaki özel alanında tutulur ve diğer uygulamalarla paylaşılmaz. Fotoğraflar kaydedilirken küçültülür; fotoğrafın içindeki konum dahil ek bilgiler (EXIF) saklanmaz, yalnızca çekim tarihi okunur.

Android'in Google hesabına otomatik yedeklemesine yalnızca yazı boyutu gibi uygulama tercihleri dahil edilir; bitkileriniz, notlarınız, bakım geçmişiniz ve fotoğraflarınız bu yedeğe girmez. Android 12 veya üzeri bir telefondan yeni telefona kabloyla ya da doğrudan aktarım yaptığınızda ise bu veriler fotoğraflarla birlikte yeni telefona taşınır; bu aktarım buluta gönderilmez. Hesap bilgileriniz aktarılmaz; bulut yedeğini kullanmak için yeni telefonda yeniden giriş yapmanız gerekir.

## İzinler

- Bildirimler: bakım zamanı ve kurtarma planı adımları geldiğinde hatırlatma göstermek için.
- Alarmlar ve hatırlatıcılar: hatırlatmaları zamanında göstermek için.
- Kamera: yalnızca siz bir bitki fotoğrafı çekmek ya da Akıllı Araçlar'ı kullanmak istediğinizde. Kamera görüntüsü telefonunuzda işlenir; kaydedilmez ve gönderilmez.
- İnternet: Google ile giriş, bulut yedeği ve reklamların yüklenmesi için.
- Reklam kimliği: Google AdMob reklamlarını göstermek ve ölçmek için.
- Yaklaşık konum: yalnızca bitki bilgi sayfasındaki "Nerede yetişir?" bölümünde "Konumumu kullan" butonuna bastığınızda. Konumunuz, iklimi size en yakın örnek şehri bulmak için o anda okunur; telefonda saklanmaz, hiçbir yere gönderilmez ve reklam için kullanılmaz. İzni vermeseniz de bölüm çalışır, şehri listeden kendiniz seçersiniz.

Uygulama rehber, mikrofon veya telefon izni istemez; hassas (GPS) konum izni de istemez.

## Google hesabıyla giriş ve bulut yedeği (isteğe bağlı)

Google ile giriş yaptığınızda:

- Hesabınızı tanımak için Firebase Authentication, Google hesabınıza ait e-posta adresinizi, adınızı, profil fotoğrafı bağlantınızı ve size özel bir kullanıcı kimliğini işler.
- Cloud Firestore'da yalnızca sizin hesabınızın erişebildiği bir alanda şu bilgiler saklanır: bitkileriniz (katalogdaki bitki türü, takma ad, not, eklenme tarihi), bakım geçmişiniz ve hatırlatıcılarınız.
- Fotoğraflar ve fotoğraf notları yedeklenmez, telefonunuzda kalır.

Bu verilerin işlenme amacı, verilerinizi kaybetmemeniz ve telefon değiştirdiğinizde geri yükleyebilmenizdir. Veriler şifreli bağlantı (TLS) üzerinden aktarılır. Firebase hizmetleri Google tarafından sağlanır; veriler Google'ın veri merkezlerinde, Türkiye dışında işlenebilir. Hizmetin sunulması ve güvenliği için bağlantı sırasında IP adresi gibi teknik bilgiler Google tarafından işlenebilir. Ayrıntılar için Firebase gizlilik açıklamasına bakabilirsiniz: firebase.google.com/support/privacy

## Reklamlar (Google AdMob)

Uygulamanın ana ekranlarının en altında Google AdMob tarafından sunulan banner reklamlar gösterilir. Reklamların gösterilmesi, ölçülmesi ve kötüye kullanımın önlenmesi için Google şu bilgileri işleyebilir:

- Android reklam kimliği (telefonunuzun Ayarlar > Google > Reklamlar bölümünden sıfırlayabilir ya da silebilirsiniz)
- IP adresi ve buna dayalı yaklaşık konum
- Cihaz ve uygulama bilgileri (model, işletim sistemi sürümü, dil)
- Reklamlarla etkileşimler (gösterim, tıklama)

Bitkileriniz, notlarınız, bakım geçmişiniz ve fotoğraflarınız reklam için kullanılmaz ve Google'a gönderilmez. Avrupa Ekonomik Alanı ve İngiltere gibi onay gerektiren bölgelerde Uygulama, kişiselleştirilmiş reklamlar için Google'ın onay formunu gösterir; tercihinizi Ayarlar > Reklam gizlilik seçenekleri bölümünden değiştirebilirsiniz. Google'ın reklam verilerini nasıl kullandığı: policies.google.com/technologies/ads

## Premium abonelik ve ödeme

Premium abonelik Google Play üzerinden satın alınır; ödeme, fatura ve kart bilgileriniz yalnızca Google tarafından işlenir ve Uygulama bunları hiçbir zaman görmez. Uygulama, Premium'un açık olup olmadığını anlamak için Google Play'den yalnızca aboneliğinizin durumunu (etkin olup olmadığını) sorgular ve bu durumu telefonunuzda saklar. Aboneliğinizi Google Play > Ödemeler ve abonelikler bölümünden yönetebilir ya da iptal edebilirsiniz.

## Uygulama içi değerlendirme

Uygulama bir kez, Google Play'in kendi değerlendirme penceresini gösterebilir. Verdiğiniz puan ve yorum doğrudan Google Play'e gider; Uygulama bunları göremez.

## Çökme raporları (Firebase Crashlytics)

Uygulama çökerse, hatanın teknik ayrıntıları (hangi ekranda ve hangi kod satırında olduğu), cihaz modeli, Android ve Uygulama sürümü ile rastgele bir kurulum kimliği Google'ın Firebase Crashlytics hizmetine gönderilir. Bu bilgiler yalnızca hataları bulup düzeltmek için kullanılır ve 90 gün saklanır. Bitkileriniz, fotoğraflarınız, notlarınız ve hesap bilgileriniz gönderilmez. Ayarlar > Çökme raporlarını gönder anahtarıyla bu gönderimi istediğiniz zaman kapatabilirsiniz.

## Verilerin paylaşılması

Verilerinizi üçüncü taraflara satmayız ve kiralamayız. Bulut yedeği için Google (Firebase), reklamlar için Google (AdMob) yukarıda açıklanan bilgileri işler. Yasal bir zorunluluk olması hâlinde veriler yetkili makamlarla paylaşılabilir.

## Saklama süresi ve silme

- Telefonunuzdaki veriler, siz silene veya Uygulamayı kaldırana kadar saklanır.
- Buluttaki yedek, hesabınız var olduğu sürece saklanır ve her yedeklemede bir öncekinin yerine geçer.
- Uygulamada Ayarlar > Hesabımı ve verilerimi sil adımıyla hesabınızı ve buluttaki tüm yedeğinizi kalıcı olarak silebilirsiniz. Telefonunuzdaki veriler bu işlemle silinmez.
- Uygulamaya erişiminiz yoksa, giriş yaptığınız Google hesabının e-posta adresinden atensostudio@gmail.com adresine "Hesap silme talebi" konulu bir e-posta göndererek silme isteyebilirsiniz. Talepler en geç 30 gün içinde sonuçlandırılır.

## Haklarınız

6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) ve bulunduğunuz ülkenin mevzuatı kapsamında; verilerinizin işlenip işlenmediğini öğrenme, bilgi talep etme, düzeltilmesini veya silinmesini isteme ve işlenmesine itiraz etme haklarına sahipsiniz. Taleplerinizi atensostudio@gmail.com adresine iletebilirsiniz.

## Çocuklar

Uygulama genel kullanıcı kitlesine yöneliktir ve 13 yaşından küçük çocuklara özel olarak tasarlanmamıştır. 13 yaşından küçük bir çocuğun hesap açtığını düşünüyorsanız bize yazın; ilgili verileri sileriz.

## Değişiklikler

Bu politika güncellenirse yukarıdaki tarih değişir. Önemli değişiklikler Uygulama içinde duyurulur.

## İletişim

Atenso — atensostudio@gmail.com
