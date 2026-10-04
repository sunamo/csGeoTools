---
schema_version: 11
type: notmine-sample
category_override: none
file_count: 19
file_extensions: cs:12, gpx:2, md:2, csproj:1, noext:1, slnx:1
file_extensions_updated: 2026-10-04
avg_lines_per_file: 50
total_lines: not run
metrics_lm: 2026-10-01 16:41:39
move_to_legacy_percent: 60
description_updated: 2026-10-01
links_updated: 2026-10-01
github_source_url: https://github.com/ConnectedCaching/csGeoTools
origin_status: found
origin_checked: 2026-10-01
article_source_url: not run
article_status: pending
article_checked: not run
last_build_ok: not run
last_build_date: not run
last_tests_run_date: not run
covered_lines: not run
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
