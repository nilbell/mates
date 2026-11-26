# Conjunts numèrics

Minijoc per repartir nombres en els conjunts **ℕ, ℤ, ℚ, 𝕀 i ℝ**. Els **complexos (ℂ)** no hi són per defecte: s'afegeixen a Configuració. Un sol fitxer: obre `index.html` amb Chrome o Edge (doble clic). No cal instal·lar res.

## Modes
- **Arrossega**: els nombres surten en una safata i s'han d'arrossegar (ratolí o dit) al conjunt **més petit** on hi càpiga, dins un diagrama de caixes imbricades. També es pot tocar el nombre i després el conjunt.
- **Classifica**: apareix un nombre i cal marcar **tots** els conjunts als quals pertany. En comprovar, es pinta de verd (ben marcat), vermell (sobra) o taronja discontinu (faltava).
- **Teoria**: dibuix dels conjunts (passant el ratolí per sobre ressalta la fitxa corresponent), definicions amb exemples i una guia de 5 passos per classificar.

## Configuració (botó ⚙)
- Activar/desactivar **ℚ**, **𝕀 + ℝ** (van junts) i **ℂ**. Per defecte **ℂ està desactivat** (cal marcar-lo aquí per afegir-lo). ℕ i ℤ sempre actius. Si actives un conjunt gran, s'activen els que hi caben a dins; el diagrama, la teoria i els nombres s'adapten.
- Tipus de nombres: fraccions i decimals exactes, decimals periòdics, arrels/π/irracionals.
- El 0 és natural (sí per defecte, conveni català).
- Nombres per ronda (8–20).
- Correcció a Arrossega: **immediata** (explica l'error al moment) o **al final** (botó «Comprova»).
- **Pantalla gran** (a la capçalera): lletra ampliada per a la pissarra digital.

La configuració es recorda al navegador (si el navegador ho permet).

## Per afegir nombres
Al principi del `<script>` de `index.html`, a la llista `POOL`, cada línia és `[conjunt més petit, tipus, nombre, valor, nota]`. Notació: `3/4` (fracció), `√16`, `∛8`, `√(9/16)`, `0,{3}` (període ratllat).
