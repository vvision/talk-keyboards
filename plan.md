# Plan — Talk "Claviers customs"

**Public :** consultants IT
**Durée :** 45 minutes
**Outil :** Slidev (`slides.md`)
**Source :** `draft.md` (ne pas modifier)

---

## Structure

| # | Section | Slides | Durée |
|---|---------|--------|-------|
| 1 | **Hook** — clavier classique → gamer → PS/2 → "pourquoi on n'y pense jamais" | 4 | 2 min |
| 2 | **Le problème du clavier standard** — héritage machine à écrire, row stagger, AZERTY/QWERTY | 4 | 5 min |
| 3 | **Anatomie d'un clavier custom** — format, switches, keycaps, controller, firmware | 6 | 8 min |
| 4 | **Dispositions physiques** — row staggered → ortholinéaire → column stagger → split | 3 | 5 min |
| 5 | **Dispositions logicielles** — AZERTY → Ergol, home row, home row mods, layers, 1DH | 5 | 7 min |
| 6 | **Choisir ses composants** — budget, filaire/BT, soudure/hotswap, kit/PCB nu, format, acoustique | 4 | 7 min |
| 7 | **Étapes d'un build** — diodes, sockets, controller, flash, boîtier, switches, test | 2 | 5 min |
| 8 | **Retour perso** — mon setup, mes layers, la Svalboard, slide de clôture | 4 | 3 min |

**Total : ~43 slides actifs + 4 slides de séparation = 47 séparateurs `---`**
(buffer de ~3 min pour les échanges avec la salle)

---

## Points à compléter (section 8)

- `Mon setup` : modèle de clavier, switches, layout logiciel utilisé, retours honnêtes
- `Mes layers` : captures KLE ou schémas des layers 0 / 1 / 2 + apprentissages
- Photo du setup réel
- Photo de la Svalboard

## Assets à fournir (`./assets/`)

| Fichier attendu | Contenu |
|-----------------|---------|
| `keyboard-standard.jpg` | Clavier standard membrane |
| `keyboard-gamer.jpg` | Clavier gamer |
| `keyboard-gamer-rgb.jpg` | Clavier gamer RGB extrême |
| `ps2-connector.jpg` | Connecteur PS/2 vert |
| `typewriter-1873.jpg` | Machine à écrire Sholes & Glidden |
| `typewriter-mechanism.jpg` | Vue de dessous — tiges des marteaux |
| `keyboard-rowstagger.jpg` | Clavier moderne — rangées décalées |
| `switch-mx-cutaway.jpg` | Switch MX en coupe |
| `switch-choc.jpg` | Switch Choc low profile |
| `keycaps-profiles.jpg` | Comparaison profils SA / DSA / Cherry |
| `controller-nicer-nano.jpg` | nice!nano ou Pro Micro |
| `hand-finger-length.jpg` | Main posée à plat — longueur des doigts |
| `corne-kyria.jpg` | Corne ou Kyria — column stagger visible |
| `keyboard-mono-pronation.jpg` | Clavier monobloc — pronation forcée |
| `keyboard-split-tenting.jpg` | Split en tenting — poignets neutres |
| `qmk-toolbox.jpg` | QMK Toolbox — interface flash |
| `my-setup.jpg` | Photo du setup personnel |
| `svalboard.jpg` | Svalboard |

## Commandes

```bash
npm install        # installer Slidev
npm run dev        # lancer en mode présentation (hot reload)
npm run build      # build statique
npm run export     # export PDF
```