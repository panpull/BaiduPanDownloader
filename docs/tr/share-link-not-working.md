# Baidu Pan paylaşım bağlantısı çalışmıyor: hangi mesaj ne anlama gelir

Bir `pan.baidu.com` bağlantısını açıyorsunuz ve dosya listesi yerine Çince kısa bir mesaj çıkıyor. Bu sayfa, mesajın ne anlama geldiğini ve neler yapabileceğinizi anlatır.

## Önce adresi kontrol edin

Sağlam bir bağlantı `https://pan.baidu.com/s/1…` biçimindedir ve `1`’den sonra uzun bir harf ve rakam dizisi gelir. Açıldıktan sonra tarayıcı bunun yerine `https://pan.baidu.com/share/init?surl=…` gösterebilir. Bu da aynı paylaşımdır.

Bağlantı kopyalanırken kesildiyse açılmaz. Asıl mesajdan, sonuna kadar yeniden kopyalayın.

## Sayfa size ne söylüyor

| Ne görüyorsunuz | Anlamı | Kim düzeltebilir |
| --- | --- | --- |
| Dört karakter isteyen bir kutu | Paylaşım korumalı. [Erişim koduna](extraction-code.md) ihtiyacınız var | Siz, sahibinden alacağınız kodla |
| Geç kaldığınızı ve paylaşımın iptal edildiğini söyleyen bir mesaj | Sahibi paylaşımı durdurmuş ya da Baidu dosyaları kaldırmış | Sahibi |
| Hak ihlali veya yasaklı içerikle ilgili bir mesaj | Baidu paylaşımı engellemiş | Kimse: paylaşım engelli kalır |
| Bazı dosyaların filtrelendiğine dair notla birlikte bir dosya listesi | Paylaşımın bir kısmı Baidu’nun kurallarını ihlal etmiş ve gizlenmiş | Sahibi |
| Paylaşımın artık geçerli olmadığını söyleyen bir mesaj | Paylaşımın süresi dolmuş | Sahibi |

Tarayıcınızın çeviri özelliği bu mesajları birbirinden ayırmanıza yardımcı olur.

## Ne yapmalı

- **Kod reddediliyor:** asıl mesajla karakter karakter karşılaştırın. Bkz. [Erişim kodu](extraction-code.md).
- **Paylaşım iptal edilmiş veya süresi dolmuş:** sahibinden dosyaları yeniden paylaşmasını ve size yeni bağlantıyla kodu göndermesini isteyin.
- **Paylaşım engellenmiş:** indirilecek bir şey yok. Sahibine dosyaların başka bir yerde olup olmadığını sorun.

## Bir şey ödemeden önce kontrol edin

Bağlantıyı [PanPull bağlantı kontrolünde](https://panpull.com/tr?utm_source=github&utm_medium=tutorial#link-checker) deneyin. Kontrol ücretsizdir. Okunabilen bir paylaşım; dosya sayısı, toplam boyut ve fiyatla birlikte döner. Okunamıyorsa bunun yerine bir hata alırsınız ve hiçbir ücret alınmaz.

Silinmiş, iptal edilmiş veya engellenmiş bir paylaşımı hiçbir hizmet geri getiremez. Bir paylaşım PanPull’da başarısız olurken sahibinde sorunsuz açılıyorsa biraz sonra yeniden deneyin: sebep geçici olabilir.

PanPull blogunda daha fazlası: [Baidu paylaşım bağlantısı çalışmıyor: neleri kontrol etmeli](https://panpull.com/tr/blog/baidu-share-unavailable-checklist?utm_source=github&utm_medium=tutorial).

---

**Elinizde bir Baidu bağlantısı mı var? [PanPull’da kontrol edin](https://panpull.com/tr?utm_source=github&utm_medium=tutorial#link-checker)** ve önce boyutu ve fiyatı görün. 150 MB’a kadar ücretsiz.

[Tüm rehberler](README.md) · [Diğer diller](../README.md#languages)
