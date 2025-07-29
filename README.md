
# Gg games - Dijital Evren Projesi

Modern, tek sayfalık bir web portalı olan **Gg games**, fütüristik bir atmosfer sunmak için saf HTML, CSS ve JavaScript kullanılarak oluşturulmuştur. Bu proje, neon-dijital estetiği, gelişmiş animasyonları ve kullanıcı dostu arayüzü ile dikkat çeker. Hiçbir harici kütüphaneye veya framework'e bağımlı olmadan, tek bir dosya içinde tam işlevsellik sunar.

![Gg games Arayüz Önizlemesi](https://i.ibb.co/L5hY5hM/gg-games-demo.gif)
*(**İpucu:** Bu GIF'i kendi ekran kaydınızla değiştirebilirsiniz. [LiceCap](https://www.cockos.com/licecap/) gibi bir araçla kolayca GIF oluşturabilirsiniz.)*

## ✨ Özellikler

-   **🚀 Tamamen Bağımsız (Standalone):** Tüm HTML, CSS ve JavaScript kodları tek bir `index.html` dosyasındadır. Sunucu veya kurulum gerektirmez.
-   **🎨 Neon-Dijital Tasarım:**
    -   Canlı ve hareketli ızgara (grid) arka planı.
    -   Atmosfer katan hareketli veri parçacıkları.
    -   Yarı şeffaf cam efekti (Glassmorphism) ile modern bir görünüm.
    -   "Orbitron" fontu ile fütüristik bir tipografi.
-   **💥 Gelişmiş Animasyonlar:**
    -   Sayfa açıldığında elementlerin sıralı ve akıcı bir şekilde yüklenmesi.
    -   Logo'da "flicker", butonlarda "pulse" ve başlıklarda "glitch" gibi efektler.
    -   Fare ile üzerine gelindiğinde (hover) akıcı ve tepkisel animasyonlar.
    -   Zarifçe açılıp kapanan modal (açılır pencere).
-   **🌍 Çoklu Dil Desteği:**
    -   **Türkçe, Azerice, İngilizce, İspanyolca, Korece ve Japonca** dilleri arasında anında geçiş.
    -   Kullanıcının dil tercihi, tarayıcı hafızasında (`localStorage`) saklanır.
-   **🔊 Ses Efektleri ve Kontrolü:**
    -   Atmosferik arka plan müziği.
    -   Etkileşimli butonlar için dijital tıklama sesleri.
    -   Ayarlar menüsünden müziği açma/kapatma ve tercihi kaydetme özelliği.
-   **🖱️ Etkileşimli Arayüz:**
    -   Sekme mantığıyla çalışan, sayfa yenilenmeden içerik değiştiren menüler.
    -   Ayarlar için animasyonlu açılır menü.
    -   Harici bir oyuna yönlendiren "Oyuna Gir" butonu.

## 🚀 Nasıl Kullanılır?

Bu projeyi çalıştırmak son derece basittir:

1.  Bu repoyu klonlayın veya ZIP olarak indirin.
2.  İndirdiğiniz klasördeki `index.html` dosyasını herhangi bir modern web tarayıcısında (Chrome, Firefox, Edge vb.) açın.
3.  Hepsi bu kadar! Proje yerel olarak sorunsuz çalışacaktır.

## 🛠️ Kullanılan Teknolojiler

-   **HTML5:** Sayfanın yapısal iskeleti.
-   **CSS3:**
    -   Flexbox ve Grid ile modern layout tasarımı.
    -   `@keyframes` ile özel animasyonlar.
    -   `backdrop-filter` ile cam efekti.
    -   `transform` ve `transition` ile akıcı geçişler.
-   **JavaScript (Vanilla JS):**
    -   DOM manipülasyonu ile tüm interaktif işlevsellik.
    -   `localStorage` ile kullanıcı tercihlerini (dil ve ses) saklama.
    -   Ses dosyalarını kontrol etmek için `HTMLAudioElement`.

## 📂 Dosya Yapısı

Proje, basitliği ve taşınabilirliği vurgulamak için kasıtlı olarak tek bir dosyada tutulmuştur.
