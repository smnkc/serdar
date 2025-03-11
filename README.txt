Hosting Yükleme Talimatları

Bu klasördeki dosyalar, web sitenizin host'a yüklenmesi gereken dosyalarıdır. Aşağıdaki adımları takip ederek sitenizi yayına alabilirsiniz:

1. dist klasöründeki tüm dosyaları hosting sağlayıcınızın sunucusuna yükleyin:
   - index.html
   - assets/ klasörü ve içindeki tüm dosyalar

2. Önemli Notlar:
   - Tüm dosyaları ana dizine (public_html, www veya hosting sağlayıcınızın belirlediği dizin) yükleyin
   - assets klasörünün yapısını bozmadan, olduğu gibi yükleyin
   - index.html dosyası ana dizinde olmalıdır

3. Yükleme Sonrası:
   - Dosyaları yükledikten sonra sitenize erişebilirsiniz
   - Herhangi bir sorun yaşarsanız:
     * index.html dosyasının ana dizinde olduğunu kontrol edin
     * assets klasörünün tüm içeriğinin doğru yüklendiğinden emin olun
     * Hosting sağlayıcınızın sunucu ayarlarının React uygulamaları için uygun olduğundan emin olun

Not: Bu bir single-page application (SPA) olduğu için, hosting sağlayıcınızın 404 yönlendirmelerini index.html'e yapılandırmanız gerekebilir. Bu ayar için hosting sağlayıcınızın dokümantasyonunu kontrol edin.