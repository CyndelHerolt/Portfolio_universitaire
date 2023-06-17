---
title: "UniFolio"
date: 2023-03-06
categories: [ "Développer une application Web interactive","Co-concevoir une réponse stratégique","Entreprendre un projet au sein d’un écosystème numérique" ]
lead: "Développpement d'un outil de création de portfolios universitaires à destination des étudiants et permettant le suivi pédagogique et l'évaluation par les enseignants"
description: "à compléter"
placeholder: "assets/logo.png"
tags: [
  "AC22.01 | Co-concevoir un produit ou un service (proposition de valeur, fonctionnalités...)",
  "AC24.01 | Produire des pages et applications Web responsives",
  "AC24.02 | Mettre en place ou développer un back office",
  "AC24.03 | Intégrer, produire ou développer des interactions riches ou des dispositifs interactifs",
  "AC24.04 | Modéliser les traitements d’une application Web",
  "AC25.01 | Gérer un projet avec une méthode d’amélioration continue par exemple une méthode agile",
  "AC25.04 | Collaborer au sein des organisations",
]
#thumbnail: "img/logoUniFolio.png"
#draft: true
---

## Présentation du projet

Le projet UniFolio est né d'un **constat** : les étudiants de l'IUT de Troyes doivent pour la plupart créer un **portfolio numérique** pour valoriser leurs travaux et compétences. Mais **le support utilisé est différent pour chaque département**.
Donc, dans une démarche d'unification et de simplification, l'IUT a décidé de créer **un outil commun à
tous les départements**. En plus d'assurer le **suivi pédagogique**, cet outil permettra aux étudiants de disposer d'une
**vitrine a présenter aux entreprises** pendant leurs recherche de stage ou d'alternance. Un autre point important est
de permettre aux étudiants de conserver leur portfolio après leur départ de l'IUT. Ils disposeront d'un accès à leur
compte pour une durée de 5 ans après leur départ et pourront **exporter les contenus** sous divers formats afin d'être
en mesure de **conserver et de compléter leurs productions**.

#### Objectifs

- Créer un outil de création de portfolios numériques à destination des étudiants
- Permettre le suivi pédagogique et l'évaluation par les enseignants
- Unifier la forme des portfolios numériques
- Proposer un outil dont l'usage est simple et intuitif
- Minimiser le temps de formation
- Faciliter la valorisation des travaux et compétences des étudiants
- Faciliter l'insertion professionnelle des étudiants

#### Méthodologie et organisation

C'est un projet d'envergure qui nécessite une méthodologie adaptée. Sans se plier à un concept de méthodologie
existant, je dirais que la manière dont nous avons abordé le projet se rapproche de la **méthode Agile**. Les grandes
lignes ont été définies mais **le projet évolue au fur et à mesure de son développement**. Lorsque je décide de
travailler sur une fonctionnalité, je la choisi **en fonction des besoins** qui se font sentir sur le moment. Je
travaille sur cette fonctionnalité jusqu'à ce qu'elle soit fonctionnelle et je passe ensuite à la suivante. Mais cela ne
m'empêche pas de revenir sur une fonctionnalité déjà développée si besoin, j'**intègre le changement** dans le processus
de production. Je travaille en **itérations** *(résolution par approximations successives)* et je **teste**
régulièrement les fonctionnalités développées. Je travaille également en **collaboration** avec mon tuteur d'alternance,
nous nous réunissons régulièrement pour **faire le point** sur l'avancement du projet, **définir les prochaines étapes** et **résoudre certains bugs**.

Pour l'instant seulement **deux acteurs** sont impliqués dans le projet : mon tuteur d'alternance et moi-même. Je
m'occupe donc de la totalité du **développement** sous la **supervision** de mon tuteur qui m'apporte son aide et ses
conseils aussi bien dans la réalisation technique que dans les reflexions. La mise en commun de nos idées et de nos
points de vue nous permet d'avancer plus rapidement et de prendre les bonnes décisions.

Le suivi du projet est assuré via **GitHub** *(plateforme de partage de projet de développement)* et les échanges se
font principalement par **mail** et **Discord**.

##### Solution collaborative

Afin de rendre le projet accessible à mon tuteur, j'ai déposé les fichiers de l'application sur mon Github (plateforme
en ligne orientée dev qui permet de **partager du code** et de **travailler à plusieurs** sur un projet). J'ai choisi de
travailler avec **Github** car il s'agit d'un outil sur lequel je n'étais alors pas très à l'aise mais qui est cependant un incontournable.
Maintenant, j'en fais une utilisation quotidienne pour mettre à jour ce projet mais également l'ensemble de mes projets
personnels et universitaires.

<figure>
    <figcaption>Calendrier de mes publications sur Github</figcaption>
    <img src="/img/github_commits.png" alt="aperçu compte github">
</figure>

Accessible au public depuis mon compte, UniFolio est protégé par la licence MPL-2.0 (Mozilla Public License 2.0) qui
permet à quiconque de **partager, modifier et contribuer au code** tout en **protégeant les droits** de l'auteur. Vous
pouvez trouver dans le repository un guide que j'ai rédigé pour **installer l'application sur votre machine** et la
tester.

#### Technologies utilisées

<div style="display: flex; justify-content: space-evenly; flex-wrap: wrap;">
<div style="width: 40%">

- **PHP** *(langage de programmation)*
- **Symfony** *(framework PHP)*

</div>
<div style="width: 40%">

- **Twig** *(moteur de template)*
- **MySQL** *(base de données)*

</div>
</div>
<hr>
<div style="display: flex; justify-content: space-evenly; flex-wrap: wrap;">
<div style="width: 40%">

