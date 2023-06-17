---
title: "Intranet"
date: 2023-04-06
categories: [ "Développer une application Web interactive", "Comprendre la stratégie de communication et l’expérience utilisateur" ]
lead: "Dans une démarche d'optimisation de l'intranet de l'IUT, j'entretiens une réflexion globale sur les problématiques d'ergonomie et d'accessibilité et entame la refonte de certains éléments."
description: "Découverte d'un code complexe et dense. Sensibilisation aux problématiques d'ergonomie et d'accessibilité des sites web."
placeholder: "assets/logo.png"
tags: [
  "AC21.03 | Traiter des données avec des outils statistiques pour faciliter leur analyse et leur exploitation",
  "AC21.04 | Identifier et décrire les parcours client à partir d’enquêtes de terrain", 
  "AC21.05 | Cartographier les expériences utilisateur : points de contact, points de friction et de satisfaction, carte d’empathie.",
  "AC22.02 | Produire une recommandation ergonomique à partir des tests utilisateurs (sur système fonctionnel, prototype ou maquette interactive)",
  "AC22.03 | Co-construire une recommandation stratégique (en structurant un plan d’action)",
  "AC24.03 | Intégrer, produire ou développer des interactions riches ou des dispositifs interactifs",
  "AC24.01 | Produire des pages et applications Web responsives",
  "AC25.04 | Collaborer au sein des organisations",
]
#draft: true
---

## Présentation du projet

L'idée ici était de réaliser un **audit** rapide de l'Intranet afin de faire ressortir les **potentielles faiblesses**,
de
proposer des **pistes d'amélioration** et de travailler sur les **problèmes existants** déjà identifiés en **priorisant
les
problématiques d'accessibilité et d'ergonomie**.

### Objectifs

- Identifier les problèmes d'ergonomie et d'accessibilité de l'Intranet
- Proposer des pistes d'amélioration
- Réaliser une refonte de certains éléments

### Méthodologie et organisation

La refonte partielle de l'Intranet est un projet qui doit m'accompagner tout au long de mon alternance en parallèle des
autres projets. **J'y travaille donc de manière ponctuelle**, lorsque du temps se libère sur mes périodes de cours ou
d'entreprise. Comme ce n'est pas un projet prioritaire, il est difficile de planifier mes actions dessus ce qui fait que
j'ai tendance à tort, à laisser traîner ce projet.

### Technologies utilisées

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

### Etapes

1. **Refonte du formulaire de stage** *(division du formulaire en plusieurs étapes et amélioration de l'ergonomie et de
   l'accessibilité)*
2. **Enquête de satisfaction** *(étudiants, enseignants, personnels)*
3. **Documentation de l'Intranet** *(Création d'un nouveau site de documentation)*
4. **Refonte de l'interface d'administration** *(amélioration de l'ergonomie et de l'accessibilité)*

## Réalisation du projet

### Refonte du formulaire de stage

La saisie des informations de stage par les étudiants se faisait via **un formulaire fastidieux, peu ergonomique** et il
n'y
avait **pas de vérification des données saisies**, ce qui entraînait de nombreuses erreurs. L'objectif était donc de
rendre ce formulaire plus ergonomique et plus accessible en le divisant en plusieurs étapes et en ajoutant des
vérifications
des données saisies (aussi bien côté serveur que côté utilisateur). J'avais le choix entre reprendre le formulaire
existant et lui apporter les modifications nécessaires ou bien le recréer entièrement. J'ai choisi la deuxième option
car le code du formulaire existant était complexe et le comprendre et le modifier correctement m'aurait pris plus de
temps que de repartir de zéro ; de plus, je pense que c'était la meilleure solution pour **comprendre le fonctionnement
des formulaires sous Symfony**.

<figure style="height: 500px; overflow-y: scroll">
   <figcaption>Exemple d'un formulaire similaire</figcaption>
   <img src="/img/intranet_stage_form_old.png" alt="Exemple d'un formulaire similaire à la version initiale">
</figure>

