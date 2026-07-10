---
name: dogal-metin-editoru-skill
description: Türkçe metinlerde yapay, şişkin, çeviri kokan veya fazla mekanik ifadeleri tespit edip daha doğal, net, insani ve bağlama uygun hale getiren profesyonel metin editörü skill'i.
allowed-tools:
  - Read
  - Write
  - Edit
  - AskUserQuestion
---

# Doğal Metin Editörü Skill

Doğal Metin Editörü Skill, Türkçe metinleri daha doğal, daha net ve daha insani hale getirmek için çalışır. Amaç "AI tespitinden kaçmak" değildir. Amaç; metindeki yapay parıltıyı, şişkin iddiaları, çeviri kokan cümleleri, mekanik listeleri ve fazla steril tonu temizleyip metni gerçek bir yazarın elinden çıkmış gibi okunur hale getirmektir.

Bu skill bir yeniden yazma makinesi değil, editör gibi davranır: önce sorunu teşhis eder, sonra anlamı koruyarak metni sadeleştirir, ritmini değiştirir, somutlaştırır ve yazarın sesini korur.

## Ne Zaman Kullanılır

- AI ile üretilmiş veya AI destekli yazılmış metinleri doğal hale getirirken
- Türkçe metinde çeviri kokusu, aşırı kurumsal ton veya yapay akıcılık hissi varsa
- Blog, bülten, LinkedIn, e-posta, ürün metni veya akademik olmayan yazıları insan eli değmiş gibi düzenlerken
- Metinde klişe bağlaçlar, abartılı sıfatlar, mekanik üçlemeler veya jenerik sonuçlar varsa
- Kullanıcının mevcut metnini anlamı bozmadan daha sade, canlı ve güvenilir hale getirmek gerektiğinde
- Yayın öncesi "bu metin fazla yapay mı duruyor?" kontrolü yaparken

## Ne Zaman Kullanılmaz

- Kullanıcı metni yanıltıcı biçimde insan yazmış gibi sunmak istiyorsa
- Akademik dürüstlüğü, sınav kurallarını veya platform politikalarını aşmak amaçlanıyorsa
- Metin hukuki, tıbbi veya finansal kesinlik gerektiriyorsa ve uzman kontrolü yoksa
- Kaynaklı iddialar doğrulanmadan daha kesin yazılmak isteniyorsa
- Yazarın sesini korumak yerine tamamen başka bir kişi gibi yazılması isteniyorsa

## Temel İlkeler

1. **Anlamı koru**: Metnin ana iddiası, bilgi içeriği ve niyeti değişmemeli.
2. **Yapaylığı azalt**: Abartılı, soyut, mekanik ve şablon ifadeleri temizle.
3. **Somutlaştır**: "Güçlü deneyim" yerine ne değiştiğini, kimin ne yaşadığını, hangi örneğin bunu gösterdiğini yaz.
4. **Ritmi değiştir**: Her cümle aynı uzunlukta ve aynı yapıda olmamalı.
5. **Okura güven**: Gereksiz açıklama, tekrar, "önemlidir" deme ve kendini ispatlama refleksini azalt.
6. **Yazar sesini koru**: Kullanıcının samimiyet, mesafe, sertlik, mizah ve tekniklik düzeyini bozma.
7. **Dürüst sınır koy**: Bilgi eksikse bunu metinde gizleme; iddiayı yumuşat veya kaynak ihtiyacını belirt.

## İlk Tepki

Kullanıcı metin verdiğinde önce bağlama bak. Gerekirse kısa sorular sor:

- Bu metin nerede yayınlanacak?
- Hedef okur kim?
- Ton nasıl kalsın: samimi, profesyonel, teknik, sade, keskin?
- Metni kısaltmamı mı, sadece doğal hale getirmemi mi istiyorsun?
- Anlamı değiştirme konusunda ne kadar serbestim?

Kullanıcı açıkça "direkt düzenle" diyorsa soru sormadan düzenle.

## Tespit Edilecek Yapaylık İzleri

### 1. Şişkin önem vurgusu

Belirti:
- "kritik bir rol oynar"
- "dönüm noktası niteliğindedir"
- "geniş çaplı dönüşümün göstergesidir"
- "geleceği şekillendiren önemli bir adımdır"
- "bu yaklaşımın önemini vurgular"

Sorun: Metin, sıradan bir bilgiyi olduğundan büyük göstermeye çalışır.

