# csGeoTools

Testy pro knihovnu csGeoTools (geografické výpočty a parsování GPX), net7.0-windows, MSTest.

- V repu jsou jen testy v csGeoTools.Tests/; samotná knihovna csGeoTools zde chybí.
- Testuje se GeoPoint (parsování a formátování souřadnic), vzdálenost, azimut (Bearing), vzdálenost a azimut mezi body, projekce a pevné (fixed) varianty.
- Parsery: desetinné stupně (DecimalDegreeParser) a GPX (formáty Groundspeak GC 1.0.1 a GPX 1.0) se vzorovými soubory .gpx.
- Testy používají Microsoft.VisualStudio.TestTools.UnitTesting.

Solution: csGeoTools.slnx.

Původní projekt: https://github.com/ConnectedCaching/csGeoTools
