# Revue — 9785-9789, rue André-Jobin

Maquettes de page d'atterrissage pour le quadruplex, Nº Centris **16713528**.
Site statique, aucune dépendance, aucun build.

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Tableau de bord — les quatre variantes côte à côte |
| `landing-occupant.html` | Variante A — l'argent d'abord |
| `landing-occupant-c.html` | Variante C — le logement d'abord |
| `landing-occupant-d.html` | Variante D — le quartier d'abord |
| `landing-investisseur.html` | Variante B — investisseur |
| `images/` | Photos optimisées, JPEG et WebP |

## Déploiement

Vercel détecte un site statique : **aucune commande de build**, dossier de
sortie à la racine. `vercel.json` ajoute l'en-tête `X-Robots-Tag: noindex`
sur toutes les routes.

## Ce dépôt doit rester privé

Trois raisons :

1. Les pages portent le **nom, le numéro de téléphone et le titre** d'une
   courtière, ainsi que la marque de son agence.
2. Elles montrent l'**intérieur d'un logement occupé**.
3. Le tableau de bord contient des **hypothèses de financement et des
   estimations de dépenses** réservées à la courtière.

## Ce ne sont pas les pages finales

Le formulaire n'envoie rien, les montants sont des illustrations, et un
bandeau rouge le rappelle en haut de chaque page. Le devis technique complet
(`spec-dev.md`) vit ailleurs, avec le reste du dossier de campagne.