- **PhpMyAdmin** *(interface d'administration de base de données)*
- **JavaScript** *(langage de script)*

</div>
<div style="width: 40%">

- **Bootstrap** *(framework CSS)*
- **PhpStorm** *(éditeur de code)*

</div>
</div>
<hr>
<div style="display: flex; justify-content: space-evenly; flex-wrap: wrap;">
<div style="width: 40%">

- **Figma** *(outil de création de maquettes)*
- **GitHub** *(plateforme de partage de projet)*

</div>
<div style="width: 40%">

- **Discord** *(plateforme de communication)*
- **Notion** *(outil de gestion de projet)*

</div>
</div>
<hr>

#### Etapes

1. **Etude de l'existant** *(méthodes actuelles des départements, outils de création de portfolios)*
2. **Etude des besoins** *(étudiants, enseignants, IUT)*
3. **Définition des fonctionnalités** *(fonctionnalités de base, fonctionnalités avancées)*
4. **Création des maquettes** *(maquettes des pages, maquettes des fonctionnalités)*
5. **Développement du back-office** -reste quelques problèmes- *(création de la base de données, de l'interface de
   gestion pour les administrateurs)*
6. **Développement de la partie publique** *(structure de la page d'accueil)*
7. **Développement de la partie étudiant** -reste quelques problèmes- *(création des pages de connexion/inscription, du
   dashboard et des différentes pages de création de contenus (traces, pages, portfolios, cv) ... )*
8. **Développement de la partie enseignant** -en cours- *(création des pages de connexion/inscription, du dashboard)*

## Réalisation du projet

### Etude de l'existant

#### Méthodes actuelles des départements

<figure>
   <figcaption>
   Une réunion est organisée pour échanger sur les procédés des différents départements et leurs besoins
   </figcaption>
   <img src="/img/mail_portfolio.png" alt="Mail pour la réunion portfolio">
</figure>


En assistant à cette réunion animée par les responsables de la SAE portfolio des l'ensemble des départements, j'ai
appris
qu'actuellement, tous les départements de l'IUT utilisent des méthodes différentes pour la création de portfolios.
Certains imposent des supports (GoogleSite, Pdf, dossier papier, ...), d'autres laissent le choix à l'étudiant. Ils ont
tout de même tous un point commun : **le portfolio doit justifier la validation des compétences de la formation**.

La justification des compétences est donc le point central de la création de portfolios. Afin d'y parvenir, les
étudiants doivent illustrer leurs travaux (intra et extra universitaires) en rassemblant un ensemble **de traces** *(
preuves de leurs compétences)* qui peuvent être de différentes natures : **textes, images, vidéos, liens, ...**.

#### Analyse sectorielle

Comme dit dans le mail plus haut, au départ la création d'un outil en interne n'était pas décidée. La possibilité
d'exploiter une solution déjà existante (Mahara, Karuta ou d'autres solutions) semblait envisageable. Cependant, après
avoir étudié ces outils, il s'est avéré qu'ils ne répondaient pas à certains pré-requis.

<div class="card">

###### Mahara • *outil open source*

Présente l'avantage d'être déjà utilisé par l'URCA et propose des **fonctionnalités intéressantes** (cv, bibliothèque
privée, commentaires ...). Cependant, après avoir réalisé quelques tests il s'avère que des fonctionnalités superflues
viennent **complexifier l'expérience utilisateur** et que l'interface n'est ni moderne ni intuitive.

<figure style="position:relative;width:fit-content;height:fit-content; margin: 0 auto">
   <figcaption>Test de création d'un portfolio</figcaption>
   <video width="640" height="360" controls>
       <source src="/files/demo_mahara.mp4" type="video/mp4">
   </video>
</figure>

<br>

En outre, même si Mahara est développé sur une techno PHP *(un langage de programmation enseigné en MMI)* **l'adaptation
de l'outil à nos besoins** nécessiterait de s'approprier un projet conséquent, ce qui est plus complexe que de partir de
zéro. Cette solution est donc écartée, car même si elle est très complète, elle se révèle trop complexe pour
l'utilisateur et demanderait un investissement plus important qu'un développement en interne.

</div>
<div class="card">

###### Karuta • *outil open source*

Impossible de tester l'outil sans l'installer sur un serveur. C'est donc à partir d'une vidéo de présentation que j'ai
pu me faire une idée.

La solution semble **complexe**, peu intuitive et ne propose **qu'un seul format de trace** *(lien)* qui nécessite une
solution d'hébergement supplémentaire pour les étudiants. De plus, **l'adaptation de l'outil à nos besoins**
nécessiterait d'apprendre le langage **java** *(langage de programmation non enseigné en MMI)*, ce qui étendrait
considérablement le temps de développement.

<figure style="height: 400px; overflow: scroll">
<figcaption>
   Discussion à propos de Karuta
</figcaption>

<img src="/img/discord_karuta.png" alt="extrait d'une discussion autour de karuta">

</figure>

Même si, d'après la conversation ci-dessus, Karuta ne semble pas être une solution viable, nous avons tout de même
creusé un peu plus le sujet en contactant l'UTT qui utilise cet outil.
La décision de **ne pas utiliser Karuta** a été arrêtée lorsque l'UTT a fait part d'un retour d'expérience sur *
*l'installation de l'outil qui se trouve être extrêment complexe et nécessiterait alors l'intervention d'un tiers**.

</div>
<div class="card">

###### Adobe Portfolio

Après avoir écarté la possibilité d'utiliser Mahara ou Karuta, nous avons décidé qu'il serait préférable de développer
un outil en interne.
J'ai donc analysé AdobePortfolio qui présente l'avantage d'être **simple d'utilisation** et **intuitif**.

<figure style="position:relative;width:fit-content;height:fit-content; margin: 0 auto">
   <figcaption>Système de templates</figcaption>
   <img src="/img/adobe_themes.png" alt="aperçu des templates proposés par AdobePortfolio">
</figure>

<figure style="position:relative;width:fit-content;height:fit-content; margin: 0 auto">
   <figcaption>Editeur de page</figcaption>
   <img src="/img/adobe_page.png" alt="aperçu de l'éditeur de page de AdobePortfolio">
</figure>
<br>

Ici, on retrouve une interface **épurée et simple**, qui ne contient que les fonctionnalités essentielles. La structure
et le processus de création sera forcément complètement différent de celui d'AdobePortfolio, mais il sera nécessaire de
s'inspirer de son **interface** pour créer un outil simple et intuitif et **des fonctionnalités** des outils vus
précédemment pour créer un outil complet et **adapté aux besoins universitaires** (exploiter les référentiels de
compétences et proposer une structure qui facilite le lien travaux/compétences).

</div>

### Etude des besoins

Les besoins ont été précisés lors de la réunion rassemblant les responsables de la SAE Portfolio. Plusieurs points ont
été évoqués, tous ne seront pas traités dans le cadre de ce projet mais le tour de table à permis de définir **les
critères de "l'outil idéal"** communs aux départements.

<figure>
<figcaption>Prise de notes pendant la réunion</figcaption>
<iframe src="/files/portfolio_reunion.pdf" width="100%" height="480" frameBorder="0" scrolling="yes" allowFullScreen></iframe>
</figure>

### Définition des fonctionnalités

A partir des besoins exprimés lors de la réunion, un document qui recense - entre autres - les fonctionnalités que devra
proposer l'outil a été rédigé. Il fait office de **cahier des charges** mais reste très flexible (il est possible de
rajouter ou modifier des fonctionnalités au cours du développement) et permet de suivre et de vérifier que le projet ne
s'écarte pas de l'idée initiale.

<figure>
<figcaption>Document général rédigé par David Annebicque</figcaption>
<iframe src="/files/portfolio_fonctionnalites.pdf" width="100%" height="480" frameBorder="0" scrolling="yes" allowFullScreen></iframe>
</figure>

