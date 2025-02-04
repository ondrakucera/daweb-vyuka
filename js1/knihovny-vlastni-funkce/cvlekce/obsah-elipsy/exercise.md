---
title: Obsah elipsy
demand: 1
---

Zlovolní zahrádkáři nám chtějí ztížit výměru pozemků a proto si pořídíli pozemek ve tvaru elipsy.

::fig[Elipsa]{src=assets/ellipse.png size=60}

Z matematiky víme, že známe-li šířku a výšku elipsy, její obsah je _polovina šířky_ krát _polovina výšky_ krát _číslo π_ (tj. přibližně 3,14).

Založte si prázdnou stránku s JavaScriptovým souborem a napište funkci `ellipseArea`, která spočítá (**vrátí**) plochu pozemku dle zadané šířky a výšky. Číslo π najdete v JavaScriptu v proměnné `Math.PI`.

Funkci `ellipseArea` otestujte (např. pomocí `console.log` vypište výsledek volání pro různé hdonoty do konzole).

- Pro šířku `1` a výšku `2` by mělo vyjít `1.5707963267948966`.
- Pro `2` a `2` pak `3.141592653589793`.

---solution

```js
const ellipseArea = (width, height) => {
  return (width / 2) * (height / 2) * Math.PI;
};

console.log(ellipseArea(1, 2));
console.log(ellipseArea(2, 2));
```