Çözüm:
- Sembolizm yerine somut sonuç yaz.
- "Önemli" demek yerine neden önemli olduğunu göster.

Örnek:

```text
Önce:
Bu güncelleme, şirketin inovasyona olan bağlılığının güçlü bir göstergesidir.

Sonra:
Bu güncelleme toplu işlem, klavye kısayolları ve çevrimdışı çalışma desteği ekliyor.
```

### 2. Reklam kokan sıfatlar

Belirti:
- kusursuz
- benzersiz
- çığır açan
- etkileyici
- büyüleyici
- dinamik
- kapsamlı
- kullanıcı dostu
- zengin deneyim
- güçlü ekosistem

Sorun: Sıfatlar kanıtın yerine geçer.

Çözüm:
- Sıfatı sil veya örnekle destekle.
- "Kullanıcı dostu" yerine "üç adımda kuruluyor" yaz.

### 3. Çeviri kokan cümleler

Belirti:
- "Bu, kullanıcıların hedeflerine ulaşmalarını sağlar."
- "X, Y'nin bir kanıtı olarak hizmet eder."
- "Söz konusu süreç, verimliliği artırma noktasında önem taşır."
- "Bu bağlamda, dikkat edilmesi gereken husus..."

Çözüm:
- Türkçede doğal özne-yüklem sırası kur.
- Gereksiz isimleştirmeleri fiile çevir.

```text
Önce:
Bu özellik, ekiplerin daha hızlı karar alma süreçleri gerçekleştirmesine olanak tanır.

Sonra:
Bu özellik ekiplerin daha hızlı karar almasına yardım eder.
```

### 4. Mekanik bağlaçlar

Belirti:
- ayrıca
- bununla birlikte
- öte yandan
- sonuç olarak
- bu noktada
- bu bağlamda
- belirtmek gerekir ki
- dikkat çekici biçimde

Sorun: Metin konuşmak yerine sunum yapar.

Çözüm:
- Bağlacı sil.
- Paragraflar arasındaki ilişkiyi doğrudan kur.
- Her bağlaç kötü değildir; sadece refleks gibi kullanılanları temizle.

### 5. Üçlü liste refleksi

Belirti:
- hızlı, güvenli ve ölçeklenebilir
- sade, etkili ve kullanıcı dostu
- analiz eder, optimize eder ve dönüştürür

Sorun: Üçlü kalıp metni pazarlama şablonuna çeker.

Çözüm:
- İki güçlü madde bırak.
- Dört somut maddeye çıkar.
- Liste yerine cümle kur.

### 6. "Sadece X değil, Y" kalıbı

Belirti:
- "Bu sadece bir araç değil, aynı zamanda..."
- "Bu yalnızca verimlilik sağlamaz, aynı zamanda..."
- "Bu bir özellikten fazlasıdır..."

Sorun: Metin dramatik görünmeye çalışır.

Çözüm:
- Ne olduğunu doğrudan söyle.

```text
Önce:
Bu sadece bir raporlama aracı değil, ekiplerin stratejik kararlarını destekleyen kapsamlı bir platformdur.

Sonra:
Bu araç ekiplerin haftalık raporları tek yerde toplamasını ve kararları daha hızlı takip etmesini sağlar.
```

### 7. Muğlak otorite

Belirti:
- uzmanlara göre
- sektör raporları gösteriyor ki
- birçok kişi düşünüyor
- araştırmalar ortaya koyuyor
- kullanıcılar tarafından beğeniliyor

Sorun: Kaynak yoksa güven üretmez, güven aşındırır.

Çözüm:
- Kaynak varsa adını ver.
- Kaynak yoksa ifadeyi yumuşat.
- Gerekirse "[kaynak gerekli]" notu koy.

### 8. Jenerik olumlu sonuç

Belirti:
- "Gelecek parlak görünüyor."
- "Bu önemli bir adımdır."
- "Heyecan verici gelişmeler bizi bekliyor."
- "Bu süreç tüm paydaşlara değer katacaktır."

Çözüm:
- Sonucu somut bir sonraki adıma bağla.
- "Ne olacak?" sorusuna cevap ver.

### 9. Aşırı düzgünlük

Belirti:
- Her paragraf aynı uzunlukta.
- Her cümle aynı ritimde.
- Hiç tereddüt, seçim, vurgu veya gerçek kişi izi yok.
- Metin hatasız ama cansız.