De mon côté, comme précisé dans les échanges Discord ci-dessus, j'ai rédigé ce qu'on pourrait qualifier de **"process
idéal"** pour la création d'un portfolio. Il s'agit d'une liste de tâches et de **fonctionnalités**, qui permet de
définir ce qu'il faudra développer et la **structure** de l'outil. Toutes ces étapes s'avèrent être des **points de
reflexion** importants pour le développement de l'outil en termes de **faisabilité** et de **pertinence**.

<figure>
<figcaption>Rédaction du "process idéal"</figcaption>
<iframe src="/files/unifolio_process.pdf" width="100%" height="480" frameBorder="0" scrolling="yes" allowFullScreen></iframe>
</figure>

### Création des maquettes

Une étape délicate dans la réalisation du projet, pas la plus captivante mais dont l'utilité est cruciale. Il s'agit de
**créer des maquettes** qui permettront de visualiser l'outil et de **définir la structure** de l'interface. Elle permet
un développement plus **efficace** et **rapide** et permet de **limiter les erreurs**.
Pour cela, j'ai utilisé le logiciel **Figma** qui permet de créer des maquettes interactives et de les partager
facilement.

Dans un premier temps il s'agissait de réaliser une **arborescence primaire** du site qui comprendrait le menu, les
pages principales et les liens entre elles. Toutes les pages n'ont pas été détaillées, **des spécificités pouvant se
présenter pendant la phase de développement**, nous avons décidé qu'il n'était pas nécessaire de rédiger une
arborescence complexe.

<figure>
<figcaption>Arborescence simple du site</figcaption>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2Fy1Su0q8ocXVJQqgAKcL1Yt%2Fportfolio-tool%3Ftype%3Dwhiteboard%26node-id%3D0%253A1%26t%3DAjeF6TLb7SqVY5t3-1" allowfullscreen></iframe>
</figure>

Pour la maquette, j'ai opté pour un **design simple**, applicable en grande partie avec des **composants Bootstrap** (
éléments réutilisables).
L'objectif étant de développer un outil simple d'utilisation, accessible à tous, j'ai **limité au maximum les artifices
graphiques** pour concentrer l'attention sur le contenu.
Etant donné que je développe cet outil seule, je n'ai pas créé toutes les pages, mais j'ai détaillé les pages et
fonctionnalités principales de l'outil. J'avais donc une ligne directrice en terme de design et de structure pour le
développement, sans pour autant toujours respecter scrupuleusement la maquette. Pour l'instant, mon attention est toute
portée sur le développement des fonctionnalités alors que l'application du design viendra dans un second temps.

<figure>
<figcaption>Wireframe, un schéma de la structure et des fonctionnalités</figcaption>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FuF4huuCYxODhobtQvM3pEe%2FProjet-portfolio%3Ftype%3Ddesign%26node-id%3D0%253A1%26t%3DiWjXv9m1FyCBH2S3-1" allowfullscreen></iframe>
</figure>

### Préparation de la base de données

Avant de créer la base de données, il est nécessaire de **définir les données** qui seront stockées et leur **structure
**. Pour cela, j'ai exploité la méthode Merise (*méthode informatique dédiée à la modélisation d'une structure à
informatiser*). Elle permet de **visualiser** les données et leurs liens et de **définir** les tables et les champs de
la base de données.

Puisque le projet reprend en partie la **structure déjà existante** de l'Intranet (structure des départements et des
référentiels de compétences) j'ai mis à profit l'existant et construit la base de données en fonction. En parallele,
j'ai réfléchi à la structure des données qui seront propres au portfolio et à leur lien avec les données existantes afin
d'optimiser le nombre de tables et de relation ManyToMany pour rendre l'exploitation des données la plus simple
possible. **Sur le schéma ci-dessous : en jaune la structure issue de l'intranet, en bleu la structure propre à l'outil
**.

Il suffisait ensuite de créer la base en suivant le modèle conçu plus tôt.

<figure>
<figcaption>Modélisation des données et de leurs liens</figcaption>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="/files/portfolioMerise.pdf" allowfullscreen></iframe>
</figure>

### Développement du back-office

Première étape du développement d'UniFolio, le back-office. C'est la partie **administrative** de l'outil. Il permet aux
utilisateurs disposants de droits **administrateurs** de **gérer les données** et de **paramétrer** l'outil. Grâce au
bundle EasyAdmin de Symfony, il est possible de créer un back-office rapidement et simplement. Il suffit de créer des *
*entités** (*classes qui représentent les tables de la base de données*) et de les **configurer** pour qu'elles soient
accessibles depuis le back-office.

La quasi totalité du code est générée par la saisie de quelques lignes de commande, il suffit de choisir les données que
l'on veut pouvoir modifier et d'adapter les formulaires pour qu'ils correspondent à nos besoins.
En premier lieu, la commande ``symfony console make:admin:dashboard`` génère un tableau de bord qui devient le point
d'entrée du back-office. Il suffit ensuite de **générer des CRUD** (*Create, Read, Update, Delete*) à l'aide de la
commande ``symfony console make:admin:crud`` et de suivre le Wizard pour chaque entité que l'on souhaite pouvoir
modifier. et de les ajouter à la méthode ``configureMenuItems()`` du fichier ``DashboardController.php`` pour qu'elles
soient accessibles depuis le tableau de bord.
J'ai donc simplement généré les CRUD pour les entités qui nécessiteraient d'être modifiées par les administrateurs.

<figure>
<figcaption>Interface de CRUD générée par EasyAdmin</figcaption>
<img src="/img/easyAdminCRUD.png" alt="aperçu d'easyadmin">
</figure>

Comme vous pouvez le voir dans la sidebar de gauche, j'ai créé des liens vers les versions etudiant et enseignant de l'
appli pour pouvoir faire des démos plus simplement ; cette fonctionnalité pourrait également permettre aux enseignants
d'accéder à la version étudiant pour peut-être proposer des démos aux étudiants. Accessible seulement aux
administrateurs, cette fonctionnalité permet de **basculer d'un rôle à un autre** sans avoir à se déconnecter et se
reconnecter grâce à quelques instructions dans les fichiers de configuration et dans la construction de l'url.

<figure>
<figcaption>Code permettant à un utilisateur de changer de rôle</figcaption>
<img src="/img/easyAdminSwitch.png" alt="aperçu de la bascule de rôle">
</figure>

Dans l'ensemble, cette partie n'a pas représenté une étape très complexe. Ce qui a été plutôt positif puisque ça a calmé
mes doutes quant à la complexité du développement d'un back-office pour une application web de cette ampleur et m'a aidé
à appréhender, de manière plus générale le développement de l'outil avec sérénité.

### Développement général

Une fois le back-office terminé, il était temps de passer à la partie la plus importante du développement : *
*l'application**. C'est la partie qui sera utilisée par les étudiants et les enseignants. Elle permettra aux étudiants
de **créer leur portfolio** et aux enseignants de **suivre les étudiants** et de **valider leurs compétences**.

