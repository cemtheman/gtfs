# Muğla Deniz Ulaşımı GTFS

Bu repository, Muğla Büyükşehir Belediyesi tarafından yayımlanacak deniz ulaşımı GTFS verilerini hat bazında barındırmak için oluşturulmuştur.

## Mevcut hatlar

### Bodrum – Datça (Körmen)

- Publisher: Muğla Büyükşehir Belediyesi
- İşletmeci: Bodrum Feribot İşletmeciliği A.Ş.
- Feed contact: info@mugla.bel.tr
- Agency contact: info@bodrumferibot.com
- 2026 toplam tek yön sefer: 1.118
- Feed sürümü: v0.5.1
- Son doğrulama: 26.08.2026
- Validator: MobilityData Canonical GTFS Schedule Validator 8.0.1
- Sonuç: **0 error, 12 warning, 0 info**
- Kalan 12 uyarı: yalnızca geçmiş 2026 servis dönemlerinden kaynaklanan `expired_calendar`

### Canlı GTFS feed

`https://raw.githubusercontent.com/cemtheman/gtfs/main/bodrum-datca/gtfs.zip`

### Doğrulama raporu

https://gtfs-validator-results.mobilitydata.org/f75afc61-70f6-445d-9cf0-74b917630a11/report.html

Yayımlanan GitHub raw feed, MobilityData validator ile yeniden doğrulanmıştır. Böylece repository üzerinde yayımlanan `gtfs.zip` dosyasının doğrudan tüketilebilir olduğu teyit edilmiştir.

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