# Polygon sushi

Interaktivní česká prezentace pro první setkání s Blenderem. Cílem je hranatá sushi scéna: maki, nigiri, dřevěný podnos a doplňky.

**Spustit:** [benes.dev/blender-sushi](https://benes.dev/blender-sushi/)

K prezentaci patří [tisknutelný tahák](https://benes.dev/blender-sushi/tahak.html) a [ukázkový model](https://benes.dev/blender-sushi/modely/polygon-sushi.blend). Zdrojový kód není veřejný.

## Obsah

24 snímků: rozhraní Blenderu, navigace, G/R/S, osy, Object a Edit Mode, low-poly styl, tři materiály, hranaté maki pomocí Inset a Extrude, duplikování, nigiri, podnos, dobrovolné doplňky, ukládání a kvíz.

V Obsahu lze zvolit 90, 120 nebo 45 minut. Výchozí 90minutový plán vede k hlavnímu podnosu. Hůlky a další části scény jsou dobrovolné. 45 minut je zkrácená ukázka jednoho maki. Plná scéna je v ukázkovém modelu.

## Ovládání

- Šipky, mezerník, PageDown a PageUp přepínají snímky. Home a End skočí na začátek a konec. Tlačítka dole a Obsah umožňují přímý skok.
- `N` zapíná poznámky pro učitele. Ukážou se v překryvu u spodního okraje a jsou vidět i na plátně. `F` zapíná celou obrazovku.
- Stopky měří čas setkání. Praktické výzvy mají samostatné časovače.
- 3D modely se otáčejí tažením, přibližují kolečkem a posouvají se Shiftem při tažení. Fungují také šipky při zaměřeném modelu, `+`, `−` a `R` pro původní pohled.
- Stav snímku, kontrolních bodů, palety a délky si pamatuje tento prohlížeč. „Nový začátek“ v Obsahu vynuluje průchod.

## Blender

Recepty počítají se standardním Blender keymap a vypnutým Emulate Numpad. Učíme levý klik pro výběr. Veškeré nové objekty se přidávají v Object Mode. Desetinná čísla se zadávají s tečkou. Před přesným insetem aplikujeme Scale.

Hlavní maki: Cube 1.6 × 1.6 × 1.2, Location Z 0.6. Horní face: `I .15`, `E -.1`, `I .375`, `E -.15`. Materiály Nori, Rice a Filling se vytvoří předem a přiřazují se přes Assign hned po každém Extrude, dokud je plocha vybraná. Nové stěny barvu zdědí. Horní úrovně jsou Z 1.2, 1.1 a .95.

Rendery i přiložená scéna vznikly v Blenderu 5.1. Ukázkový soubor obsahuje i studiovou kameru a osvětlení. Pro první setkání stačí uložený .blend a snímek Material Preview.

## Zdroje

Oficiální Blender Manual je odkazovaný v poznámkách a v okně „Ovládání a zdroje“. Všechny obrázky jsou rendery přiložené ukázkové scény. Scéna vznikla podle referenčního obrázku neznámého autora, který v prezentaci není.

Písma Big Shoulders, Atkinson Hyperlegible Next a JetBrains Mono jsou vložená pro offline použití pod licencí OFL.
