# Doğal Metin Editörü Skill

Türkçe metinlerde yapay, şişkin, çeviri kokan veya fazla mekanik ifadeleri temizleyen profesyonel AI agent skill'i.

Bu skill metni "AI tespitinden kaçırmak" için değil, daha iyi Türkçe yazmak için tasarlanmıştır. Metni sadeleştirir, ritmini düzeltir, soyut ifadeleri somutlaştırır ve yazarın sesini koruyarak daha doğal hale getirir.

## Kime Uygun?

- İçerik üreticileri
- Kurucu ve solo girişimciler
- Pazarlama ekipleri
- LinkedIn ve bülten yazarları
- Ürün, landing page ve e-posta metni yazan ekipler
- AI destekli metinleri yayın öncesi insan editinden geçirmek isteyenler

## Ne İşe Yarar?

- Yapay ve mekanik cümleleri tespit eder
- Şişkin pazarlama dilini sadeleştirir
- Çeviri kokan Türkçeyi doğallaştırır
- Aşırı bağlaç, üçlü liste ve jenerik sonuçları temizler
- Metni daha net, daha somut ve daha okunur hale getirir
- Yazarın tonunu koruyarak alternatif versiyonlar üretir
- Gerekirse 50 puanlık doğallık değerlendirmesi yapar

## Kurulum

Skill klasörünü kullandığın agent'ın skill dizinine kopyala.

Claude Code için tipik konum:

```bash
mkdir -p ~/.config/claude-code/skills
cp -r dogal-metin-editoru-skill ~/.config/claude-code/skills/
```

## Kullanım Örnekleri

```text
Doğal Metin Editörü Skill'i kullan.
Aşağıdaki metni daha doğal, daha sade ve daha az AI kokan hale getir.
Anlamı değiştirme.
```

```text
Bu LinkedIn paylaşımını düzenle.
Ton samimi kalsın, ama fazla pazarlama dili olmasın.
```

```text
Bu landing page metnindeki yapay ifadeleri teşhis et.
Sonra daha net ve daha profesyonel bir versiyon yaz.
```

## Ürün Konumlandırması

Kısa açıklama:

> Doğal Metin Editörü Skill, Türkçe metinleri daha doğal, net ve insani hale getiren profesyonel AI editör skill'idir.

Daha satış odaklı açıklama:

> AI destekli metinleri yayınlamadan önce insan eli değmiş gibi düzenle. Doğal Metin Editörü Skill, şişkin cümleleri sadeleştirir, çeviri kokusunu temizler ve metni gerçek Türkçe akışına yaklaştırır.

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
