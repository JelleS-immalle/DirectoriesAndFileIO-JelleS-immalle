# Analyseer

Bekijk de volledige commit-geschiedenis om te bestuderen hoe dit project tot stand gekomen is.

Probeer volgende vragen te beantwoorden:

i.v.m. MSTest:

- Welke Assert-methods worden naast `Assert.AreEqual` nog allemaal gebruikt?
> Assert.AreNotEqual, Assert.AreNotSame, Fail, IsFalse, ...
- Waarom heeft `TestDirectories` een `Initialize`- en `CleanUp`-method?
> In de 'Initialize'-method worden de variabelen gedeclareerd en in de 'CleanUp`-method wordt nagekeken of bepaalde variabelen een correcte inhoud bevatten.
- Zijn de attributen `[TestMethod]`, `[TestClass]`, ... noodzakelijk? (Test uit!)
> Ja denk ik, ze verwijzen naar een namespace wie gebruikt wordt.
- Wat is de shortcut om alle tests uit te voeren in VS?
> CTRL + R & CTRL + A

i.v.m. Files en Directories:

- Wat is het voordeel van `Path.Combine` i.v.m. strings aan elkaar plakken?
- Wordt de return-waarde van `Directory.CreateDirectory(...)` steeds opgevangen? (TIP: gebruik `CTRL-SHIFT-F`)
- Wat is de return-waarde van `Directory.CreateDirectory(...)`?
- Wanneer is het nuttig om de return-waarde van `Directory.CreateDirectory(...)` op te vangen?

i.v.m. duidelijkheid/geschiedenis van de code:

- Lukken de testen in de commit 3ffe2c86? Waarom (niet)?
- Wat lost commit d0320b6a op?
- Wat is het probleem met de files in commit 9d184949?
- Wat doet commit 9b3e4065? Maakt dit de code makkelijker leesbaar? Makkelijker uitbreidbaar?