La première étape consistait à réaliser une **maquette Figma** du formulaire afin de pouvoir visualiser les différentes
étapes du
processus pour une **validation par mon tuteur**. J'ai construit cette maquette dans **le respect du design actuel de l'
Intranet**, en exploitant notamment certains éléments du template de thème qui lui est
appliqué (<a href="http://thetheme.io/theadmin/uikit/progress-process.html" target="_blank">UiKit thème</a>) comme par
exemple la barre de progression qui permet à l'utilisateur de se repérer dans le processus et qui est *un impératif d'
ergonomie** lors de la réalisation d'un **processus complexe** comme ce
formulaire (<a href="https://checklists.opquast.com/fr/assurance-qualite-web/les-processus-complexes-sont-accompagnes-de-la-liste-de-leurs-etapes" target="_blank">
règle 85</a>
et <a href="https://checklists.opquast.com/fr/assurance-qualite-web/letape-en-cours-dun-processus-complexe-est-indiquee" target="_blank">
règle 86</a> de la <a href="https://checklists.opquast.com/fr/assurance-qualite-web/" target="_blank">Checklist
Opquast</a>).

<figure>
    <figcaption>Maquette du formulaire</figcaption>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2Fir0N88DBXFe9uf9tnTV4pj%2Fintranet%3Ftype%3Ddesign%26node-id%3D0%253A1%26t%3Deswc8HbFiMSKQT9D-1" allowfullscreen></iframe>
</figure>

La problématique de **vérification des données saisies** a été partiellement résolue en
utilisant <a href="" target="_blank">Stimulus</a>, un framework JavaScript adapté à Symfony. J'ai utilisé ce framework
pour gérer l'affichage d'un modal qui récupère les informations saisies par l'utilisateur pour une relecture. Ce modal
est affiché à la fin de chaque étape du processus et permet à l'utilisateur de vérifier les informations saisies et de
les modifier si besoin. Même si l'utilisateur doit valider les informations pour passer à l'étape suivante, elles ont
déjà été envoyées en base de données afin de **ne pas perdre les données saisies** en cas de fermeture du navigateur ou
de
perte de connexion.

<figure> 
   <figcaption>Modal de vérification post étape</figcaption>
   <img src="/img/intranet_stage_modal.png" alt="">
</figure>

D'autres vérification ont été ajoutées **côté serveur**, notamment pour vérifier que les dates saisies sont cohérentes (
date
de début de stage antérieure à la date de fin de stage, date de début de stage postérieure à la date de début de stage,
etc.) et pour vérifier que les dates saisies ne sont pas antérieures à la date du jour. Mêlant **JavaScript et PHP**,
ces
vérifications permettent également de calculer le nombre de jours ouvrés de stages en fonction des dates saisies par
l'utilisateur et la complétion automatique de certains champs comme la gratification.

