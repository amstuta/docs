---
title: 'Installer son site avec les modules en 1 clic'
slug: modules-en-1-clic
excerpt: 'Découvrez comment installer votre site via nos modules en 1 clic'
section: CMS
order: 01
updated: 2023-01-31
---

**Dernière mise à jour le 15/02/2023**

## Objectif

Les modules en 1 clic permettent l'installation facile et rapide d'un site Internet (sans compétences techniques requises). Ils utilisent les CMS les plus connus : WordPress, PrestaShop, Drupal et Joomla!.

**Découvrez comment installer votre site via nos modules en 1 clic.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZrYmmPbMl4I?rel=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Prérequis

- Disposer d'une offre d'[hébergement web](https://www.ovhcloud.com/fr/web-hosting/) compatible.
- Être connecté à l'[espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr).
- Utiliser [une version de PHP compatible](https://docs.ovh.com/fr/hosting/configurer-le-php-sur-son-hebergement-web-mutu-2014/) sur votre hébergement web.
- Avoir [configuré correctement votre fichier .ovhconfig](https://docs.ovh.com/fr/hosting/configurer-fichier-ovhconfig/).
- Le répertoire où sera installé votre module doit être vide ou actuellement inexistant.
- Le domaine (avec sous-domaine si souhaité) qui sera utilisé pour votre site internet doit être déclaré en tant que multisite.

## En pratique

### Étape 1 : bien choisir son CMS

Un CMS (pour Content Management System) vous permet de concevoir un site web via une interface simple d'utilisation. Il en existe plusieurs types en fonction des projets de chacun. Vous pourrez ainsi bénéficier d'une structure de site prête à l'emploi à personnaliser (thème, textes, etc.) à votre convenance.

OVHcloud propose 4 quatre CMS avec ses modules en 1 clic. En utilisant cette solution, vous devrez donc choisir dans cette liste. Si votre choix s'est déjà porté sur l'un d'entre eux, poursuivez les différentes étapes de ce tutoriel. Dans le cas contraire, ce [comparatif des CMS](https://www.ovhcloud.com/fr/web-hosting/uc-cms-comparison/) pourrait vous aider dans votre décision.

Si vous souhaitez installer un CMS non proposé par les modules en 1 clic OVHcloud, vous pouvez toujours l'installer manuellement sur votre hébergement, sous réserve de la compatibilité de ce CMS avec votre offre (retrouvez nos offres [ici](https://www.ovhcloud.com/fr/web-hosting/)).

![Logo des CMS](images/CMS_logo.png){.thumbnail}


### Étape 2 : accéder à la gestion des modules 1 clic

Connectez-vous à votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr) puis sélectionnez `Web Cloud`{.action}. Cliquez sur `Hébergements`{.action} et choisissez l'offre concernée.

Vous pourrez y consulter les différents modules en 1 clic déjà installés, les gérer et en installer de nouveaux.

![Accès à la section Modules 1 clic](images/access_to_the_1_click_modules_section.png){.thumbnail}

### Étape 3 : ajouter un module

L'installation d'un nouveau module en 1 clic s’initie en cliquant sur le bouton `Ajouter un module`{.action}.

Dans la fenêtre qui s'affiche, choisissez le CMS souhaité puis le domaine sur lequel vous souhaitez installer votre site :

![Choix du module](images/add_a_module.png){.thumbnail}

Si vous ne trouvez pas le domaine voulu dans la liste, rendez-vous dans l'onglet `Multisite`{.action} pour l'ajouter, puis essayez de nouveau d'ajouter un module.

Vous pouvez également consulter le guide [Comment partager mon hébergement web entre plusieurs sites](https://docs.ovh.com/fr/hosting/multisites-configurer-un-multisite-sur-mon-hebergement-web/){.external} pour vous aider.

Une fois le CMS sélectionné, vous devrez choisir entre une installation simple ou avancée :

- Concernant l'installation simple (sélectionnée par défaut) : nous réalisons l'installation du CMS et vous communiquons vos identifiants pour l'administrer. Il s'agit de la manière la plus simple et la plus rapide pour installer un module.
- Concernant l'installation avancée : vous pouvez personnaliser la configuration à appliquer pour l'installation du CMS. Pour cela, vous devez renseigner plusieurs informations indispensables au bon fonctionnement du CMS sur votre votre base de données : informations de connexion, répertoire d'installation, langue, identifiant administrateur, etc.

#### Installation simple d'un module

Pour réaliser cette installation, assurez-vous que la case `Installation en mode avancé`{.action} ne soit pas cochée, puis cliquez sur le bouton `Installer`{.action}.

> [!warning]
>
> Le répertoire d'installation de votre module doit être vide et vous devez disposer d'une base de données disponible pour que l'installation puisse se faire.
> 

![Installation simple d'un module](images/choose_installation.png){.thumbnail}

Une fois l'installation terminée, vous recevrez un e-mail comportant les informations nécessaires à votre connexion à l'interface administrateur du CMS. Connectez-vous alors à celle-ci pour personnaliser votre site.

#### Installation avancée d'un module

Pour réaliser cette installation, assurez-vous que la case `Installation en mode avancé`{.action} soit cochée, puis cliquez sur le bouton `Suivant`{.action} :

![Installation avancée d'un module](images/advanced_installation.png){.thumbnail}

##### Choisir la base de données

Vous devez à présent renseigner les informations de connexion à votre base de données. Il existe plusieurs possibilités :

- la base de données est déjà créée sur votre hébergement : sélectionnez-la dans la liste et complétez les informations demandées ;
- la base de données n'est pas encore créée sur votre hébergement : suivez les indications afin de créer cette dernière, puis effectuez de nouveau la manipulation ;
- la base de données est créée sur mon instance Web Cloud Databases : sélectionnez-la dans la liste `Base de données en dehors de votre hébergement web`{.action} et complétez les informations demandées. L'instance et l'hébergement web doivent être hébergés dans le même centre de données ;
- la base de données est créée sur un autre hébergement Web OVHcloud : sélectionnez-la dans la liste `Base de données en dehors de votre hébergement web`{.action} et complétez les informations demandées. La base de données et l'hébergement web doivent être hébergés dans le même centre de données ;

Une fois les informations complétées, cliquez sur le bouton `Suivant`{.action}.

> [!warning]
>
> Si les informations que vous indiquez sont incorrectes, l'installation n'arrivera pas à son terme. Pour éviter cela, nous vous invitons en premier lieu à tester la connexion à votre base de données.
> 

![Base de données pour installation avancée](images/advanced_installation_database.png){.thumbnail}

##### Configurer le module

Vous devez à présent renseigner les informations suivantes pour la configuration du module :

- *nom ou e-mail de l'administrateur :* il s'agit de l'identifiant que vous utiliserez pour vous connecter à l'administration de votre CMS ;
- *mot de passe :* il s'agit du mot de passe que vous utiliserez pour vous connecter à l'interface d'administration de votre CMS ;
- *domaine :* il s'agit du domaine sur lequel vous souhaitez installer votre site ;
Vous pouvez également consulter le guide [Comment partager mon hébergement web entre plusieurs sites](https://docs.ovh.com/fr/hosting/multisites-configurer-un-multisite-sur-mon-hebergement-web/) pour vous aider.
- *langue :* il s'agit de langue dans laquelle le CMS sera installé ;
- *chemin d’installation :* ce dernier est automatiquement renseigné à la sélection du domaine. Vous avez la possibilité de le compléter en y renseignant des sous-répertoires.

Une fois ces informations complétées, cliquez sur le bouton `Suivant`{.action} :

> [!warning]
>
> Le chemin d'installation renseigné doit être vide de tout contenu pour que l'installation arrive à son terme.
> 

![Configuration du module pour installation avancée](images/advanced_installation_configuration.png){.thumbnail}

##### Confirmer l'installation

Dernière étape de l'installation avancée, nous vous invitons à vérifier les informations affichées, puis de cliquez sur `Valider`{.action} :

![Validation de l'installation en mode avancé](images/advanced_installation_summary.png){.thumbnail}

### Étape 4 : personnaliser mon site

Vous recevrez un e-mail vous confirmant la bonne installation du module CMS et vous invitant à vous connecter à son interface d'administration. Vous pourrez alors modifier le thème de votre site web et y publier vos premiers contenus.

Si vous désirez obtenir de l'aide concernant les fonctionnalités de votre site, nous vous invitons à vous rapprocher du site de l'éditeur du CMS où vous trouverez de la documentation pour vous accompagner dans votre projet.

|CMS|Documentation officielle|
|---|---|
|WordPress|[Premiers pas avec WordPress](https://codex.wordpress.org/fr:Premiers_pas_avec_WordPress){.external}|
|PrestaShop|[Documentation en français PrestaShop](http://doc.prestashop.com/pages/viewpage.action?pageId=2424836){.external}|
|Joomla|[Infos techniques Joomla](https://www.joomla.fr/actualites/infos-techniques){.external}|
|Drupal|[Bien démarrer avec Drupal](https://www.drupal.fr/documentation/bien-demarrer-drupal){.external}|

## Aller plus loin

[Choisir un CMS pour créer un site web](https://www.ovhcloud.com/fr/web-hosting/uc-cms-comparison/){.external}

[Comment partager mon hébergement Web entre plusieurs sites](https://docs.ovh.com/fr/hosting/multisites-configurer-un-multisite-sur-mon-hebergement-web/){.external}

[Gestion d’une base de données depuis un hébergement mutualisé](https://docs.ovh.com/fr/hosting/gestion-dune-base-de-donnees-depuis-un-hebergement-mutualise/){.external}

Découvrez nos [offres Web Cloud Databases](https://www.ovh.com/fr/cloud/cloud-databases/){.external}

[Gérer votre CMS](https://docs.ovh.com/fr/hosting/1-click-module-management/)

[Désinstaller votre CMS](https://docs.ovh.com/fr/hosting/1-click-module-management/#etape-3-supprimer-votre-module)

Pour des prestations spécialisées (référencement, développement, etc), contactez les [partenaires OVHcloud](https://partner.ovhcloud.com/fr/).

Si vous souhaitez bénéficier d'une assistance à l'usage et à la configuration de vos solutions OVHcloud, nous vous proposons de consulter nos différentes [offres de support](https://www.ovhcloud.com/fr/support-levels/).

Échangez avec notre communauté d'utilisateurs sur <https://community.ovh.com>.
