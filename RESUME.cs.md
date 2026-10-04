---
schema_version: 6
type: notmine_sample
file_count: 19
avg_lines_per_file: 50
move_to_legacy_percent: 60
generated_date: 2026-10-01
generated_time: 16:41:39
github_source_url: https://github.com/ConnectedCaching/csGeoTools
last_build_ok: 
last_build_date: 
last_tests_run_date: 
covered_lines: 
total_lines: 
---

## Description

Testovací projekt (MSTest, net7.0-windows) ke knihovně csGeoTools pro geografické výpočty. Testuje GeoPoint, vzdálenosti, azimuty, projekce a parsery desetinných stupňů a GPX (GC 1.0.1, GPX 1.0). Samotná knihovna v repu chybí, jsou zde jen testy.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [ConnectedCaching/csGeoTools](https://github.com/ConnectedCaching/csGeoTools)

- Zdroj určen podle: git hash-object dvou vzorových souborů Gc101Sample.gpx a Gpx10Sample.gpx se shoduje s blob sha v upstreamu, všech 14 souborů v csGeoTools.Tests má stejné názvy a cesty jako upstream, hledání gh search csGeoTools vrátilo jen tento repozitář; ostatní testy jsou lokálně upravené (jiné hashe).

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **60 %** — zdrojáky knihovny chybí, zůstaly jen testy, ale mají hodnotu jako referenční sada.

- Repo má 19 souborů, jen MSTest testy (net7.0) ke knihovně csGeoTools.
- Testy pokrývají GeoPoint, vzdálenosti, azimuty, projekce a parsery GPX, což může být užitečné jako vzor.
- Původ souvisí s GitHubem, samotná knihovna v repu není, takže testy bez ní neběží.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
