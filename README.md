# Beertija

Sajt pivnice Beertija (Kneza Višeslava 63, Beograd).

## Hostovanje na GitHub Pages

1. Napravi novi repozitorijum na GitHubu.
2. Prebaci sadržaj ovog foldera u repozitorijum (index.html, support.js, assets/, .nojekyll).
3. Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, folder: `/ (root)`.
4. Sajt je posle minut-dva dostupan na `https://<korisnik>.github.io/<repo>/`.

## QR kod za jelovnik

Kad sajt bude živ, QR treba da vodi na link sa dodatkom `#jelovnik`:

```
https://<korisnik>.github.io/<repo>/#jelovnik
```

Gost skenira i odmah pada na sekciju jelovnika.

## Fajlovi

- `index.html` — ceo sajt (jedna stranica, sekcije povezane navigacijom)
- `support.js` — runtime potreban za renderovanje
- `assets/` — logo i fotografije
- `.nojekyll` — sprečava GitHub Jekyll obradu
