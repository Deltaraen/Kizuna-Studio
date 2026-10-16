KIZUNA — site statique prêt à personnaliser

OUVRIR
- Décompressez le ZIP puis ouvrez index.html dans un navigateur.
- Gardez le dossier assets avec les fichiers HTML.

ÉLÉMENTS AJOUTÉS
- Nouvelle image de caisse générée et optimisée, utilisée dans l’accueil et la première vignette de service.
- CTA visible dès l’arrivée et bouton de contact fixe sur mobile.
- Meta title/description, Open Graph, Twitter card et visuels de partage.
- Favicons SVG/PNG et icône Apple.
- robots.txt, sitemap.xml, page 404, page de confidentialité et page merci.
- Alt text, attributs dimensions, chargement différé des images secondaires et breakpoints mobiles.
- Validation accessible du formulaire avec états d’erreur.
- Bandeau de consentement. Google Analytics est préparé mais PAS activé tant que l’identifiant GA4 réel n’est pas renseigné.

AVANT PUBLICATION — IMPORTANT
1. Remplacez chaque occurrence de https://VOTRE-DOMAINE.fr dans robots.txt, sitemap.xml et index.html par le vrai nom de domaine HTTPS.
2. Remplacez G-XXXXXXXXXX dans index.html par votre vrai identifiant Google Analytics 4, uniquement si vous souhaitez utiliser Analytics. Sans identifiant, aucune mesure Analytics ne se charge.
3. Complétez la politique de confidentialité avec le nom légal, l’adresse professionnelle et l’hébergeur.
4. Le formulaire actuel prépare un e-mail dans l’application du visiteur : il ne l’envoie pas automatiquement. Pour un formulaire envoyé directement depuis le site et une page de confirmation réellement déclenchée après l’envoi, il faut connecter un service de formulaire/backend.
5. « Charge en moins de 2 secondes » dépend de l’hébergement, du réseau et du domaine : les images sont optimisées et les images secondaires différées, mais il faut mesurer la version publiée avec PageSpeed Insights.
6. Le fichier 404.html doit être associé à la page d’erreur dans les paramètres de l’hébergeur si celui-ci ne la détecte pas automatiquement.

CONTACT
kizunasas@proton.me · 06 88 13 98 86

Mise à jour design : le hero utilise désormais assets/hero-restaurant.webp, une image distincte de la photo 01 / Caisse Square. La section Services est passée en grille de quatre cartes avec visuels uniformisés, numéros, textes courts et liens d'action. Le design utilise un hero sombre photographique, des cartes blanches arrondies et une palette bleu nuit/bleu clair, avec adaptation mobile.

Dernière finition de la section Mes services : la carte Menu utilise désormais une composition horizontale qui conserve l'image portrait en entier, sur un fond doux assorti au site. Le titre est simplifié en « Menu » et les liens « En savoir plus » ont été supprimés des quatre cartes.

AMÉLIORATIONS ÉDITORIALES — OCTOBRE 2026
- Accroche plus humaine, orientée sur la simplicité pour le commerçant.
- Parcours d’accompagnement clarifié, de l’analyse des besoins à la formation.
- Section « Qui suis-je ? » renforcée autour de l’expérience réelle de restaurateur.
- Appel à l’action et texte du formulaire rendus plus rassurants.
- Focus clavier visible et ajustements de cadrage pour les images de services.

À NE PAS OUBLIER AVANT PUBLICATION
- Renseigner le vrai domaine dans les métadonnées Open Graph, robots.txt et sitemap.xml.
- Compléter les mentions légales avec l’identité exacte de l’éditeur et de l’hébergeur.
- Le formulaire ouvre l’application e-mail du visiteur ; il ne s’agit pas d’un formulaire serveur. Pour envoyer directement depuis la page et afficher une vraie confirmation d’envoi, connecter un service de formulaire.
- Analytics reste désactivé tant que l’identifiant GA4 n’est pas remplacé. N’activez pas l’outil sans vérifier la conformité du consentement et de la politique de confidentialité.


MISE À JOUR DESIGN — OCTOBRE 2026
- Accueil plus aéré : titre élargi, espaces augmentés et texte plus lisible.
- Pictogrammes remplacés par des icônes SVG pertinentes : boutique, cœur, réglages.
- Sur mobile, les cartes services sont empilées pour éviter les textes trop serrés.
- Le formulaire est maintenant préparé pour Netlify Forms avec une page de confirmation /merci.html.
- Le bandeau cookies et le code Analytics ont été différés : ils seront configurés après la mise en ligne, uniquement si Analytics est retenu.