Seulement, avant de se pencher sur les fonctionnalités dédiées aux étudiants et aux enseignants, il était nécessaire de
**créer un système d'authentification** pour que chaque utilisateur puisse accéder à l'application et à ses
fonctionnalités en fonction de son rôle. Pour cela, j'ai utilisé le **bundle Symfony Security** qui permet de créer un
système d'authentification rapidement et simplement. Il suffit de créer une entité User qui représente les utilisateurs
de l'application et de configurer le bundle pour qu'il puisse gérer les utilisateurs et les rôles. J'ai donc créé une
entité User contenant un champ Role qui permet de définir les rôles des utilisateurs.

<figure>
<figcaption>Déclaration des différents champs dans l'entité Users</figcaption>

```php
#[ORM\Id]
    #[ORM\GeneratedValue]
    #[ORM\Column]
    private ?int $id = null;

    #[ORM\Column(length: 180, unique: true)]
    private ?string $username = null;

    #[ORM\Column]
    private array $roles = ["ROLE_USER"];

    /**
     * @var string The hashed password
     */
    #[ORM\Column]
    private ?string $password = '';

    #[ORM\OneToOne(inversedBy: 'users', cascade: ['persist', 'remove'])]
    private ?Etudiant $etudiant = null;

    #[ORM\OneToOne(inversedBy: 'users', cascade: ['persist', 'remove'])]
    private ?Enseignant $enseignant = null;

    #[ORM\Column(length: 255, nullable: true)]
    private ?string $email = null;

    #[ORM\Column]
    private ?bool $isVerified = false;
```

</figure>

A l'image du back-office, la quasi totalité du code est générée par la saisie de quelques lignes de commande. La
commande ``bin/console make:auth`` a généré le système d'authentification, la
commande ``bin/console make:registration-form`` a généré le formulaire d'inscription et la
commande ``bin/console make:reset-password`` a généré un système de réinitialisation de mot de passe. Seules quelques
modifications ont été nécessaires pour que ces systèmes correspondent à mes besoins les commandes ayant généré toutes
les routes, controller, templates, formulaires et fichiers de configuration. J'ai par exemple dû exploiter une méthode
interne au framework permettant de crypter les mots de passe.

<figure>
<figcaption>Code permettant de crypter les mots de passe</figcaption>

```php
            $plaintextPassword = $user->getPassword();

//             hash the password (based on the security.yaml config for the $user class)
            $hashedPassword = $passwordHasher->hashPassword(
                $user,
                $plaintextPassword
            );
            $user->setPassword($hashedPassword);
```

</figure>

Alors qu'une partie de ma structure devait être synchronisée avec l'Intranet mais que je n'avais pas encore accès aux
données, j'ai développé des **DataFixtures** (*code permettant d'injecter des données dans la base à l'appel d'une
commande*) pour pouvoir tester l'application. J'ai donc créé des utilisateurs fictifs et recréé partiellement la
structure de l'Intranet (departement, groupes, référentiels de compétences...) pour pouvoir tester le système
d'authentification et les différentes fonctionnalités de l'application.

<figure>
<figcaption>Code permettant de créer des utilisateurs fictifs</figcaption>

```php
class UsersFixture extends Fixture implements OrderedFixtureInterface
{
    public function load(ObjectManager $manager
    ): void
    {
        $user2 = new Users();

        $password = $this->encoder->hashPassword($user2, 'test');

        $user2->setUsername('etudiant')
            ->setPassword($password)
            ->setRoles(['ROLE_ETUDIANT', 'ROLE_ADMIN', 'ROLE_TEST'])
            ->setEmail('etudiant@etudiant.univ-reims.fr')
            ->setIsVerified(true);
        $etudiant = new Etudiant();
        $biblio = new Bibliotheque();

        $etudiant->setUsers($user2);

        $etudiant->setNom('Herolt');
        $etudiant->setPrenom('Cyndel');
        $etudiant->setMailPerso('persoEtudiant@mail.com');
        $etudiant->setMailUniv('etudiant@etudiant.univ-reims.fr');
        $etudiant->setTelephone('0103456781');
        $etudiant->setBio('Vestibulum elementum odio lectus, vitae tempor ante viverra non. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Ut scelerisque bibendum ipsum, non tincidunt risus ultrices vel.');
        $etudiant->setUsername('etudiant');

        $biblio->setEtudiant($etudiant);

        $manager->persist($etudiant);
        $manager->persist($biblio);

        $manager->persist($user2);
        $manager->flush();

    }
}
```

</figure>

<figure>
<figcaption>Mail de transmission des données anonymisées de l'Intranet</figcaption>
<iframe src="/files/mailApi.pdf" width="100%" height="480" allowFullScreen></iframe>
</figure>

Ensuite, alors que j'avais bien entamé le développement de l'application, j'ai pu récupérer les données de l'Intranet.
L'objectif ici n'était pas de piocher aveuglément dans la base de données mais plutôt de choisir les données à importer
en fonction des besoins.
Pour y parvenir, j'ai déjà dû importer les données dans ma version locale de l'Intranet afin de pouvoir faire des tests
avant d'accéder aux véritables données en ligne et d'entamer le développement de requêtes API (*code servant à
communiquer entre deux ou plusieurs applications*).

<figure>
<figcaption>Code ajouté dans l'Intranet pour récupérer les données des étudiants dans un tableau JSON en préparation d'une requête</figcaption>

```php
class EtudiantController extends BaseController
{
    #[Route(path: '/api/unifolio/etudiant', name: 'api_etudiant_liste')]
    public function listeEtudiant(
        Request $request,
        EtudiantRepository $etudiantRepository,
    )
    {
        $this->checkAccessApi($request);

        $etudiants = $etudiantRepository->findAll();

        $tabEtudiant = [];

        foreach ($etudiants as $etudiant) {
            $groupes = [];
            foreach ($etudiant->getGroupes() as $groupe) {
                $groupes[] = [
                    'id' => $groupe->getId(),
                    'libelle' => $groupe->getLibelle(),
                ];
            }

            $semestre = $etudiant->getSemestre();
            if (null !== $semestre) {
                $semestre = [
                    'id' => $semestre->getId(),
                    'libelle' => $semestre->getLibelle(),
                ];
            }
            else {
                $semestre = null;
            }

            $tabEtudiant[$etudiant->getId()] = [
                'id' => $etudiant->getId(),
                'nom' => $etudiant->getNom(),
                'prenom' => $etudiant->getPrenom(),
                'username' => $etudiant->getUsername(),
                'mail_univ' => $etudiant->getMailUniv(),
                'mail_perso' => $etudiant->getMailPerso(),
                'telephone' => $etudiant->getTel1(),
                'semestre' => $semestre,
                'groupes' => $groupes,
            ];
        }

        return $this->json($tabEtudiant);
    }

}
```

