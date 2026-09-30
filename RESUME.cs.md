---
schema_version: 5
type: tests
file_count: 19
delete_recommendation_percent: 60
generated_date: 2026-09-30
generated_time: 16:13:28
github_origin: yes
github_source_url: https://github.com/ConnectedCaching/csGeoTools
first_commit_date: 2019-03-22
last_commit_date: 2026-09-25
commit_count: 24
---

## Description

Testovací projekt (MSTest, net7.0-windows) ke knihovně csGeoTools pro geografické výpočty. Testuje GeoPoint, vzdálenosti, azimuty, projekce a parsery desetinných stupňů a GPX (GC 1.0.1, GPX 1.0). Samotná knihovna v repu chybí, jsou zde jen testy.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [ConnectedCaching/csGeoTools](https://github.com/ConnectedCaching/csGeoTools)

- Zdroj určen podle: git hash-object dvou vzorových souborů Gc101Sample.gpx a Gpx10Sample.gpx se shoduje s blob sha v upstreamu, všech 14 souborů v csGeoTools.Tests má stejné názvy a cesty jako upstream, hledání gh search csGeoTools vrátilo jen tento repozitář; ostatní testy jsou lokálně upravené (jiné hashe).

## Doporučení ke smazání

Doporučení ke smazání: **60 %** — zdrojáky knihovny chybí, zůstaly jen testy, ale mají hodnotu jako referenční sada.

- Repo má 19 souborů, jen MSTest testy (net7.0) ke knihovně csGeoTools.
- Testy pokrývají GeoPoint, vzdálenosti, azimuty, projekce a parsery GPX, což může být užitečné jako vzor.
- Původ souvisí s GitHubem, samotná knihovna v repu není, takže testy bez ní neběží.

## Historie commitů

- První commit: 2019-03-22
- Poslední commit: 2026-09-25
- Celkem commitů: 24

- Počítá se bez commitů, které jen generovaly RESUME.cs.md nebo README.md.
