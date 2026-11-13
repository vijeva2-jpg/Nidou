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
- `/#/materiel` : achats, dépenses initiales et charges à prévoir (budget de trésorerie indicatif de 1 430 € et contributions internes valorisées à 2 850 €)

## Modèle économique retenu
- **Monétisation :** commission sur les prestations réservées et payées via Nidou ; 15 % comme hypothèse de travail, encore à valider.
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
Le questionnaire et les interviews des familles/doulas sont encore à réaliser. Les hypothèses de panier moyen (75 €), de commission (15 %), de dépenses de lancement (1 430 € de décaissement prévu) et de valorisation des contributions internes (2 850 € non décaissés) sont des bases pédagogiques, pas des résultats validés.

## Simulation des frais de paiement (hypothèses)
Pour une réservation de 75 €, une commission de 15 % donne 11,25 € de chiffre d'affaires brut pour Nidou. Au tarif Stripe standard de 1,5 % + 0,25 € pour une carte EEE standard, les frais de paiement sont de 1,375 €, soit environ 9,88 € de commission conservée **si Nidou supporte ces frais**, avant autres dépenses et taxes. La doula reçoit dans ce scénario 63,75 € avant ses propres charges. Stripe Connect peut modifier la répartition des frais et ajouter des frais de comptes ou de virements selon le mode de tarification choisi. Sources : https://stripe.com/fr/pricing et https://stripe.com/fr/connect/pricing. Les frais de transaction variables sont distincts du budget initial de trésorerie (1 430 €).
