# ZED'S DEAD — SCUM client mods

## Version testée sans minimap

Installez **les deux fichiers** suivants dans `SCUM/SCUM/Content/Paks/~mods` :

- [Télécharger le PAK client sans minimap](https://github.com/lacrampe09/zeddead/releases/download/v2026.10.27-no-minimap/ZEDDEAD_AllInOne_Client_Kamaz_MH6_280_AZERTY_NoMinimap_P.pak)
- [Télécharger le PAK de texte français](https://github.com/lacrampe09/zeddead/releases/download/v2026.10.27-no-minimap/zzzzzz_ZEDDEAD_FrenchText_1008_P.pak)

| Fichier | Taille | SHA-256 |
| --- | ---: | --- |
| `ZEDDEAD_AllInOne_Client_Kamaz_MH6_280_AZERTY_NoMinimap_P.pak` | 329 792 154 octets | `A2D76A64913715712C5201B8BA3A56735B6FBFE2F90C437D1B016D301173FD44` |
| `zzzzzz_ZEDDEAD_FrenchText_1008_P.pak` | 3 605 132 octets | `6E24FABD2FED59722A6754642E0E284D63A4988FA78630FC65C0F27B5EB31552` |

Fermez SCUM avant de remplacer les PAK. Retirez les versions précédentes du client ZED'S DEAD et le PAK `ZEDDEAD Minimap.pak` du dossier `Paks` et de ses sous-dossiers `mods` et `~mods`, afin d'éviter que plusieurs versions soient chargées ensemble.

Les PAK déjà présents à la racine du dépôt (`ZEDDEAD Minimap.pak`, `ZEDDEAD_AllInOne_Client_Kamaz_MH6_280_AZERTY_French_P.pak` et `zz_ZedsDead_AllInOne_P 1.01.pak`) sont historiques. Ne les installez pas avec les deux fichiers de la release sans minimap. Le dernier reste référencé par un ancien launcher.

Cette version a été testée en jeu : le MH6 et le Kamaz fonctionnent, et la minimap a disparu. Elle ne contient pas le mod #61. La validation par GGhost reste à obtenir.

Le launcher ancien pointe encore vers `zz_ZedsDead_AllInOne_P 1.01.pak` et ne téléchargera pas automatiquement cette nouvelle version tant que sa configuration n'aura pas été mise à jour.

