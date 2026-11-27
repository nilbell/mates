# Inkscape per a la làser

Tutorial en català (HTML) per aprendre a dissenyar amb **Inkscape 1.4** peces per a una **talladora làser**: tallar, gravar i marcar fusta (contraxapat/DM de 3 mm). Pensat per al professorat i per a l'alumnat d'**ESO** (nivell bàsic) i **Batxillerat** (nivell avançat).

## Com obrir-lo

Obre `index.html` amb un navegador (Chrome, Edge, Firefox). No cal internet excepte per a les tipografies (si no n'hi ha, fa servir les del sistema).

> Si l'obres des de Google Drive al navegador web, Drive no executa HTML: descarrega la carpeta o obre-la des de la unitat sincronitzada (`H:\La meva unitat\...`).

## Què hi ha

| Fitxer / carpeta | Contingut |
|---|---|
| `index.html` | El tutorial complet (17 apartats + configuració). |
| `js/exemples.js` | Els SVG d'exemple incrustats (els fa servir `index.html` per descarregar-los amb els colors triats). **Generat**, no editar a mà. |
| `svg/` | Fitxers SVG d'exemple amb els colors per defecte: plantilla, mostra, clauer, rètol, posagots, caixa amb encaixos. |
| `img/cap-*.png` | Captures de pantalla d'Inkscape en català. |
| `img/preview-*.png` | Vistes prèvies dels SVG (renderitzades amb Inkscape). |
| `scripts/genera_svgs.py` | Genera `svg/*.svg` i `js/exemples.js`. |
| `scripts/captura.ps1` | Funcions PowerShell per obrir Inkscape i fer captures automàtiques. |
| `docs/PROJECTE.md` | Decisions, com continuar el projecte des d'un altre ordinador, tasques pendents. |
| `CLAUDE.md` | Instruccions per a Claude Code si s'hi torna a treballar. |

## Configuració dins del tutorial

Botó **Configuració** (a dalt a la dreta):

- **Programa de la talladora:** LightBurn, RDWorks/LaserCut, xTool Creative Space, LaserGRBL o Altres (Trotec, Epilog, Glowforge). Els requadres amb vora verda del tutorial canvien segons la tria.
- **Colors de cada capa:** per defecte **tall = negre `#000000`**, **gravat = vermell `#FF0000`**, **marcat = blau `#0000FF`**.
- **Amplada del traç** (0,1 mm per defecte; 0,01 mm per a Trotec/Epilog).
- **Material i paràmetres** (potència, velocitat, passades) que es mostren a l'apartat 12.
- **Nivell:** mostrar o amagar els continguts de Batxillerat.

La configuració es desa al navegador de cada usuari (localStorage). Per canviar els **valors per defecte per a tothom**, edita l'objecte `DEFAULTS` al final de `index.html`.

## Regenerar els exemples

```powershell
python scripts/genera_svgs.py
```

Vegeu `docs/PROJECTE.md` per a la resta de procediments.
