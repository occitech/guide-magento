# Documentation Utilisateur Magento CE 1.7 #

Librement adaptée du User Guide Magento officiel en anglais à l'usage des exploitants disposant d'une boutique installée et fonctionnelle.

Des chapitres entiers du User Guide Magento officiel ont donc été ignorés. L'objectif est uniquement d'aider les exploitants à utiliser l'administration de Magento.

## 1 Présentation de Magento CE ##

### 1.1 Qu'est-ce que Magento CE ? ###

Magento CE est la version communautaire open-source du produit Magento. En effet, Magento existe aussi en version Enterprise à partir de 15 550 $ par an avec plus de fonctionnalités natives et du support. [En savoir plus.](http://www.magentocommerce.com/product/overview-compare?icid=topnav)

###  1.2 Licence d'utilisation de Magento CE ###

Magento CE est sous la licence Open Software Licence (OSL) v3.0, une licence certifiée open-source. Plus d'informations sur les licences Magento peuvent être trouvées sur [http://www.magentocommerce.com/license/](http://www.magentocommerce.com/license/).

### 1.3 La partie boutique et la partie administration de Magento CE ###

#### Partie boutique ####

La partie boutique est celle visitée par les internautes qui leur permet de consulter le catalogue et passer commande.

#### Partie administration ####

La partie administration est réservée au commerçant et ses éventuels partenaires pour gérer son catalogue, ses commandes et les réglages de la boutique.

### 1.4 Lexique ###

Pour utiliser Magento CE efficacement, vous devez être familier avec les termes et concepts suivants.

**Attribut:** Une caractéristique d'un produit. Par exemple, un attribut d'un appareil photo numérique peut être
«Résolution», et la valeur de cet attribut pour un appareil photo numérique particulier pourrait être "10
mégapixels. "Les clients peuvent filtrer une liste de produits par des valeurs d'un ou de plusieurs attributs.

**Catégorie:** Une classification des produits définie par l'utilisateur. Une catégorie peut avoir n'importe quel nombre de niveaux de sous-catégories.

**Commande:** Une commande est une demande pour des produits.

**Expédition:** Une expédition est un enregistrement des produits d'une commande qui ont été expédiés. Plusieurs expéditions peuvent être associées à une seule commande.

**Facture:** Une facture dans Magento CE représente une confirmation de paiement. Plus d'une facture peut être associée à une seule commande. Si les produits d'une commande sont expédiés en plusieurs expéditions, une facture est générée pour chaque expédition pour les produits de cette expédition.

**Groupe d'attributs:** Un regroupement logique des attributs au sein d'un jeu d'attributs.

**jeu d'attributs:** Une collection d'attributs, personnalisée pour répondre à un certain type de produit. Par exemple, si vous vendez plusieurs sortes de T-shirts sur votre site web, vous pouvez créer le jeu d'attribut T-
shirt qui comprend les attributs simples communément partagées par l'ensemble de votre T-shirts. Il peut s'agir de la couleur, la taille, le sexe, et la marque.

**Magasin:** Le deuxième niveau de votre hiérarchie magasin. Un site peut avoir plusieurs magasins (chacun,
potentiellement, avec sa catégorie propre racine), et un magasin peut avoir des vues multiples.

**Panier:** L'ensemble des produits que le client a choisi d'acheter, mais n'a pas encore acheté.

**Portée** cela précise à quel niveau de la hiérarchie de votre boutique un paramètre donné est modifié.
Un paramètre peut avoir une portée **globale** (tous les sites Web, les magasins, et vues des magasins), **site Web** (le site sélectionné et tous les magasins et vues des magasins en vertu de celle-ci), **magasin** (le magasin choisi et toutes les vues en dessous), et **vue** (la vue magasin sélectionnée). Certains paramètres définis à un niveau plus haut peut être modifiés à un niveau inférieur.

**Produits apparentés:** ils sont proposés aux clients en complément du produit consulté.

**produit composé:** Ce produit est composé d'éléments qui sont présentés de différentes façons
et sont fabriqués à partir de produits existants. Un bon exemple d'un produit composé est un ordinateur complet. Pour cet ordinateur, vous pouvez configurer la quantité de RAM ou quel type de moniteur est fourni avec cet ordinateur dans votre boutique.

**Produit configurable:** Ce produit permet à vos clients de choisir la variante qui leur convient en choisissant des options. Par exemple, vous pouvez vendre des T-shirts en deux couleurs et trois tailles. Vous aurez à créer les six variantes en tant que produits individuels (chacun avec son propre SKU / référence) puis ajouter ces six produits à un produit configurable où les clients peuvent choisir la taille et couleur, puis l'ajouter à leur panier.

**Produit téléchargeable:** Un produit, comme un fichier multimédia, que les clients téléchargent à partir de la boutique après l'achat. Ces fichiers téléchargeables peuvent résider sur votre serveur ou être fournis sous forme d'URL vers un autre serveur.

**Produit groupé:** Cette option vous permet d'afficher plusieurs produits similaires sur une seule page. Par exemple, si vous vendez des couteaux de cuisine et que vous avez le même couteau en quatre tailles, vous pouvez faire un produit groupé pour afficher les quatre tailles. Les clients peuvent sélectionner la taille ou les tailles qu'ils veulent et les ajouter au panier à partir de cette page.

**Produit simple:** C'est le type de produit le plus élémentaire. Il est adapté pour toutes sortes de produits physique (livrable).

**Produit virtuel:** C'est un produit qui ne nécessite pas d'expédition ou d'inventaire. Il est généralement
utilisé pour des garanties ou des services.

**Règles de taxe:** Une combinaison de classes de taxes sur les produits, de classes de taxes client, et de taux de taxe. Cette règle définit quelle taux de taxe est appliqué.

**SEO:** ensemble des techniques et des stratégies qui garantissent que votre site est répertorié en bonne place dans les résultats des moteurs de recherche, augmentant ainsi la probabilité que les clients trouveront votre site.

**Site Web:** Le plus haut niveau de votre hiérarchie magasin. Vous pouvez avoir plusieurs sites Web, et chaque
site web peut avoir un nom de domaine différent. Les sites Web peuvent être mis en place pour partager ou pas les données des client. Typiquement, chaque site dispose de lignes de produits différents et peuvent avoir des
bases clients différentes.

**Statut de la commande:** Le statut de la commande indique l'endroit où elle est dans le cycle des commandes. Dans Magento CE, les valeurs du système de commande d'état sont les suivantes:

- **En attente** - Les commandes en attente sont des commandes toutes récentes qui n'ont pas été traitées. En règle générale, ces commandes doivent être facturées puis expédiées.
- **Bloquée** - L'utilisateur ne peut pas procéder au traitement de la commande si elle est dans cet état. Cette fonction est pratique si, par exemple, certaines données doivent être vérifiées.
- **Attente paiement PayPal** (Possible pour les commandes PayPal uniquement) - Ce sont des nouvelles commandes
qui n'ont pas été confirmées par PayPal. Lorsque vous utilisez PayPal comme un moyen de paiement, les clients sont redirigés vers le site PayPal. Si elles n'ont pas été payées, les commandes restent sur ce statut. Il n'est pas recommandé de traiter ces commande sans vérifier sur PayPal d'abord pour voir si le paiement a été fait.
- **Vérification du paiement** - Aussi longtemps qu'une passerelle de paiement externe est en train de vérifier le paiement d'une commande, celle-ci sera positionnée sur ce statut.
- **En cours de traitement** - Cela indique que la commande a été soit facturée soit livrée, mais
pas les deux.
- **soupçons de fraude** (Possible pour les commandes PayPal uniquement) - La transaction n'a pas passé au moins un des filtres anti-fraude de Paypal et le système à reçu la réponse de PayPal que la transaction est à l'étude par le Service anti-fraude.
- **Terminée** - Les commandes marquées comme terminées ont été entièrement facturées et ont été expédiés.
- **Annulée** - La commande peut être de ce statut si le client appelle en fait la demande et si la commande n'a pas été payé.

L'administrateur peut créer des statuts de commandes personnalisés, les affecter aux états de commandes et définir les valeurs par défaut des états de commandes.

**Type de produit:** Magento CE classe les produits parmi l'un des types de produits prédéfinis: Produit simple, produit virtuel, produit téléchargeable, produit groupé, produit configurable, produit composé.

**Ventes croisées:** Les produits de vente croisée apparaissent à côté du panier. Quand un client accède à
la page du panier, ces produits sont affichés sous forme de ventes croisées aux articles déjà présents dans le
panier. Ils sont semblables aux achats impulsifs, comme les magazines et les bonbons à la caisse des supermarchés.

**Ventes incitatives:** Ce sont des produits du même type que celui consulté mais qui peuvent être plus coûteux, de meilleure qualité, ou plus populaire, et permettent de produire une marge plus élevée.

**Vue:** Le niveau le plus bas de la hiérarchie de votre magasin. Typiquement, une vue magasin est créée pour
chaque pays ou chaque langue. Toutes les vues d'un même magasin partagent le même catalogue. Les clients peuvent généralement changer de vue depuis l'interface (pour la langue par exemple) ou sont redirigés automatiquement (pour une vue mobile par exemple).

## 2 Accès à l'administration ##

Généralement, l'adresse de l'administration est celle de votre site en rajoutant "/admin" à la fin (ex : http://demo-admin.magentocommerce.com/admin/). Cependant, votre prestataire peut avoir donné une adresse différente car c'est une bonne pratique que de changer cette adresse pour des raisons de sécurité. Demandez donc à votre prestataire l'adresse correcte et mettez-là en favori.


## 3 Hiérarchie de la boutique ##

Magento possède plusieurs niveaux de hiérarchie car il est multi-boutique. Vous n'avez bien entendu aucun besoin d'utiliser cette hiérarchie si votre projet ne contient qu'une seule boutique et qu'une seule langue par exemple. Il est toutefois utile de savoir quelles sont les possibilités offertes par la solution, cela pourrait éventuellement vous donner des idées d'évolutions fonctionnelles ou commerciales.

Une installation Magento peut donc gérer plusieurs sites web, ayant chacun plusieurs boutiques, ayant chacune plusieurs vues.

### Site Web ###

Le site web a son adresse (url) bien à lui. Logiquement, si vous vendez différents types de produits qui n'ont rien à voir ensemble, vous souhaiterez les vendre sur des sites séparés. Avec Magento, vous pourrez toutefois les gérer depuis la même administration, et décider de partager entre les sites des informations (produits, clients par exemple), ou pas !

### Boutique ###

Dans un même site web, vous pouvez souhaiter créer des espaces distincts, selon des gammes de produits ou selon la clientèle. Par exemple, clients particuliers et clients professionnels. Chaque famille de client, donc chaque Boutique, aura sa propre organisation de catégories produits, et pourquoi pas des produits différents de l'un à l'autre (à l'unité pour des particuliers, par palette pour les professionnels).

### Vues ###

Les vues permettent de modifier l'affichage d'une boutique, ou seulement d'une catégorie ou d'un produit. Les vues peuvent être utilisées pour proposer plusieurs langues, ou bien une présentation optimisée pour les appareils mobiles, ou encore pour modifier temporairement l'habillage de votre boutique pour des occasions particulières (Soldes, Noël, etc...).

## 4 Gestion des commandes ##

Dans l'administration, allez dans Ventes -> Commandes

Vous voyez la liste des commandes passées sur votre site par ordre anté-chronologique, quel que soit leur état.

Vous pouvez filtrer et ordonner les commandes avec les contrôles en tête des colonnes du tableau. Pensez à valider votre filtrage avec le bouton "Chercher" en haut à droite du tableau. Vous pouvez réinitialiser les filtres en cliquant sur le bouton "réinitialiser le filtre"

Vous pouvez appliquer des actions groupées disponibles dans le menu déroulant "Actions" à toutes les commandes que vous aurez préalablement coché.

Pour rentrer dans le détail d'une commande, cliquez simplement dessus.

### 4.1 Détail d'une commande

Magento CE fournit une grande variété d'informations pour chaque commande. Cette section propose une rapide revue de ces informations pour une commande existante. La navigation latérale gauche vous permet de naviguer parmi les différentes sections de la commande : informations, factures, avoirs, expéditions, historique de commentaires, transactions.

**Informations**

Cette page fournit une vue globale des informations les plus importantes de la commande, comme son statut actuel, les produits commandés, les informations sur le client, la facturation, l'expédition et le paiement.

La section **Historique de commentaires** de cette page fournit des informations sur le cycle de vie de la commande. Chaque événement notoire de la commande y est mentionné, en spécifiant si le client en a été averti. Vous pouvez changer le statut de la commande grâce au menu déroulant et éventuellement laisser un commentaire au client.

**Pour ajouter un commentaire à la commande**

1. Saisissez votre commentaire dans la zone texte
2. Si vous voulez que le client reçoive une notification par E-mail, cochez la case "avertir le client par email"
3. Si vous voulez que le commentaire soit visible par le client sur son compte, cochez la case "visible sur le site côté client"
4. Cliquez sur "Envoyer un commentaire"

Tous les commentaire sont stockés sur l'onglet "historique de commentaires".

**Factures**

Une facture représente une confirmation de paiement. Cet onglet vous permet de consulter les factures générées pour une commande.
Vous pouvez générer une facture individuellement ou groupée avec une expédition. Si les produits de la commande sont envoyés en plusieurs expéditions, alors une facture sera générée pour chaque expédition en fonction des produits qu'elle contient.

**Avoirs**

Cette page affiche une liste des remboursements concernant des produits de cette commande. Vous pouvez cliquer sur une avoir pour voir le détail de son contenu.

**Expéditions**

Une expédition est un enregistrement des produits d'une commande qui ont été envoyés. Comme pour les factures, une commande peut générer plusieurs expéditions.

Cette page propose une liste des expéditions générées pour cette commande. Vous pouvez cliquer sur une expédition pour voir le détail de son contenu.

### 4.2 Cycle de vie d'une commande ###

Une commande suivie d'une paiement en ligne validé passe (généralement) directement en facturation (statut "en cours").

Sinon, pour les paiements demandant une validation manuelle, elle reste en commande (statut "attente de paiement").

#### 4.2.1 Passer une commande en facture (paiement reçu) ####

Allez dans Ventes -> Commandes.

Cliquez sur la commande et cliquez sur le bouton "Facturer" en haut à droite.

Vous arrivez sur un écran qui récapitule la commande. Tout en bas, valider le paiement en cliquant sur "Soumettre la facture". Éventuellement, vous aurez préalablement coché "ajouter les commentaires" pour que le client voit le commentaire saisi, et "Envoyer une copie de la facture par mail" pour que le client la reçoive.

#### 4.2.2 Passer une commande en expédiée ####

Théoriquement, votre commande est déjà facturée (statut "en cours"). Allez dessus et cliquez sur le bouton "Expédier" en haut à droite.

Vous voyez une nouvelle fenêtre qui récapitule la commande. Vous devez, dans le bloc "Informations de livraison", spécifier le mode de livraison et un éventuel No de tracking.

Puis tout en bas, cliquer sur "Valider l'expédition" en ayant préalablement si besoin partagé votre commentaire avec le client ("ajouter les commentaires") et/ou  envoyé au client une alerte d'expédition ("Envoyer une copie de la livraison par mail").

Quand la commande est passée en "expédiée" vous pouvez cliquer sur le bouton "imprimer" en haut à droite qui vous sortira le bordereau d'expédition.

### 4.3 Créer une commande en administration ###

**Attention** : une commande créée en administration ne peut pas être payée par CB en ligne.

Allez dans Ventes -> Commandes et cliquez sur "Créer une nouvelle commande"

Sélectionnez un client, et si vous avez plusieurs sites, boutiques et vues, sélectionner auquel cette commande se rattache.

Vous arrivez sur une page qui contient plusieurs blocs d'informations.

Choisissez dans quelle devise la commande doit être créée tout en haut.

#### 4.3.1 Sélectionner les produits par l'historique du client ####

Sur la colonne gauche, vous retrouverez des informations sur le client :

- Articles dans le panier
- Articles dans la liste d'envie
- Derniers articles commandés
- Articles dans la liste de comparaison
- Derniers produits comparés
- Derniers produits consultés

De chaque bloc vous pourrez prendre un article pour le mettre dans les "articles commandés" en cochant la case "ajouter à la commande" puis en cliquant sur le bouton "Mettre à jour les modification" présent en haut et en bas de cette colonne. Vous pouvez également supprimer des produits de ces emplacements et vider le panier.

#### 4.3.2 Sélectionner les produits par le catalogue ####

Cliquer sur le bouton "Ajouter des produits". Vous avez alors accès au moteur de recherche du catalogue et pouvez ajouter n'importe quel article actif du catalogue en cochant la case correspondant de l'avant-dernière colonne du tableau, spéciant une quantité dans la dernière colonne et en cliquant sur "Ajouter les produits sélectionnés à la commande".

#### 4.3.3 Finaliser la commande ####

Vous pouvez manuellement modifier le prix des articles.

Sélectionnez ensuite (ou créez) les adresses de facturation et de livraison.

Dans le bloc "Mode de livraison", cliquez sur "Récupérer les modes de livraison et les taux".
Vous pourrez ensuite choisir un mode de livraison et un moyen de paiement.

Vous pouvez saisir un commentaire, puis envoyer la commande tout en bas en notifiant éventuellement le client.


## 5 Gestion du catalogue ##

### 5.1 Gestion des catégories du catalogue ###

Cette section décrit comment afficher, créer et éditer les catégories et sous-catégories du catalogue.

Les produits de la boutique sont regroupés dans des catégories. Les catégories permettent de structurer votre boutique. Dans chaque boutique, une unique catégorie parente sert de base au catalogue. Toutes les autres catégories devront être crées en tant que sous-catégorie de celle-ci.

Rappel : chaque produit peut être assigné à une ou plusieurs catégories.

Allez dans Catalogue -> Gérer les catégories. Les catégories sont affichées dans un arbre.

#### 5.1.1 Créer une catégorie ####

Sélectionner la catégorie parente dans laquelle vous souhaitez créer votre catégorie et cliquez sur "Ajouter une sous-catégorie".

**Informations générales**

1. Donnez un nom à votre catégorie
2. Spécifiez si elle est active ou non (apparaît ou pas sur la boutique)
3. La "clé d’URL" sera déduite du nom si vous ne remplissez rien. C'est l'adresse par laquelle on arrivera sur la page de cette catégorie, peut être utile au référencement.
4. "Thumbnail image" ou "vignette" est une image petit format qui accompagnera éventuellement la catégorie dans sa catégorie parente, selon les options graphiques sélectionnées avec votre prestataire.
5. La description est un petit texte qui sera affiché sur la page de la catégorie pour la définir éventuellement selon les options graphiques sélectionnées avec votre prestataire. Peut être utile au référencement.
6. L'image est affichée sur la page de la catégorie pour l'illustrer, selon les options graphiques sélectionnées avec votre prestataire.
7. Le titre de la page s'affichera dans l'onglet de votre navigateur. Peut être utile au référencement.
8. Les mots-clé meta ne sont plus vraiment utilisés pour le référencement. Listez ici les mots-clé qui définissent cette catégorie (vraiment facultatif voire inutile).
9. "Include in navigation menu" ou "Inclure dans la navigation" permet de spécifier si la catégorie apparaît dans le menu de navigation.
10. cliquer sur "sauvegarder la catégorie" en haut à droite

**Paramètres d'affichage**

Cet onglet permet de spécifier comment cette catégorie est présentée aux clients.

1. "Display mode" ou "mode d'affichage" spécifie si on affiche uniquement les produits, les produits et le bloc CMS ou seulement le bloc CMS. N'afficher qu'un bloc CMS permet d'utiliser une catégorie comme simple page de contenu.
2. "CMS block" spécifie le bloc CMS à afficher selon l'option choisie ci-dessus.
3. "Is anchor" ou "est une ancre". Si mise à oui, les filtres produits seront affichés dans cette catégorie.
4. "Available Product Listing Sort By" : spécifie les attributs avec lesquels les clients pourront trier les produits dans cette catégorie. Par défaut, tous sont sélectionnés.
5. "Default Product Listing Sort By" sélectionne l'attribut avec lequel la liste de produit est triée par défaut.
6. "Layered navigation Price Step" spécifie l'amplitude des écarts de prix pour le filtre "par prix" en mode "navigation par filtres".

**Design personnalisé**

Cet onglet contient des réglages additionnels pour contrôler le thème et les options graphiques pour cette catégorie. Généralement vous n'aurez pas, en tant qu'exploitant, à toucher à ces options. C'est plutôt votre prestataire qui y fera des réglages initiaux ou ponctuels selon vos besoins.

1. "Use parent category settings" : choisissiez "oui" pour hériter des réglages de la catégorie parente.
2. "Apply to products" : choisissez "oui" pour appliquer les réglages de cette catégorie aux pages produit des produits qu'elle contient.
3. "Design personnalisé" vous permet de choisir une mise en page différente pour cette catégorie parmi les vues disponibles. A n'utiliser qu'avec les recommandations de votre prestataire.
4. "Actif à partir du "..."jusqu'au" : permet de sélectionner de quand à quand le design personnalisé doit être appliqué, utile pour les opérations commerciales liées à des événements.
5. "Agencement de la page" permet de sélectionner une mise en page spécifique pour cette catégorie, si cela est compatible et prévu avec le thème utilisé.
6. "Mise à jour d'agencement personnalisé" est un réglage que vous n'aurez jamais à utiliser directement.

**Produits de la catégorie**

Vous pouvez consulter et gérer les produits contenus dans cette catégorie.

*ajouter ou supprimer des produits à la catégorie*

Les produits dont la case en début de ligne sont cochés appartiennent à la catégorie. Si vous souhaitez chercher des produits du catalogue pour les assigner à cette catégorie, modifiez le filtre de la 1ère colonne et mettez "non" puis utilisez les autres filtres pour trouver les articles à ajouter. Cocher la case en première colonne des produits à ajouter et sauvegardez la catégorie : ces produits appartiennent maintenant à cette catégorie.

Pour supprimer des produits de cette catégorie, décocher la case en première colonne des produits concernés et sauvegardez la catégorie.

Attention à bien réinitialiser les filtres pour voir les produits de la catégorie.

*Rappels :*

- un produit peut appartenir à une ou plusieurs catégories.
- vous pouvez aussi depuis la fiche d'une produit choisir la ou les catégories dans lesquelles il doit apparaître

### 5.2 Navigation par filtres ###

Pour simplifier l'utilisation de la boutique par le client parmi un grand choix de produits dans une même catégorie, il est possible de proposer des filtres qui vont leur permettre de restreindre la sélection de produit et donc de trouver plus rapidement le produit qu'il cherche.

**Navigation par filtres par défaut**

 Par défaut, Magento CE propose 2 filtres : le prix et les sous-catégories (si elles existent) de la catégorie en cours si elle est en "is anchor".

**Définir d'autres filtres en navigation par filtres**

Pour rajouter de nouveaux filtres, il faut créer les attributs correspondants et les définir comme filtrables.
Les attributs se gèrent dans Catalogue -> Attributs -> Gérer les attributs.

Dans le bloc "Propriétés du frontend" de l'attribut, modifiez la valeur de "Utiliser dans la navigation par filtres".
La valeur **Filtrable (avec résultats)** ne propose que les valeurs du filtre qui ont des produits correspondants.
La valeur **Filtrable (pas de résultats)** propose toutes les valeurs du filtre.
Les types d'attributs qui permettent une navigation par filtres sont : liste déroulante, sélection multiple ou prix.

### 5.3 Gérer les attributs produits ###

#### 5.3.1 Définition ####

Un attribut représente une propriété du produit comme : son nom, une image, sa référence, sa couleur, son fabricant, etc... Les attributs vous permettent d'ajouter de nouvelles propriétés sans avoir besoin d'écrire une seule ligne de code. Comprendre les attributs est crucial pour faciliter son utilisation par les clients.

Vous assignez des attributs à vos produits afin de permettre à vos clients et aux moteurs de recherche de les trouver plus facilement. Magento CE affichera automatiquement (si techniquement possible et activé au cas par cas) des filtres correspondants aux attributs définis.

Les **attributs système** définissent les propriétés requises par Magento pour fonctionner correctement. Ils ne peuvent pas être supprimés.

Vous pouvez ajouter autant d'attributs que nécessaire. Vous pouvez définir des jeux d'attributs. Cela simplifie la création de produit car en lui assignant un jeu d'attribut particulier, tous les attributs requis lui seront automatiquement assignés. Vous pouvez ainsi créer des jeux d'attributs spécifiques pour chaque type de produit : TV, chaussures, appareils photos, etc...Quand un nouvel appareil photo est ajouté à votre catalogue, définissez son jeu d'attribut comme "appareil photo" et les attributs pertinents pour ce type de produit seront disponibles lors de la saisie de sa fiche.

Il vous faut d'abord créer les attributs, puis les jeux d'attribut.

#### 5.3.2 Créer les attributs ####

Rappel : Seuls les jeux d'attributs sont assignés aux produits, pas les attributs individuellement.

1. Allez dans Catalogue -> Attributs -> Gérer les attributs
2. Cliquez sur "Ajouter un attribut"
3. Dans le champ "Code", spécifie un identifiant unique pour cet attribut. N'utilisez pas d'espace. Ce code n'apparaîtra pas sur la partie boutique.
4. Dans le champ "portée" spécifiez à quelle portée vous voulez que l'attribut existe (voir hiérarchie de la boutique)
5. Le champ "Type d'entée catalogue pour le propriétaire de la boutique" contrôle comment le propriétaire spécifie les valeurs pour cet attribut. Attention, certains types ne sont pas utilisables pour la navigation par filtres.
6. Si cet attribut a une valeur par défaut, spécifiez la dans "Valeur par défaut".
7. Si la valeur de cet attribut doit être unique pour chaque produit (comme une référence), précisez "oui" pour "Valeur unique".
8. Si la valeur de cet attribut ne peut pas être vide pour aucun produit, spécifiez "oui" pour "valeurs requises".
9. Dans le champ "Validation requise", vous pouvez demander à Magento de valider les valeurs saisies selon des schémas, comme "nombre entier, email, URL".
10. Si cet attribut ne s'applique qu'à certains types de produit, sélectionnez "Types de produit sélectionnés" dans "S'applique à" puis cliquez sur les types de produits concernés (touche CONTROL + click pour sélection multiple).
11. Pour que cet attribut soit utilisé comme mot-clé dans les recherches rapides ou avancées, sélectionnez "Oui" dans le champ approprié.
12. Pour "Comparable sur le front-office" sélectionnez "oui" si vous souhaitez que cet attribut soit affiché dans le comparateur de produits.
13. "Utiliser dans la navigation par filtres" spécifie si cet attribut permet de filtrer les produits (vu dans navigation par filtres). Il en va de même pour la navigation par filtres dans les résultats de recherche.
14. "Utiliser pour les conditions de règles de promotions" permet de créer des règles de promotions à partir des valeurs de cet attribut.
15. Le champ "Position" permet de définir la position de cet attribut en tant que filtre dans la navigation par filtres en fonction des autres attributs.
16. "Autoriser les balises HTML sur le front-end" permet d'interpréter les balises HTML qui seraient saisies dans les valeurs en tant que tel.
17. "Visible sur la page produit du magasin" permet de définir si cet attribut s'affiche tout seul sur la fiche produit.
18. "Utiliser dans les listes de produits" affiche la valeur de cet attribut dans la liste de produit de la catégorie (si le thème le permet).
19. "Utiliser pour le tri des listes de produits" permet de trier la liste des produits d'une catégorie selon cet attribut.
20. Cliquez sur l'onglet "Gérer les labels / les options" en haut à gauche pour gérer les labels et valeurs de cet attribut.
21. Spécifiez un nom pour l'attribut et éventuellement les valeurs dans l'administration et pour chaque vue magasin.
22. Cliquez sur "Sauvegardez l'attribut"

#### 5.3.3 Les jeux d'attributs ####

Un jeu d'attribut est une collection d'attributs personnalisée pour répondre à certains types de produits. Tous les jeux d'attributs doivent contenir tous les attributs système de Magento mais vous pouvez les modifier pour inclure différentes combinaisons d'attributs simples.

Seuls les jeux d'attributs peuvent être assignés aux produits.

Si vous voulez ajouter des attributs à tous les produits, vous pouvez les ajouter au jeu nommé "default" (défaut).

Quand on créé un jeu d'attributs, il peut hériter des attributs déjà précisé dans un autre jeu pour gagner du temps.

**Créer un nouveau jeu d'attributs**

Dans l'administration, allez dans Catalogue -> Attributs -> Gérer les jeux d'attributs


1. Cliquez sur "Ajouter un jeu" en haut à droite
2. Mettez dans le champ "Nom" un nom qui vous aidera à le sélectionner quand vous créerez un produit. Ce nom ne sera pas visible des clients.
3. Dans le champ "basé sur", sélectionné le jeu d'attributs dont celui que vous créez héritera. Le plus simple et le moins personnalisé doit toujours être "default".
4. Cliquez sur "Sauvegardez le jeu d'attributs".
5. Vous passez alors en édition du jeu d'attributs. Voir ci-dessous.

**Modifier un jeu d'attributs**

Vous arrivez sur cet écran si vous cliquez sur un jeu d'attributs existants depuis la liste des jeux d'attributs, ou si vous venez de créer un nouveau jeu d'attributs.

1. A gauche vous pouvez modifier le nom du jeu d'attributs.
2. Vous pouvez ajouter ou supprimer des attributs dans le jeu d'attributs. La colonne centrale représente les attributs actifs, classés dans des groupes d'attributs. La colonne de droites ("Attributs non assignés") ceux qui ne sont pas assignés à ce jeu. Vous pouvez les placer dans le jeu d'attributs en les glissant avec la souris dans le groupe souhaité de la colonne centrale, et retirer ceux nous souhaités en les glissant avec la souris de la colonne centrale vers celle de droite.
3. Sauvegardez le jeu d'attributs

**Créer un groupe d'attributs**

La colonne centrale de l'édition d'un jeu d'attributs montre un arbre hiérarchique représentant des groupes d'attributs.

Vous pouvez comparer les groupes d'attributs à des dossiers. Chaque groupe correspond aux onglets d'ajout / édition d'un produit. Magento propose 6 onglets par défaut qui contiennent les attributs système et les attributs proposé de base.

Vous pouvez créer un groupe spécifique en utilisant le bouton "Ajouter" au dessus de la colonne centrale.


### 5.4 Gérer les produits ###

*Rappel : il faut avoir d'abord créé les attributs et jeux d'attributs avant de créer vos produits*

#### 5.4.1 Types de produits ####

**Produit simple:** C'est le type de produit le plus élémentaire. Il est adapté pour toutes sortes de produits physique (livrable).

**Produit configurable:** Ce produit permet à vos clients de choisir la variante qui leur convient en choisissant des options. Par exemple, vous pouvez vendre des T-shirts en deux couleurs et trois tailles. Vous aurez à créer les six variantes en tant que produits individuels (chacun avec son propre SKU / référence) puis ajouter ces six produits à un produit configurable où les clients peuvent choisir la taille et couleur, puis l'ajouter à leur panier.

**Produit groupé:** Cette option vous permet d'afficher plusieurs produits similaires sur une seule page. Par exemple, si vous vendez des couteaux de cuisine et que vous avez le même couteau en quatre tailles, vous pouvez faire un produit groupé pour afficher les quatre tailles. Les clients peuvent sélectionner la taille ou les tailles qu'ils veulent et les ajouter au panier à partir de cette page.

**produit composé:** Ce produit est composé d'éléments qui sont présentés de différentes façons
et sont fabriqués à partir de produits existants. Un bon exemple d'un produit composé est un ordinateur complet. Pour cet ordinateur, vous pouvez configurer la quantité de RAM ou quel type de moniteur est fourni avec cet ordinateur dans votre boutique.

**Produit téléchargeable:** Un produit, comme un fichier multimédia, que les clients téléchargent à partir de la boutique après l'achat. Ces fichiers téléchargeables peuvent résider sur votre serveur ou être fournis sous forme d'URL vers un autre serveur.

**Produit virtuel:** C'est un produit qui ne nécessite pas d'expédition ou d'inventaire. Il est généralement
utilisé pour des garanties ou des services.

#### 5.4.2 Créer un nouveau produit####

Allez dans Catalogue -> Produits et cliquez en haut à droite sur "Ajouter un produit"

**Assistant, 1ère page**

La première étape consiste à déterminer le jeu d'attributs utilisé pour ce produit, puis son type. L'explication de ces paramètres a été donnée plus haut.

Cliquez sur "Continuer" pour commencer à remplir les informations de votre nouveau produit.

**Onglet "Général"**

Remplissez les champs obligatoires signalés par une étoile ( * ) rouge.

*Nom* : Nom du produit tel qu'il apparaît sur la boutique

*Description* : Texte affiché sur la page produit

*Description courte* : peut être utilisé selon le thème sur la page catégorie du produit.

*Réf* : Référence unique de votre produit, aussi appelée "SKU". La portée de cet attribut est globale (toutes les boutiques installées sur votre Magento). Si vous synchronisez votre boutique avec des solutions de gestion commerciale (EBP par exemple), la référence doit être identique à celle utilisée dans votre gestion commerciale.

*Poids* : poids du produit, utilisé pour calculer les frais de port si basés sur le poids total de la commande.

*Nouveautés depuis jusqu'au* : intervalle de dates pendant lequel le produit peut être promu en tant que nouveauté sur la partie client, selon votre thème.

*Statut* : choisissez "activé" pour que le produit soit accessible sur la partie client.

*Clé d'url* : générée automatiquement si vous la laissez vide à partir du nom du produit, cette chaîne de caractère permettra de déterminer l'adresse de la page produit. Ne pas mettre d'espaces vides. A une utilité pour votre référencement.

*Visibilité* :

- "Catalogue, Recherche" : le produit est accessible via les catégories auxquelles il est affecté, et par le moteur de recherche.

- "Catalogue" : le produit n'est accessible que via les catégories auxquelles il est affecté, mais pas par le moteur de recherche

- "Chercher" : le produit n'est accessible que par le moteur de recherche

- "Non visible individuellement" : le produit n'est pas affiché sur les pages de catégories auxquelles il est affecté. Cependant, il peut être un composant d'un produit configurable, groupé ou composé.


*Fabricant* : comme son nom l'indique...

*Pays de fabrication* : comme son nom l'indique

**Onglet Prix**

Remplissez les champs obligatoires signalés par une étoile ( * ) rouge.

*Prix* : prix de vente. Selon la configuration vue avec votre prestataire, le prix est à saisir HT ou TTC.

*Group price* : permet de définir un prix particulier pour les groupes de clients (voir groupes clients)

*Prix spécial* : permet de définir un prix promotionnel.

*Prix spécial à partir jusqu'au* : intervalle durant lequel le prix spécial est appliqué.

*Tier price* : permet de proposer des remises quantitatives, par groupe client.

*Prix au détail conseillé par le fabricant* : si prévu par le thème, affiche le prix public.

*Appliquer un prix minimum affiché*, *Afficher les vrais prix* : cas très particuliers, non expliqués ici.

*Classe de TVA* : la classe de TVA du produit à appliquer


**Onglet Informations méta**

*Titre méta* : titre de la page dans l'onglet du navigateur.

*Mots-clé meta* : mots-clé qui décrivent le produit.

*Méta description* : description du produit et de la boutique affiché sur les moteurs de recherche.

**Onglet Images**

Cet onglet permet de gérer toutes les images du produit aux différents endroits possibles dans la boutique.

*Note sur les images : bien que Magento redimensionne automatiquement les images, veillez à utiliser des images pas trop lourdes pour réduire votre temps de gestion.*

Cliquez sur "Browse Files..." ou "Parcourir", choisissez une ou plusieurs images depuis votre ordinateur, puis cliquez sur "Upload Files".

Les images envoyées vont apparaître dans le tableau. L'aperçu dans la première colonne se fait au survol de la souris.

Pour chaque image, vous pouvez choisir à quel endroit elle sera utilisée :
- *Base image* : utilisée sur la fiche produit
- *Small image* : utilisée dans les catégorie, listes de souhaits et autres listes
- *Thumbnail* : utilisée dans le panier et les produits liés

Le champ libellé est à remplir obligatoirement et doit décrire le contenu de l'image; son impact sur le référencement est important.

La case "Exclure" permettra de ne pas afficher cet image dans les miniatures de la fiche produit.

Vous pouvez supprimer les images existantes en cochant la case correspondante puis en sauvegardant le produit.

**Onglet Profil récurrent**

Utilisé pour des produits renouvelables (abonnements par ex), il est très peu utilisé et demande un moyen de paiement compatible.

**Onglet Design**

Cet onglet permet de paramétrer la façon dont la fiche produit est affichée.

*Design personnalisé* : permet de choisir une mise en page particulière parmi les thèmes créés pour votre boutique.

*Actif à partir...jusqu'au* : programme le design personnalisé pendant une période définie.

*Mise en page d'agencement personnalisé* : réservé à votre prestataire pour des réglages complexes.

*Agencement de page* : permet selon votre thème de modifier l'affichage ou pas des colonnes latérales.

*Afficher les options de produits dans* :  sélectionne l'endroit où les options produits apparaissent.

**Onglet options cadeau**

Vous pouvez choisir ici, si vous avez activé l'option cadeau à l'échelle de la boutique, si ce produit peut en bénéficier ou pas.

**Onglet Inventaire**

Cet onglet vous permet de gérer plusieurs options relatives à la gestion des stocks.
Beaucoup de ces réglages sont gérés à l'échelle globale de la boutique dans Système -> Configuration -> Catalogue -> Inventaire.

*Gérer les stocks* : active les options de gestion d'inventaire pour ce produit (de nouvelles options vont apparaître).

*Activer les incréments de quantité* : si votre produit est vendu par lots, activez cette option puis préciser la quantité contenue dans le lot dans le champ "Incréments de quantités" qui apparaît.

Les options suivantes apparaissent uniquement si le champ "Gérer les stocks" est sur "oui" :

*Qté* : quantité disponible en stock

*Qté pour que le statut du produit passe à épuisé* : en dessous de cette valeur, le produit passe en statut "Epuisé".

*Qté mini/maxi autorisée dans le panier* : permet de limiter par le bas et le haut la quantité qu'un client peut mettre dans son panier.

*La quantité utilise des décimales* :  permet au client de commander des quantités avec virgules comme pour un produit au kilo ou au poids.

*Commande en rupture de stock* : permet d'autoriser ou pas la commande de produit qui ne sont temporairement plus en stock. La dernière option avec "et prévenir le client" l'informe que le produit n'est pas en stock mais qu'il peut tout de même le commander.

*Notifier quand la quantité passe en dessous de* : si activé, la boutique vous enverra un email lorsque le produit descend sous la valeur de stock spécifiée.

*Activer les incréments de quantité* : si activé, vous permet de spécifier les valeurs de quantité qui seront proposées aux clients pour mettre le produit dans son panier.

*Disponibilité* : contient 2 valeurs : "En stock" et "épuisé". Le comportement offert aux clients sur le statut "Epuisé" dépend des options ci-dessus.

*Onglet site web* : en module multi-boutique, vous permet de choisir sur quelle(s) boutique(s) le produit est proposé.

**Onglet Catégories**

vous permet de cocher la ou les catégories qui proposeront ce produit. Attention, il n'est pas nécessaire de cocher les catégories parentes sauf si, en accord avec votre prestataire, votre thème propose des options spécifiques et requiert ce réglage.

Rappels : un produit peut être proposé dans plusieurs catégories. Vous pouvez également depuis la gestion d'une catégorie sélectionner les produits qui la composent.

**Onglet Produits apparentés**

vous permet de sélectionner les produits qui seront proposé aux clients sur la fiche de ce produit en tant que complément. Votre thème doit afficher cet espace.

**Onglet Ventes incitatives**

(up-selling) vous permet de sélectionner les produits qui seront proposé aux clients sur la fiche de ce produit en tant que produit équivalent ou mieux. Votre thème doit afficher cet espace.

**Onglet Ventes croisées**

vous permet de sélectionner les produits qui seront proposé aux clients dans le panier si il achète ce produit en tant que consommable (généralement). Votre thème doit afficher cet espace.

**Onglet Commentaires**

contient une liste des commentaires réalisés par des clients sur ce produit. Vous pouvez approuver, éditer ou supprimer les commentaires.

Notes :

- les réglages généraux du site vous permettent de spécifier si les commentaires sont activés, affichés avant ou après votre approbation.
- un flux RSS est disponible sur cette page pour être maintenu au courant des nouveaux commentaires sur tous les produits.

**Onglet Mots clés du produit**

Affiche les mots-clés reliés à ce produit et leur nombre d'utilisation dans la recherche.

**Onglet Clients ayant proposé des mots-clés**

affiche la liste des mots-clés attribués par les clients à ce produit (si fonctionnalité activée). Vous pouvez gérer ces mots-clés (approuver, modifier, supprimer).

**Onglet Options personnalisables**

Cet onglet vous permet de rajouter facilement des variantes de produits ou des options personnalisables par le client. Voir chapitre **Créer des variations de produits**.

### 5.4.3 Créer des variations de produits###

Cette section permet de comprendre comment créer des variations de produits en ajoutant des contrôles à une page produit (différentes couleurs ou taille).

**Attention** : si vous souhaitez gérer les stocks pour chaque option, utilisez plutôt les produits configurables. Idem si chaque option a un poids particuliers, ou autre chose de différent que le prix (qui est gérable en option personnalisable).

Pour saisir des options personnalisables, reprenons la fin de la saisie d'un produit : allez sur le dernier onglet "Options personnalisables".

Cliquez sur "ajouter une option".

Une ligne apparaît vous demandant de saisir un titre, un type puis de préciser si cette option est obligatoire pour le client, et enfin un ordre de tri d'affichage si vous créez plusieurs options. Vous pouvez donc créer autant d'options que souhaité.

Chaque type possible va vous permettre de spécifier à minima :
- l'éventuel écart de prix par rapport au produit sans cette valeur (en fixe ou en pourcentage)
- une référence particulière si besoin (qui sera rajoutée à la référence du produit initial)

Ensuite, selon les types d'autres valeurs pourront vous être demandées (nb caractères pour un champ texte, format acceptés pour des fichiers, etc...).

Il faut donc créer toutes les valeurs possibles pour chaque option. Puis vous pouvez créer d'autres options si besoins.


## 6 Groupes clients##

Rassembler les clients dans des groupes permet de définir des règles de gestion spécifiques à ces groupes.
Tarifs préférentiels, classes de TVA spécifiques, promotions spécifiques, etc...

Sauf utilisation d'une extension spécifique, le client ne peut pas choisir son groupe et c'est bien normal. C'est à vous, exploitant de la boutique, de créer les groupes puis y assigner des clients existants.

### 6.1 Gérer les groupes clients###

Allez dans Clients -> Groupes clients.

Vous pouvez d'ici créer, modifier et supprimer les groupes clients.
A la création d'un groupe, vous devrez uniquement lui donner un nom et une classe de TVA correspondante.

### 6.2 Assigner un client à un groupe###

Allez dans Clients -> Gérer les clients.

Cliquez sur un client existant puis dans l'onglet "Informations du compte". Vous y trouverez le champ "Groupe" qui vous permettra d'assigner un groupe à ce client, ou à l'en retirer.

### 6.3 Créer un prix produit spécifique pour un groupe###

Se référer au chapitre §5.4.2

### 6.4 Créer une promotion pour un groupe###

A la création d'une règle de promotion, vous pouvez choisir à quel(s) groupe(s) elle s'applique. Voir chapitre sur les promotions pour le reste de la configuration.

### 6.5 Autres réglages liés aux groupes###

En fonction de vos besoins et des extensions utilisées, certains paramètres peuvent être liés à un ou plusieurs groupes, comme des moyens de livraison ou de paiement. Voyez avec votre prestataire si vous avez des besoins particuliers pour gérer vos groupes clients.

## 7 Promotions##

Il y a plusieurs façons de créer une promotion :

- Créer un prix spécial unitairement pour un produit pour tous les clients
- Créer une promotion "règle de prix catalogue" qui va appliquer avec des critères aux produits concernés un prix spécial
- Créer une promotion "règle de prix panier" qui va, selon le contenu du panier et d'autres critères, créer une remise globale sur la commande. Pour créer un coupon de réduction, c'est ici.

### 7.1 Prix spécial###

Comme vu au chapitre 5.4.2, dans l'onglet "Prix" d'un produit, vous pouvez spécifier un prix spécial éventuellement avec une plage de date applicable. Si votre thème le permet, le prix normal sera barré et le prix spécial mis en avant.

La loi Française demande, pour les promotions, de spécifier les dates applicables. Pensez donc à modifier votre thème en fonction.

### 7.2 Règle de prix catalogue###

Les règles de prix catalogue servent à définir des remises et promotions au catalogue. Elles s'appliquent avant que le client mette le produit dans son panier sans qu'il n'est rien à faire. Elles se mettent en place en 3 étapes :

Allez dans Promotions -> Règles de prix catalogue, puis cliquez sur "Créer une nouvelle règle"

**Informations**

*Nom de la règle* : Donne un nom pour la reconnaître dans la liste des règles

*Description* : Ajoute une description qui pourra être affichée aux clients

*Statut* : doit être sur "Actif" pour fonctionner

*Sites web* : en mode multi-boutique, permet d'assigner la règle à une ou plusieurs boutiques.

*Groupes clients* : permet de n'autoriser que certains groupes clients à utiliser cette règle

*Date de début - fin* : permet de limiter la règle dans le temps

*Priorité* : si plusieurs règles répondent aux critères d'un client, la priorité la plus petite prévaut sur les autres.

**Conditions**

Il est impossible d'expliquer toutes les combinaisons offertes par ce module !
N'oubliez pas que vous pouvez utiliser certains attributs comme conditions pour créer vos règles.

Exemple : réduction de 10% sur les T-SHIRT de plus de 20 €.

	Si toutes ces conditions sont vraies :

	Catégorie est égale à T-SHIRT
	Price est supérieur(e) ou égal(e) à 20

(la réduction se définit dans l'onglet suivant "actions").

Vous pouvez créer toute sorte de combinaison et cas particulier que seul l'entraînement et l'utilisation vous donneront.

**Actions**

Vous définirez ici comment s'applique la remise.

- En pourcentage du prix d'origine (spécifier pourcentage dans champ "remise")
- Remise d'un montant fixe (ex 5 € / spécifier remise dans champ "remise")
- Pourcentage du prix original (Ex : 10% = 90 % de remise !!! / spécifier pourcentage dans champ "remise")
- Nouveau prix en montant fixe (spécifier nouveau prix dans champ "remise")

Pour notre exemple, nous choisirons donc "En pourcentage du prix d'origine" puis "10" dans "remise".

*Activer les remises sur les sous-produits* : appliquer la remise sur les produits simples qui constituent les produits configurables par exemple.

*Ne pas traiter les règles suivantes* : permet de spécifier des règles à ne pas traiter si celle-ci est appliquée

Les règles de prix catalogue nécessitent un traitement sur la base de produits. Aussi faut-il cliquer sur "Appliquer" si vous souhaitez qu'elles soient actives immédiatement. Sinon elles seront appliquées durant un traitement de nuit, chaque nuit.


### 7.3 Règles de prix panier ###

Ces règles de promotion sont appliquées quand le client atteint le panier. Elles peuvent s'activer automatiquement ou après saisie d'un code (ou coupon), et comprennent des options plus avancées que les règles catalogue. Elles se créent en 3 étapes :

Allez dans Promotions -> Règles de prix panier, puis cliquez sur "Créer une nouvelle règle"

**Informations règle**

*Nom de la règle* : Donne un nom pour la reconnaître dans la liste des règles

*Description* : Ajoute une description qui pourra être affichée aux clients

*Statut* : doit être sur "Actif" pour fonctionner

*Sites web* : en mode multi-boutique, permet d'assigner la règle à une ou plusieurs boutiques.

*Groupes clients* : permet de n'autoriser que certains groupes clients à utiliser cette règle

*Bon de réduction* : si vous laissez "pas de bon de réduction", la règle s'appliquera automatiquement à tous les clients (selon critères ci-dessus). Par contre, en mettant "Bon de réduction spécifique", le client devra saisir le code que vous aurez entré dans le champ "Code du bon de réduction" qui apparaît alors (et que vous lui aurez donc communiqué) pour que la règle s'applique.

*Nombre d'utilisation par coupon* : disponible uniquement si vous avez choisi d'utiliser un bon. Permet de limiter l'utilisation globale de ce bon, pour une offre limitée par exemple.

*Nombre d'utilisation par client* : permet de limiter combien de fois un même client peut utiliser cette réduction.

*Date de début - fin* : permet de limiter la règle dans le temps

*Priorité* : si plusieurs règles répondent aux critères d'un client, la priorité la plus petite prévaut sur les autres.

*Public dans le flux RSS* : permet de spécifier dans votre flux RSS les offres en cours. A vous de voir si cette offre doit être publique ou pas.

**Conditions**

Comme pour les règles catalogue, il existe une infinité de possibilités pour créer des règles. Sauf que vous avez accès ici à plus de champ, notamment à l'échelle globale du panier (comme le sous-total, le poids total, etc...).
Il est donc conseillé de faire appel pour les premières fois à votre prestataire et de s’entraîner.

**Actions**

*Appliquer* : spécifie le type de remise parmi :

- Remise en pourcentage du prix du produit (spécifier pourcentage dans champ "Remise")
- Remise d'une valeur fixe (comprendre par produit, spécifier pourcentage dans champ "Remise"))
- Remise d'un montant fixe pour l'ensemble du panier (spécifier montant fixe dans champ "Remise")
- X achetés, Y gratuits (spécifier la valeur Y dans remise, et X dans "Quantité pour obtenir la remise")

*Qté maxi à laquelle la remise est appliquée* : spécifie la quantité maximale de produit sur laquelle la remise sera appliquée. Les produits au-delà seront facturés sans remise.

*Appliquer au montant de la livraison* : permet d'appliquer la remise si possible à la livraison

*Livraison gratuite* : Offre en outre la livraison, sur les expéditions contenant les produits concernés ou seulement sur l'expédition des produits concernés.

*Ne pas traiter les règles suivantes* : permet de ne pas cumuler cette remise avec celles qui pourraient venir ensuite, selon l'ordre de priorité.

*Sélection des produits applicables* : vous pouvez vouloir créer une règle qui a des conditions globales (montant du panier global) mais dont la réduction ne s'applique qu'à certains articles. Exemple : Si votre panier atteint 500 €, 20% de remise sur les chaussures. Vous pouvez ainsi spécifier grâce à des conditions les produits qui recevront la remise.

**Libellés**

Permet de spécifier en administration comme sur la boutique le nom de la règle appliquée.
