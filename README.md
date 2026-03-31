# GoIT Markup Homework 03 - WebStudio (Layout & Flexbox)

Bu proje, GoIT Full Stack Developer eğitimi kapsamında hazırlanan **WebStudio** projesinin üçüncü aşamasıdır. Bu modülde, sayfanın yerleşim planı (layout) kuralları belirlenmiş, Box Model disiplini uygulanmış ve esnek kutu modeli (Flexbox) kullanılarak öğeler hizalanmıştır.

## 🚀 Proje Gereksinimleri ve Teknik Standartlar

Bu çalışma, belirtilen tüm teknik kriterlere ve mizanpaj kurallarına (A1-A8 ve B1-B16) tam uyumlu olarak kodlanmıştır:

### 🏗️ Dosya ve Proje Yapısı (A Serisi)
- **Varlık Yönetimi:** Görseller `images` klasöründe, CSS dosyası ise `css/styles.css` olarak tek bir dosyada toplanmıştır.
- **Normalizasyon:** Tarayıcılar arası varsayılan farkları ortadan kaldırmak için `modern-normalize` kütüphanesi projeye dahil edilmiştir.
- **Dosya Adlandırma:** Klasör ve dosya adlarında sadece İngilizce küçük harfler kullanılmış; boşluk veya özel karakter kullanılmamıştır.
- **Formatlama:** Kodun standartlara uygunluğu ve okunabilirliği için **Prettier** kullanılmıştır.

### 📐 Tasarım ve Düzen Kuralları (B Serisi)
- **Global Reset:** `<h1>`...`<h6>`, `<p>` ve `<ul>` etiketleri için varsayılan tarayıcı boşlukları etiket seçicilerle sıfırlanmıştır.
- **Box Model Disiplini:** - Öğeler arasındaki dikey boşluklar için `margin` kullanılmıştır.
  - İçerik ile çerçeve arasındaki boşluklar `padding` ile mizanpaja sadık kalınarak verilmiştir.
- **Kapsayıcı (.container):** Sayfa içeriğini sınırlandırmak ve ortalamak için `1158px` genişliğinde ortak bir `.container` sınıfı oluşturulmuş; üstbilgi, altbilgi ve bölümler bu sınıf ile sarmalanmıştır.
- **Esnek Yerleşim (Flexbox):** Flexbox yalnızca yatayda hizalanması gereken elemanlar (navigasyon, liste öğeleri vb.) için gerekli yerlerde kullanılmıştır.
- **Yükseklik Mantığı:** Elemanlara sabit bir yükseklik verilmemiş; yüksekliklerin içerik tarafından belirlenmesi sağlanmıştır.
- **Bölüm Düzenleri (.section):** Sayfa bölümleri bir kitap yığını gibi üst üste `margin` olmadan dizilmiştir. Tüm bölümlerde içeriği içeri iten `120px` üst ve alt `padding` içeren ortak `.section` sınıfı kullanılmıştır.
- **Görsel Detaylar:** - Başlık (Header) bölümünün alt kısmına mizanpajda yer alan ince `border` çizgisi eklenmiştir.
  - "Portföyümüz" bölümündeki kartlara yalnızca alt kısımda yer alacak şekilde kenarlık (`border`) tanımlanmıştır.

## 🛠️ Kullanılan Araçlar
* **HTML5 & CSS3**
* **Modern-Normalize**
* **Prettier** (Kod Biçimlendirme)

## 🔗 Canlı Önizleme
Projenin yayındaki haline aşağıdaki bağlantıdan ulaşabilirsiniz:
[GitHub Pages Üzerinden Görüntüle](https://emineacici.github.io/goit-markup-hw-03/)

---
*Hazırlayan: [Emine Acıcı](https://github.com/EmineAcici)*