HÉBERGEUR CONSEILLÉ : NETLIFY
1. Créez un compte gratuit sur https://app.netlify.com/.
2. Décompressez l’archive ZIP.
3. Ouvrez le dossier « kizuna-site-final » et déposez le dossier sur Netlify Drop ou dans la zone de déploiement de votre site.
4. Une fois le site publié, allez dans l’onglet Forms et activez « Form detection », puis redéployez le site.
5. Dans Forms, vérifiez que « contact-kizuna » apparaît. Ajoutez une notification par e-mail vers kizunasas@proton.me depuis les paramètres de notifications du formulaire.
6. Testez le formulaire vous-même et vérifiez que la page merci.html s’affiche.
7. Netlify donne une adresse gratuite en .netlify.app. Un nom de domaine personnalisé (par exemple kizuna.fr) est payant séparément ; vous pourrez le connecter plus tard.

À SAVOIR
- L’offre Netlify Free est à 0 $ et inclut un quota mensuel de 300 crédits. Les formulaires sont gratuits sur les offres à crédits, mais les déploiements de production, les requêtes et le trafic consomment des crédits. Le site peut être suspendu jusqu’au mois suivant si le quota est atteint. Vérifiez le tableau de bord de consommation.
- Pour les formulaires, activez bien la détection et redéployez après l’activation ; Netlify ne commencera à traiter les nouveaux formulaires qu’après ce déploiement.
- Ne pas ajouter Google Analytics avant d’avoir choisi les réglages de confidentialité et le mécanisme de consentement. Nous compléterons aussi les mentions légales avec votre identité juridique et les coordonnées exactes de l’hébergeur avant la publication définitive.
- Pour un nom de domaine gratuit, gardez d’abord l’adresse .netlify.app. Les domaines personnalisés fiables sont généralement payants.

Sources officielles utiles :
- Tarifs Netlify : https://www.netlify.com/pricing/
- Configuration des formulaires : https://docs.netlify.com/manage/forms/setup/
- Notifications de formulaire : https://docs.netlify.com/manage/forms/notifications/


CORRECTIFS TECHNIQUES
- Les icônes SVG et les styles associés sont séparés proprement.
- Les cartes de services passent en présentation verticale sur mobile.
- Le formulaire valide les champs dans le navigateur, puis transmet le POST à Netlify.


MISE A JOUR : le texte de la section « Qui suis-je ? » présente désormais Thomas.
Attention : le formulaire du site est encore configuré pour Netlify Forms. Sur GitHub Pages, il faudra connecter un service de formulaire externe avant que les messages envoyés via le formulaire arrivent par e-mail.


MISE À JOUR POUR GITHUB PAGES — FORMULAIRE DE CONTACT

Le formulaire a été adapté à FormSubmit, un service externe qui transmet les demandes à kizunasas@proton.me. Aucun serveur n’est nécessaire sur GitHub Pages.

À FAIRE APRÈS AVOIR PUBLIÉ LES FICHIERS :
1. Sur GitHub, ouvrez le dépôt https://github.com/deltaraen/Kizuna-Studio.
2. Remplacez les fichiers par ceux de cette archive en conservant la structure : index.html et merci.html doivent être à la racine du dépôt, et le dossier assets doit rester à côté.
3. Une fois le site déployé, ouvrez https://deltaraen.github.io/Kizuna-Studio/ et envoyez un message test depuis le formulaire.
4. Lors du premier envoi, FormSubmit peut envoyer un e-mail de confirmation à kizunasas@proton.me. Ouvrez cet e-mail et cliquez sur le lien de confirmation pour autoriser la réception des messages. Vérifiez aussi les courriers indésirables.
5. Recommencez un envoi test et vérifiez que le message arrive dans la boîte de réception.

À SAVOIR : FormSubmit est un service tiers. La première demande n’est pas considérée comme testée tant que l’adresse n’a pas été confirmée et qu’un message réel n’a pas été reçu. Le service peut afficher son propre contrôle anti-spam. Ne mettez jamais de clé secrète dans les fichiers du site.