<figure> 
   <figcaption>Méthode de calcul des jours de stages selon les dates sélectionnées en PHP</figcaption>

   ```php
   public function calculJoursDeStage(Request $request): Response
    {
        $tab = json_decode($request->getContent(), true);
        $date_debut = Carbon::createFromFormat('d/m/Y', $tab['date1']); // new \DateTime($tab['date1']);
        $date_fin = Carbon::createFromFormat('d/m/Y', $tab['date2']); // new \DateTime($tab['date2']);
        $interval = $date_debut->diff($date_fin);

        $interval = $interval->format('%y') * 365 + $interval->format('%m') * 30 + $interval->format('%d');

        $annee1 = $date_debut->format('Y');
        $annee2 = $date_fin->format('Y');

        $tab = [];
        for ($i = $annee1; $i <= $annee2; ++$i) {
            $easter = easter_date($annee1, CAL_FRENCH); // paque (dimanche)
            $easterDay = (int) date('d', $easter);
            $easterMonth = (int) date('m', $easter);
            $easterYear = (int) date('Y', $easter);

            $lundiPaque = mktime(0, 0, 0, $easterMonth, $easterDay + 1, $easterYear);
            $jeudiAscension = mktime(0, 0, 0, $easterMonth, $easterDay + 39, $easterYear);
            $lundiPentecote = mktime(0, 0, 0, $easterMonth, $easterDay + 50, $easterYear);

            $tabJoursFeries = [
                $i.'-11-01', // toussaints
                $i.'-11-11', // armistice
                $i.'-12-25', // noel
                $i.'-01-01', // jour de l'an
                $i.'-05-01', // fete du travail
                $i.'-05-08', // victoire
                $i.'-07-14', // fete nationale
                $i.'-08-15', // assomption
                date('Y-m-d', $easter), // dimanche de pâque
                date('Y-m-d', $lundiPaque), // lundi de pâque
                date('Y-m-d', $jeudiAscension), // jeudi ascension
                date('Y-m-d', $lundiPentecote), // lundi de pentecote
            ];
            $tab[] = $tabJoursFeries;
        }
        $tabFeries = array_merge(...$tab);

        while ($date_debut <= $date_fin) {
            if (in_array($date_debut->format('Y-m-d'), $tabFeries, true)) {
                --$interval;
            } elseif ('Saturday' == $date_debut->format('l') || 'Sunday' == $date_debut->format('l')) {
                --$interval;
            }
            $date_debut->add(new \DateInterval('P1D'));
        }

        return $this->json(['duree' => $interval]);
    }
   ```

</figure>

<figure>
   <figcaption>Complétion des champs de jours de stage et de gratification en JavaScript</figcaption>

```js
window.addEventListener('load', () => {

    //------------------------------------------------------------------------------
    //-----------------------CALC NBR JOURS-----------------------------------------

    document.getElementById('form_type_stage_date_fin_stage').addEventListener('change', calcJours)
    document.getElementById('form_type_stage_date_debut_stage').addEventListener('change', calcJours)

    let gratificationOui = document.getElementById('form_type_stage_gratification_0')
    let gratificationNon = document.getElementById('form_type_stage_gratification_1')
    gratificationOui.addEventListener('click', () => {
        document.getElementById(('gratif_opt1')).style.display = 'block'
        document.getElementById(('gratif_opt2')).style.display = 'block'
    })
    gratificationNon.addEventListener('click', () => {
        document.getElementById('gratif_opt1').style.display = 'none'

        document.getElementById('gratif_opt2').style.display = 'none'
    })

    function calcJours(e) {
        let dateDebutStage = document.getElementById('form_type_stage_date_debut_stage').value
        let dateFinStage = document.getElementById('form_type_stage_date_fin_stage').value

        fetch('{{ path('calendar') }}', {
            method: 'Post',
            body: JSON.stringify({date1: dateDebutStage, date2: dateFinStage}),
        }
    )
    .
        then((data) => {
            return data.json()
        })
            .then((data) => {
                document.getElementById('form_type_stage_duree_jours_stage').value = data.duree
            })
            .then(() => {
                //---------------------------------------------GRATIFOBLIGATOIRE---------------------------------------------
                // -----------------------------------------------------------------------------------------------------------
                let interval = document.getElementById('form_type_stage_duree_jours_stage')
                let gratification = document.getElementById('form_type_stage_gratification')

                if (interval.value >= 40) {
                    gratificationOui.checked = true
                    document.getElementById(('gratif_opt1')).style.display = 'block'
                    document.getElementById(('gratif_opt2')).style.display = 'block'
                    document.getElementById(('gratif')).style.display = 'block'
                    document.querySelector('.form-check:nth-child(1)').style.display = 'block'
                    document.querySelector('.form-check:nth-child(2)').style.display = 'none'
                } else {
                    // gratification.value = 'non'
                    gratificationNon.checked = true
                    document.getElementById('form_type_stage_gratification_periode_2').value = ''
                    document.getElementById('form_type_stage_gratification_periode_1').value = ''
                    document.getElementById('form_type_stage_gratification_periode_0').value = ''

                    document.getElementById('form_type_stage_gratification_montant').value = 0
                    document.getElementById(('gratif_opt1')).style.display = 'none'
                    document.getElementById(('gratif_opt2')).style.display = 'none'
                    document.getElementById(('gratif')).style.display = 'block'
                    document.querySelector('.form-check:nth-child(1)').style.display = 'block'
                    document.querySelector('.form-check:nth-child(2)').style.display = 'block'
                }
            })
    }
})
```

