PAUL TECH SERVICES — prototype de site web
===========================================

Contenu
-------
- index.html : site vitrine responsive avec services, formulaire de demande de devis et parcours de paiement en mode démonstration.
- AUCUN paiement réel n'est effectué.
- Le formulaire fonctionne localement dans le navigateur et n'envoie ni n'enregistre les données.
- Les prix affichés sont des exemples à valider.

Tester sur votre ordinateur
---------------------------
1. Téléchargez et décompressez paul_tech_services_site.zip.
2. Ouvrez le dossier.
3. Double-cliquez sur index.html pour l'ouvrir dans Chrome, Edge ou Firefox.
4. Testez le formulaire de devis avec des informations fictives.
5. Cliquez sur « Tester le parcours (démo uniquement) » : aucun paiement n'est réalisé.

Publier gratuitement
--------------------
Option simple : GitHub Pages.
1. Créez un compte sur https://github.com si nécessaire.
2. Créez un nouveau dépôt public nommé paul-tech-services-site.
3. Téléversez index.html à la racine du dépôt.
4. Dans le dépôt, ouvrez Settings > Pages.
5. Choisissez le déploiement depuis la branche principale (main), dossier /(root), puis enregistrez.
6. GitHub affichera l'adresse publique du site après publication.

Autres options : Netlify ou Cloudflare Pages. Les menus et conditions gratuites peuvent changer.

Avant de rendre le site public
------------------------------
- Remplacez les prix d'exemple par vos vrais tarifs.
- Ajoutez un numéro de téléphone professionnel et une adresse de contact vérifiée.
- Le formulaire est actuellement une démo locale : il ne transmet pas les demandes.
- N'ajoutez pas de numéro ou de bouton de paiement Orange Money avant d'avoir confirmé le processus officiel.
- Pour encaisser réellement en ligne, contactez Orange Burkina et demandez les conditions de paiement marchand / API, l'éligibilité, les frais, les documents et les étapes de test.
- Une intégration réelle doit utiliser un serveur sécurisé et vérifier les confirmations de paiement côté serveur.
- Ne demandez jamais aux clients leur code PIN ou OTP. Ne stockez pas ces informations.
- Les dépôts, retraits et transferts pour des tiers peuvent nécessiter des autorisations et un partenariat distincts.

Pour personnaliser
------------------
Ouvrez index.html avec un éditeur de texte (par exemple VS Code) :
- Nom de l'entreprise : rechercher « PAUL TECH SERVICES »
- Tarifs : modifier les textes « À partir de ... FCFA »
- Coordonnées : section « Contact » dans le pied de page
- Couleurs : variables CSS au début du bloc <style>
