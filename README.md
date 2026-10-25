# bugraky.github.io

BGR Dev'in uygulama sayfaları: tanıtım, destek ve gizlilik politikaları. GitHub Pages bu deponun
`main` dalının kökünden yayınlar; `.nojekyll` olduğu için dosyalar Jekyll'den geçmeden, olduğu
gibi sunulur. Sayfalar düz HTML, ortak stil `assets/style.css`; dışarıdan hiçbir şey (font, analitik)
yüklenmez.

| Yol | Ne |
|---|---|
| `/` | Geliştirici sayfası ve uygulama listesi |
| `/app-ads.txt` | AdMob yetkili satıcılar dosyası. Alan adının **kökünde** olmak zorunda |
| `/sonant/` | Sonant tanıtım ve destek |
| `/sonant/privacy/` | Sonant gizlilik politikası (Play Console'daki adres) |

**Yeni uygulama:** `/<uygulama>/` ve `/<uygulama>/privacy/` klasörlerini aç, ana sayfadaki listeye
ekle. Gizlilik politikası her uygulamanın kendine özel olmalı (Play şartı). Aynı AdMob hesabını
kullanıyorsa `app-ads.txt` değişmez; başka bir hesapsa onun satırı eklenir.

**Alan adı bağlanırsa:** kökte bir `CNAME` dosyası ile. Ardından Play Console'daki web sitesi ve
gizlilik politikası adresleri yeni alan adına çevrilmeli: AdMob, `app-ads.txt` için başka bir alan
adına yönlendirmeyi izlemez.
