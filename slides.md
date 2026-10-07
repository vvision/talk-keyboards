---
theme: default
title: "Reprogrammer son clavier"
author: Victor Voisin
highlighter: shiki
transition: slide-left
mdc: true
layout: cover
class: text-white
---

<img src="./assets/steampunk_kb_sxb.jpeg" alt="" class="absolute inset-0 w-full h-full object-cover -z-10" />
<div class="absolute inset-0 bg-black/60 -z-10" />

# Reprogrammer son clavier

<div class="text-xl text-white/85 mt-4">D'AZERTY au split : ergonomie, configuration et assemblage</div>

<div class="mt-12 text-sm text-white/70">
  Victor Voisin · Jeudi 8 octobre 2026 · 12h15
</div>

<!--
Laisser le titre respirer. Ne pas commencer à parler tout de suite.
-->

---

# Vous connaissez tous ça.

<div class="flex gap-8 items-center justify-center mt-8">
  <img src="./assets/logitech_k120.webp" alt="Clavier Logitech K120" class="h-100 rounded shadow object-contain" />
</div>

<!--
Commencer en silence. Laisser l'image parler.
"Vous avez tous ça sur votre bureau, ou quelque chose qui y ressemble."
-->

---

# Et peut-être ça aussi.

<div class="flex gap-8 items-center justify-center mt-8">
  <img src="./assets/corsair_k68.webp" alt="Clavier Corsair K68" class="h-110 rounded shadow object-contain" />
</div>

<!--
Demander à la salle: "Y'a des gamers parmi nous ?"
-->

---

# Et les plus anciens se souviendront...

<div class="flex gap-8 items-center justify-center mt-8">
  <img src="./assets/ps2_port.jpg" alt="Clavier Corsair K68" class="h-80 rounded shadow object-contain" />
</div>

<p class="text-center text-gray-400 mt-4 text-sm">La prise verte. La prise violette. Le bon vieux PS/2.</p>

<!--
Pause nostalgie. Laisser les gens sourire.
"C'est l'outil qu'on utilise 8h par jour, qu'on ne choisit presque jamais, et auquel on ne pense jamais."
-->

---
layout: center
class: text-center
---

# Pourquoi parler de claviers ?

<p class="text-xl mt-4 text-gray-400">
  C'est notre interface principale avec l'ordinateur.
</p>

<p class="text-xl mt-2 text-gray-400">
  Des milliers de frappes par jour, pendant des années.
</p>

<p class="text-xl mt-6 font-semibold">
  Et pourtant, on ne choisit presque jamais ce qu'on utilise.
</p>

<!--
Transition vers la section suivante.
"On va voir pourquoi ça mérite qu'on s'y intéresse — et ce qu'on peut faire."
-->

---
layout: two-cols
---

# 1873.

<div class="flex flex-col justify-center h-full pr-8">
  <p class="text-lg">Christopher Latham Sholes invente la machine à écrire commerciale.</p>
  <p class="text-lg mt-4">Il conçoit le layout <strong>QWERTY</strong> pour résoudre un problème mécanique : éviter que les marteaux adjacents se coincent.</p>
  <p class="text-lg mt-4 text-gray-400">Pas pour la vitesse. Pas pour le confort. Pour la <em>mécanique</em>.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <div class="h-56 w-72 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 machine à écrire Sholes & Glidden 1873
  </div>
</div>

<!--
"Le clavier qu'on utilise aujourd'hui a 150 ans. Il a été conçu pour éviter un problème mécanique qui n'existe plus depuis l'invention du clavier électronique."
-->

---

# Le row stagger : un héritage mécanique

<div class="flex gap-10 items-center justify-center mt-6">
  <div class="flex flex-col items-center gap-3">
    <div class="h-44 w-64 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
      📷 vue de dessous machine à écrire — tiges des marteaux
    </div>
    <p class="text-sm text-gray-400">Les tiges s'entrecroisent en diagonale</p>
  </div>
  <div class="text-4xl text-gray-300">→</div>
  <div class="flex flex-col items-center gap-3">
    <div class="h-44 w-64 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
      📷 clavier moderne — rangées décalées
    </div>
    <p class="text-sm text-gray-400">On a gardé le décalage... sans les tiges</p>
  </div>
</div>

<!--
"Les rangées de touches sont décalées entre elles — pas parce que c'est ergonomique, mais parce que les tiges mécaniques des marteaux s'organisaient en diagonale. On a retiré les tiges, on a gardé le décalage."
-->

---
layout: center
class: text-center
---

# Nos mains s'adaptent à l'outil.

<p class="text-xl mt-6 text-gray-400">Pas l'inverse.</p>

<div class="mt-10 flex justify-center gap-16 text-left">
  <div>
    <p class="font-semibold mb-2">Ce qu'on fait naturellement</p>
    <ul class="text-gray-400 space-y-1">
      <li>Poignets dans l'axe des avant-bras</li>
      <li>Doigts qui tombent verticalement</li>
      <li>Mains légèrement écartées</li>
    </ul>
  </div>
  <div>
    <p class="font-semibold mb-2">Ce que le clavier standard impose</p>
    <ul class="text-gray-400 space-y-1">
      <li>Poignets en pronation forcée</li>
      <li>Doigts en diagonale (row stagger)</li>
      <li>Mains rapprochées sur un bloc</li>
    </ul>
  </div>
</div>

<!--
"Sur la durée : tensions, TMS, syndrome du canal carpien. Et tout ça pour un design qui date de 1873 et qui résolvait un problème qui n'existe plus."
Transition : "Alors qu'est-ce qu'on peut faire ?"
-->

---
layout: center
class: text-center
---

# Il existe une alternative.

<p class="text-2xl mt-6 font-semibold">Le clavier custom.</p>

<p class="text-xl mt-4 text-gray-400">
  Choisir chaque composant. Adapter à sa morphologie. Programmer ses raccourcis.
</p>

<!--
Transition vers la section anatomie / panorama technique.
"Voyons d'abord de quoi est fait un clavier — pour comprendre ce qu'on peut changer."
-->

---
layout: center
class: text-center
---

# Un clavier, c'est 5 composants.

<div class="mt-10 flex justify-center gap-6 text-center">
  <div class="flex flex-col items-center gap-2">
    <div class="text-3xl">📐</div>
    <p class="font-semibold">Format</p>
    <p class="text-sm text-gray-400">nombre de touches</p>
  </div>
  <div class="flex flex-col items-center gap-2">
    <div class="text-3xl">🔘</div>
    <p class="font-semibold">Switches</p>
    <p class="text-sm text-gray-400">le mécanisme de frappe</p>
  </div>
  <div class="flex flex-col items-center gap-2">
    <div class="text-3xl">🔲</div>
    <p class="font-semibold">Keycaps</p>
    <p class="text-sm text-gray-400">les capuchons</p>
  </div>
  <div class="flex flex-col items-center gap-2">
    <div class="text-3xl">🧠</div>
    <p class="font-semibold">Controller</p>
    <p class="text-sm text-gray-400">le cerveau</p>
  </div>
  <div class="flex flex-col items-center gap-2">
    <div class="text-3xl">💾</div>
    <p class="font-semibold">Firmware</p>
    <p class="text-sm text-gray-400">la programmation</p>
  </div>
</div>

<!--
"Chacun de ces composants est un choix. Et chaque choix a des implications sur le confort, le son, le prix, et les fonctionnalités."
-->

---

# Format : combien de touches ?

<div class="mt-6 space-y-4">
  <div class="flex items-center gap-4">
    <span class="w-28 text-right text-sm text-gray-400">Full size</span>
    <div class="h-8 bg-blue-500 rounded" style="width: 100%"></div>
    <span class="text-sm text-gray-400 w-12">~104</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="w-28 text-right text-sm text-gray-400">TKL</span>
    <div class="h-8 bg-blue-400 rounded" style="width: 82%"></div>
    <span class="text-sm text-gray-400 w-12">~87</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="w-28 text-right text-sm text-gray-400">65%</span>
    <div class="h-8 bg-blue-300 rounded" style="width: 63%"></div>
    <span class="text-sm text-gray-400 w-12">~68</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="w-28 text-right text-sm text-gray-400">60%</span>
    <div class="h-8 bg-blue-200 rounded" style="width: 55%"></div>
    <span class="text-sm text-gray-400 w-12">~61</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="w-28 text-right text-sm text-gray-400">Split 36–42</span>
    <div class="h-8 bg-green-400 rounded flex items-center px-2" style="width: 38%">
      <span class="text-xs text-white">⬅ main gauche</span>
    </div>
    <div class="h-8 bg-green-400 rounded flex items-center px-2" style="width: 38%">
      <span class="text-xs text-white">main droite ➡</span>
    </div>
  </div>
</div>

<p class="mt-6 text-sm text-gray-400">Moins de touches = moins de déplacement = mains qui restent en position.</p>

<!--
"On croit souvent qu'on a besoin de toutes ces touches. En pratique, avec des layers, 42 touches couvrent tout — et les mains bougent beaucoup moins."
-->

---
layout: two-cols
---

# Switches : le mécanisme de frappe

