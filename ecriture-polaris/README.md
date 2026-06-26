# L'écriture de Polaris — le système d'écriture construit

> Connaissances distillées de l'artefact interactif **`Polaris - Ecriture unifiee.html`**
> (« germe d'écriture · v2 »), y compris la spécification technique extraite de sa logique.
> C'est un **conscript** : le système d'écriture visuel de la civilisation Polaris.

> **Statut : germe d'écriture · système assemblé · à casser ou valider.** Un prototype
> cohérent, pas une norme figée.

---

## Principe général

Un système **featural et syllabique**, de **logique hangul** : les lettres ne s'alignent
pas, elles **s'imbriquent dans un carré** comme un sinogramme. Influences visuelles
revendiquées : **latin · cyrillique · hanzi**.

- **10 consonnes** — des *fûts verticaux*, squelettes latins / cyrilliques.
- **6 voyelles** — un axe vertical commun ; **la position d'une marque (le « tic ») encode le son**.

> L'artefact présente le mot **`polaris`** comme exemple-étalon et fournit un **champ de
> traduction vivant** : on tape en latin, la composition syllabique se dessine en direct.

---

## 1. L'inventaire des consonnes

Dix consonnes, chacune un glyphe à fût vertical évoquant un squelette latin ou cyrillique :

| Glyphe | Gloss visuel approximatif | Couvre les sons (latin → glyphe) |
|---|---|---|
| **k** | un « K » | k, c, q |
| **t** | un « T » | t, d |
| **n** | deux fûts + barre médiane (forme en « H ») | n |
| **s** | une courbe (« S »/« C ») | s, z, j |
| **l** | fût oblique à empan | l |
| **m** | un « M » | m |
| **r** | un « R » | r |
| **p** | un « P » | p, b, f, v |
| **g** | fût + barre haute (forme en « Γ ») | g |
| **x** | un « X » | x, h, w |

`⚑` **Couverture phonétique.** L'alphabet latin entier est projeté sur ces 10 consonnes
par familles (occlusives, fricatives, etc.) : `c/q → k`, `d → t`, `z/j → s`, `b/f/v → p`,
`h/w → x`, `g → g`. C'est un système **phonétique simplifié**, pas une translittération
lettre à lettre.

---

## 2. La logique featural des voyelles

> **La forme encode le son.** Toutes les voyelles partagent le **même axe vertical** ;
> seul le **tic** change — côté, nombre, symétrie. *On apprend six glyphes en apprenant une
> seule règle.*

| Voyelle | Construction | Règle |
|---|---|---|
| **i** | axe nu | l'axe seul, sans marque |
| **a** | tic à **droite** | une marque, à droite, à mi-hauteur |
| **o** | tic à **gauche** | une marque, à gauche (miroir de `a`) |
| **e** | **double** tic droit | deux marques à droite |
| **y** | tic des **deux côtés** | marque symétrique gauche + droite |
| **u** | **axe horizontal** | l'exception : axe couché (voyelle « horizontale ») |

`⚑` `u` est le cas particulier : son axe est **horizontal**, ce qui change sa façon de se
composer dans le bloc (empilement plutôt qu'imbrication — voir § 3).

---

## 3. La grammaire du carré

Les lettres **s'imbriquent dans un carré**, à la manière d'un sinogramme. **Les traits se
touchent et se croisent** ; la **consonne finale remonte** dans le corps du bloc. Une
syllabe = **attaque (C) + noyau (V) + coda (C) optionnelle**, condensée en un bloc unique.

| Exemple | Type | Composition |
|---|---|---|
| **ka** | voyelle verticale | la voyelle s'**imbrique** à droite de la consonne, son axe coupant dans le corps de la consonne |
| **tu** | voyelle horizontale | la consonne en haut, la voyelle **empilée** dessous |
| **nas** | finale (coda) | la consonne finale **remonte et croise** dans le bloc |

> La densité « idéogramme » est voulue : le placement ménage un **chevauchement
> délibéré** pour que les traits se touchent, comme dans un caractère hangul.

### Lecture d'un mot
Les blocs se lisent **de gauche à droite**. Exemple-étalon :

> **po · la · ris → Polaris** — trois blocs syllabiques.

---

## 4. Une écriture, deux mains

Le même mot existe en **deux registres**, qui rejouent la tension centrale du monde *(le
froid des dômes contre le sacré — voir [`../univers/`](../univers/))* :

| Registre | Forme | Usage |
|---|---|---|
| **Gravé · officiel** | traits secs, angles vifs, graisse égale | l'administratif et **les rapports d'archéo-num** |
| **Pinceau · rituel** | attaques pressées, traits gonflés qui se lient | **le culte de l'Architecte** et les inscriptions du Sanctuaire |

`⚑` **Lien narratif.** Cette dualité gravé/pinceau est l'incarnation typographique du
**double registre de lecture** : le froid scientifique d'un côté, le sacré du culte de
l'autre. Les **documents intercalés** (niveau 2 du récit) pourraient porter cette
distinction visuelle.

---

## 5. L'artefact interactif

Le fichier [`../sources/Polaris - Ecriture unifiee.html`](../sources/) est une application
web autonome (page « bundlée » : un petit runtime JavaScript déballe le contenu et les
polices embarquées — aucune dépendance réseau). Sections de la démo :

1. **Champ de traduction** — saisie latine → composition vivante.
2. **L'inventaire** — les 10 consonnes et 6 voyelles.
3. **La logique featural des voyelles**.
4. **La grammaire du carré** (ka / tu / nas).
5. **Un mot** — `polaris` décomposé.
6. **Une écriture, deux mains** — gravé vs pinceau.

Réglages exposés par la démo : graisse du trait, affichage de la grille de construction,
accent (gravé / pinceau / les deux), espacement des blocs.

---

## Notes & pistes ouvertes

- `?` **Casser ou valider** : le système est un *germe*. Points à éprouver — le rendu des
  codas complexes, les mots à voyelles multiples, la lisibilité réelle du registre pinceau.
- `?` La projection phonétique fusionne des sons distincts (`b/f/v → p`, `h/w → x`). À
  décider : est-ce un **trait de civilisation** (Polaris a perdu ces distinctions) ou une
  simplification de prototype à raffiner ?
- `?` Quel **rapport historique** entre cette écriture et la langue de Polaris ? Est-elle
  née aux dômes (exode arctique → influences slaves/cyrilliques, cohérent avec le prénom
  *Tanya*) ? À relier à [`../univers/`](../univers/).
