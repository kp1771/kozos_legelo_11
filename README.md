# A KÖZÖS LEGELŐ

## Feladatkiírás

- Készíts négy, egymással navigációval összekapcsolt HTML-oldalt!
- A történet számait, állomásait és a gazdák eltérő nézőpontjait jelenítsd meg.
- Az oldal fő szerkezete, a navigáció, a tehenek csoportja és a kártyák Flexboxszal rendeződjenek.
- Az utolsó oldalra készíts címkézett HTML-űrlapot rádiógombbal, jelölőnégyzettel,
  szövegdobozzal és küldés gombbal. A gombnak nem kell kiértékelnie a válaszokat.
- Haladóknak: készíts CSS-animációt a tehenek megjelenéséhez.

Az oldalak a felső navigációval és az alsó gombokkal járhatók végig.

Minden elrendezéshez **Flexboxot** használj!

A tehenek saját SVG-rajzból jelennek meg.
JavaScript és külső könyvtár nincs.

### Oldalak

1. index.html – 9 gazda, 9 tehén, napi 10 liter/tehén.
2. dontes.html – az egyik gazda második tehenet vesz; 10 tehén, napi 9 liter/tehén.
3. kovetkezmeny.html – mindegyik gazda második tehenet vesz; 18 tehén, napi 1 liter/tehén.
4. reflexio.html – rádiógomb, jelölőnégyzet, szövegmező és beépített HTML-ellenőrzés.

<img src="assets/tehenes_minta1.png" alt="minta">

### Színek és betűtípusok

A megadott színektől eltérhetsz, de css változókat használj!

:root {
--ink: #24372d;
--green: #2c6e50;
--dark: #174b38;
--mint: #e8f3df;
--cream: #f7f7ee;
--line: #d6e1d1;
--orange: #d77939;
--white: #fff;
}

Betűtípus: "Segoe UI"

### Űrlap

Az űrlap csak bemutató: a böngésző újratölti az oldalt, az adatokat senki nem értékeli
és nincs tároló szerver. Ne kérj személyes adatot.

<img src="assets/tehenes_minta4.png" alt="minta">

### Extrák

Haladó CSS-animáció: az első három HTML-fájl head részében a halado_animacio.css
link soráról távolítsd el a <!-- és --> jelölést. A reduced motion rendszerbeállítást
tiszteletben tartja. Bővítésként a tanulók külön késleltetést adhatnak a teheneknek
az egyedi --i változóval, vagy megváltoztathatják a kiemelt tehenek mozgását.

**Forrás:** Zöld Föld, szakképzés 9–10. évfolyam, 12–13. oldal. A webes szöveg
a tankönyvi példát saját szavakkal dolgozza fel.