<div class="pr-8 space-y-4 mt-4">
  <div>
    <p class="font-semibold">Membrane</p>
    <p class="text-sm text-gray-400">Une membrane en caoutchouc sous les touches. Silencieux, peu cher, peu de retour tactile. Le standard des claviers d'entreprise.</p>
  </div>
  <div>
    <p class="font-semibold">Mécanique</p>
    <p class="text-sm text-gray-400">Un switch individuel par touche. Trois familles :</p>
    <ul class="text-sm text-gray-400 mt-1 space-y-1">
      <li><strong class="text-white">Linéaire</strong> — frappe fluide, pas de clic (ex: Red)</li>
      <li><strong class="text-white">Tactile</strong> — retour physique sans clic sonore (ex: Brown)</li>
      <li><strong class="text-white">Clicky</strong> — retour tactile + sonore (ex: Blue)</li>
    </ul>
  </div>
  <div>
    <p class="font-semibold">MX vs Choc</p>
    <p class="text-sm text-gray-400">MX = hauteur standard. Choc (Kailh) = low profile, clavier plus plat, compatibilité split.</p>
  </div>
</div>

::right::

<div class="flex flex-col gap-4 items-center justify-center h-full">
  <div class="h-36 w-56 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 switch MX en coupe
  </div>
  <div class="h-36 w-56 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 switch Choc low profile
  </div>
</div>

<!--
"Le switch, c'est ce qui donne au clavier son feeling. C'est souvent la première chose qu'on personnalise — et c'est aussi ce qu'on peut changer avec le hotswap, on en reparlera."
-->

---
layout: two-cols
---

# Keycaps : les capuchons

<div class="pr-8 space-y-4 mt-4">
  <div>
    <p class="font-semibold">Matière</p>
    <ul class="text-sm text-gray-400 space-y-1 mt-1">
      <li><strong class="text-white">ABS</strong> — brillant avec le temps, moins cher</li>
      <li><strong class="text-white">PBT</strong> — mat, plus résistant, son plus sourd</li>
    </ul>
  </div>
  <div>
    <p class="font-semibold">Profil (la hauteur et la forme)</p>
    <ul class="text-sm text-gray-400 space-y-1 mt-1">
      <li><strong class="text-white">OEM / Cherry</strong> — profil sculpté, rangées à hauteur différente</li>
      <li><strong class="text-white">DSA / XDA</strong> — uniforme, toutes rangées identiques</li>
      <li><strong class="text-white">SA</strong> — haut et sculpté, son très clicky</li>
    </ul>
  </div>
  <p class="text-sm text-gray-400 mt-2">Le profil uniforme (DSA/XDA) est souvent préféré en split et ortholinéaire — toutes les touches sont interchangeables.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <div class="h-64 w-56 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 comparaison profils keycaps SA / DSA / Cherry
  </div>
</div>

<!--
"Les keycaps, c'est souvent ce qui fait l'esthétique du clavier. Mais le profil a aussi un impact sur le confort — surtout quand on commence à changer la disposition physique des touches."
-->

---
layout: two-cols
---

# Controller & Firmware

<div class="pr-8 mt-4 space-y-5">
  <div>
    <p class="font-semibold">Le controller</p>
    <p class="text-sm text-gray-400 mt-1">Un microcontrôleur qui lit la matrice de touches et envoie les signaux USB (ou Bluetooth).</p>
    <ul class="text-sm text-gray-400 space-y-1 mt-2">
      <li><strong class="text-white">Pro Micro / Elite-C</strong> — filaire, USB-C</li>
      <li><strong class="text-white">RP2040</strong> — filaire, plus puissant, mémoire flash généreuse (ex: Pico, KB2040)</li>
      <li><strong class="text-white">nice!nano</strong> — sans-fil, Bluetooth, batterie</li>
    </ul>
  </div>
  <div>
    <p class="font-semibold">Le firmware</p>
    <ul class="text-sm text-gray-400 space-y-1 mt-1">
      <li><strong class="text-white">QMK</strong> — filaire, open source, très complet</li>
      <li><strong class="text-white">ZMK</strong> — sans-fil (BLE), open source</li>
    </ul>
    <p class="text-sm text-gray-400 mt-2">C'est le firmware qui permet les layers, les macros, le home row mods — on y reviendra.</p>
  </div>
</div>

::right::

<div class="flex flex-col gap-4 items-center justify-center h-full">
  <div class="h-36 w-56 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 nice!nano ou Pro Micro
  </div>
  <div class="font-mono text-xs text-gray-400 bg-gray-100 dark:bg-gray-800 rounded p-3 w-56">
    <p>// QMK keymap.c</p>
    <p>LAYOUT(</p>
    <p>&nbsp;&nbsp;KC_A, KC_B, MO(1),</p>
    <p>&nbsp;&nbsp;...</p>
    <p>)</p>
  </div>
</div>

<!--
"Le firmware, c'est là où le clavier devient vraiment custom. Vous pouvez redéfinir chaque touche, créer des layers, des macros, des comportements selon le contexte. On y revient dans la section layout logiciel."
-->

---

# Dispositions physiques : 4 familles

<div class="grid grid-cols-2 gap-4 row-gap-4 mt-6">

  <div>
    <p class="font-semibold mb-2">Row staggered <span class="text-gray-400 text-sm font-normal">— l'héritage</span></p>
    <div class="font-mono text-xs leading-relaxed bg-gray-100 dark:bg-gray-800 rounded p-3">
      <div class="flex gap-1">
        <span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">Q</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">W</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">E</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">R</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">T</span>
      </div>
      <div class="flex gap-1 mt-1 ml-3">
        <span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">A</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">S</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">D</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">F</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">G</span>
      </div>
      <div class="flex gap-1 mt-1 ml-6">
        <span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">Z</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">X</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">C</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">V</span><span class="bg-gray-300 dark:bg-gray-600 px-1.5 py-1 rounded">B</span>
      </div>
    </div>
    <p class="text-xs text-gray-400 mt-1">Décalage horizontal hérité des tiges mécaniques</p>
  </div>

  <div>
    <p class="font-semibold mb-2">Ortholinéaire <span class="text-gray-400 text-sm font-normal">— la grille</span></p>
    <div class="font-mono text-xs leading-relaxed bg-gray-100 dark:bg-gray-800 rounded p-3">
      <div class="flex gap-1">
        <span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">Q</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">W</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">E</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">R</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">T</span>
      </div>
      <div class="flex gap-1 mt-1">
        <span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">A</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">S</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">D</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">F</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">G</span>
      </div>
      <div class="flex gap-1 mt-1">
        <span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">Z</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">X</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">C</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">V</span><span class="bg-blue-300 dark:bg-blue-700 px-1.5 py-1 rounded">B</span>
      </div>
    </div>
    <p class="text-xs text-gray-400 mt-1">Colonnes alignées, doigts tombent droit</p>
  </div>

  <div>
    <p class="font-semibold mb-2">Column staggered <span class="text-gray-400 text-sm font-normal">— l'anatomique</span></p>
    <div class="font-mono text-xs leading-relaxed bg-gray-100 dark:bg-gray-800 rounded p-3">
      <div class="flex gap-1 items-end">
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:6px">Q</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:10px">W</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:14px">E</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:8px">R</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:2px">T</span>
      </div>
      <div class="flex gap-1 items-end">
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:6px">A</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:10px">S</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:14px">D</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:8px">F</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded" style="margin-bottom:2px">G</span>
      </div>
    </div>
    <p class="text-xs text-gray-400 mt-1">Colonnes décalées selon la longueur des doigts</p>
  </div>

  <div>
    <p class="font-semibold mb-2">Split <span class="text-gray-400 text-sm font-normal">— deux moitiés</span></p>
    <div class="font-mono text-xs leading-relaxed bg-gray-100 dark:bg-gray-800 rounded p-3 flex gap-3">
      <div>
        <div class="flex gap-1">
          <span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">Q</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">W</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">E</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">R</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">T</span>
        </div>
        <div class="flex gap-1 mt-1">
          <span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">A</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">S</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">D</span>
<span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">F</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">G</span>
        </div>
      </div>
      <span class="text-gray-400 self-center">⟵ ⟶</span>
      <div>
        <div class="flex gap-1">
          <span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">Y</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">U</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">I</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">O</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">P</span>
        </div>
        <div class="flex gap-1 mt-1">
          <span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">H</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">J</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">K</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">L</span><span class="bg-purple-300 dark:bg-purple-700 px-1.5 py-1 rounded">/</span>
        </div>
      </div>
    </div>
    <p class="text-xs text-gray-400 mt-1">Écartement réglable, épaules décontractées</p>
  </div>

</div>

<!--
"Ces quatre familles ne sont pas exclusives — un split peut être column staggered. C'est même la combinaison la plus répandue en clavier ergonomique."
-->

---
layout: center
class: text-center
---

# Le column stagger suit l'anatomie.

