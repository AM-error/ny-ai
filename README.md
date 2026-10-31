# 🌿 Naturmanden

En lille web-app til når man har det dårligt – fysisk eller psykisk. Man beskriver sit problem med egne ord og får:

- 👆 **Trykpunkter & massage** – hvor de sidder og hvordan man trykker
- 🍯 **Naturlige midler** – honning, ingefær, kamille, varme osv.
- 🧘 **Øvelser** – udstrækning, nerveglidning, vejrtrækning
- 💡 **Simple råd** til hverdagen
- 🩺 **Hvornår man skal søge læge**

Skriver man noget, der kan være akut (brystsmerter, lammelser, selvmordstanker …), vises 112 og Livslinien øverst.

## Kør den

Det er én HTML-fil uden afhængigheder. Åbn `index.html` i en browser, eller start en lokal server:

```
python3 -m http.server 8000
```

Læg den på GitHub Pages (Settings → Pages → branch), så kan den åbnes på telefonen og lægges på hjemmeskærmen. Den virker også offline.

## Tilføj et emne

Alt indhold ligger i `EMNER`-listen i `index.html`. Hvert emne har søgeord (`ord`), trykpunkter, midler, øvelser, råd og lægeråd.

> Appen giver almene råd om egenomsorg og erstatter ikke en læge.
