# Nidou — Présentation du projet INSEEC

Site vitrine statique et étude stratégique de la plateforme fictive **Nidou**, une marketplace de mise en relation avec des doulas indépendantes.

## Pages
- `/#/` : accueil et sept accès avec bulles interactives
- `/#/interface` : prototype fictif de recherche et fiches de doulas
- `/#/pestel` : analyse PESTEL
- `/#/porter` : cinq forces concurrentielles de Porter
- `/#/swot` : SWOT et axes TOWS
- `/#/bmc` : Business Model Canvas en neuf blocs (commission, réservation/paiement sur plateforme, lancement national)
- `/#/concurrents` : panorama des concurrents et tarifs publics sourcés
- `/#/materiel` : achats, dépenses initiales et charges à prévoir (budget indicatif de 2 900 €)

## Modèle économique retenu
- **Monétisation :** commission sur les prestations réservées et payées via Nidou.
- **Parcours :** réservation et paiement intégrés à Nidou (fonctionnalités envisagées, non actives dans le prototype).
- **Déploiement :** ouverture nationale ; l’offre disponible dépendra de la couverture des doulas selon les zones.

## Lancer localement
Ouvrir `index.html` dans un navigateur ou lancer un serveur statique (`python -m http.server 8000`).

## Déployer avec Cloudflare Pages
- Brancher le dépôt GitHub `vijeva2-jpg/Nidou`.
- Framework preset : **None**.
- Build command : **aucune**.
- Build output directory : **/** (racine du dépôt).
- Les pages utilisent des routes hash pour fonctionner sans configuration de redirection.

## Direction artistique
Palette pastel « baby » : rose poudré, bleu layette, lavande, jaune beurre et prune doux pour les textes. Illustrations vectorielles intégrées sans dépendance d'image.

## Limitations
Ceci est un **projet pédagogique**. Les profils, tarifs et services de l'interface sont fictifs. Aucun paiement, prise de rendez-vous ni formulaire réel. Les appréciations PESTEL/Porter/SWOT/BMC sont qualitatives et destinées à être confirmées par étude de marché et revue juridique.

## Sources
Références listées au bas de la page PESTEL : INSEE, Santé publique France, CNIL, DGCCRF et Doulas de France.

## Travail de terrain à compléter
Le questionnaire et les interviews des familles/doulas sont encore à réaliser. Les hypothèses de panier moyen (75 €), de commission (15 %) et de dépenses de lancement sont des bases pédagogiques, pas des résultats validés.