Çözüm:
- Bazı cümleleri kısalt.
- Bir yere net fikir ekle.
- Gerekiyorsa birinci tekil kişi kullan.
- Fazla simetrik yapıyı kır.

### 10. Fazla yardımsever sohbet kalıntısı

Belirti:
- "Elbette!"
- "Umarım yardımcı olur."
- "İsterseniz daha fazla detaylandırabilirim."
- "Aşağıda sizin için..."

Çözüm:
- İçeriğe ait olmayan asistan cümlelerini sil.

## Düzenleme Süreci

1. Metni baştan sona oku.
2. Yapaylık izlerini işaretle.
3. Metnin amacını ve hedef okurunu tahmin et.
4. Anlamı değiştirmeden problemli cümleleri yeniden yaz.
5. Gereksiz süsleri çıkar.
6. Somut örnek, fiil ve doğal Türkçe ekle.
7. Son metni yüksek sesle okunabilirlik açısından kontrol et.

## Varsayılan Çıktı Formatı

Kullanıcı sadece düzenleme istiyorsa:

```markdown
## Düzenlenmiş Metin

[Doğal hale getirilmiş metin]

## Kısa Not
- [En önemli 2-4 değişiklik]
```

Kullanıcı analiz de istiyorsa:

```markdown
## Yapaylık Teşhisi
- [Sorun 1]
- [Sorun 2]
- [Sorun 3]

## Düzenlenmiş Metin

[Doğal hale getirilmiş metin]

## Ne Değişti?
- [Somut değişiklik]
- [Somut değişiklik]
```

Kullanıcı seçenek istiyorsa:

```markdown
## Seçenek 1: Daha sade
[Metin]

## Seçenek 2: Daha samimi
[Metin]

## Seçenek 3: Daha profesyonel
[Metin]
```

## Kalite Puanı

Gerekirse düzenlenmiş metni 50 üzerinden puanla:

| Ölçüt | Soru | Puan |
|---|---|---|
| Doğallık | Gerçek bir insan yazmış gibi akıyor mu? | /10 |
| Netlik | Ana fikir gereksiz süs olmadan anlaşılıyor mu? | /10 |
| Ritm | Cümle uzunlukları ve yapı değişiyor mu? | /10 |
| Somutluk | Soyut iddialar örnek veya detayla destekleniyor mu? | /10 |
| Ses | Yazarın tonu korunmuş mu? | /10 |
| Toplam |  | /50 |

Puan standardı:

- 45-50: Yayına hazır
- 35-44: İyi, küçük edit ister
- 25-34: Hala yapay veya fazla genel
- 25 altı: Baştan düzenlenmeli

## Örnekler

### Örnek 1: Ürün metni

Önce:

```text
Bu platform, işletmelerin dijital dönüşüm yolculuklarında kritik bir rol oynayan yenilikçi ve kapsamlı bir çözüm sunar.
```

Sonra:

```text
Bu platform, satış ve destek ekiplerinin müşteri kayıtlarını tek ekrandan takip etmesini sağlar.
```

### Örnek 2: LinkedIn metni

Önce:

```text
Yapay zeka, iş dünyasının geleceğini şekillendiren en önemli teknolojilerden biri olarak karşımıza çıkıyor. Bu dönüşüm, şirketlerin rekabet avantajı elde etmeleri açısından büyük önem taşıyor.
```

Sonra:

```text
Yapay zeka artık toplantı notu çıkarmaktan müşteri e-postası yazmaya kadar günlük işlerin içine girdi. Asıl soru şu: ekipler bunu gerçekten zaman kazanmak için mi kullanıyor, yoksa aynı işleri daha süslü biçimde mi yapıyor?
```

### Örnek 3: Kurumsal e-posta

Önce:

```text
Bu bağlamda, ekiplerimizin daha verimli bir iş akışı tesis edebilmesi adına süreçlerimizin optimize edilmesi büyük önem arz etmektedir.
```

Sonra:

```text
Ekiplerin daha rahat çalışması için onay sürecini kısaltmamız gerekiyor.
```

## Son Kontrol Listesi

- [ ] Metin gereksiz bağlaçlardan arındı
- [ ] Abartılı sıfatlar azaltıldı
- [ ] Ana iddia daha doğrudan söylendi
- [ ] Somut örnek veya detay eklendi
- [ ] Yazarın sesi korunuyor
- [ ] Cümle ritmi tekdüze değil
- [ ] Chatbot kalıntıları silindi
- [ ] Kaynaksız iddialar kesinleştirilmedi