</figure>

<figure>
<figcaption>Code permettant de récupérer les données des étudiants dans l'application depuis le tableau JSON</figcaption>

```php
class UserSynchro extends AbstractController
{
    #[Route('/api/intranet/etudiant', name: 'app_synchro_intranet_etudiant')]
    public function synchroEtudiant(
        $login,
        $user,
        HttpClientInterface $client,
        EtudiantRepository $etudiantRepository,
        BibliothequeRepository $bibliothequeRepository,
        GroupeRepository $groupeRepository,
        SemestreRepository $semestreRepository,
    )
    {

        $response = $client->request(
            'GET',
            'https://127.0.0.1:8001/fr/api/unifolio/etudiant',
            [
                'headers' => [
                    'Accept' => 'application/json',
                    'Content-Type' => 'application/json',
                    'X_API_KEY' => $this->getParameter('api_key')
                ],
            ]
        );

        $response = $response->toArray();

            if (in_array($login, array_column($response, 'username'))) {
                //Sélectionner l'etudiant dans le tableau
                $etudiant = array_filter($response, function ($etudiant) use ($login) {
                    return $etudiant['username'] === $login;
                });
                foreach ($etudiant as $data) {
                    $semestre = $semestreRepository->findOneBy(['libelle' => $data['semestre']]);
                    // Créer un nouvel etudiant dans la base de données avec les données de $etudiant
                    $newEtudiant = new Etudiant();
                    $newEtudiant->setUsers($user);
                    $biblio = new Bibliotheque();
                    $biblio->setEtudiant($newEtudiant);
                    $newEtudiant->setNom($data['nom']);
                    $newEtudiant->setPrenom($data['prenom']);
                    $newEtudiant->setUsername($data['username']);
                    $newEtudiant->setMailUniv($data['mail_univ']);
                    $newEtudiant->setMailPerso($data['mail_perso']);
                    $newEtudiant->setTelephone($data['telephone']);
                    $newEtudiant->setSemestre($semestre);
//                    dd($data['groupes']);
                    foreach ($data['groupes'] as $groupe) {
                        $groupe = $groupeRepository->findOneBy(['id' => $groupe]);
                        $newEtudiant->addGroupe($groupe);
                    }
                    $etudiantRepository->save($newEtudiant, true);
                    $bibliothequeRepository->save($biblio, true);
                }
                return true;
            } else {
                return false;
            }
        }
}
```

</figure>

Après avoir récupéré l'ensemble des données dont j'avais besoin, je me suis aperçu que cecrtains processus que j'avais
imaginés présentaient des **failles**. Par exemple, je me suis rapidement dit qu'il serait pratique de récupérer les
données d'un utilisateur depuis l'intranet à son inscription dans l'application. Cela implique qu'il devra renseigner un
élément qui lui est propre et qui est stocké dans la base de l'Intranet, son mail universitaire ou son login URCA par
exemple.
Seulement, ça soulève une problématique : la **protection des données**. Les login URCA et les adresses mail
universitaires étant tous construits sur le même modèle, il est possible de récupérer les données de n'importe quel
utilisateur en connaissant son login ou son adresse mail. Il est donc nécessaire de **protéger l'accès à ces données**
en vérifiant que l'utilisateur qui souhaite récupérer les données est bien celui qu'il prétend être. La façon la plus
efficace m'a semblé être celle que l'on rencontre dans la plupart des applications web, la **vérification de compte par
mail**. Ainsi, lorsqu'un utilisateur souhaite récupérer ses données, il doit renseigner son login URCA. L'application
envoie alors un mail à l'adresse renseignée dans la base de l'intranet pour ce login ; contenant un lien qui permettra
de récupérer les données. Ce lien est valable pendant une durée limitée et **ne peut être utilisé qu'une seule fois**.
De plus, il est **généré de façon aléatoire** et est donc impossible à deviner. Ainsi, seul l'utilisateur qui a accès à
l'adresse mail universitaire peut récupérer ses données.

<figure> 
<figcaption>Méthode permettant de récupérer le l'adresse et d'envoyer un mail appelée à la création d'un objet User</figcaption>

```php
    #[Route('/api/intranet/etudiant', name: 'app_email_intranet_etudiant')]
    public function CheckEmailEtudiant(
        $login,
        HttpClientInterface $client,
        MailerService $mailerService,
        VerifyEmailHelperInterface $verifyEmailHelper,
    )
    {

        $response = $client->request(
            'GET',
            'https://127.0.0.1:8001/fr/api/unifolio/etudiant',
            [
                'headers' => [
                    'Accept' => 'application/json',
                    'Content-Type' => 'application/json',
                    'X_API_KEY' => $this->getParameter('api_key')
                ],
            ]
        );

        $response = $response->toArray();

            if (in_array($login, array_column($response, 'username'))) {
                //Sélectionner l'etudiant dans le tableau
                $etudiant = array_filter($response, function ($etudiant) use ($login) {
                    return $etudiant['username'] === $login;
                });
                foreach ($etudiant as $data) {
                    // Créer un nouvel etudiant dans la base de données avec les données de $etudiant
                    $mailEtudiant = $data['mail_univ'];
                    $signatureComponents = $verifyEmailHelper->generateSignature(
                        'app_verify_email',
                        $data['username'],
                        $data['mail_univ'],
                        ['id' => $data['username']]
                    );
                    $mailerService->sendMail($mailEtudiant, 'Vérification de compte UniFolio', 'Afin de vérifier votre compte, merci de cliquer sur le lien suivant : ' . $signatureComponents->getSignedUrl());
                }
                return true;
            }
//            dd($response);
            return false;
    }
```

</figure>