</figure>

Après avoir **testé mon code** et constaté qu'il fonctionnait, j'ai fait une **pull request** sur le dépôt de
l'application pour
que mon code y soit intégré. Une fois **mis en production**, les étudiants ont pu saisir leurs informations de stage
plus
facilement et il semblerait que pour la première fois depuis plusieurs années, **il n'y ait pas eu de problème majeur
qui
soit remonté**. Un rapide retour de mon tuteur sur ce code m'a permis de savoir qu'il était bon et qu'**aucune
modification
n'a dû être apportée**. J'ai cependant omis de rendre la page responsive comme demandé, mais cela n'a pas posé de
problème
car l'utilisation de Bootstrap pour la génération des champs de formulaire le rend utilisable sur téléphone, **une
optimisation de cet aspect sera malgré tout nécessaire dans un futur proche**.

### Enquête de satisfaction

Afin de pouvoir **évaluer la qualité de l'Intranet** et **cibler les points à améliorer**, , j'ai mis en place une *
*enquête de satisfaction** à l'aide de la solution GoogleForm. J'ai d'abord **créé un questionnaire** avec les questions
que je souhaitais poser aux utilisateurs de manière générales puis proposé une ou deux questions spécifiques aux
étudiants, aux enseignants et aux personnels administratif. Pour m'assurer de couvrir tous les aspects de l'utilisation
de l'Intranet, j'ai **organisé le questionnaire en catégories** (Utilisation générale, Accessibilité, Navigation,
Fonctionnalités, Design, Assistance).

<figure> 
   <figcaption>Document de travail</figcaption>
<iframe src="/files/enquete.pdf" width="100%" height="480" frameBorder="0" scrolling="yes" allowFullScreen></iframe>
</figure>

La diffusion du formulaire s'est faite par **mail**, j'ai rédigé le contenu du mail et mon tuteur s'est chargé de le
transmettre à l'ensemble des cibles. J'ai ensuite **analysé les résultats** et **réalisé un rapport** pour présenter les
résultats de l'enquête. J'ai pu constater que **l'Intranet était globalement bien perçu** par les utilisateurs, mais que
**certains points de faiblesses** apparaissaient dans les réponses de manière récurrente (responsive, temps de
chargement ...) et **certains besoins en fonctionnalités** étaient également demandés (cahier de texte, forum, lien
crous...).

La **réalisation de cette enquête** m'a permis de **mieux comprendre les besoins des utilisateurs** et de **cibler les
points à améliorer**. J'ai également pu **m'exercer à la rédaction d'un questionnaire** et à l'analyse des résultats. La
prochaine étape consiste à classer les besoins en fonctionnalités par ordre de priorité et à **définir un planning de
développement** à long terme et de **réaliser un audit de qualité et d'accessibilité** pour mettre à niveau l'intranet
sur ces problématiques.

<figure> 
   <figcaption>Checklist Opquast integrée au document de travail pour l'audit</figcaption>
<iframe src="/files/checklist_notion.pdf" width="100%" height="480" frameBorder="0" scrolling="yes" allowFullScreen></iframe>
</figure>

### Documentation de l'Intranet

L'idée de ce projet était de **revoir et améliorer la mise en page du site de documentation de l'Intranet**. C'est un
recueil de tutoriels et de documentations sur l'utilisation de l'Intranet qui permet d'accompagner l'utilisateur dans
des processus plus ou moins complexes. Initialement développé à l'aide de la
solution <a href="https://gohugo.io" target="_blank">Hugo</a>, l'ancien site prenait une forme assez similaire à un
GitBook. Il était composé d'une barre de navigation latérale et d'un contenu principal. La navigation dans le site se
faisait en cliquant sur les liens de la barre latérale qui redirigeaient vers les différentes pages, sur lesquelles ont
pouvait trouver pour certaines, **des screenshots accompagnés d'explications ou directement des vidéos tutoriel**.

