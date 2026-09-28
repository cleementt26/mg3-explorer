# MG3 Night Garage

Showroom 3D migré depuis Higgsfield vers GitHub Pages.

- Vues 3/4, face, arrière, profil et dessus
- Rotation 360°, orbite tactile/souris et zoom
- Ambiances Studio et Nocturne
- Modèle GLB original récupéré du showroom : carrosserie et quatre roues séparées, 613 956 octets, conservé sans modification

## Développement

Avec Node.js 22.12 ou ultérieur : `npm install`, puis `npm run dev`.

## Publication

`npm run build` génère `docs/`. GitHub Pages publie la branche `main`, dossier racine. Les fichiers compilés sont à la racine du dépôt ; les sources React/Three.js et le modèle original sont dans `mg3-night-garage-source.zip`. Après une modification, reconstruire et remplacer les fichiers publiés par le contenu de `docs/`.

## Limites du modèle

La carrosserie est statique : aucun ouvrant articulé ni intérieur exploitable. La migration conserve les maillages existants ; les STL haute définition ne sont pas inclus dans le dépôt récupéré.