Voila entre autres les problématiques de dev que je qualifierai de **générales** (*qui concernaient aussi bien les
utilisateurs étudiants qu'enseignants*) sur lesquelles j'ai beaucoup appris ; notamment sur la **manipulation de données
** depuis une base de données ou une autre application.

Au delà de l'aspect technique, j'ai aussi appris qu'on pouvait perdre beaucoup de temps si on ne prépare pas
suffisamment son projet en amont. En effet, j'ai perdu du temps à cause de problèmes de **conception**. Par exemple,
j'ai dû revoir en grande partie la structure de l'application et de la base de données car je n'avais pas
scrupuleusement respecté celle de l'intranet qui allait finalement devenir la base de mon application.
Mais j'ai quand même rebondi sur ces problèmes en les considérant comme des **opportunités d'apprentissage** qui me
serviront de leçon pour mes prochains projets.

#### Partie étudiant

Etape cruciale, elle représente un **enjeu majeur** pour le projet. Il est donc important de la **développer avec soin**
et de la **tester rigoureusement**. Heureusement, les étapes préparatoires offraient déjà une bonne base de travail avec
**la définition de la structure générale et du processus**.

La difficulté de cette partie réside dans le nombre important d'**interactions plus ou moins complexes** entre
l'application et l'utilisateur. L'interface se doit alors d'être ergonomique pour que l'utilisateur puisse **comprendre
rapidement** comment utiliser l'outil et **exploiter toutes ses fonctionnalités**. Pour cela, j'ai utilisé le framework
CSS Bootstrap qui permet de créer des interfaces **responsive** et **intuitives**. Il offre également une **grande
variété de composants** qui permettent de créer des interfaces **modernes** et **esthétiques** très rapidement. Par
exemple, la totalité des formulaires de l'application sont générés par Bootstrap, ce qui représente une partie
conséquente de cet espace puisque **toutes les étapes de création d'un portfolio se font via des formulaires**.

<figure>
<figcaption>Aperçu du formulaire de création de trace généré via bootstrap</figcaption>
<img src="" alt="aperçu de la bascule de rôle">
</figure>

Le système de **création de trace**, qui permet d'intégrer des médias de type lien, image, vidéo et pdf m'a apporté l'
opportunité de découvrir le **concept de composant** (*code permettant de lier un objet à un template, ce qui facilite
le rendu et la réutilisabilité de petites "unités" de template*) de Symfony. En effet, j'ai créé un composant qui permet
de générer un formulaire de création de trace en fonction du type de média choisi par l'utilisateur. Ce composant est
ensuite appelé dans le Controller et permet entre autre de générer le formulaire correspondant au média choisi par
l'utilisateur. Cela permet de **simplifier le code** et de rendre le template plus lisible mais aussi de ne pas avoir à
modifier l'ensemble de la structure si un nouveau type de média devait être ajouté plus tard.

<figure>
<figcaption>Aperçu du composant pour les médias de type Image permettant de déclarer des variables et des méthodes propres à ce type de média</figcaption>

```php
<?php

namespace App\Components\Trace\TypeTrace;

use App\Components\Trace\Form\TraceTypeImageType;
use App\Entity\Trace;
use App\Repository\TraceRepository;
use Symfony\Component\DomCrawler\Crawler;

class TraceTypeImage extends AbstractTrace implements TraceInterface
{
final public const TAG_TYPE_TRACE = 'image.s';
final public const FORM = TraceTypeImageType::class;
final public const HELP = 'Upload d\'image - format accepté : jpg, jpeg, png, gif';
final public const ICON = 'fa-solid fa-3x fa-image';
final public const TEMPLATE = 'Components/Trace/type/image.html.twig';

    public function __construct(protected TraceRepository $traceRepository)
    {
        $this->type_trace = 'TraceTypeImage';
    }

    public function display(): string
    {
        return self::TAG_TYPE_TRACE;
    }

    public function getTypeTrace(): ?string
    {
        return $this->type_trace;
    }

    public function save($form, $trace, $traceRepository, $traceRegistry): array
    {
        $max_size = 2 * 1024 * 1024; // 2 Mo en octets
        $imageFiles = $form['contenu']->getData();

        if ($trace->getId() != null) {
            if ($trace->getContenu() != null) {
                $contenu = $trace->getContenu();
            } else {
                $contenu = null;
            }
        }

        if ($imageFiles) {

            foreach ($imageFiles as $imageFile) {
                // Vérifier si la taille de l'image est inférieure ou égale à 2 Mo
                if ($imageFile->getSize() > $max_size) {
                    $error = 'Le fichier doit faire 2mo maximum';
                    return array('success' => false, 'error' => $error);
                }
                $imageFileName = uniqid() . '.' . $imageFile->guessExtension();
                //Vérifier si le fichier est au bon format
                if (in_array($imageFile->guessExtension(), ['jpg', 'jpeg', 'png', 'gif', 'svg', 'webp'])) {
                    //Déplacer le fichier dans le dossier déclaré sous le nom files_directory dans services.yaml
                    $imageFile->move('files_directory', $imageFileName);
                    $contenu[] = 'files_directory' . '/' . $imageFileName;
                } else {
                    $error = 'Le fichier n\'est pas au bon format';
                    return array('success' => false, 'error' => $error);
                }
            }
        }

        $trace->setContenu($contenu);
        $traceRepository->save($trace, true);
        return array('success' => true);
    }

}
```

</figure>

<figure>
   <figcaption>Exemple de l'utilisation d'une variable dans un composant.</figcaption>

<small>Ici la variable ``FORM`` déclarée dans le fichier de composant contient un formulaire propre au type Image et des
formulaires propres aux autres types dans les fichiers des autres types</small>

```php
final public const FORM = TraceTypeImageType::class;
```

<small>Cette variable est ensuite appelée dans le Controller et permet de générer le formulaire correspondant au média
choisi par l'utilisateur, tout ça grâce à cette simple ligne.</small>

```php
$form = $this->createForm($traceType::FORM, $trace, ['user' => $user]);
```

</figure>

Même si il est toujours en cours de développement, ce segment d'UniFolio, par sa complexité et son aspect interactif,
m'a donné l'occasion de **mieux comprendre le fonctionnement de Symfony et du modèle MVC** et d'en explorer les
possibilités. J'ai également pu **approfondir mes connaissances Javascript** en l'utilisant pour la gestion de quelques
formulaires complexes (*Collection Type*). Certaines problématiques comme la gestion des types de traces se sont
révélées plus difficultueuses que ce que j'avais imaginé.

#### Partie enseignant

Etape la plus **abstraite** du projet et dont je commence tout juste le développement, la partie enseignant est la plus difficile à conceptualiser. Il faut définir une **approche pédagogique** et appliquer un **système de gestion des groupes et des compétences** afin que chaque enseignant soit en mesure de savoir quelles sont ses missions et leurs limites.

Nous sommes donc partis du principe qu'un enseignant a une spécialité propre au département dans lequel il enseigne et qu'il doit donc être en mesure d'**évaluer les compétences** de cette spécialité. Cependant, il peut également être amené à évaluer des compétences d'autres spécialités, c'est pourquoi nous avons décidé de lui donner la possibilité de **choisir les compétences qu'il souhaite évaluer** en offrant une interface permissive sur laquelle un enseignant aura accès à toutes les compétences de tous les étudiants de son département. 

La majeure partie du travail à venir relèvera de la conceptualisation en parallèle du développement de fonctionnalités telles que l'**évaluation des compétences** et apprentissages critiques (*qui se fera de manière ternaire : acquis, en cours, non acquis*) mais aussi de proposer un système de **retours pédagogiques**, des commentaires permettant par exemple d'orienter l'étudiant sur des pistes d'amélioration.

<figure>
    <figcaption>Dessin de l'interface de commentaires de Traces</figcaption>
    <img src="/img/dessin.png">
</figure>

Pour l'instant, je développe le tableau de bord de l'utilisateur enseignant qui lui permettra de visualiser les portfolios de ses étudiants et d'en évaluer les compétences. A l'image de l'Intranet, l'application est formalisée en fonction du département de l'enseignant, mais puisque certains enseignants travaillent dans plusieurs départements il est nécessaire de donner la possibilité de **choisir son département**.

<figure>

<figcaption>Méthode permettant de changer de département</figcaption>

```php
 #[Route(path: '/choix-departement', name: 'app_choix_departement')]
    public function choixDepartement(
        Request                         $request,
        EnseignantDepartementRepository $enseignantDepartementRepository,
        EnseignantRepository            $enseignantRepository,
        RequestStack                    $session,
        EntityManagerInterface          $entityManager,
    )
    {
//        dd('hello');
        $user = $this->getUser();
        $enseignant = $enseignantRepository->findOneBy(['username' => $user->getUsername()]);
        if (!$enseignant) {
            return $this->redirectToRoute('app_login', ['message' => 'Vous devez être intervenant ou enseignant pour accéder à cette page.']);
        }

        $departements = $enseignantDepartementRepository->findByEnseignant($enseignant);
        $update = null;
        // si le formulaire est envoyé
        if ('POST' === $request->getMethod()) {
            $update = $enseignantDepartementRepository->findOneBy(['enseignant' => $enseignant, 'defaut' => true]);
            // Si aucun departement est Defaut = true on set Defaut à true pour le departement sélectionné
            if (null === $update) {
                $update = $enseignantDepartementRepository->findOneBy(['enseignant' => $enseignant, 'departement' => $request->request->get('departement')]);
                $update->setDefaut(true);
                $this->redirectToRoute('app_dashboard');
                $entityManager->flush();
            } else {
                // Si un departement est Defaut = true on set Defaut à false pour ce département et on set Defaut à true pour le departement sélectionné
//                dd($update);
                $update->setDefaut(false);
// On set Defaut à true pour le departement sélectionné
                $update = $enseignantDepartementRepository->findOneBy(['enseignant' => $enseignant, 'departement' => $request->request->get('departement')]);
//                dd($update);
                $update->setDefaut(true);
                $this->redirectToRoute('app_dashboard');
                $entityManager->flush();
            }

            if (null !== $update && null !== $update->getDepartement()) {
                $this->addFlash('success', 'Formation par défaut sauvegardée');
                $session->getSession()->set('departement', $update->getDepartement()); // on sauvegarde

                return $this->redirectToRoute('app_accueil');
            }

        }
        return $this->render('security/choix-departement.html.twig',
            ['departements' => $departements, 'user' => $user]);
    }
```

</figure>
<figure>

<figcaption>Vue relative à la méthode</figcaption>

```TWIG
 <div class="row dept_infos">
    <div class="col-3">
        <p>Département {{ data_user.departement.libelle }}</p>

        {% if data_user.allDepartementsEnseignant|length > 1 %}

            <form action="{{ path('app_choix_departement') }}" method="post" class="dept_list">
                <div class="dropdown">
                    <button type="submit" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
                        <i class="fa-solid fa-shuffle"></i>
                    </button>
                    <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                        {% for departement in data_user.allDepartementsEnseignant %}
                            <li>
                                <input type="submit"
                                       class="btn-check dropdown-item"
                                       name="departement"
                                       value="{{ departement.id }}"
                                       id="departement_{{ departement.id }}"
                                       autocomplete="off">
                                <label for="departement_{{ departement.id }}">
                                    {{ departement.libelle }}
                                </label>
                            </li>
                            <hr>
                        {% endfor %}
                    </ul>
                </div>
            </form>

        {% endif %}
    </div>
    <div class="col-2">
    </div>
</div>
```

</figure>

Sur ce tableau de bord, l'enseignant aura accès à une liste de ses étudiants et pourra consulter leurs portfolios. Aux vues du nombre important de groupes et d'étudiants dans un département, il est nécessaire de **filtrer les étudiants** par semestre et par groupe. Pour y parvenir j'ai exploité le composant NavTabs de Bootstrap qui permet de mettre en place un système d'onglets internes. Je récupère les données de l'enseignant que j'ai préalablement stockées dans la session grâce à un ensemble de méthodes et je les utilise pour filtrer les étudiants.

<figure>

<figcaption>Extrait de la Vue permettant de filtrer les étudiants de première année</figcaption>

```TWIG
<div class="tab-content active" id="myTabContent">
    <div class="tab-pane fade show active" id="but1" role="tabpanel" aria-labelledby="but1-tab">
        <ul class="nav nav-tabs" id="semestre1Tab" role="tablist">
            {% for semestre in data_user.semestresActifs|filter(semestre => semestre.annee.ordre == 1) %}
                <li class="nav-item" role="presentation">
                    <button class="nav-link{% if loop.first %} show active {% endif %}"
                            id="typeGroupe1{{ loop.index }}-tab"
                            data-bs-toggle="tab" data-bs-target="#typeGroupe1{{ loop.index }}" type="button"
                            role="tab"
                            aria-controls="typeGroupe1{{ loop.index }}"
                            aria-selected="{% if loop.first %}true{% else %}false{% endif %}">
                        {{ semestre.libelle }}
                    </button>
                </li>

            {% endfor %}
        </ul>

        <div class="tab-content" id="typeGroupe1Content">
            {% for semestre in data_user.semestresActifs|filter(semestre => semestre.annee.ordre == 1) %}
                <div class="tab-pane fade{% if loop.first %} show active{% endif %}" id="typeGroupe1{{ loop.index }}"
                     role="tabpanel" aria-labelledby="typeGroupe1{{ loop.index }}-tab">
                    <ul class="nav nav-tabs" id="groupe1Tab{{ loop.index }}" role="tablist">
                        {% for typeGroupe in semestre.typeGroupes %}
                            <li class="nav-item" role="presentation">
                                <button class="nav-link{% if loop.first %} show active{% endif %}"
                                        id="groupe1{{ loop.index }}-{{ typeGroupe.id }}-tab"
                                        data-bs-toggle="tab"
                                        data-bs-target="#groupe1{{ loop.index }}-{{ typeGroupe.id }}-content"
                                        type="button" role="tab"
                                        aria-controls="groupe1{{ loop.index }}-{{ typeGroupe.id }}-content"
                                        aria-selected="{% if loop.first %}true{% else %}false{% endif %}">
                                    {{ typeGroupe.libelle }}
                                </button>
                            </li>
                        {% endfor %}
                    </ul>

                    <div class="tab-content" id="groupe1Content{{ loop.index }}">
                        {% for typeGroupe in semestre.typeGroupes %}
                            <div class="tab-pane fade{% if loop.first %} show active{% endif %}"
                                 id="groupe1{{ loop.index }}-{{ typeGroupe.id }}-content" role="tabpanel"
                                 aria-labelledby="groupe1{{ loop.index }}-{{ typeGroupe.id }}-tab">
                                <ul class="nav nav-tabs" id="groupe1Tab{{ loop.index }}-{{ typeGroupe.id }}"
                                    role="tablist">
                                    {% for groupe in typeGroupe.groupes %}
                                        <li class="nav-item" role="presentation">
                                            <button class="nav-link{% if loop.first %} show active{% endif %}"
                                                    id="groupe1{{ loop.index }}-{{ typeGroupe.id }}-{{ loop.index }}-tab"
                                                    data-bs-toggle="tab"
                                                    data-bs-target="#groupe1{{ loop.index }}-{{ typeGroupe.id }}-{{ loop.index }}-content"
                                                    type="button" role="tab"
                                                    aria-controls="groupe1{{ loop.index }}-{{ typeGroupe.id }}-{{ loop.index }}-content"
                                                    aria-selected="{% if loop.first %}true{% else %}false{% endif %}">
                                                {{ groupe.libelle }}
                                            </button>
                                        </li>
                                    {% endfor %}
                                </ul>

                                <div class="tab-content"
                                     id="groupe1Content{{ loop.index }}-{{ typeGroupe.id }}">
                                    {% for groupe in typeGroupe.groupes %}
                                        <div class="tab-pane fade{% if loop.first %} show active{% endif %}"
                                             id="groupe1{{ loop.index }}-{{ typeGroupe.id }}-{{ loop.index }}-content"
                                             role="tabpanel"
                                             aria-labelledby="groupe1{{ loop.index }}-{{ typeGroupe.id }}-{{ loop.index }}-tab">
                                            <table>
                                                <thead>
                                                <tr>
                                                    <th>Nom de l'étudiant.e</th>
                                                    <th>Groupe</th>
                                                    <th>Dernier retour pédagogique</th>
                                                    <th>Traces</th>
                                                    <th>Portfolios</th>
                                                </tr>
                                                </thead>
                                                <tbody>
                                                {% for etudiant in groupe.etudiants %}
                                                    <tr>
                                                        <td>{{ etudiant.prenom }} {{ etudiant.nom }}</td>
                                                        <td>{{ groupe.libelle }}</td>
                                                        <td>retours pédagogiques</td>
                                                        <td>liens vers les traces de l'étudiant</td>
                                                        <td>
                                                            <a href="{{ path('app_vue_portfolio', {'id': etudiant.id}) }}">bibliothèque
                                                                de portfolios</a></td>
                                                    </tr>
                                                {% endfor %}
                                                </tbody>
                                            </table>
                                        </div>
                                    {% endfor %}
                                </div>
                            </div>
                        {% endfor %}
                    </div>
                </div>
            {% endfor %}
        </div>
    </div>
```

</figure>

J'ai aussi pu découvrir le système de session de Symfony qui permet de stocker des données en mémoire pendant une durée déterminée (*ici tant que l'utilisateur est connecté*). Le développement de la gestion de session impliquait la rédaction d'un certain nombre de requête DQL (Doctrine Query Language) qui permettent de récupérer des données dans la base de données de manière très précise. J'ai donc pu approfondir mes connaissances sur ce langage de requête et simplifier l'appel des données dans les vues.

