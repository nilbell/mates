# Diagrames de Venn

Versió pròpia, en català, de l'activitat *Venn Paint* de Transum (Venn Diagram, 3 nivells de pintar i Exam Questions). Un sol fitxer, `index.html`, sense instal·lar res i sense internet.

**Com obrir-lo:** doble clic a `Obrir-Venn.bat` (Chrome o Edge) o obre `index.html` directament.

## Pestanyes

| Pestanya | Què hi ha |
|---|---|
| **Venn inicial** | Tres cercles amb una propietat cadascun (per defecte Parell, Primer i Quadrat perfecte). S'arrosseguen els nombres de l'1 al 16 (o al 24) a la regió correcta. Es poden canviar les propietats, fer un **repte aleatori**, **Comprova** (verd/vermell), **Mostra solució** i **Reinicia**. |
| **Pinta · Nivell 1** | 15 diagrames de dos conjunts (`A`, `A∪B`, `A∩B`, `Ā`, `(A∪B)‾`…). |
| **Pinta · Nivell 2** | 20 diagrames de tres conjunts (`(A∩B)∪C`, `A∩(B∪C)`, `(C∪A)∩B`…). |
| **Pinta · Nivell 3** | 15 diagrames amb conjunts separats, inclosos o parcialment creuats. |
| **Preguntes d'examen** | 8 problemes de conjunts (llistes, enquestes de 2 i 3 conjunts, llegir un Venn, percentatges, fórmula de la unió, notació de zones acolorides). Es corregeixen sols; cada problema té la seva solució desplegable. |

## Pintar (nivells 1–3)

Es tria un color (el blanc fa de goma) i es clica sobre les regions. **Desfés/Refés**; **Comprova** (a dalt) revisa tots els diagrames d'un cop, i el botó **Comprova** de cada diagrama en revisa només aquell (✓ o ✗), per anar-los fent un a un; **Mostra solucions** (ratlles blaves sobre la zona correcta) o el botó **Solució** de cada diagrama. El rectangle també es pot pintar: representa l'univers, i per això `Ā` inclou la part de fora dels cercles.

## Notació

El complementari s'escriu com a **A barra** (`Ā`, amb ratlla a sobre), i `(A∪B)‾` és la ratlla damunt de tota la unió. Les expressions que barregen `∪` i `∩` duen parèntesis.

## Preguntes d'examen

Les respostes numèriques accepten comes o punts decimals; les probabilitats, fracció (`3/10`), decimal (`0,3`) o percentatge (`30%`). Les llistes d'elements s'escriuen separades per comes (`2, 4, 6`).

## Botons de dalt a la dreta

- **Web original ↗:** obre l'activitat de Transum en una pestanya nova.
- **Projecció:** lletra més gran per a la pissarra.
- **Imprimir:** imprimeix la vista actual.

## Per al docent que vol canviar-ho

- Expressions dels nivells: llistes `LV` dins de l'script (`["(A∪B)'","v2"]`: l'apòstrof és la barra). Formes dels diagrames: `LAYS`.
- Problemes: llista `Q`. Els resultats de les llistes es calculen sols; els de recompte (Venn amb nombres) són a mà.