Derrière cette idée se dégageait également la possibilité de proposer en parallèle **un site vitrine de l'Intranet** qui
permettrait de présenter les différentes fonctionnalités et mettre en avant les nouveautés. Mais aussi de proposer **une
documentation pour l'installation** de l'Intranet en local, ce qui permettrait aux universités qui le souhaitent de
pouvoir l'installer et le tester **en vue d'une éventuelle adoption**.

<figure> 
   <figcaption>Message de précision du périmètre du projet</figcaption>
   <img src="/img/discord_doc_intranet1.png" alt="Message de précision du périmètre du projet">
</figure>

Comme pour les autres projets, j'ai commencé par faire une **maquette du site à l'aide de Figma**. Je trouvais la
version actuelle plutôt réussie ce qui a rendu l'élaboration de la maquette compliquée... En effet, quitte à refaire un
site, autant proposer quelque chose de vraiment différent, **qui apporte une réelle plus-value**. En parcourant le site
d'origine, j'ai remarqué qu'on gagnerait en ergonomie à **organiser, classifier plus précisément son contenu**. Pendant
que je réfléchissais à cette problématique, j'ai commencé la maquette par la "page vitrine" qui devait regrouper les
informations principales sur l'Intranet. Au delà d'un espace "nouveautés", j'ai pensé qu'il serait intéressant de
proposer un espace qui regrouperait l'ensemble des fonctionnalités, le tout classé en fonction du rôle de
l'utilisateur (une section étudiant, une enseignant et une administration).

<figure>
   <figcaption>Vestiges de la maquette</figcaption>
   <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2Fir0N88DBXFe9uf9tnTV4pj%2Fintranet%3Ftype%3Ddesign%26node-id%3D228%253A12%26t%3Deswc8HbFiMSKQT9D-1" allowfullscreen></iframe>
</figure>