<div class="mt-8 flex justify-center gap-16 items-start">
  <div class="flex flex-col items-center gap-2">
    <div class="h-52 w-44 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
        <img src="./assets/etude_main_de_vinci.jpg" alt="Etude des mains - Léonard De Vinci" class="h-100 rounded shadow object-contain" />
    </div>
    <p class="text-sm text-gray-400">L'auriculaire est plus court.<br>Le majeur est le plus long.</p>
  </div>
  <div class="text-4xl text-gray-300 self-center">→</div>
  <div class="flex flex-col items-center gap-2">
    <div class="h-52 w-44 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
      📷 Corne / Kyria — column stagger visible
    </div>
    <p class="text-sm text-gray-400">Les colonnes suivent<br>la longueur naturelle des doigts.</p>
  </div>
</div>

<!--
"Sur un row staggered, tous vos doigts font le même trajet vertical. Sur un column staggered, chaque colonne est positionnée pour que le doigt correspondant atterrisse naturellement dessus, sans extension."
-->

---
layout: two-cols
---

# Le split : pourquoi ça change tout

<div class="pr-8 mt-4 space-y-4">
  <div>
    <p class="font-semibold">Posture</p>
    <p class="text-sm text-gray-400">Un clavier monobloc rapproche les mains et force la pronation des poignets. Le split permet de placer chaque moitié dans l'axe naturel des avant-bras.</p>
  </div>
  <div>
    <p class="font-semibold">Angle et hauteur libres</p>
    <p class="text-sm text-gray-400">On peut incliner les deux moitiés en tenting (rotation vers le haut) pour réduire encore la pronation. Ou les écarter davantage selon la morphologie.</p>
  </div>
  <div>
    <p class="font-semibold">Connexion</p>
    <p class="text-sm text-gray-400">Les deux moitiés sont reliées par câble TRRS (filaire) ou en Bluetooth (sans-fil avec nice!nano + ZMK).</p>
  </div>
</div>

::right::

<div class="flex flex-col gap-4 items-center justify-center h-full">
  <div class="h-40 w-56 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 clavier monobloc — pronation forcée
  </div>
  <div class="h-40 w-56 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 split en tenting — poignets neutres
  </div>
</div>

<!--
"C'est souvent le changement le plus impactant, même avant de changer le layout logiciel. Juste séparer les deux moitiés améliore déjà la posture."
Transition : "Une fois qu'on a le bon clavier physiquement, on peut s'attaquer au layout logiciel — ce que les touches font réellement."
-->

---

# Layouts logiciels : ce que les touches font

<div class="mt-6 space-y-3">
  <div class="flex items-center gap-4 p-3 rounded bg-gray-100 dark:bg-gray-800">
    <span class="w-36 font-semibold text-sm shrink-0">QWERTY / AZERTY</span>
    <span class="text-sm text-gray-400">Héritage machine à écrire. Lettres fréquentes éparpillées, home row peu optimisée pour la langue.</span>
  </div>
  <div class="flex items-center gap-4 p-3 rounded bg-gray-100 dark:bg-gray-800">
    <span class="w-36 font-semibold text-sm shrink-0">Dvorak / BÉPO</span>
    <span class="text-sm text-gray-400">Années 1930–2000. Optimisés pour minimiser les déplacements (anglais / français). Première génération d'alternatives sérieuses.</span>
  </div>
  <div class="flex items-center gap-4 p-3 rounded bg-blue-50 dark:bg-blue-900">
    <span class="w-36 font-semibold text-sm shrink-0">Colemak-DH</span>
    <span class="text-sm text-gray-400">Optimisé anglais, très populaire. Variante DH déplace D et H sur la home row, réduit les extensions latérales de l'index.</span>
  </div>
  <div class="flex items-center gap-4 p-3 rounded bg-blue-50 dark:bg-blue-900">
    <span class="w-36 font-semibold text-sm shrink-0">QWERTY-Lafayette</span>
    <span class="text-sm text-gray-400">Garde QWERTY comme base (transition douce) et ajoute un layer dédié aux caractères français et symboles via une touche morte.</span>
  </div>
  <div class="flex items-center gap-4 p-3 rounded bg-blue-50 dark:bg-blue-900">
    <span class="w-36 font-semibold text-sm shrink-0">Ergol</span>
    <span class="text-sm text-gray-400">Français (2023). Optimisé pour français <em>et</em> anglais + code. Tire parti des layers pour les accents sans couche morte complexe.</span>
  </div>
</div>

<p class="text-xs text-gray-400 mt-4">La courbe d'apprentissage existe — compter 2 à 4 semaines pour retrouver sa vitesse.</p>

<!--
"Changer de layout logiciel, c'est un investissement. Mais si vous passez 40h par semaine à taper, ça vaut la peine de l'optimiser."
"Je ne dis pas qu'il faut tous changer — mais comprendre que c'est possible et que ça a un impact réel, c'est déjà beaucoup."
-->

---

# La home row : position de repos

<div class="mt-4 flex flex-col items-center gap-6">

  <div class="text-center">
    <p class="text-sm text-gray-400 mb-2">AZERTY — home row</p>
    <div class="flex gap-1 justify-center font-mono text-sm">
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">Q</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">S</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">D</span>
      <span class="bg-orange-200 dark:bg-orange-800 px-2 py-1.5 rounded font-bold">F</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">G</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">H</span>
      <span class="bg-orange-200 dark:bg-orange-800 px-2 py-1.5 rounded font-bold">J</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">K</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">L</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">M</span>
    </div>
    <p class="text-xs text-gray-400 mt-1">Lettres fréquentes en français : E, A, I, S, N, R, T... <strong class="text-orange-400">aucune ici sauf S</strong></p>
  </div>

  <div class="text-center">
    <p class="text-sm text-gray-400 mb-2">Ergol — home row</p>
    <div class="flex gap-1 justify-center font-mono text-sm">
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">C</span>
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">S</span>
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">E</span>
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">N</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">F</span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded">L</span>
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">R</span>
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">T</span>
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">I</span>
      <span class="bg-green-200 dark:bg-green-800 px-2 py-1.5 rounded font-bold">U</span>
    </div>
    <p class="text-xs text-gray-400 mt-1">Les lettres les plus fréquentes <strong class="text-green-400">sont sur la home row</strong></p>
  </div>

</div>

<!--
"L'objectif d'un layout optimisé : que vos doigts ne bougent presque pas. Les lettres viennent à eux, pas l'inverse."
-->

---
layout: two-cols
---

# Home row mods

<div class="pr-8 mt-4 space-y-4">
  <p class="text-sm text-gray-400">Une touche, deux rôles selon comment on l'utilise :</p>

  <div class="bg-gray-100 dark:bg-gray-800 rounded p-3 space-y-2 text-sm">
    <div class="flex justify-between">
      <span><strong>Tap</strong> (frappe rapide)</span><span class="text-gray-400">→ la lettre</span>
    </div>
    <div class="flex justify-between">
      <span><strong>Hold</strong> (maintien)</span><span class="text-gray-400">→ le modifier</span>
    </div>
  </div>

  <div class="font-mono text-xs text-center mt-2">
    <div class="flex gap-1 justify-center">
      <span class="bg-blue-200 dark:bg-blue-800 px-2 py-1.5 rounded">A<br><span class="text-xs text-blue-600 dark:text-blue-300">⌘</span></span>
      <span class="bg-blue-200 dark:bg-blue-800 px-2 py-1.5 rounded">S<br><span class="text-xs text-blue-600 dark:text-blue-300">⌥</span></span>
      <span class="bg-blue-200 dark:bg-blue-800 px-2 py-1.5 rounded">D<br><span class="text-xs text-blue-600 dark:text-blue-300">⇧</span></span>
      <span class="bg-blue-200 dark:bg-blue-800 px-2 py-1.5 rounded">F<br><span class="text-xs text-blue-600 dark:text-blue-300">⌃</span></span>
      <span class="bg-gray-200 dark:bg-gray-700 px-2 py-1.5 rounded opacity-40">G</span>
    </div>
  </div>

  <p class="text-sm text-gray-400">Les modifiers (Ctrl, Shift, Alt, Cmd) sont accessibles sans déplacer les mains, sans douleur au petit doigt.</p>
  <p class="text-xs text-gray-400">Configuré dans QMK/ZMK avec des timings ajustables.</p>
</div>

::right::

