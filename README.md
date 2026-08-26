# Muğla Deniz Ulaşımı GTFS

Bu repository, Muğla Büyükşehir Belediyesi tarafından yayımlanacak deniz ulaşımı GTFS verilerini hat bazında barındırmak için oluşturulmuştur.

## Mevcut hatlar

### Bodrum – Datça (Körmen)

- Publisher: Muğla Büyükşehir Belediyesi
- İşletmeci: Bodrum Feribot İşletmeciliği A.Ş.
- Feed contact: info@mugla.bel.tr
- Agency contact: info@bodrumferibot.com
- 2026 toplam tek yön sefer: 1.118
- Validator sonucu: 0 error, 12 warning
- Kalan uyarılar: yalnızca geçmiş 2026 servis dönemlerinden kaynaklanan `expired_calendar`

GTFS dosyası: `bodrum-datca/gtfs.zip`

Kalıcı raw feed adresi:

`https://raw.githubusercontent.com/cemtheman/gtfs/main/bodrum-datca/gtfs.zip`

## Repository yapısı

```text
gtfs/
├── README.md
└── bodrum-datca/
    ├── gtfs.zip
    ├── source/
    │   └── official_fares.csv
    └── docs/
        └── release-readiness.txt
```

İleride yeni hatlar aynı yapı altında ayrı klasörlerde eklenecektir.

## Notlar

- GTFS feed publisher: Muğla Büyükşehir Belediyesi.
- Operator/agency: ilgili hattın işletmecisi.
- Bodrum–Datça hattında yaklaşık 110 dakikalık tek yön süre operasyonel ortalamadır; kesin planlı varış süresi olarak değerlendirilmemelidir.
- Araç/feribot ataması, bakım, arıza ve personel planlaması GTFS kapsamı dışındadır.
