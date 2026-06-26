# Sources — documents de travail originaux

Ce dossier conserve les **fichiers originaux** du projet, intacts. Ils font **foi** :
les `README.md` thématiques des autres dossiers en sont une distillation organisée,
mais ne les remplacent pas. Toute divergence se tranche ici.

## Inventaire

### `Resurgence_Worldbuilding_v1.2.docx`
**Bible de worldbuilding — document de travail, v1.2 (juin 2026).**
Le document de fond. Couvre :

1. Concept central, glissement de registre, régime du doute, structure en accordéon, tell toléré.
2. Contexte historique (Grand Chaos → Émergence de Polaris → Cristallisation → Reterraformation).
3. Anatomie du régime de Polaris (technoféodalisme, culte de l'Architecte, les quatre factions, double lecture, objectifs de mission).
4. Le terrain (Paris saharien et souterrain, l'équipe, les trois couches de péril physique).
5. Personnage principal — Tanya (profil, moteur psychologique, faille, quête généalogique, trahison fondatrice).
6. Dispositif narratif (trois niveaux, structure en spirale).
7. Les cinq mouvements.
8. L'arc narratif des corpus webculture.
9. Inventaire webculture (Backrooms, SCP, Slender Man, mèmes, vaporwave, threads politiques, wikis, communautés alternatives).
10. Questions ouvertes.

→ Distillé dans : [`univers/`](../univers/), [`personnages/`](../personnages/), [`structure-recit/`](../structure-recit/), [`corpus-webculture/`](../corpus-webculture/).

### `Resurgence_Plan_ecriture.docx`
**Plan d'écriture — feuille de route par mouvement (juin 2026).**
Le document opérationnel. Une feuille de route, pas un carcan :

- Les cinq mouvements détaillés en **scènes** (`◆`) et **beats** (`·`), chacun avec sa fonction.
- La **grille de gestion de l'information** — qui sait quoi, quand (lecteur / Tanya / équipe).
- Les **vérités d'auteur** à ne jamais écrire en clair.
- L'évolution autorisée, mystère par mystère.
- La règle de la refissuration (Phase 3).
- Les chantiers transversaux (tri des corpus, composition de l'équipe, points de refissuration).

→ Distillé dans : [`plan-ecriture/`](../plan-ecriture/) et [`structure-recit/`](../structure-recit/).

### `Polaris - Ecriture unifiee.html`
**Artefact interactif — le système d'écriture de Polaris (« germe d'écriture · v2 »).**
Une application web autonome (page « bundlée », rendue par un petit runtime JavaScript)
présentant un **conscript** : un système d'écriture featural et syllabique inspiré du
hangul, avec influences latine, cyrillique et hanzi. Inclut un champ de traduction
vivant (on tape en latin, la composition se dessine) et une démonstration des deux
registres (gravé / pinceau).

→ Distillé dans : [`ecriture-polaris/`](../ecriture-polaris/).

> **Ouvrir le HTML** : double-clic dans un navigateur (JavaScript requis). Le contenu
> est empaqueté et déballé côté client ; il n'y a pas de dépendance réseau au texte
> lui-même (les polices et le runtime sont embarqués).

## Note de versionnage

Le worldbuilding est en **v1.2** : les versions antérieures contenaient au moins une
hypothèse abandonnée (la religion de Polaris aurait eu un rapport avec la webculture —
**corrigé** : elle n'en a aucun, voir [`univers/`](../univers/) § culte). Toute reprise
doit partir de la v1.2.