<div class="flex flex-col justify-center h-full gap-4 pl-4">
  <div class="bg-gray-100 dark:bg-gray-800 rounded p-4 space-y-2 text-sm">
    <p class="font-semibold text-xs text-gray-400 uppercase tracking-wide">Exemple</p>
    <p><span class="font-mono bg-blue-100 dark:bg-blue-900 px-1 rounded">tap A</span> → écrit "a"</p>
    <p><span class="font-mono bg-blue-100 dark:bg-blue-900 px-1 rounded">hold A</span> → active ⌘ (Cmd)</p>
    <p><span class="font-mono bg-blue-100 dark:bg-blue-900 px-1 rounded">hold A + tap C</span> → ⌘C (copier)</p>
  </div>
  <p class="text-xs text-gray-400">La clé : le firmware distingue tap et hold grâce à la durée et au contexte (d'autres touches pressées simultanément).</p>
</div>

<!--
"C'est un des concepts les plus puissants du clavier custom. Au début ça demande un peu d'adaptation, mais une fois intégré, ça devient naturel — et on ne comprend plus comment on faisait avant."
-->

---

# Layers et philosophie 1DH

<div class="grid grid-cols-2 gap-8 mt-4">

  <div>
    <p class="font-semibold mb-3">Les layers : des claviers virtuels empilés</p>
    <div class="space-y-2 text-sm">
      <div class="flex items-center gap-3 p-2 rounded bg-gray-100 dark:bg-gray-800">
        <span class="font-mono text-xs bg-gray-200 dark:bg-gray-700 px-2 py-1 rounded w-16 text-center">Layer 0</span>
        <span class="text-gray-400">Lettres — usage normal</span>
      </div>
      <div class="flex items-center gap-3 p-2 rounded bg-blue-50 dark:bg-blue-900">
        <span class="font-mono text-xs bg-blue-200 dark:bg-blue-800 px-2 py-1 rounded w-16 text-center">Layer 1</span>
        <span class="text-gray-400">Chiffres, symboles</span>
      </div>
      <div class="flex items-center gap-3 p-2 rounded bg-green-50 dark:bg-green-900">
        <span class="font-mono text-xs bg-green-200 dark:bg-green-800 px-2 py-1 rounded w-16 text-center">Layer 2</span>
        <span class="text-gray-400">Navigation (↑↓←→, PgUp…)</span>
      </div>
      <div class="flex items-center gap-3 p-2 rounded bg-purple-50 dark:bg-purple-900">
        <span class="font-mono text-xs bg-purple-200 dark:bg-purple-800 px-2 py-1 rounded w-16 text-center">Layer 3</span>
        <span class="text-gray-400">Fonctions, raccourcis app</span>
      </div>
    </div>
    <p class="text-xs text-gray-400 mt-3">On active un layer en maintenant une touche (comme Fn sur un laptop).</p>
  </div>

  <div>
    <p class="font-semibold mb-3">Philosophie 1DH</p>
    <p class="text-sm text-gray-400 mb-3"><strong class="text-white">1 Distance de la Home row</strong> maximum. Aucun doigt ne s'étend à plus d'une touche de sa position de repos.</p>
    <div class="font-mono text-xs bg-gray-100 dark:bg-gray-800 rounded p-3">
      <div class="flex gap-1 justify-center">
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
      </div>
      <div class="flex gap-1 justify-center mt-1">
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded text-xs font-bold">H</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded text-xs font-bold">O</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded text-xs font-bold">M</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded text-xs font-bold">E</span>
        <span class="bg-green-300 dark:bg-green-700 px-1.5 py-1 rounded text-xs font-bold">R</span>
      </div>
      <div class="flex gap-1 justify-center mt-1">
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
        <span class="bg-yellow-200 dark:bg-yellow-800 px-1.5 py-1 rounded text-xs">•</span>
      </div>
      <p class="text-center text-gray-400 mt-2 text-xs">Zone verte = home row<br>Zone jaune = 1DH max</p>
    </div>
    <p class="text-xs text-gray-400 mt-2">Ce principe justifie 36–42 touches : tout ce dont on a besoin tient dans cette zone, avec les layers.</p>
  </div>

</div>

<!--
"C'est la boucle qui ferme tout : peu de touches, layers pour tout atteindre, home row mods pour les modifiers. Les mains ne bougent presque plus."
Transition vers la section suivante : "Maintenant qu'on sait quoi choisir, comment on construit ?"
-->

---
layout: center
class: text-center
---

# Construire son clavier : par où commencer ?

<p class="text-xl mt-4 text-gray-400">Six questions à se poser, dans l'ordre.</p>

<div class="mt-8 flex justify-center gap-3 flex-wrap">
  <span class="px-4 py-2 bg-gray-100 dark:bg-gray-800 rounded-full text-sm font-semibold">💶 Budget</span>
  <span class="px-4 py-2 bg-gray-100 dark:bg-gray-800 rounded-full text-sm font-semibold">🔌 Filaire ou sans-fil</span>
  <span class="px-4 py-2 bg-gray-100 dark:bg-gray-800 rounded-full text-sm font-semibold">🔧 Soudure ou hotswap</span>
  <span class="px-4 py-2 bg-gray-100 dark:bg-gray-800 rounded-full text-sm font-semibold">📦 Kit ou PCB nu</span>
  <span class="px-4 py-2 bg-gray-100 dark:bg-gray-800 rounded-full text-sm font-semibold">📐 Format</span>
  <span class="px-4 py-2 bg-gray-100 dark:bg-gray-800 rounded-full text-sm font-semibold">🔊 Acoustique</span>
</div>

<!--
"Ces six questions se répondent dans l'ordre — chaque réponse réduit l'espace des choix suivants."
-->

---

# Budget & connectivité

<div class="grid grid-cols-2 gap-8 mt-6">

  <div>
    <p class="font-semibold mb-3">💶 Budget</p>
    <div class="space-y-2">
      <div class="flex items-start gap-3 p-3 rounded bg-gray-100 dark:bg-gray-800 text-sm">
        <span class="font-mono text-green-500 font-bold shrink-0">~100 €</span>
        <span class="text-gray-400">Kit basique, switches d'entrée de gamme. Bon pour tester.</span>
        <span class="">(<a href="https://tompi.github.io/cheapino/">cheapino</a>)</span>
      </div>
      <div class="flex items-start gap-3 p-3 rounded bg-gray-100 dark:bg-gray-800 text-sm">
        <span class="font-mono text-yellow-500 font-bold shrink-0">200–300 €</span>
        <span class="text-gray-400">Kit complet, bons switches, boîtier correct. Le sweet spot.</span>
      </div>
      <div class="flex items-start gap-3 p-3 rounded bg-gray-100 dark:bg-gray-800 text-sm">
        <span class="font-mono text-red-400 font-bold shrink-0">400 €+</span>
        <span class="text-gray-400">Boîtier aluminium, switches haut de gamme lubrifiés, keycaps PBT gravées laser.</span>
      </div>
    </div>
    <p class="text-xs text-gray-400 mt-2">Le plus grand budget : le temps. Compter 2–5h de build pour un débutant.</p>
  </div>

  <div>
    <p class="font-semibold mb-3">🔌 Filaire ou sans-fil ?</p>
    <div class="space-y-3 text-sm">
      <div class="p-3 rounded bg-gray-100 dark:bg-gray-800">
        <p class="font-semibold">Filaire</p>
        <ul class="text-gray-400 mt-1 space-y-0.5">
          <li>✅ Firmware QMK, très mature</li>
          <li>✅ Pas de batterie à gérer</li>
          <li>✅ Latence minimale</li>
          <li>❌ Câble(s) sur le bureau</li>
        </ul>
      </div>
      <div class="p-3 rounded bg-blue-50 dark:bg-blue-900">
        <p class="font-semibold">Sans-fil (BLE)</p>
        <ul class="text-gray-400 mt-1 space-y-0.5">
          <li>✅ Bureau épuré, multi-device</li>
          <li>✅ Firmware ZMK, actif</li>
          <li>❌ Batterie à charger (~mois)</li>
          <li>❌ Légèrement plus complexe à flasher</li>
        </ul>
      </div>
    </div>
  </div>

</div>

<!--
"Le sans-fil, c'est tentant — mais pour un premier build, le filaire simplifie beaucoup le debug. On peut toujours switcher le controller plus tard."
-->

---

# Soudure ou hotswap ? Kit ou PCB nu ?

<div class="grid grid-cols-2 gap-8 mt-6">

  <div>
    <p class="font-semibold mb-3">🔧 Soudure vs hotswap</p>
    <div class="space-y-2 text-sm">
      <div class="p-3 rounded bg-gray-100 dark:bg-gray-800">
        <p class="font-semibold">Soudure</p>
        <ul class="text-gray-400 mt-1 space-y-0.5">
          <li>✅ Plus de choix de switches</li>
          <li>✅ Connexion plus fiable long terme</li>
          <li>❌ Irréversible sans dessouder</li>
          <li>❌ Nécessite fer à souder + pratique</li>
        </ul>
      </div>
      <div class="p-3 rounded bg-green-50 dark:bg-green-900">
        <p class="font-semibold">Hotswap (sockets Kailh)</p>
        <ul class="text-gray-400 mt-1 space-y-0.5">
          <li>✅ Switches remplaçables à la main</li>
          <li>✅ Idéal pour expérimenter</li>
          <li>✅ Recommandé pour un premier build</li>
          <li>❌ Légèrement plus fragile si mal manipulé</li>
        </ul>
      </div>
    </div>
  </div>

  <div>
    <p class="font-semibold mb-3">📦 Kit ou PCB nu ?</p>
    <div class="space-y-2 text-sm">
      <div class="p-3 rounded bg-green-50 dark:bg-green-900">
        <p class="font-semibold">Kit complet</p>
        <ul class="text-gray-400 mt-1 space-y-0.5">
          <li>✅ PCB + boîtier + composants fournis</li>
          <li>✅ Guide de build disponible</li>
          <li>✅ <strong>Recommandé pour commencer</strong></li>
          <li class="text-gray-500">Ex : Corne, Lily58, Kyria, Sofle</li>
        </ul>
      </div>
      <div class="p-3 rounded bg-gray-100 dark:bg-gray-800">
        <p class="font-semibold">PCB nu / design custom</p>
        <ul class="text-gray-400 mt-1 space-y-0.5">
          <li>✅ Liberté totale (KiCad + EasyEDA)</li>
          <li>✅ Fabriquer chez JLCPCB, PCBWay</li>
          <li>❌ Requiert des bases en électronique</li>
          <li>❌ Plusieurs itérations avant d'être satisfait</li>
        </ul>
      </div>
    </div>
  </div>

</div>

<!--
"Pour un premier build : kit + hotswap. C'est la combinaison la plus forgiving — si un switch ne te plaît pas, tu le changes en 2 secondes."
-->

---

# Format et acoustique

<div class="grid grid-cols-2 gap-8 mt-6">

  <div>
    <p class="font-semibold mb-3">📐 Quel format choisir ?</p>
    <div class="space-y-2 text-sm text-gray-400">
      <p>La question honnête : <strong class="text-white">êtes-vous prêt à désapprendre ?</strong></p>
      <div class="space-y-1.5 mt-2">
        <div class="flex items-center gap-2">
          <span class="w-2 h-2 rounded-full bg-gray-400 shrink-0"></span>
          <span>Vous voulez juste de meilleures touches → <strong class="text-white">65% ou TKL</strong></span>
        </div>
        <div class="flex items-center gap-2">
          <span class="w-2 h-2 rounded-full bg-blue-400 shrink-0"></span>
          <span>Vous voulez tester l'ortho → <strong class="text-white">Planck / Preonic</strong></span>
        </div>
        <div class="flex items-center gap-2">
          <span class="w-2 h-2 rounded-full bg-green-400 shrink-0"></span>
          <span>Vous visez l'ergo → <strong class="text-white">split column stagger 42 touches</strong> (Corne, Kyria)</span>
        </div>
      </div>
      <p class="mt-3 text-xs">Conseil : ne pas changer le layout logiciel en même temps que le physique. Un changement à la fois.</p>
    </div>
  </div>

  <div>
    <p class="font-semibold mb-3">🔊 Acoustique</p>
    <div class="space-y-2 text-sm text-gray-400">
      <p>Le son d'un clavier dépend de toute la chaîne :</p>
      <div class="space-y-1.5 mt-2">
        <div class="flex items-center gap-2">
          <span class="w-24 text-white text-xs shrink-0">Switches</span>
          <span>Linéaire = silence relatif. Clicky = à éviter en open space.</span>
        </div>
        <div class="flex items-center gap-2">
          <span class="w-24 text-white text-xs shrink-0">Boîtier</span>
          <span>Plastique résonne. Aluminium ou polycarbonate amortissent mieux.</span>
        </div>
        <div class="flex items-center gap-2">
          <span class="w-24 text-white text-xs shrink-0">Foam</span>
          <span>Couche de mousse sous le PCB — réduit le "ping" métallique.</span>
        </div>
        <div class="flex items-center gap-2">
          <span class="w-24 text-white text-xs shrink-0">Gasket mount</span>
          <span>PCB suspendu sur joints — son plus doux et "bouncier".</span>
        </div>
      </div>
      <p class="text-xs mt-3">En open space : switches silencieux (Gateron Silent, Boba U4) + boîtier foam.</p>
    </div>
  </div>

</div>

<!--
"L'acoustique, les gens n'y pensent pas au début — et puis ils reçoivent leurs Kailh Blue et leurs collègues les détestent."
Transition : "Maintenant qu'on a tout choisi sur le papier, on construit comment ?"
-->

---

# Assembler son clavier : les étapes

<div class="mt-4 grid grid-cols-2 gap-x-12 gap-y-3">

  <div class="flex items-start gap-3">
    <span class="text-2xl font-bold text-gray-300 shrink-0 w-8">1</span>
    <div>
      <p class="font-semibold text-sm">Diodes</p>
      <p class="text-xs text-gray-400">Souder les diodes sur le PCB — attention à l'orientation (cathode/anode). Petites, nombreuses, critiques.</p>
    </div>
  </div>

  <div class="flex items-start gap-3">
    <span class="text-2xl font-bold text-gray-300 shrink-0 w-8">2</span>
    <div>
      <p class="font-semibold text-sm">Sockets hotswap <span class="text-gray-500 font-normal">ou soudure directe</span></p>
      <p class="text-xs text-gray-400">Sockets Kailh sur chaque emplacement de switch. Peu de soudure, gros impact sur la flexibilité future.</p>
    </div>
  </div>

  <div class="flex items-start gap-3">
    <span class="text-2xl font-bold text-gray-300 shrink-0 w-8">3</span>
    <div>
      <p class="font-semibold text-sm">Controller</p>
      <p class="text-xs text-gray-400">Souder le Pro Micro / nice!nano sur les headers. Sur un split : un controller par moitié.</p>
    </div>
  </div>

  <div class="flex items-start gap-3">
    <span class="text-2xl font-bold text-gray-300 shrink-0 w-8">4</span>
    <div>
      <p class="font-semibold text-sm">Flash du firmware</p>
      <p class="text-xs text-gray-400">Compiler et flasher QMK ou ZMK avant de monter le boîtier — plus facile d'accès au bouton reset.</p>
    </div>
  </div>

  <div class="flex items-start gap-3">
    <span class="text-2xl font-bold text-gray-300 shrink-0 w-8">5</span>
    <div>
      <p class="font-semibold text-sm">Boîtier & plaque</p>
      <p class="text-xs text-gray-400">Vis, entretoises, plaque top. Certains kits incluent du foam à insérer entre PCB et boîtier.</p>
    </div>
  </div>

  <div class="flex items-start gap-3">
    <span class="text-2xl font-bold text-gray-300 shrink-0 w-8">6</span>
    <div>
      <p class="font-semibold text-sm">Switches & keycaps</p>
      <p class="text-xs text-gray-400">Clipser les switches dans les sockets. Monter les keycaps. Le moment satisfaisant.</p>
    </div>
  </div>

  <div class="flex items-start gap-3 col-span-2">
    <span class="text-2xl font-bold text-green-400 shrink-0 w-8">7</span>
    <div>
      <p class="font-semibold text-sm text-green-400">Test de chaque touche</p>
      <p class="text-xs text-gray-400">Via QMK Test Mode, ou simplement dans un éditeur de texte. Identifier les touches mortes avant de fermer définitivement le boîtier.</p>
    </div>
  </div>

</div>

<p class="text-xs text-gray-400 mt-3">Durée typique pour un premier build : <strong class="text-white">3 à 5 heures</strong>. Beaucoup de guides vidéo disponibles pour chaque kit.</p>

<!--
"Le conseil le plus important : flasher AVANT de monter le boîtier. Accéder au bouton reset une fois tout vissé, c'est pénible."
-->

---
layout: two-cols
---

# Flash & debug

<div class="pr-8 mt-4 space-y-4">
  <div>
    <p class="font-semibold">Compiler le firmware</p>
    <div class="font-mono text-xs bg-gray-100 dark:bg-gray-800 rounded p-3 mt-1 space-y-1">
      <p class="text-gray-400"># QMK</p>
      <p>qmk compile -kb corne -km default</p>
      <p>qmk flash -kb corne -km default</p>
      <p class="text-gray-400 mt-2"># ou via QMK Toolbox (GUI)</p>
    </div>
  </div>
  <div>
    <p class="font-semibold">ZMK (sans-fil)</p>
    <p class="text-sm text-gray-400 mt-1">Build via GitHub Actions — on pousse le config, GitHub compile, on télécharge le <code>.uf2</code> et on le copie sur le controller en mode bootloader (comme une clé USB).</p>
  </div>
  <div>
    <p class="font-semibold">Tester les touches</p>
    <p class="text-sm text-gray-400 mt-1">Touche morte = soudure froide sur la diode ou le socket. On ressoude, on reteste. Rarement plus compliqué que ça.</p>
  </div>
</div>

::right::

<div class="flex flex-col gap-4 items-center justify-center h-full pl-4">
  <div class="h-36 w-56 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 QMK Toolbox — interface flash
  </div>
  <div class="bg-gray-100 dark:bg-gray-800 rounded p-3 w-56 text-xs text-gray-400 space-y-1">
    <p class="font-semibold text-white">Checklist debug</p>
    <p>☐ Firmware bien flashé sur les 2 moitiés</p>
    <p>☐ Câble TRRS branché avant USB</p>
    <p>☐ Diodes dans le bon sens</p>
    <p>☐ Socket bien en contact</p>
    <p>☐ Controller pas à l'envers</p>
  </div>
</div>

<!--
"Le debug d'un clavier custom, c'est très accessible. La plupart des problèmes sont mécaniques — une mauvaise soudure ou un socket mal clipé — pas logiciels."
Transition : "Le clavier est prêt. Mais il reste une chose à apprendre : comment s'en servir correctement."
-->

---
layout: two-cols
---

# La dactylographie

<div class="pr-8 mt-4 space-y-4 text-sm">
  <p class="text-gray-400">Taper sans regarder le clavier, chaque doigt responsable de sa zone — c'est la dactylographie. Sans ça, un clavier ergonomique ne sert à rien.</p>

  <div>
    <p class="font-semibold">La position de base</p>
    <div class="font-mono text-xs bg-gray-100 dark:bg-gray-800 rounded p-3 mt-1 space-y-1">
      <p class="text-gray-400">Main gauche : <span class="text-white">A S D F</span> (index sur F)</p>
      <p class="text-gray-400">Main droite : <span class="text-white">J K L ;</span> (index sur J)</p>
      <p class="text-gray-400 mt-1">Pouces sur la barre espace.</p>
      <p class="text-gray-400">Les repères tactiles (bump) sur F et J.</p>
    </div>
  </div>

  <div>
    <p class="font-semibold">Comment progresser</p>
    <ul class="text-gray-400 space-y-1 mt-1">
      <li><strong class="text-white">Précision avant vitesse</strong> — la vitesse vient avec la précision, pas l'inverse</li>
      <li><strong class="text-white">Pratique délibérée</strong> — 15 min par jour valent mieux que 2h le week-end</li>
      <li><strong class="text-white">Ne pas tricher</strong> — si on regarde le clavier, on ne progresse pas</li>
      <li><strong class="text-white">Accepter la régression</strong> — changer de layout fait temporairement baisser la vitesse</li>
    </ul>
  </div>
</div>

::right::

<div class="flex flex-col justify-center h-full gap-4 pl-4">
  <p class="font-semibold text-sm">Ressources</p>
  <div class="space-y-3 text-sm">
    <div>
      <a href="https://www.typingclub.com/sportal/program-1.game" class="text-blue-400 hover:underline font-semibold">Typing Club</a>
      <p class="text-xs text-gray-400 mt-0.5">Basics → Jungle. Progression guidée, adapté aux débutants et aux changements de layout.</p>
    </div>
    <div>
      <a href="https://www.typing.com/student/lessons" class="text-blue-400 hover:underline font-semibold">typing.com</a>
      <p class="text-xs text-gray-400 mt-0.5">Leçons structurées, suivi de la progression, gratuit.</p>
    </div>
    <div>
      <a href="https://www.keybr.com/" class="text-blue-400 hover:underline font-semibold">keybr.com</a>
      <p class="text-xs text-gray-400 mt-0.5">Génère des exercices ciblés sur les touches les moins maîtrisées. Idéal pour ancrer un nouveau layout.</p>
    </div>
    <div>
      <a href="https://monkeytype.com/" class="text-blue-400 hover:underline font-semibold">monkeytype.com</a>
      <p class="text-xs text-gray-400 mt-0.5">Test de vitesse / précision, très configurable. Bon baromètre de progression.</p>
    </div>
  </div>
</div>

<!--
"Un clavier ergonomique sans dactylographie, c'est une voiture de sport avec un conducteur qui regarde ses pieds pour changer de vitesse."
"keybr est particulièrement utile quand on change de layout — il identifie les lettres qui bloquent et génère des exercices ciblés dessus."
-->

---
layout: two-cols
---

# Mon setup

<div class="pr-8 mt-4 space-y-3 text-sm">
  <div>
    <p class="font-semibold">Le clavier</p>
    <p class="text-gray-400">
      <!-- TODO: nom du clavier, ex: Corne v3, Kyria, Ferris Sweep... -->
      ✏️ <em class="text-orange-400">À compléter : modèle, nombre de touches</em>
    </p>
  </div>
  <div>
    <p class="font-semibold">Les switches</p>
    <p class="text-gray-400">
      <!-- TODO: ex: Kailh Choc Robin, Gateron Brown, Boba U4... -->
      ✏️ <em class="text-orange-400">À compléter : switches utilisés</em>
    </p>
  </div>
  <div>
    <p class="font-semibold">Le layout logiciel</p>
    <p class="text-gray-400">
      <!-- TODO: ex: Ergol, Colemak-DH, QWERTY perso... -->
      ✏️ <em class="text-orange-400">À compléter : layout utilisé</em>
    </p>
  </div>
  <div>
    <p class="font-semibold">Ce que j'aurais fait différemment</p>
    <ul class="text-gray-400 space-y-1 mt-1">
      <!-- TODO: retours honnêtes sur ton parcours -->
      <li>✏️ <em class="text-orange-400">À compléter : erreurs, regrets, surprises</em></li>
    </ul>
  </div>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <div class="h-64 w-72 rounded shadow bg-gray-200 dark:bg-gray-700 flex items-center justify-center text-gray-400 text-sm italic">
    📷 photo de ton setup réel
  </div>
</div>

<!--
Moment personnel. Parler du parcours : premier clavier, découverte du split, changement de layout.
Ce que ça a changé concrètement au quotidien.
-->

---

# Mes layers — vue d'ensemble

<div class="mt-6 space-y-2 text-sm">
  <div class="flex items-center gap-4 p-2 rounded bg-gray-100 dark:bg-gray-800">
    <span class="w-32 font-semibold shrink-0">BASE (QWERTY)</span>
    <span class="w-40 font-mono text-xs text-gray-500 shrink-0">— layer par défaut</span>
    <span class="text-gray-400">Lettres + home row mods (⌘ ⌥ ⌃ ⇧ sur ASDF/JKL;)</span>
  </div>
  <div class="flex items-center gap-4 p-2 rounded bg-purple-50 dark:bg-purple-900">
    <span class="w-32 font-semibold shrink-0">SYM</span>
    <span class="w-40 font-mono text-xs text-gray-500 shrink-0">hold <kbd class="px-1 bg-gray-200 dark:bg-gray-700 rounded">↵</kbd></span>
    <span class="text-gray-400">Symboles ({} [] () ^ $ % @ & * …)</span>
  </div>
  <div class="flex items-center gap-4 p-2 rounded bg-green-50 dark:bg-green-900">
    <span class="w-32 font-semibold shrink-0">NAV / NUM</span>
    <span class="w-40 font-mono text-xs text-gray-500 shrink-0">hold <kbd class="px-1 bg-gray-200 dark:bg-gray-700 rounded">⎵</kbd> / hold <kbd class="px-1 bg-gray-200 dark:bg-gray-700 rounded">⌫</kbd></span>
    <span class="text-gray-400">Navigation (flèches, Home/End) + pavé numérique</span>
  </div>
  <div class="flex items-center gap-4 p-2 rounded bg-orange-50 dark:bg-orange-900">
    <span class="w-32 font-semibold shrink-0">ADJUST</span>
    <span class="w-40 font-mono text-xs text-gray-500 shrink-0">SYM + NAV simultanés</span>
    <span class="text-gray-400">Bluetooth, médias, flash firmware</span>
  </div>
  <div class="flex items-center gap-4 p-2 rounded bg-blue-50 dark:bg-blue-900">
    <span class="w-32 font-semibold shrink-0">DIA</span>
    <span class="w-40 font-mono text-xs text-gray-500 shrink-0">sticky layer ◆</span>
    <span class="text-gray-400">Diacritiques français (à â é ê è ç î ï ô ù û)</span>
  </div>
</div>

<div class="mt-5 border-t border-gray-200 dark:border-gray-700 pt-4 text-xs text-gray-400 space-y-1">
  <p class="font-semibold text-gray-500">Inspirations</p>
  <p>Symboles & diacritiques : <a href="https://qwerty-lafayette.org/42" class="text-blue-400 hover:underline">QWERTY-Lafayette 42</a> et <a href="https://ergol.org/" class="text-blue-400 hover:underline">Ergol</a></p>
  <p>Organisation du code : <a href="https://github.com/manna-harbour/miryoku_zmk" class="text-blue-400 hover:underline">Miryoku ZMK</a> — permet de builder le firmware pour différents claviers sans tout réécrire</p>
</div>

<!--
"5 layers couvrent tout ce dont j'ai besoin — sans jamais déplacer les mains de la home row."
"Le code s'inspire de Miryoku : les layers sont définis une fois, et je peux compiler pour n'importe quel clavier compatible ZMK."
-->

---

# Layer BASE — QWERTY + home row mods

<div class="flex gap-8 justify-center mt-6 font-mono">

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">Q</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">W</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">E</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">R</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">T</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">A</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌘</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">S</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌥</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">D</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌃</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">F</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⇧</span></div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">G</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">Z</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">X</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">C</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">V</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">B</div>
    </div>
    <div class="flex gap-1 justify-end mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-300 dark:bg-gray-600 text-[9px]">ESC</div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-gray-300 dark:bg-gray-600 text-[8px] leading-tight"><span>ESC</span><span class="text-[6px] text-gray-500">⇧</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-green-200 dark:bg-green-800 text-[8px] leading-tight"><span>⎵</span><span class="text-[6px] text-green-600 dark:text-green-300">NAV</span></div>
    </div>
  </div>

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">Y</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">U</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">I</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">O</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">P</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">H</div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">J</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⇧</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">K</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌃</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">L</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌥</span></div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-200 dark:bg-purple-800 text-[9px]">◆</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">N</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">M</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-[9px]">,;</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-[9px]">.:</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-700 text-xs">/?</div>
    </div>
    <div class="flex gap-1 mt-1">
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-purple-200 dark:bg-purple-800 text-[8px] leading-tight"><span>↵</span><span class="text-[6px] text-purple-600 dark:text-purple-300">SYM</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-orange-200 dark:bg-orange-800 text-[8px] leading-tight"><span>⌫</span><span class="text-[6px] text-orange-600 dark:text-orange-300">NUM</span></div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-300 dark:bg-gray-600 text-[9px]">DEL</div>
    </div>
  </div>

</div>

<div class="mt-4 flex justify-center gap-6 text-xs text-gray-400">
  <span><span class="inline-block w-3 h-3 rounded bg-blue-200 dark:bg-blue-800 mr-1"></span>home row mod (tap = lettre, hold = modifier)</span>
  <span><span class="inline-block w-3 h-3 rounded bg-green-200 dark:bg-green-800 mr-1"></span>layer NAV</span>
  <span><span class="inline-block w-3 h-3 rounded bg-purple-200 dark:bg-purple-800 mr-1"></span>layer SYM / DIA</span>
  <span><span class="inline-block w-3 h-3 rounded bg-orange-200 dark:bg-orange-800 mr-1"></span>layer NUM</span>
</div>

<!--
Montrer sur le vrai clavier. Insister sur : les doigts ne bougent pas de la home row.
-->

---

# Layer DIA — Diacritiques français

<div class="flex gap-8 justify-center mt-6 font-mono">

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">é</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">è</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">à</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">ê</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-300 dark:bg-gray-500 text-[9px]">⇧</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">â</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">ç</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1 justify-end mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
    </div>
  </div>

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">ù</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-[10px] leading-tight"><span class="font-bold">û</span><span class="text-[7px] text-blue-500">⇧</span></div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">î</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-blue-100 dark:bg-blue-900 text-xs font-bold">ô</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1 mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
    </div>
  </div>

</div>

<p class="text-center text-xs text-gray-400 mt-3">Activé via la touche ◆ (sticky) — une pression suffit, le layer reste actif pour la prochaine touche.</p>

<!--
"Le layer DIA, c'est ce qui me permet d'écrire en français sans changer de layout. Sticky layer = je presse ◆ puis la lettre, le layer se désactive tout seul."
-->

---

# Layer SYM — Symboles

<div class="flex gap-8 justify-center mt-6 font-mono">

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">^</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">&lt;</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">&gt;</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">$</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">%</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">{</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌘</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">(</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌥</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">)</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌃</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">}</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⇧</span></div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">=</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">~</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">[</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">]</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">_</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">#</div>
    </div>
    <div class="flex gap-1 justify-end mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
    </div>
  </div>

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">@</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">&amp;</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">*</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">'</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">`</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">\</div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">+</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⇧</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">-</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌃</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">/</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌥</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">"</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌘</span></div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">|</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">!</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">;</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">:</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-100 dark:bg-purple-900 text-xs">?</div>
    </div>
    <div class="flex gap-1 mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-purple-300 dark:bg-purple-700 text-[8px]">↵</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
    </div>
  </div>

</div>

<p class="text-center text-xs text-gray-400 mt-4">▲ = transparent (pass-through vers layer base)</p>

<!--
"Les home row mods restent actifs sur SYM — je peux faire ⌘+= ou ⇧+{ sans déplacer les mains."
-->

---

# Layer NAV / NUM — Navigation & Chiffres

<div class="flex gap-8 justify-center mt-4 font-mono">

  <div class="flex flex-col gap-1">
    <p class="text-[10px] text-gray-400 text-center mb-1">← NAV (hold ⎵)</p>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[9px]">TAB</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[9px]">Home</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-xs">↑</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[9px]">End</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[9px]">PgUp</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[8px]">⌃A</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-200 dark:bg-green-800 text-xs font-bold">←</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-200 dark:bg-green-800 text-xs font-bold">↓</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-200 dark:bg-green-800 text-xs font-bold">→</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[9px]">PgDn</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[8px]">⌃Z</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[8px]">⌃X</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[8px]">⌃C</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[8px]">⌃V</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-100 dark:bg-green-900 text-[8px]">⇧TAB</div>
    </div>
    <div class="flex gap-1 justify-end mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-green-300 dark:bg-green-700 text-[8px]">⎵</div>
    </div>
  </div>

  <div class="flex flex-col gap-1">
    <p class="text-[10px] text-gray-400 text-center mb-1">NUM (hold ⌫) →</p>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs">/</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs font-bold">7</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs font-bold">8</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs font-bold">9</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs">-</div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">4</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⇧</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">5</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌃</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">6</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌥</span></div>
      <div class="w-8 h-8 flex flex-col items-center justify-center rounded bg-blue-200 dark:bg-blue-800 text-[10px] leading-tight"><span class="font-bold">0</span><span class="text-[7px] text-blue-600 dark:text-blue-300">⌘</span></div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs">,</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs font-bold">1</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs font-bold">2</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs font-bold">3</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-100 dark:bg-orange-900 text-xs">.</div>
    </div>
    <div class="flex gap-1 mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-orange-300 dark:bg-orange-700 text-[8px]">⌫</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
    </div>
  </div>

</div>

<!--
"NAV à gauche pour les déplacements, NUM à droite style pavé numérique. Les deux s'activent depuis le pouce — jamais besoin de regarder le clavier."
-->

---

# Layer ADJUST — Bluetooth & Médias

<div class="flex gap-8 justify-center mt-6 font-mono">

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">BT 0</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">BT 1</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">BT 2</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">BT 3</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">BT 4</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">OUT</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">⬅🖥</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">⊞</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">🖥➡</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-red-200 dark:bg-red-900 text-[8px]">⚡</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-red-200 dark:bg-red-900 text-[8px]">↺</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">🖼</div>
    </div>
    <div class="flex gap-1 justify-end mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
    </div>
  </div>

  <div class="flex flex-col gap-1">
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-xs">🔇</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-xs">⏯</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-xs">🔉</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-xs">🔊</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[8px]">⏮⏭</div>
    </div>
    <div class="flex gap-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-yellow-100 dark:bg-yellow-900 text-[7px]">Teams 🔇</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-30">·</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-red-200 dark:bg-red-900 text-[8px]">↺</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-red-200 dark:bg-red-900 text-[8px]">⚡</div>
    </div>
    <div class="flex gap-1 mt-1">
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
      <div class="w-8 h-8 flex items-center justify-center rounded bg-gray-200 dark:bg-gray-600 text-[8px] opacity-40">▲</div>
    </div>
  </div>

</div>

<p class="text-center text-xs text-gray-400 mt-3"><span class="text-red-400">⚡ = bootloader (flash firmware)</span> · <span class="text-red-400">↺ = reset</span> · BT 0–4 = profils Bluetooth</p>

<!--
"ADJUST s'active en maintenant les deux layer-keys simultanément. Bluetooth pour switcher entre appareils, ⚡ pour reflasher le firmware."
-->

---
layout: center
class: text-center
---

# Panorama : quelques claviers custom

<p class="text-xl mt-4 text-gray-400">Du kit entrée de gamme à la commande sur-mesure.</p>

<!--
"Avant de passer à l'extrême absolu, un tour d'horizon de quelques claviers custom que vous pourrez rencontrer — ou commander."
-->

---
layout: two-cols
---

# Cheapino

<div class="pr-8 mt-4 space-y-4 text-sm">
  <div class="flex gap-2 flex-wrap">
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">36 touches</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">split</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">filaire</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">soudure</span>
    <span class="px-2 py-0.5 rounded bg-green-100 dark:bg-green-900 text-green-700 dark:text-green-300 text-xs font-semibold">~30–50 €</span>
  </div>
  <p class="text-gray-400">PCB open source conçu par <strong class="text-white">tompi</strong>. On commande les fichiers Gerber chez JLCPCB, on soude, on assemble.</p>
  <p class="text-gray-400">Le point d'entrée le plus accessible du split custom. Column stagger, 3 touches de pouce par main, firmware QMK.</p>
  <p class="text-xs text-gray-500 mt-2">Idéal pour : tester le split sans budget, apprendre à souder.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <img src="./assets/showcase/cheapino.png" alt="Clavier Cheapino" class="max-h-full w-full rounded shadow object-contain" />
</div>

<!--
"Le Cheapino, c'est le clavier custom le moins cher possible. On imprime le PCB pour quelques euros, on soude les composants — et on a un split column stagger fonctionnel pour moins de 50€ tout compris."
-->

---
layout: two-cols
---

# Corne

<div class="pr-8 mt-4 space-y-4 text-sm">
  <div class="flex gap-2 flex-wrap">
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">42 touches</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">split</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">filaire ou BLE</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">hotswap</span>
    <span class="px-2 py-0.5 rounded bg-green-100 dark:bg-green-900 text-green-700 dark:text-green-300 text-xs font-semibold">80–150 €</span>
  </div>
  <p class="text-gray-400">Le <strong class="text-white">kit de référence</strong> du split custom. Column stagger, écran OLED optionnel, compatible MX et Choc.</p>
  <p class="text-gray-400">Communauté massive, guides de build nombreux, firmware QMK et ZMK très bien supportés.</p>
  <p class="text-xs text-gray-500 mt-2">Idéal pour : premier build sérieux, bonne balance entre accessibilité et fonctionnalités.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <img src="./assets/showcase/corne_halcyon.jpg" alt="Clavier Halcyon Corne" class="max-h-full w-full rounded shadow object-contain" />
</div>

<!--
"Le Corne, c'est le clavier custom le plus populaire. Si vous cherchez un premier kit sérieux avec une communauté pour vous aider, c'est lui."
-->

---
layout: two-cols
---

# Ferris Sweep

<div class="pr-8 mt-4 space-y-4 text-sm">
  <div class="flex gap-2 flex-wrap">
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">34 touches</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">split</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">filaire</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">Choc low profile</span>
    <span class="px-2 py-0.5 rounded bg-green-100 dark:bg-green-900 text-green-700 dark:text-green-300 text-xs font-semibold">60–120 €</span>
  </div>
  <p class="text-gray-400">Conçu par <strong class="text-white">Pierre Chevalier</strong>. Minimalisme absolu : pas d'écran, pas de diode visible, pas de boîtier nécessaire.</p>
  <p class="text-gray-400">Switches Choc uniquement — profil ultra-plat. 34 touches demandent une vraie discipline dans le layout logiciel.</p>
  <p class="text-xs text-gray-500 mt-2">Idéal pour : les adeptes de la philosophie 1DH portée à son maximum.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <img src="./assets/showcase/aurora_sweep.jpg" alt="Clavier Aurora Sweep" class="max-h-full w-full rounded shadow object-contain" />
</div>

<!--
"Le Ferris Sweep, c'est 34 touches. Deux de moins que le Corne. Chaque touche est réfléchie. C'est un clavier qui force à bien configurer ses layers — pas de béquille possible."
-->

---
layout: two-cols
---

# ZSA Moonlander

<div class="pr-8 mt-4 space-y-4 text-sm">
  <div class="flex gap-2 flex-wrap">
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">72 touches</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">split</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">filaire</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">hotswap</span>
    <span class="px-2 py-0.5 rounded bg-yellow-100 dark:bg-yellow-900 text-yellow-700 dark:text-yellow-300 text-xs font-semibold">~365 $</span>
  </div>
  <p class="text-gray-400">Produit commercial de <strong class="text-white">ZSA</strong>. Configurateur Oryx en ligne, pas de compilation nécessaire, support client.</p>
  <p class="text-gray-400">Row stagger léger, pouce cluster articulé, tenting réglable. Clé en main — de la boîte au bureau en une heure.</p>
  <p class="text-xs text-gray-500 mt-2">Idéal pour : passer au split sans toucher à un terminal ni souder une seule fois.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <img src="./assets/showcase/zsa_moonlander.png" alt="Clavier ZSA Moonlander" class="h-110 rounded shadow object-contain" />
</div>

<!--
"Le Moonlander, c'est le split pour ceux qui ne veulent pas bricoler. Plug and play, configurateur visuel, SAV. Le prix de la tranquillité."
-->

---
layout: two-cols
---

# Charybdis

<div class="pr-8 mt-4 space-y-4 text-sm">
  <div class="flex gap-2 flex-wrap">
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">~40 touches</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">split</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">filaire</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">trackball intégré</span>
    <span class="px-2 py-0.5 rounded bg-yellow-100 dark:bg-yellow-900 text-yellow-700 dark:text-yellow-300 text-xs font-semibold">200–300 €</span>
  </div>
  <p class="text-gray-400">Par <strong class="text-white">Bastard Keyboards</strong>. La moitié droite embarque un trackball — la souris disparaît du bureau.</p>
  <p class="text-gray-400">Column stagger, firmware QMK, boîtier imprimé 3D. Kit complet disponible, assemblage requis.</p>
  <p class="text-xs text-gray-500 mt-2">Idéal pour : éliminer les allers-retours clavier → souris tout en gardant le split ergonomique.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <img src="./assets/showcase/charibdys.jpg" alt="Clavier Charybdis" class="max-h-full w-full rounded shadow object-contain" />
</div>

<!--
"Le Charybdis pousse l'idée encore plus loin : pas seulement réduire les mouvements des doigts, mais aussi supprimer la souris. La main droite navigue sans quitter le clavier."
-->

---
layout: two-cols
---

# Bayleaf

<div class="pr-8 mt-4 space-y-4 text-sm">
  <div class="flex gap-2 flex-wrap">
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">60% · ortholinéaire</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">split</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">sans-fil</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">ZMK Studio</span>
    <span class="px-2 py-0.5 rounded bg-gray-100 dark:bg-gray-800 text-xs">aluminium CNC · 5 mm</span>
  </div>
  <p class="text-gray-400">Conçu par <strong class="text-white">Sebastian Graz</strong>. Un build custom avec l'ambition d'un produit commercial : boîtier aluminium usiné CNC, finitions soignées, 180g.</p>
  <p class="text-gray-400">Switches Kailh PG1316S ultra-plats (épaisseur totale : 5 mm). Ortholinéaire sans stagger — pour le look du rectangle parfait.</p>
  <p class="text-xs text-gray-500 mt-2">Form over function assumé — la preuve qu'un clavier custom peut ressembler à un produit studio.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <img src="./assets/showcase/bayleaf.png" alt="Clavier Bayleaf" class="max-h-full w-full rounded shadow object-contain" />
</div>

<!--
"Le Bayleaf, c'est l'anti-thèse du clavier ergonomique classique — son auteur le dit lui-même, c'est du form over function. Mais c'est aussi la preuve qu'un build custom peut avoir une finition digne d'un produit commercial."
-->

---
layout: two-cols
---

# La Svalboard

<div class="pr-8 mt-4 space-y-4 text-sm">
  <p class="text-gray-400">La conclusion logique de la philosophie 1DH, poussée à l'extrême.</p>

  <div>
    <p class="font-semibold">Le principe</p>
    <p class="text-gray-400">Chaque doigt a exactement 5 touches dédiées, disposées en croix autour de sa position de repos. Le doigt ne se déplace presque plus — c'est la touche qui est là où le doigt va naturellement.</p>
  </div>

  <div>
    <p class="font-semibold">En pratique</p>
    <ul class="text-gray-400 space-y-1 mt-1">
      <li>Conçu par Kyle Boatright</li>
      <li>Inspiré du DataHand (années 90)</li>
      <li>Courbe d'apprentissage : plusieurs semaines</li>
      <li>Résultat : mouvement des doigts quasi nul</li>
    </ul>
  </div>

  <p class="text-gray-400 text-xs mt-2">Cas extrême — pas une recommandation. Mais illustre jusqu'où peut aller la logique ergonomique.</p>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <img src="./assets/showcase/svalboard.png" alt="Clavier Svalboard" class="h-110 rounded shadow object-contain" />
</div>

<!--

-->

---
layout: center
class: text-center
---

# Votre clavier, votre outil.

<div class="mt-8 space-y-3 text-xl text-gray-400">
  <p>Vous passez des milliers d'heures à taper.</p>
  <p>Autant le faire avec un outil qui travaille <strong class="text-white">pour</strong> vous,</p>
  <p>pas <strong class="text-white">contre</strong> vous.</p>
</div>

<p class="mt-10 text-lg">
  Réinvestir dans son clavier, c'est réinvestir dans sa santé,<br>son confort — et son efficacité.
</p>

<p class="mt-12 text-gray-400">Des questions ?</p>

<!--
Lire lentement. Laisser le silence après "Des questions ?"
Avoir le clavier sous la main pour une démo si quelqu'un veut tester.
-->

---
layout: center
class: text-center
---

# Références

<div class="mt-8 space-y-3 text-left inline-block">
  <div class="flex items-center gap-4">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">Ma config ZMK</span>
    <a href="https://github.com/vvision/zmk-config" class="font-mono text-blue-400 hover:underline">github.com/vvision/zmk-config</a>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">QWERTY-Lafayette 42</span>
    <a href="https://qwerty-lafayette.org/42" class="font-mono text-blue-400 hover:underline">qwerty-lafayette.org/42</a>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">Ergol</span>
    <a href="https://ergol.org/" class="font-mono text-blue-400 hover:underline">ergol.org</a>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">Miryoku ZMK</span>
    <a href="https://github.com/manna-harbour/miryoku_zmk" class="font-mono text-blue-400 hover:underline">github.com/manna-harbour/miryoku_zmk</a>
  </div>
  <div class="flex items-center gap-4 pt-2 mt-1 border-t border-gray-200 dark:border-gray-700">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">Typing Club</span>
    <a href="https://www.typingclub.com/sportal/program-1.game" class="font-mono text-blue-400 hover:underline">typingclub.com</a>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">typing.com</span>
    <a href="https://www.typing.com/student/lessons" class="font-mono text-blue-400 hover:underline">typing.com</a>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">keybr</span>
    <a href="https://www.keybr.com/" class="font-mono text-blue-400 hover:underline">keybr.com</a>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-gray-400 w-40 text-sm text-right shrink-0">monkeytype</span>
    <a href="https://monkeytype.com/" class="font-mono text-blue-400 hover:underline">monkeytype.com</a>
  </div>
</div>

<!--
Laisser ce slide affiché pendant les échanges.
-->
