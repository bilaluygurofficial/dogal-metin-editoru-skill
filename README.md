# Doğal Metin Editörü Skill

Türkçe metinlerde yapay, şişkin, çeviri kokan veya fazla mekanik ifadeleri temizleyen profesyonel AI editör skill'i.

Doğal Metin Editörü Skill, AI destekli ya da aceleyle yazılmış metinleri daha doğal, daha net ve daha insani hale getirir. Amaç "AI tespitinden kaçmak" değildir. Amaç; iyi Türkçe yazmak, gereksiz süsleri temizlemek, çeviri kokusunu azaltmak ve yazarın sesini korumaktır.

Bu skill metni baştan yazan bir makine gibi değil, editör gibi çalışır: önce yapaylık izlerini teşhis eder, sonra anlamı koruyarak ritmi, tonlamayı ve somutluğu iyileştirir.

## Neden Gerekli?

AI destekli metinler çoğu zaman ilk bakışta düzgün görünür. Sorun da burada başlar:

- Cümleler temizdir ama fazla pürüzsüzdür.
- Her paragraf aynı ritimde akar.
- "Kritik rol", "dijital dönüşüm", "kapsamlı çözüm" gibi şişkin kalıplar kanıtın yerine geçer.
- Türkçe cümleler İngilizce düşünülmüş gibi durur.
- Metin çok yardımsever, çok dengeli, çok güvenli ve bu yüzden cansızdır.
- Sonuç bölümü genelde "gelecek parlak" gibi hiçbir şey söylemeyen bir iyimserlikle biter.

Doğal Metin Editörü Skill bu kalıpları yakalar ve metni daha gerçek bir Türkçe akışına yaklaştırır.

## Hızlı Başlangıç

Skill klasörünü kullandığın agent'ın skill dizinine kopyala.

Claude Code için tipik kurulum:

```bash
mkdir -p ~/.config/claude-code/skills
cp -r dogal-metin-editoru-skill ~/.config/claude-code/skills/
```

Sonra agent'a şöyle yaz:

```text
Doğal Metin Editörü Skill'i kullan.
Aşağıdaki metni daha doğal, daha sade ve daha az yapay hale getir.
Anlamı değiştirme, yazar sesini koru.
```

## Tespit Ettiği Yapaylık İzleri

| Kategori | Belirti | Editör yaklaşımı |
|---|---|---|
| Şişkin önem vurgusu | "kritik rol", "dönüm noktası", "geleceği şekillendirir" | Somut sonuç yaz |
| Reklam kokan sıfatlar | "kusursuz", "benzersiz", "çığır açan" | Kanıt veya örnek ekle, gerekirse sil |
| Çeviri kokusu | "olanak tanır", "hizmet eder", "bu bağlamda" | Türkçe fiil yapısına çevir |
| Mekanik bağlaçlar | "ayrıca", "bununla birlikte", "sonuç olarak" | Gereksiz olanları çıkar |
| Üçlü liste refleksi | "hızlı, güvenli ve ölçeklenebilir" | İki güçlü madde veya somut detay kullan |
| Dramatik kalıplar | "sadece X değil, Y" | Doğrudan söyle |
| Muğlak otorite | "uzmanlara göre", "araştırmalar gösteriyor" | Kaynak iste veya iddiayı yumuşat |
| Jenerik sonuç | "gelecek parlak", "önemli bir adım" | Somut sonraki adım yaz |
| Aşırı düzgünlük | Her cümle aynı ritimde | Cümle uzunluğunu ve yapıyı değiştir |
| Chatbot kalıntısı | "Elbette", "umarım yardımcı olur" | İçerik dışı asistan cümlelerini sil |

## Kullanım Senaryoları

LinkedIn metni:

```text
Doğal Metin Editörü Skill'i kullan.
Bu LinkedIn paylaşımını daha doğal hale getir.
Ton samimi kalsın, fazla pazarlama dili olmasın.
```

Landing page metni:

```text
Bu landing page metnindeki yapay ifadeleri teşhis et.
Sonra daha net, daha profesyonel ve daha somut bir versiyon yaz.
```

Kurumsal e-posta:

```text
Bu e-postayı daha sade Türkçeye çevir.
Resmi ton korunsun ama bürokratik ve çeviri kokan ifadeler temizlensin.
```

AI çıktısı temizleme:

```text
Bu metinde AI kokan ifadeleri işaretle.
Sonra anlamı koruyarak daha doğal bir versiyon yaz.
En sonda neyi değiştirdiğini kısa listele.
```

## Örnek Dönüşümler

Ürün metni:

```text
Önce:
Bu platform, işletmelerin dijital dönüşüm yolculuklarında kritik bir rol oynayan yenilikçi ve kapsamlı bir çözüm sunar.

Sonra:
Bu platform, satış ve destek ekiplerinin müşteri kayıtlarını tek ekrandan takip etmesini sağlar.
```

LinkedIn girişi:

```text
Önce:
Yapay zeka, iş dünyasının geleceğini şekillendiren en önemli teknolojilerden biri olarak karşımıza çıkıyor.

Sonra:
Yapay zeka artık toplantı notu çıkarmaktan müşteri e-postası yazmaya kadar günlük işlerin içine girdi.
```

Kurumsal ifade:

```text
Önce:
Bu bağlamda, ekiplerimizin daha verimli bir iş akışı tesis edebilmesi adına süreçlerimizin optimize edilmesi büyük önem arz etmektedir.

Sonra:
Ekiplerin daha rahat çalışması için onay sürecini kısaltmamız gerekiyor.
```

## Varsayılan Çıktı Formatı

```markdown
## Düzenlenmiş Metin

[Doğal hale getirilmiş metin]

## Kısa Not
- [En önemli değişiklik]
- [Silinen veya sadeleştirilen kalıp]
- [Korunan ton]
```

Analiz istendiğinde:

```markdown
## Yapaylık Teşhisi
- [Sorun 1]
- [Sorun 2]
- [Sorun 3]

## Düzenlenmiş Metin
[Metin]

## Ne Değişti?
- [Somut değişiklik]
```

## Kalite Puanı

Gerekirse metni 50 üzerinden değerlendir:

| Ölçüt | Soru | Puan |
|---|---|---|
| Doğallık | Gerçek bir insan yazmış gibi akıyor mu? | /10 |
| Netlik | Ana fikir gereksiz süs olmadan anlaşılıyor mu? | /10 |
| Ritm | Cümle uzunlukları ve yapı değişiyor mu? | /10 |
| Somutluk | Soyut iddialar örnek veya detayla destekleniyor mu? | /10 |
| Ses | Yazarın tonu korunmuş mu? | /10 |
| Toplam |  | /50 |

## Güvenli Konumlandırma

Bu skill'in amacı AI tespit sistemlerini kandırmak değildir. Kullanım amacı:

- Metin kalitesini artırmak
- Türkçe doğallığı güçlendirmek
- Gereksiz şişkinliği azaltmak
- Yazarın sesini korumak
- Yayın öncesi editör kontrolü yapmak

Akademik dürüstlük, sınav, iş başvurusu, resmi beyan veya platform politikalarını aşma amacıyla kullanılmamalıdır.

## Tasarım Fikri

Bu skill, `op7418/Humanizer-zh` projesinden fikir ve yapı düzeyinde ilham alır. Kaynak proje de `blader/humanizer`, `hardikpandya/stop-slop` ve Wikipedia'nın AI writing signs rehberinden yararlandığını belirtir.

Bu uyarlamanın odağı şudur:

- Türkçe metinlerde çeviri kokusunu azaltma
- Pazarlama şişkinliğini sadeleştirme
- Mekanik AI kalıplarını temizleme
- Doğal ritim ve yazar sesi
- Güvenli ve dürüst kullanım

## Dosya Yapısı

```text
dogal-metin-editoru-skill/
|-- SKILL.md
|-- README.md
|-- NOTICE.md
`-- LICENSE
```

## Lisans ve Uyarlama Notu

Bu çalışma, `op7418/Humanizer-zh` projesinden fikir ve yapı düzeyinde uyarlanmıştır. Kaynak proje MIT lisanslıdır ve kendisi de `blader/humanizer`, `hardikpandya/stop-slop` ve Wikipedia'nın AI writing signs rehberinden yararlandığını belirtir.

Bu uyarlama birebir çeviri değildir. Türkçe yazı alışkanlıkları, pazarlama dili, çeviri kokusu ve yerel ifade kalıpları dikkate alınarak yeniden yazılmıştır.

Detaylar için `NOTICE.md` dosyasına bak.
