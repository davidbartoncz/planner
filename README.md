# Plánek

Úkoly, termíny a plán dne pro práci, domov i školu. Jeden HTML soubor, data zůstávají v zařízení.

## Zveřejnění na GitHub Pages

1. Na GitHubu vytvoř nový repozitář (např. `planek`) a nahraj do něj všechny soubory z této složky.
2. V repozitáři otevři **Settings → Pages**, u „Source“ zvol **Deploy from a branch**, větev `main`, složku `/ (root)` a ulož.
3. Za minutu až dvě bude aplikace na adrese `https://<tvuj-ucet>.github.io/planek/`.

Repozitář může být veřejný: veřejný je jen kód aplikace, tvoje úkoly se nikam neodesílají.

## Přidání na plochu

- **iPhone (Safari):** otevři adresu, klepni na Sdílet → Přidat na plochu.
- **Android (Chrome):** otevři adresu, v menu zvol Nainstalovat aplikaci (nebo Přidat na plochu).

Po prvním otevření funguje i offline.

## Přenos dat

Data jsou vázaná na adresu a prohlížeč. Na iPhonu má aplikace přidaná na plochu vlastní úložiště, oddělené od Safari.

1. Ve staré verzi: Více → Data → Zálohovat do souboru.
2. V nové verzi (už spuštěné z ikony na ploše): Více → Data → Obnovit ze zálohy.

Zálohu dělej pravidelně, třeba při týdenní revizi.

## Aktualizace

Nahraj nový `index.html` do repozitáře. Aplikace si novou verzi stáhne při dalším spuštění s internetem.
Pokud měníš i ikony nebo manifest, zvyš v `sw.js` číslo v `CACHE`.