<figure>

<figcaption>Exemple de requêtes DQL pour la gestion des données des groupes d'étudiants</figcaption>

```php
    public function findByDepartementBuilder(Departement $departement): QueryBuilder
    {
        return $this->createQueryBuilder('g')
        // seuls ceux qui ont une correspondance entre les colonnes 'type_groupe' de la table "Groupe" et 'id' de la table "TypeGroupe" seront inclus dans les résultats
            ->innerJoin(TypeGroupe::class, 't', 'WITH', 'g.type_groupe = t.id')
            ->innerJoin('t.semestre', 's')
            ->innerJoin(Annee::class, 'a', 'WITH', 'a.id = s.annee')
            ->innerJoin(Diplome::class, 'd', 'WITH', 'd.id = a.diplome')
            ->where('d.departement = :departement')
            ->setParameter('departement', $departement->getId());
    }

    public function findByDepartementSemestreActifBuilder(Departement $departement): QueryBuilder
    {
        return $this->createQueryBuilder('g')
            ->innerJoin(TypeGroupe::class, 't', 'WITH', 'g.type_groupe = t.id')
            ->innerJoin('t.semestre', 's')
            ->innerJoin(Annee::class, 'a', 'WITH', 'a.id = s.annee')
            ->innerJoin(Diplome::class, 'd', 'WITH', 'd.id = a.diplome')
            ->where('d.departement = :departement')
            ->andWhere('s.actif = 1')
            ->setParameter('departement', $departement->getId());
    }

    public function findByDepartementSemestreActif(Departement $departement): array
    {
        return $this->findByDepartementSemestreActifBuilder($departement)
            ->getQuery()
            ->getResult();
    }
    public function findByTypeGroupe(?TypeGroupe $typegroupe): array
    {
        return $this->createQueryBuilder('g')
            ->where('g.type_groupe = :type_groupe')
            ->orderBy('g.ordre', Criteria::ASC)
            ->setParameter('type_groupe', $typegroupe)
            ->getQuery()
            ->getResult();
    }

    public function findGroupesEtudiant($etudiant): array
    {
        return $this->createQueryBuilder('g')
            ->innerJoin('g.etudiants', 'e')
            ->where('e.id = :etudiant')
            ->setParameter('etudiant', $etudiant)
            ->getQuery()
            ->getResult();
    }
```

</figure>

Cette partie de l'application étant celle sur laquelle j'ai le moins réfléchi en amont, j'ai dû faire face à un certain nombre de **problèmes de conception**. En effet, j'ai dû modifier plusieurs fois la structure de la base de données pour pouvoir répondre aux besoins de l'application. J'ai également dû modifier la structure des entités ; ces modifications ont été assez longues à mettre en place et à optimiser. C'est là que je me suis rendu compte de **l'importance de la phase de conception** dans le développement d'une application et que j'ai réalisé que j'allais devoir **mettre à plat un modèle** avant d'entamer le développement des fonctionnalités pour **plus d'efficacité et moins de contre-productivité**.


### Retour d'expérience

Une organisation plutôt erratique, un investissement personnel très important, des doutes, des remises en question, des
victoires et surtout la culture de la confiance en soi et la confirmation d'un engouement certain pour le développement
back-end !
Consciente que le projet n'est pas parfait et que le code pourrait être grandement optimisé, je suis tout de même très
fière de ce que j'ai pu accomplir et de la qualité du résultat actuel. J'ai pu mettre en pratique mes connaissances
mais surtout en acquérir de nouvelles, découvrir de nouveaux concepts et apprendre de mes erreurs .

## Compétences mises en oeuvre