A tort, j'ai rapidement **abandonné la maquette** pour découvrir l'outil de développement que j'allais utiliser pour le
site : <a href="https://cecil.app" target="_blank">Cecil.app</a>. **Construit en PHP sur une base Symfony**, Cecil
propose une syntaxe qui commençait à m'être familière, notamment grâce à l'utilisation de **TWIG** dans les templates.
Cependant, à l'inverse d'un projet en Symfony, il n'y a pas de Controller pour définir et manipuler les données ; **des
variables sont automatiquement définies dans les templates en fonction de la structure du site**. Par exemple, pour la
page d'accueil, la variable `site.pages` contient l'ensemble des pages du site, et il est possible de filtrer ces pages
en fonction de leur section (étudiants, enseignants, administration, etc.) définines dans le front-matter (ensemble de
variables définies au début d'une page en Markdown et délimitées par les symboles `---`) pour les afficher dans des
blocs dédiés.

<figure> 
   <figcaption>Snippet de code de la page d'accueil du site</figcaption>

```twig
  <div>
      <i class="fa-solid fa-graduation-cap fa-xl"></i>
      <h5>Etudiants</h5>
      <ul>
         {%- for themes in site.pages|filter_by('section', 'etudiants')|sort_by_weight ~%}
            <li>
               <a href="/{{ themes.path }}">{{ themes.title }}</a>
            </li>
         {% endfor %}
      </ul>
  </div>
```

</figure>

Le plus intéressant dans cet outil est qu'il permet de générer un site statique à partir de fichiers Markdown. Cela
permet de **simplifier la gestion du contenu** et de **faciliter la contribution**. Il suffit de créer un fichier
Markdown dans le dossier correspondant pour que le contenu soit généré automatiquement. De plus, Cecil propose un
système de thèmes qui permet de **personnaliser facilement l'apparence du site** ; mais Cecil reste un petit outil et *
*les thèmes disponibles sont assez limités**. J'ai donc décidé de partir du thème de base et de le modifier au fur et à
mesure pour qu'il corresponde à mes attentes. J'ai ensuite **adapté le contenu** du site à la nouvelle structure "au fil
de l'eau" puisque je n'avais pas vraiment fait de maquette. Un fois toutes les rubriques créée, nous avons mis en place
un système de recherche pour faciliter la navigation dans le site en
utilisant <a href="https://www.algolia.com" target="_blank">Algolia</a>.

<figure> 
   <figcaption>Page d'accueil du site</figcaption>
   <img src="/img/intranet_documentation.png" alt="">
</figure>

Même si il est aujourd'hui <a href="https://documentation.iutranet.fr" target="_blank">en ligne ici</a>, cette
réalisation est une déception pour moi. En effet, je n'ai pas réussi à **proposer une réelle plus-value** par rapport à
la version actuelle. J'ai passé du temps à **chercher une solution pour organiser le contenu** mais je n'ai pas réussi à
en trouver une satisfaisante. Le visuel du site ne me convient pas non plus, je le trouve lourd, peu lisible et mal
équilibré. Je pense que j'aurais dû passer plus de temps sur la maquette pour la terminer plutôt que de passer
directement au développement. Cela m'aurait permis de **mieux cerner les problématiques** et de **proposer une solution
plus adaptée**. De ce fait, plutôt que d'alimenter cette version, je préfèrerais **repartir de zéro** pour proposer une
version plus aboutie.

### Refonte de l'interface d'administration

Un des **grands axes de refonte de l'Intranet** concernait la partie Administration. Lors d'une réunion avec certains
utilisateurs, j'ai pu constater que l'interface d'administration posait parfois des soucis, notamment dans sa *
*hiérarchie** puisque certains témoignaient de difficultés à trouver les rubriques qu'ils cherchaient ; faiblesse que
j'ai moi-même identifiée en découvrant l'interface (un visuel lourd).

<figure>
        <figcaption>Ancienne version</figcaption>
        <img src="/img/intranet_admin_bfore.png" alt="ancienne version de la page d'administration"> 
</figure>

Avant de me lancer dans la refonte de cette interface, j'ai **réalisé une maquette** pour présenter ma proposition à mon tuteur afin d'obtenir son feu-vert. 

J'ai donc commencé par définir **les objectifs** de cette refonte :
- **Simplifier la navigation** en proposant une interface plus légère et plus claire
- **Hierarchiser les rubriques** pour faciliter la recherche
- **Proposer une interface responsive** pour faciliter la navigation sur mobile

J'ai ensuite défini **les contraintes** :
- **Utiliser le framework Bootstrap** pour faciliter le développement
- **Conserver les fonctionnalités actuelles et dans les grandes lignes la structure** pour ne pas déstabiliser les utilisateurs

Les éléments `button` présents sur la version de base ont été remplacés par des liens pour **alléger l'interface**. J'ai également décidé d'intégrer des icônes pour **faciliter le repérage** dans les rubriques et de développer l'organisation de la rubrique "Etudiants" en différenciant la gestion des étudiants de FI et de FC **afin que l'utilisateur accède plus rapidement à la fonctionnalité qu'il cherche**.

<figure>
        <figcaption>Maquette de la nouvelle version</figcaption>
        <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2Fir0N88DBXFe9uf9tnTV4pj%2Fintranet%3Ftype%3Ddesign%26node-id%3D336%253A673%26t%3DtQxJZFWuj7yKcUyz-1" allowfullscreen></iframe>
</figure>

Une fois la maquette validée, j'ai pu **développer la nouvelle interface**. Ici rien de compliqué puisque la structure de la page était déjà construite ; les blocs sont des composants `card` de Bootstrap donc aucun css n'était nécessaire et l'aspect responsive de la page est également géré par Bootstrap et son système de ``container``,``row`` et ``col``. Il a donc suffit de transformer les éléments `button` en liens et d'ajouter les icônes.

*J'ai quand même ajouté quelques entrées dans certains blocs mais il suffisait alors d'ajouter le lien menant à la bonne page*

<figure>
        <figcaption>Code de la Vue du premier bloc "Etudiants"</figcaption>

```TWIG
<div class="col-md-12 col-lg-12  col-sm-12">
    <div class="card administration">
        <header class="card-header">
            <h2 class="card-title">{{ 'adm.etudiants'|trans }}</h2>
        </header>
        <div class="card-body">
            {{ render_esi(controller(
                'App\\Controller\\administration\\AbsenceController::listeTempsReel'
            )) }}
            <div class="row">
                <div class="col-lg-3 col-10 d-grid d-block mb-2 etudiant_bloc">
                    <div class="admin_links_bloc_header">
                        <i class="fa-solid fa-user-graduate fa-2x"></i>
                        <h4>Formation Continue</h4>
                        <small>Gestion des absences, des notes, des étudiants, des fins de semestres,
                            des alternances et des PPN</small>
                    </div>
                    <hr>
                    {% for semestre in user_data.semestres|filter(semestre => semestre.actif == true) %}
                        {% if semestre.annee.optAlternance == true %}
                            <a href="{{ path('administration_semestre_index', {'semestre': semestre.id } ) }}">{{ semestre.displayAvecTypeDiplome }}</a>
                        {% endif %}
                    {% endfor %}
                </div>
                <div class="col-lg-3 col-10 d-grid d-block mb-2 etudiant_bloc">
                    <div class="admin_links_bloc_header">
                        <i class="fa-solid fa-user-graduate fa-2x"></i>
                        <h4>Formation Initiale</h4>
                        <small>Gestion des absences, des notes, des étudiants, des fins de semestres, des stages</small>
                    </div>
                    <hr>
                    {% for semestre in user_data.semestres|filter(semestre => semestre.actif == true) %}
                        {% if semestre.annee.optAlternance == false %}
                            <a href="{{ path('administration_semestre_index', {'semestre': semestre.id } ) }}">{{ semestre.displayAvecTypeDiplome }}</a>
                        {% endif %}
                    {% endfor %}
                </div>
                <div class="col-lg-3 col-10 d-grid d-block mb-2 etudiant_bloc">
                    <div class="admin_links_bloc_header">
                        <i class="fa-solid fa-users fa-2x"></i>
                        <h4>Général</h4>
                        <small>Gestion des différents semestres</small>
                    </div>
                    <hr>
                    <a href="{{ path('administration_etudiant_index') }}">Tous les étudiants</a>
                    <a href="{{ path('administration_cohorte_index') }}">Cohortes</a>
                    <a href="{{ path('administration_statistique_index') }}">Statistiques</a>
                    <a href="{{ path('administration_sous_commission_mise_a_jour') }}">Mise à jour d’une
                        sous-commission</a>
                    <a href="{{ path('administration_etudiant_semestre_add') }}" methods="_POST">Ajouter des
                        étudiants</a>
                </div>
            </div>
        </div>
    </div>
</div>
```

</figure>

<div style="display: flex; height: 600px">
<figure  style="width: 50%; height: 100%; overflow-y: scroll;">
        <figcaption>Version mobile integrée</figcaption>
        <img src="/img/intranet_admin_mobile.png" alt="version mobile"> 
</figure>
<figure style="width: 50%; height: 100%; overflow-y: scroll;">
        <figcaption>Version desktop integrée</figcaption>
        <img src="/img/intranet_admin_after.png" alt="version desktop">
</figure>
</div>

<br>
<br>

### Retour d'expérience

Ce projet a été l'occasion d'apprendre à **découvrir, modifier et exploiter un code complexe existant** et de **travailler en équipe sur un projet de grande envergure**. J'ai également pu découvrir encore plus le framework Symfony et ses composants. Travailler sur l'Intranet m'a aussi permis de découvrir le fonctionnement d'un établissement d'enseignement supérieur et de **comprendre les enjeux de la gestion des données** tout en **collaborant avec les différents acteurs** de l'établissement puisque je reçois souvent des demandes et des suggestions de la part des enseignants, personnels administratifs et étudiants. Ça a très certainement participé à mon intégration dans l'équipe.

## Compétences mises en oeuvre
