# Sofra Grup — 24 Kasım Öğretmenler Günü

İç eğitmenlere gönderilen 24 Kasım Öğretmenler Günü tebrik kartı ve e-posta materyalleri.

## Yayın bağlantısı

https://sofragrup.github.io/

Sayfa etkileşimlidir: mesaj satır satır açılır. Okuyan kişi ekrana dokunarak,
tıklayarak, kaydırarak ya da ok tuşlarıyla ilerler.

1. **Hitap** — "Değerli İç Eğitmenlerimiz," büyük puntoyla, çiçekler eşliğinde
2. **Bilgi dönüşüyor** — "güvene / ustalığa / yeni bir hedefe" satırları tek tek belirir
3. **Sizler** — teşekkür paragrafı
4. **Kutlama** — "gününüzü en içten dileklerimizle kutluyoruz" satırında konfeti ve çiçek patlaması
5. **Final** — "Öğretmenler Gününüz Kutlu Olsun", ardından imza ve marka

Yukarı kaydırma / yukarı ok bir adım geri götürür; sonda "Tekrar izle" düğmesi vardır.

## İçerik

| Dosya | Açıklama |
|---|---|
| `index.html` | Etkileşimli tebrik sayfası (yayınlanan sürüm) |
| `klasik-kart.html` | Önceki sürüm: zarf kendiliğinden açılır, kart tek parça görünür |
| `kart-dokununca-acilan.html` | Önceki sürüm: önce zarf görünür, dokununca açılır |
| `gorseller/zarf.gif` | E-postaya konacak hareketli zarf. Kart sayfası bağlantısı bu görsele eklenir. |
| `gorseller/kart-acilis.gif` | Zarfın açılıp kartın çıktığı tam animasyon. Bağlantı gerekmez. |
| `metinler/Mesaj_Metni.txt` | Kartın son metni |
| `gorseller/sofra-compass-logo.png` | Sofra Grup \| Compass Group logosu, şeffaf zeminli (karta gömülü sürümün kaynağı) |
| `gorseller/favicon.png` | Tarayıcı sekmesi simgesi |

## E-postada paylaşma

1. Outlook'ta yeni e-posta → Ekle → Resimler → `gorseller/zarf.gif`
2. Görsele sağ tık → Bağlantı → yukarıdaki yayın bağlantısını yapıştırın.
3. Alıcıları Bcc'ye ekleyin, önce kendinize deneme gönderin.

## Marka

Final sahnesinde (ve klasik kartların altında) Sofra Grup | Compass Group logosu yer alır. Logo, kaynak görselin
siyah zemininden ayrılıp şeffaf hale getirilmiştir; kurumsal renkler (altın `#C6AB72`,
kurum grisi `#3B3B3B`) değiştirilmemiştir. HTML dosyaları kendi kendine yeter —
logo içlerine gömülüdür, internet bağlantısı olmadan da görünür.

## Not

İç eğitmen listesi (`ozel/Ic_Egitmen_Listesi.csv`) kişisel veri içerdiği için depoya
dahil edilmemiştir; yalnızca yerel klasörde durur (bkz. `.gitignore`).
