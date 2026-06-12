---
type: slide
title: L'imposture du Logiciel Libre / Aleks / JDLL 2026
slideOptions:
    backgroundTransition: 'none'
---

<style>
    a { font-weight: bold; color: #1c4ee1 !important; }
    img { border: none !important; box-shadow: none !important; background: none !important; }
    small { vertical-align: unset !important; }
    .reveal, #doc section {
        font-family: "Source Sans Pro", "Gotham", Open Sans, Helvetica, sans-serif !important;
        background-color: #fafafa !important;
        color: #333;
        position: unset;
    }
    #doc {
        max-width: unset;
        margin: 0;
        padding-left: calc(50% - 600px);
        line-height: normal;
        width: 95%;
        text-align: left !important;
    }
    #doc section {
        font-size: 1.2em;
        width: 1200px;
        height: 630px;
        text-align: left;
        inset: unset !important;
        transform: unset !important;
        text-align: left !important;
        padding-top: 1em !important;
    }
    .reveal {
        padding-left: 1em;
        padding-right: 1em;
        padding-top: 0.5em;
        padding-bottom: 0.5em;
        font-size: 2.4em;
    }
    section {
        top: unset !important;
    }
    section::before { display: none !important; }
    #doc section div {
        padding: 0 1em;
        position: relative;
        top: 0;
        left: 0;
        right: 0;
        transform: none !important;
    }
    .reveal h1, .reveal h2, .reveal h3, .reveal h4, .reveal h5, .reveal h6, #doc h1, #doc h2, #doc h3, #doc h4, #doc h5, #doc h6 {
        color: #333;
        font-weight: bold;
        font-family: "LIBERTARIO", "Gotham", Open Sans, Helvetica, sans-serif !important;
        margin: 0.2em;
    }
    .reveal h2, #doc h2 {
        color: dodgerblue;
    }
    .reveal section > div { position: relative; }
    .slides {
        width: 95% !important;
        text-align: left !important;
        inset: unset !important;
        transform: unset !important;
    }
    #doc p { margin: 20px 0 !important; line-height: 1.3 !important; }
    #doc li + li { margin-top: 0; }
    .slide-number > a { color: white !important; font-weight: bold !important; }
</style>

<center>
<h1 style="margin-top: 0.5em; line-height: 1.1em; font-size: 3.5em;">L'imposture du<br/>logiciel libre</h1>

<br/>

<div style="font-size: 1.2em;">
<p>
<em>a.k.a : Le logiciel libre est-il libéral ou libertaire ?</em>

<em>a.k.a : Le logiciel libre qui cache la forêt de l'émancipation numérique</em>

<em>a.k.a : Logiciel libre partout, liberté nulle part</em>

<em>a.k.a : JPP des gens qui prennent le logiciel libre comme une finalité en soi,<br/>bordel de merde, on défend quoi politiquement en vrai ?</em>
</p>
</div>

<br/>

<h2 style="color: #333; text-align: center;">Aleks / JDLL 2026</h2>
<h3>URL des slides : <a href="https://link.infini.fr/imposture">link.infini.fr/imposture</a></h3>
</center>

---

## Pourquoi cette conférence

- **Profonde exaspération des trucs centrés sur le logiciel libre, et de l'absence de formulation politique**
    - Déjà dénoncé depuis au moins 8-10 ans, plutôt avec des pincettes
    - par ex. Pyg @ RMLL 2018, *Peut-on faire du libre sans vision politique ?*
    - et pleins d'autres
- Titre 100% premier degré, expect spice
- **Secouer le cocotier consensuel** : non, le libre c'est pas un truc qui va révolutionner la société
- Nouvelle mouture d'une conf "beta" en octobre 2023 devant des non-technicien·nes @ Coopaname

<br/>
<br/>
<br/>
<br/>

- Je pars du principe que vous êtes sensibilisé·e aux enjeux
- ... et que vous pensez (ou pas ?) que le libre c'est fondamentalement politique
- **Non, mon propos n'est pas de dire qu'il faut arrêter le logiciel libre, mais qu'il faut aller au-delà**

---

## À propos de moi

<center>
    <img src="https://md.globenet.org/uploads/9ecf9821-a945-4212-8a84-128cfa90f235.png" style="width: 12em;"/>
    <img src="https://md.globenet.org/uploads/246f74ab-55f8-4024-92e3-6d14a46a47f4.png" style="height: 7em;"/>
    <img src="https://md.globenet.org/uploads/3c39b5df-1f5a-4ddf-8bdb-a48ddb29514f.png" style="height: 7em;"/>
    <img src="https://md.globenet.org/uploads/07eaa1fc-589a-48b5-af57-e2e0cf6c1ee9.png" style="height: 7em;"/>
    <img src="https://md.globenet.org/uploads/3cd069c9-8e0a-436c-b5f2-22b999b4e884.png" style="height: 7em;"/>
</center>

- Aleks, il/lui
- Mec blanc cisgenre hétéro ingénieur trentenaire
- Informaticien dans une coopérative parisienne, [Coopaname](https://coopaname.coop)
- Contrib/mainteneur du projet [YunoHost](https://yunohost.org) (distribution Linux pour gérer facilement <small>(dans l'idéal)</small> des services numériques)
- Membre de [Hackstub](https://hackstub.eu) (hackerspace @ Strasbourg) et [Alsace Réseau Neutre](https://arn-fai.net) / [Sans-nuage](https://)
- J'aime les stickers, les memes et les opossums
- Autoradicalisé par les débats à l'A.N sur la Hadopi autour de 18 ans
- Anciennement turbo-libriste




---

## Les 4 libertés


<div style="display: flex; margin: auto; width: 90%;">
    <div>
        <img src="https://md.globenet.org/uploads/bcfccd8e-d976-412a-ad27-9b28d96246e6.png" style="height: 10em; padding-right: 1em;" />
    </div>
    <div>
    <center>
        <img src="https://md.globenet.org/uploads/416db157-1a89-4292-97a4-d40a13244117.png"  style="width: 12em; padding-bottom: 1em;" />
    </center>
    <ol start="0" style="padding-right: 30px;">
        <li>la liberté d'<strong>utiliser</strong> le programme, pour n'importe quel usage ;</li>
        <li>la liberté d'<strong>étudier</strong> le fonctionnement du programme ;</li>
        <li>la liberté de <strong>redistribuer</strong> des copies du programme ;</li>
        <li>la liberté d'<strong>améliorer</strong> le programme et de distribuer ces améliorations.</li>
    </ol>
    </div>
    <div>
        <img src="https://md.globenet.org/uploads/dcdbbc12-f8f9-49c9-9ce8-8d7b8e96012a.png"  style="height: 10em;" />
    </div>
</div>

<br/>
<br/>

- Émerge dans les années 80-90 : à l'époque, **si on a un ordi, on \*est\* développeur·euse**
- **"Hack juridique"** : retourne la propriété intellectuelle contre elle-même dans l'espoir de créer un genre de "commun"
- En pratique, formalisé dans des licences (GPL, MIT, BSD, Apache, ...) adopté par les auteurices
- **Binaire** : si ça respecte ces 4 libertés, c'est libre, donc c'est éthique, Bien™ (sinon → c'est propriétaire, donc c'est Mal™)

<center style="padding-top: 1em;">
    <strong>→ Mais est-ce que les gens se tournent vers le libre vraiment pour "les 4 libertés" ?</strong>
</center>

---

## Logiciel libre : pillier de l'alternumérisme

<table style="width: 100%; text-align: center;">
<tr>
<td style="width: 50%; text-align: center; border: none;"><strong style="background-color: #ddd; padding: 0.5em;">Ce que les gens viennent chercher dans le libre</strong></td>
<td style="width: 50%; text-align: center; border: none;"><strong style="background-color: #ddd; padding: 0.5em;">L'intention, l'ambition politique (?)</strong></td>
</tr>
<tr>
<td style="width: 50%; text-align: center; border: none;">
Un alternumérisme<br/>
Une informatique qui se fout pas de leur gueule,<br/>qui déclenche pas une mise à jour au moment d'éteindre l'ordi,<br/>prolonger la vie d'un laptop,<br/> gratuit, qui "redonne du contrôle", "éthique", "respectueuse"...
</td>
<td style="width: 50%; text-align: center; border: none;">
<img src="https://md.globenet.org/uploads/a5dd12e8-86aa-47c7-8412-2cdeed17054a.jpeg" style="height: 9em;" />
<img src="https://md.globenet.org/uploads/d8717aed-c192-4865-a17f-1aacffb73297.jpg" style="height: 9em;" />
<img src="https://md.globenet.org/uploads/574d7dc3-8bfe-4f3b-b7bb-3a819cc04c8b.png" style="height: 7em;" />
<br/>
"Libriste", "Communs", JDLL, RMLL, CdL, FOSDEM, ...
</td>
</tr>
<tr>
<td style="width: 50%; text-align: center; border: none;"><strong style="background-color: #ddd; padding: 0.5em;">Ce qu'on planque sous le tapis</strong></td>
<td style="width: 50%; text-align: center; border: none; "><strong style="background-color: #ddd; padding: 0.5em;">Ce que le logiciel libre *est vraiment*</strong></td>
</tr>
<tr>
<td  style="width: 50%; text-align: center;">
<center style="padding-bottom: 0.2"><strong>
Rien dans le logiciel libre<br/>ne garantie une quelconque "éthique" ou émancipation
</strong></center>
<ul>
<li>Si "tu sais pas coder", une seule liberté te concerne : utiliser</li>
<li><a href="https://linuxfr.org/news/les-drones-de-combat-americains-basculent-sous-linux">Drones américains sous Linux</a>, contrôle social, ... ?</li>
<li>GAFAMs construits grâce au logiciel libre</li>
<li>Rien n'empêche de coder des fonctionnalités toxiques</li>
<li>Accessibilité à chier ? (cf <a href="https://cstrobbe.gitlab.io/Liberte0/">collectif Liberté 0</a>)</li>
<li>Auto-exploitation, dictateurs-bénévoles</li>
<li>« Si t'aimes pas, t'as qu'à contribuer ou forker »</li>
</ul>
</td>
<td style="width: 50%; text-align: center;"><img src="https://md.globenet.org/uploads/589a3da6-dd33-4a52-a296-b13e7742151b.png" style="height: 13em;" />
</td>
</tr>
</table>

---

## Le logiciel libre : bon OK

Très simple à mettre en place, "low-friction"

Transparence du code
  - → tout le monde peut auditer le code → sécurité
  - → si y'a un truc malveillant, ça va finir par se voir

~Gratuité

On peut <small>(si on a les moyens)</small> forker pour s'affranchir d'un éditeur qui part en vrille ou met la clef sous la porte
  - → ~indépendance
  - → ~pérennité

---

## L'open source : « libre » c'était déjà trop de politique ?

<center style="padding-top: 1em;">
    <img src="https://md.globenet.org/uploads/3ee70359-aea0-497a-b114-44d6c27fff23.jpeg" style="height: 9em;" />
    <img src="https://md.globenet.org/uploads/ce241c85-4275-4ab0-9142-c52d1e8723f4.png" style="height: 9em; padding-left: 1em;" />
</center>

Réapropriation aseptisée par les acteurs économiques
- aussi parce que "free" software laissait trop penser que c'est gratuit = ça incite pas trop les clients à payer
- mais confusion source "disponibles" vs sources "ouvertes à la contribution"
- open-washing : c'est à la mode, ça sonne comme éthique mais sans trop se mouiller

<br/>
<br/>

<center>

Juridiquement : **pas de différence entre libre et open source**

Philosophiquement : **Libre = Open source + ✨ Des Valeurs ✨** <span style="color: red; font-weight: bold;">(= ??? mais lesquelles ???)</span>

Un projet sous licence AGPL qui fait la promotion d'idées catho-réactionnaire, c'est libre ou pas ?
</center>

---

## Le modèle économique impossible ?

<center>
 <img src="https://md.globenet.org/uploads/40b2dca0-e7ed-40cc-abd5-8f60deaa1993.png" style="height: 9em;" />
</center>

- **Fonctionnalités payantes** (« open core ») : trucs pas libres → sourcils froncés des libristes

- **Vente de service** : "les gros payent" pour du support ou du dev, mais applicable seulement pour certains projets

- **Mécénat** : perte d'indépendance

- **Dons / subventions** : demande pas mal d'énergie, logique "projet" alors que le plus gros du taf, c'est la maintenance

- **Auto-exploitation** (a.k.a bénévolat) : applicable aux petits projets, bombe à retardement
   - [des tonnes de logiciels sont maintenus par une poignée de personne, voir une seule personne, ... voir *zéro*](https://framatube.org/w/8uNwWJqPe4yKqnYKibD6JB?start=10m55s)
   - [**`xz-utils`**, catastrophe évitée de justesse](https://www.youtube.com/watch?v=aoag03mSuXQ) -> un dev tout seul, sous l'eau et harcelé par les issues
   - [**`python-requests`**, ou le logiciel libre comme piège-tremplin pour personne bipolaire](https://kennethreitz.org/essays/2026-03-18-open_source_gave_me_everything_until_i_had_nothing_left_to_give)

---

## Logiciel libre partout, GAFAM partout

<div style="display: flex;">
<div style="width: 75%; margin: auto;">
   <img src="https://md.globenet.org/uploads/ab824220-e553-4983-ad9a-f2f7c87f7251.png" width="100%"/>
</div>
<div>
    <br/><br/>
    <div><strong>Différentes typologies</strong></div>
        <ul>
    <li>logiciels "grand publics" / connus</li>
    <li>logiciels niches</li>
    <li>système d'exploitation (distros linux)</li>
    <li>briques (librairies)</li>
    <li>langages de programmation</li>
    <li>formats, protocoles</li>
</ul>
<br/>
<br/>
<strong>Les GAFAMs utilisent aussi des logiciels libres</strong>

On pourrait presque dire que leur empire <br/>s'est construit *grâce* au logiciels libres ...
</div>
</div>

---

## 2007 : le tournant

- Premiers smartphones, Android développé par Google (libre/open source, basé sur Linux !)
- Montée de Facebook, des plateformes en ligne, du "cloud", <strong style="text-decoration-line: underline; text-decoration-thickness: 5px;">grâce au libre/open source</strong>

<br/>
<br/>

<center>
→ <strong>émergence du capitalisme de surveillance, hégémonie des GAFAMs, ...</strong>
<br/><br/>
<img src="https://md.globenet.org/uploads/78562462-889a-4ca6-a233-7dd4fdb1ebb4.jpeg" style="height: 12em;" />
<img src="https://md.globenet.org/uploads/60f8601f-9684-449b-9d03-fea8eef727c7.jpeg" style="height: 12em;" />
<img src="https://md.globenet.org/uploads/916a090d-5c1b-4e19-ab4e-f992129227f2.png" style="height: 12em;" />
<br/><br/>
→ Changement des "règles du jeu" : <strong>de moins en moins de programmes tournent "sur nos machines"</strong>
<br/>
→ <strong>Peu importe si ils sont libres ou non ? À quel point peut-on faire confiance aux tiers ... <br/>Qui gère les services ? Qu'advient-il des données, etc ...</strong>
</center>

---

## 2014 : même Microsoft fini par faire copain

<center>
<img src="https://md.globenet.org/uploads/8cec61aa-0462-4695-86ac-9f9171c5ce0f.png" style="height: 20em;" />

<img src="https://md.globenet.org/uploads/8b110815-1fc3-4667-a611-970415a7205f.jpeg" style="height: 20em;" />

<br/>

→ <strong style="padding-top: 1em; text-decoration-line: underline; text-decoration-thickness: 5px;">Le logiciel libre n'est plus une menace, c'est une ressource pour le capital, c'est le <em>status quo</em></strong>
</center>



---

## 202x : le libre continue d'être phagocyté par les GAFAMs

- **Google, sponsor numéro 1 du FOSDEM** (plus grosse conférence sur le Libre/Open Source en Europe)

<center>
    <img src="https://md.globenet.org/uploads/b67f2da5-dd81-4e0d-859a-7d3c7e792d06.png" style="height: 25em;"  />

<strong>Logiciel libre partout, libertés numériques nulle part ?</strong>
</center>

---

## 202x : le libre continue d'être phagocyté par les GAFAMs

- **[Chromium](https://fr.wikipedia.org/wiki/Chromium)/Chrome et [Android](https://fr.wikipedia.org/wiki/Android) sont des logiciels libres, pierres angulaires de l'empire Google**

<center>
    <img src="https://md.globenet.org/uploads/282e5e32-adf1-4af2-ad7b-2056ef8a9e81.png" style="height: 6em;" />
</center>


- **Firefox est financé [à 90% par Google](https://fr.wikipedia.org/wiki/Mozilla_Firefox#Partenariats_et_d%C3%A9pendance_%C3%A0_Google)**
    - ?!?!?
    - Un logiciel « libre » ? Les devs de Mozilla sont-iels « libres » de coder n'importe quel fonctionnalité ?
    - Pourtant un enjeu énorme en terme d'évolution des règles/fonctionnement du web

- **Amazon qui abuse de MongoDB sans contribuer en retour** ([1](https://techcrunch.com/2019/01/09/aws-gives-open-source-the-middle-finger/), [2](https://mjtsai.com/blog/2019/01/14/aws-mongodb-and-the-economic-realities-of-open-source/))
    - Planche à billet pour Amazon sous forme de SaaS
    - MongoDB et Elasticsearch contre-attaquent en créant [la license SSPL](https://en.wikipedia.org/wiki/Server_Side_Public_License) (Server-Side Public License, un genre de AGPL hardcore)
    - ... pas considérée comme libre
    - → échec et mat, **soit le grand capital exploite "les communs", soit restreindre l'usage (liberté 0) = ÇéPaLibre™**

- **Microsoft entraîne son IA sur les bases de code hébergées sur GitHub** ...

---

## L'enlisement dogmatique : l'épisode de la charte CHATONS


<center>
<img src="https://md.globenet.org/uploads/81f85f68-3b2a-4d9a-a66e-d155f0b1a882.png"  style="height: 15em;" />
    <div style="width: 150px; display: inline-block;"> </div>
<img src="https://md.globenet.org/uploads/2ff7e9b9-1c09-4485-b2eb-dd98a03526a2.png" style="height: 15em;" />
</center>

<center style="padding-top: 0.5em;"><strong>
    Zone grise : recréer de l'interopérabilité peut nécessiter <span style="text-decoration-line: underline; text-decoration-thickness: 5px;"> des briques propriétaires</span> !! ... ??
</strong></center>

**Schisme**
- **Librisme puriste dogmatique** : <strong>\*100%\*</strong> de libre et puis c'est tout, quitte à exclure des usages, des cas légitimes, des collectifs ...
- **Informatique émancipatrice** : logiciel libre ni suffisant, (ni nécessaire?), à équilibrer avec le pragmastisme et la finalité, approche plus générale ...

<center style="padding-top: 0.5em;"><strong>
→ 3~6 mois d'énergie bénévole engloutie, le collectif CHATONS qualifié de "propriétaire", ça a pris des proportions dingues ...
</strong></center>

---

## Le logiciel libre : une lutte obsolète

- Le logiciel libre a été inventé **il y a 40 ans**
- Pas vraiment de remise en cause ou d'évolution depuis, malgré le zbeul des 20 dernières années

<br/>
<br/>
<center style="font-size: 1.2em;">
    <strong>En réalité, <span style="text-decoration-line: underline; text-decoration-thickness: 5px;">si demain le code de Facebook ou Twitter était publié sous licence libre</span></strong><br/>
    <strong><span style="text-decoration-line: underline; text-decoration-thickness: 5px;">grosso-modo ça ne change rien aux enjeux de société</span></strong>
</center>
<br/>

- **Gouvernance** : c'est Facebook / Twitter qui choisi comment évolue son code / les "règles du jeu".
    - Fais une PR si tu veux, elle sera pas intégrée
- **Effet réseau** : tu peux forker / monter ton propre Facebook si tu veux, y'aura personne dessus
- **Centralisation, monétisation de la vie privée, surveillance généralisée** : si c'est centralisé et que ça grossit, ça finira par être corrompu par l'argent et le pouvoir
- **Impunité** : code ouvert ou pas, on sait que les GAFAMs ne sont pas en danger malgré tous les scandales déguelasses
- ...

<br/>
<br/>
<center style="font-size: 1.2em;">
   <strong style="text-decoration-line: underline; text-decoration-thickness: 5px;">Chrome(ium) et Android sont libres, ça n'enlève pas de pouvoir à Google, au contraire</strong><br/>
    <strong>Certains outils / briques libres viennent de Meta ou Twitter : Bootstrap, React, Docusaurus, ...</strong>
<br/>
</center>


---

<br/>
<center>
    <h2>« Free Software, Free Society », vraiment mec ?</h2>
</center>


<div style="width: 80%; margin: auto; border-left: 10px solid lightgrey; padding-left: 10px; ">
    <em>
Radier des chômeurs avec des e-mails envoyés sur Thunderbird, refuser un traitement avec un classeur LibreOffice Calc, ça n’améliore rien.

Que notre police raciste tue sans forme de procès puis saisisse son rapport sous Linux ne la rendra pas moins raciste.

La vidéosurveillance ne me rendra pas la vie plus douce si je sais que tout est sauvegardé sur un serveur auto-hébergé et regardé sur VLC installé sur Manjaro.

Dans une société raciste, capitaliste, sexiste et réactionnaire sur tous les domaines, tout reste pourri et amer, même s’il y a Tux sur le fond d’écran. Elon Musk vous paraîtrait-il plus sympathique s’il était un fervent admirateur des licences GPL ? Quid de <a href="https://www.portail-ie.fr/univers/blockchain-data-et-ia/2024/grok-1-lia-open-source-delon-musk-alimentee-par-x/">son IA Open Source</a>?
    </em>
</div>

<center>
(copypasta de <a href="https://blog.cyphergoat.net/blog/a-quoi-servent-les-libristes/">À quoi servent les libristes -- Cyphergoat.net</a>)
</center>

<br/>

<center>
<em>« Oui non mais c'est parce que le logiciel libre est <strong>neutre,</strong><br/>
    on peut pas restreindre l'usage, c'est une pente glissante ! »</em>

→ Ok mec, perso j'ai pas envie de rester neutre face au bruit des bottes.
**Dans un an on peut avoir l'ED au pouvoir et toi tu ... installes Coreboot et organise des TupperVim ?**
</center>


---

<center>
    <h2>L'imposture du logiciel libre</h2>
</center>

<center>
<img src="https://md.globenet.org/uploads/b20395a9-9723-42d6-bbd5-46fb9b445c90.gif" style="height: 12em;"  />
    <div style="width: 50px; display: inline-block;"></div>
<img src="https://md.globenet.org/uploads/455ba080-8fb3-427f-85bc-6126cb80062e.png" style="height: 12em;" />
<br/>
<img src="https://md.globenet.org/uploads/90bac76c-6400-4a6d-9214-e97429744130.jpg" style="height: 10em;"/>
<img src="https://md.globenet.org/uploads/f1146fb2-bff0-46b2-b20b-c759906f1429.jpg" style="height: 10em;" />
<br/>

<strong>More like « Free Software, Free Les Ingés de la Silicon Valley », amirite?</strong>

</center>

---

<center>
    <h2>Le logiciel libre est une lutte obsolète,</br>
    et pourtant cache la forêt de l'émancipation numérique</h2>


 <img src="https://md.globenet.org/uploads/6ea6e724-84bd-4dd7-8ea4-614feba6c345.png" style="height: 25em;" />
</center>

---

<center>
    <h1 style="font-size: 3em; width: 75%; margin-top: 2.5em;">Qu'est-ce qu'on<br/>défend<br/><span style="text-decoration-line: underline; text-decoration-thickness: 10px;">vraiment</span> ?</h1>
</center>

---

## Qu'est-ce qu'on défend vraiment ?

<br/>
<center>
<strong>Si le logiciel libre est juste une facette d'une lutte plus large,
    <br/>
    comment la définir ?</strong>
</center>
<br/><br/>

<div style="display: flex;" >
    <div style="width: 50%; padding: 0 70px;">
        <ul>
            <li>Décentralisation d'internet</li>
            <li>Chiffrement bout en bout</li>
            <li>Respect de la vie privée</li>
            <li>Gouvernances horizontales</li>
            <li>FAI associatifs</li>
            <li>Dénoncer la technopolice, PRISM/5EYES ...</li>
            <li>Interopérabilité</li>
            <li>Transparence de la technique</li>
            <li>Accessibilité, inclusivité</li>
            <li>Sobriété technologique, anti-obsolecence</li>
            <li>Consentement</li>
            <li>...</li>
        </ul>
    </div>
    <div style="width: 40%; border-left: 10px solid darkgrey; text-align: center;">
        <br/>
        <br/>
        <br/>
        <strong>→ Quel dénominateur commun ?</strong>
    </div>
</div>

---

## Qu'est-ce qu'on défend vraiment ?

<br/>
<center>
<strong>Si le logiciel libre est juste une facette d'une lutte plus large,
    <br/>
    comment la définir ?</strong>
</center>
<br/><br/>

<div style="display: flex;" >
    <div style="width: 50%; padding: 0 70px;">
        <ul>
            <li>Décentralisation d'internet</li>
            <li>Chiffrement bout en bout</li>
            <li>Respect de la vie privée</li>
            <li>Gouvernances horizontales</li>
            <li>FAI associatifs</li>
            <li>Dénoncer la technopolice, PRISM/5EYES ...</li>
            <li>Interopérabilité</li>
            <li>Transparence de la technique</li>
            <li>Accessibilité, inclusivité</li>
            <li>Sobriété technologique, anti-obsolecence</li>
            <li>Consentement</li>
            <li>...</li>
        </ul>
    </div>
    <div style="width: 40%; border-left: 10px solid darkgrey; text-align: center;">
        <br/>
        <br/>
        <br/>
        <strong>→ Quel dénominateur commun ?
        <br/><br/>
        Lutter contre les rapports de domination
        <br/>
        véhiculés par la technologie / les outils
        <br/>
        <br/>
        L'émancipation,<br/>l'horizontalité, l'auto-détermination</strong>
    </div>
</div>

<br/>
<center>
    <strong>Dis-donc ça ressemble furieusement à la définition de "libertaire" ou "anarchisme"</strong>
</center>


---

## Le cyber-anarchisme

(Non l'anarchisme c'est pas le chaos ni poser des bombes dans le métro, merci CNews et BFMTV...)

Wikipédia :
<div style="padding-left: 15px; border-left: 15px solid grey; width: 85%; margin: auto;">
    Le projet <strong>libertaire</strong> ou <strong>anarchiste</strong> a pour but de développer <strong>une société sans domination et sans exploitation, où les individus-producteurs s'associent et coopèrent librement dans une dynamique d'autogestion, de fédéralisme et de liberté politique</strong> par la démocratie directe organisée autour du mandatement impératif.
</div>

Appliqué à l'informatique, au numérique, aux technologies, ça donne :
<center>

(Le télé-communisme ? le techno-libertarisme ?)

<h4>
    le cyber-anarchisme, voire même ✨ le cyber-LGBTQIACABnarchisme ✨
</h4>


<img src="https://md.globenet.org/uploads/ed91a340-cdbd-4c59-9b7a-7c4f1114ab22.jpg" style="height: 8em;" />
<span style="width: 50px; display: inline-block;"></span>
<img src="https://md.globenet.org/uploads/b1fd12ad-0801-4523-b51e-f6a7a6461d5c.jpg" style="height: 8em;" />

<h5>
La critique des rapports de pouvoir véhiculés par la technologie / les outils,<br/>
la réappropriation, l'émancipation, la construction d'outils au travers de dynamiques horizontales...
</h5>


</center>


---

<br/>
<br/>
<center style="font-size: 1.2em;">
    <h2>
        Étape 1
    </h2>
<strong>Renommer les JDLL en</strong>
<br/>

✨ Journées de l'Émancipation Technologique et De l'Anarcho-Informatique-Libertaire ✨

<h3>(JÉTD'AIL)</h3>


ou bien

✨ Congrès de l'Informatique Anarchiste ✨

<h3>(CIA)</h3>


ou bien

✨ Congrès du Numérique et de l'Informatique Libertaire ✨

<h3>(CNIL)</h3>

</center>

---

## Converger avec les autres luttes

## Y'a milles trucs à apprendre avec les autres camarades

- Comment créer des espaces inclusifs (IRL ou online)
- Techniques d'éduc pop
- Méthodes d'accueil, d'animation, d'organisation de communauté, intelligence collective
- Savoir prendre soin des collectifs
- Savoir communiquer avec le public
- Enjeux écologiques
- Théories politiques
- Comprendre de quoi les gens ont vraiment besoin en terme d'outils ou fonctionnalité, sur le terrain
- Comprendre en quoi les outils qui existent n'y répondent pas
- ...

<center>
Voir aussi : <a href="http://www.cooperations.infini.fr/spip.php?article11428">Dépasser le fonctionnement en silo : la "tragédie du LSD", Libre, Solidaire et Durable</a>
<br/>
<img src="https://md.globenet.org/uploads/58fbfd3b-1513-45f3-95ec-33a92d6205f0.jpeg" style="height: 9em;" />
</center>

---

## Fuck le mépris techno-solutioniste

L'émancipation numérique est **une question systémique**, bien au dela des aspects purement "logiciels" ou "techniques" ...

- *« Les gens sont cons d'utiliser Whatapp alors que y'a Signal »*
  - Oui bah en fait, quitter Whatsapp ça peut vouloir dire se couper de sa famille. Se couper de sa famille, ça rend libre ?

<br/>

- *« LoL t'utilises Google/Windaube/un Mac, c'est pas bien »*
  - Oui bah, en fait, si c'était facile de quitter une hégémonie, le problème n'existerais pas

<center style="padding: 30px 0;">
<img src="https://md.globenet.org/uploads/403497b8-caa4-48a9-9051-e1c13d1c6f56.jpg" style="height: 12em;"/>
</center>

<center>
<strong>
On émancipera personne à grand coup d'injonctions techno-solutionistes culpabilisantes.

C'est juste une manière de faire l'autruche sur tout un pan du problème, et se placer au dessus des autres.
</strong>
</center>

---

## Lutter, c'est collectif

<center>
<img src="https://md.globenet.org/uploads/3c82c63c-fa6a-4539-badb-bf757d19054c.png" style="height: 2em;" />
</center>

- « Moi j'auto-héberge mes mails »
    - Génial, mais si tout le reste de la société utilise GMail, Google aura quand même tes e-mails

- « T'as qu'à faire pareil, il suffit d'utiliser Docker, c'est facile »
    - En fait, non, c'est pas facile, t'es juste un mec blanc ingénieur auto-didacte qui baigne dans l'informatique

- « Le gouvernement censure mais moi je sais utiliser un VPN et changer mes DNS »
    - Tant mieux pour toi, quid des 99.99% restant de la population ?

<br/><br/>

<center><strong>
Si seulement toi et tes potes ingénieurs savent s'émanciper,<br/>
c'est pas de l'émancipation,<br/>
c'est juste de la techno-branlette entre privilégiés
</strong></center>


---

## Check tes privilèges

Profil typique du libriste : homme blanc hétéro cisgenre, jeune, valide, bac+5 / auto-didacte, né en Occident

<center>
<strong>→ À quel point tu crois pouvoir être subversif et créer un alternumérisme émancipateur,<br/>quand toi-même tu fais parti du top 0.1% des privilégiés à l'échelle mondiale ?</strong>
</center>

<br/>

- [5-10%](https://arxiv.org/pdf/2105.08777) de femmes dans le logiciel libre (~1% dans Debian), contre [~20%](https://rootstack.com/en/blog/women-tech-2024-increasing-their-presence-development-world) dans l'informatique en général
- LinuxFR qui s'enflamment au moindre point médian, soudaine empathie pour les personnes dyslexiques
- 32 libristes qui sortent du bois dès que ça parle de faire un événement en non-mixité / mixité choisie
    - ex. LUGate @ Strabourg : réaction sur la ML du LUG pour l'atelier Cybercabanes par Hackstub/Hacqueen en 2022
- Des témoignages à la pelle de personnes qui se sentent pas légitimes, ou de l'effort que ça demande de s'intégrer dans un tel milieu
- *« Oh non y'a un drapeau trans dans mon interface, pourtant la technologie devrait rester neuuuuuutre »*

<center>
<img src="https://md.globenet.org/uploads/845a5f4e-1527-4381-83ce-fada33d93568.png" style="height: 7em;" />
<img src="https://md.globenet.org/uploads/0eab6ac4-5945-4ebb-b61a-554c89b2c61f.jpg" style="height: 7em;" />

Apparament, "afficher un drapeau trans le 31 mars" = "pousser une idéologie politique" (au secours) 🤦
</center>

---

## Check tes privilèges

Profil typique du libriste : homme blanc hétéro cisgenre, jeune, valide, bac+5 / auto-didacte, né en occident

<center>
<strong>→ À quel point tu crois pouvoir être subversif et créer un alternumérisme émancipateur,<br/>quand toi-même tu fais parti du top 0.1% des privilégiés à l'échelle mondiale ?</strong>
</center>

<br/>

- [5-10%](https://arxiv.org/pdf/2105.08777) de femmes dans le logiciel libre (~1% dans Debian), contre [~20%](https://rootstack.com/en/blog/women-tech-2024-increasing-their-presence-development-world) dans l'informatique en général
- LinuxFR qui s'enflamment au moindre point médian, soudaine empathie pour les personnes dyslexiques
- 32 libristes qui sortent du bois dès que ça parle de faire un événement en non-mixité / mixité choisie
    - ex. LUGate @ Strabourg : réaction sur la ML du LUG pour l'atelier Cybercabanes par Hackstub/Hacqueen en 2022
- Des témoignages à la pelle de personnes qui se sentent pas légitimes, ou de l'effort que ça demande de s'intégrer dans un tel milieu
- *« Oh non y'a un drapeau trans dans mon interface, pourtant la technologie devrait rester neuuuuuutre »*

<center>
<img src="https://md.globenet.org/uploads/845a5f4e-1527-4381-83ce-fada33d93568.png" style="height: 7em;" />
<img src="https://md.globenet.org/uploads/0eab6ac4-5945-4ebb-b61a-554c89b2c61f.jpg" style="height: 7em;" />

Apparament, "afficher un drapeau trans le 31 mars" = "pousser une idéologie politique" (au secours) 🤦
</center>


<img src="https://md.globenet.org/uploads/98221104-d600-4968-ab23-a99e818c9e89.gif" style="position: absolute; bottom: 3em; left: 35em; height: 9em;" />
<img src="https://md.globenet.org/uploads/d01542b9-c799-4729-b4f5-9344b31bc047.png" style="position: absolute; transform: rotate(-20deg); bottom: 10em; left: 9em; width: 40em;" />



---

<center  style="padding-top: 2em;">
<img src="https://md.globenet.org/uploads/e821f2a0-7ff9-4e9d-aa52-ecaaec4a6741.jpeg" style="height: 25em;" />
</center>

---

## L'écologie, bah c'est un sujet aussi


<center style="padding-top: 3em;">
<img src="https://md.globenet.org/uploads/07f8115e-ab19-47cd-8b38-f31076c5f9f5.png" style="height: 17em;" />
<span style="display: inline-block; width: 100px;"></span>
<img src="https://md.globenet.org/uploads/90ef0c11-4c90-4d2d-b3b0-07879dd421bd.png" style="height: 17em;" />
</center>
<div style="padding-left: 350px;"><small>(idée de visuel <a href="https://louisderrac.com/conferences/libre-acceptable/">volée à Louis Derrac</a>)</small></div>

<center style="font-weight: bold; padding-top: 1em;">
    → Tout ça a des implications concrètes en terme de matériel acheté par les gens, donc fabriqué, donc miné
    <br/>
    et en terme de "qui dans le monde peut effectivement utiliser ces logiciels"
</center>


---


## Le logiciel libre comme technocratie / do-ocratie


<center>
    <img src="https://md.globenet.org/uploads/c32d9f49-5292-447a-acc7-f05000796181.png" style="height: 25em;" />
</center>

---

## Le logiciel libre comme technocratie / do-ocratie


<center>
    <img src="https://md.globenet.org/uploads/48a2df53-1e9f-4d18-b4dd-572656788056.png" style="height: 25em;" />
</center>

---

## "T'as qu'à contribuer", "T'as qu'à faire une PR"

<center>
    <img src="https://md.globenet.org/uploads/6088c97d-3653-42f4-81f9-ad5b6f9197bc.jpg" style="height: 25em;" />
</center>

---

## Firefox Ideas

<center>
    <img src="https://md.globenet.org/uploads/0872871a-39f1-4cec-af16-695d379b5206.png" style="height: 25em;"/>
</center>

---

## Le logiciel libre comme technocratie / do-ocratie

<center>

<div width="100%" style="padding-top: 3em;">
Les 4 libertés du logiciel libre (en tant que dev qui a du temps et de l'énergie) :
</div>

<div>
<ol start="0" width="100%">
    <li>utiliser</li>
    <li>étudier</li>
    <li>redistribuer</li>
    <li>améliorer</li>
</ol>
</div>

---

## Le logiciel libre comme technocratie / do-ocratie

<center>

<div width="100%" style="padding-top: 3em;">
    Les 4 libertés du logiciel libre <strong>en tant qu'utilisateur⋅ice</strong> :
</div>

<div>
<ol start="0" width="100%">
    <li style="font-weight: bold;">utiliser</li>
    <li style="text-decoration: line-through;">étudier</li>
    <li style="text-decoration: line-through;">redistribuer</li>
    <li style="text-decoration: line-through;">améliorer</li>
</ol>
</div>

<div style="padding-top: 3em;">
(Funfact : les premières définitions du logiciel libre n'incluaient même pas la liberté 0 ...)

<br/>

<strong >
En terme de base pour l'émancipation, on a vu mieux...
</strong>
</div>

</center>

---

## Le logiciel libre comme technocratie / do-ocratie

<div style="margin: auto; width: 65%; padding-top: 4em;">
<strong>Technocratie</strong>: Manière de gouverner qui consiste à donner le <strong>pouvoir à ceux qui ont des compétences techniques</strong>
<br/>
<br/>
<br/>
<strong>Do-ocratie</strong>: Organisation dans laquelle les individus ont du <strong>pouvoir à la mesure de ce qu'ils font</strong>, des tâches qu'ils choisissent et exécutent de manière autonome.
</div>

<center style="padding-top: 2em;">
Des formes d'organisation / gouvernance qui ont leur avantages ... et aussi leurs limites.

<strong>Surtout quand celle⋅eux qui sont impacté⋅es ne peuvent pas nécessairement "faire"...</strong>

Ça ressemble vachement à une domination au travers d'un outil ...
</center>

---

## Déconstruire la culture techno-élitiste

Les libristes :
- *« T'as qu'à contribuer »*
- *« Pour que les gens s'émancipent, il faut qu'iels sachent coder, utiliser la ligne de commande etc. »*
- *« `Docker` c'est facile »* <small>(bah non en fait)</small>
- *« Tu devrais plutôt utiliser BSDFromScratch avec NixPkgs sur un kernel Hurd, j'ai ça pour le cluster Kubernetes de mon site web »*

<br/>

Mais ça va plus loin, <strong style="text-decoration-line: underline; text-decoration-thickness: 3px;">les utilisateurices elleux-même ont internalisé l'élitisme</strong> :
- *« Moi je suis nul·le en informatique »*
- *« Je suis noob, j'utilise l'interface graphique plutôt que la ligne de commande »*
- "L'outil a forcément raison" (Anecdote Valérie de la compta de Coopaname : *« Ça me dit que j'ai pas le droit, donc c'est que j'ai pas le droit »* <small>Spoiler: elle aurait dû, en fait, avoir le droit</small>)

<br/><br/>
<center>
De manière générale, <strong>l'informatique est vécue comme magique</strong>

et sutout, <strong style="text-decoration-line: underline; text-decoration-thickness: 3px;">les personnes se disent non-expertes</strong> (voir s'auto-flagellent),  <strong style="text-decoration-line: underline; text-decoration-thickness: 3px;">donc non-légitime à critiquer / remettre en question l'outil</strong>
</center>

---

## Être prolétaire vs Être artisan

Les outils informatiques sont **des outils de production**

Ils définissent **certaines règles de la société** (ex. plateformes sociales)

ou **comment faire son métier** (ex. logiciel de comptabilité) (voir aussi [*Code is law* -- Lawrence Lessig](https://framablog.org/2010/05/22/code-is-law-lessig/))

**L'outil conditionne la manière qu'on a de l'utiliser, de travailler, de penser**

- Avoir juste le droit d'utiliser l'outil, et sans la légitimé de le critiquer, <strong style="text-decoration-line: underline; text-decoration-thickness: 3px;">c'est être prolétaire de l'informatique</strong>
- C'est accepter de s'adapter à un outil qui n'est pas adapté
- C'est accepter la souffrance engendré par l'outil
- C'est nier l'expertise qu'on a sur l'utilisation et le besoin


<div style="width: 75%; text-align: center; margin: auto; padding-top: 2em;">
Les premières personnes à savoir comment un outil devrait fonctionner,<br/>
ce sont les personnes qui l'utilisent.
<br/>
    <br/>
<strong>
    S'émanciper c'est avoir le pouvoir sur son outil : <span style="text-decoration-line: underline; text-decoration-thickness: 3px;" >être artisan</span>,<br/>
    comprendre comment il fonctionne,<br/>
    et savoir dire comment il devrait fonctionner
</strong>
</div>

---

<br/>
<br/>
<center style="font-size: 1.2em;">
    <h2>
        Étape 1
    </h2>
<h3>Fuck le techno-élitisme</h3>
<br/>

C'est mon outil de travail

Je sais comment je l'utilise, j'ai le droit de savoir comment il fonctionne

<strong>Je suis pas dev, mais <span style="text-decoration-line: underline; text-decoration-thickness: 3px;" >j'ai le droit d'avoir un regard critique sur mon outil</span></strong>

<strong>Je suis pas dev, mais <span style="text-decoration-line: underline; text-decoration-thickness: 3px;" >je suis légitime à dire comment je pense qu'il devrait fonctionner</span></strong>

<strong>Je suis pas dev, mais <span style="text-decoration-line: underline; text-decoration-thickness: 3px;" >j'ai le droit de m'attendre à ce que mon avis soit pris en compte</span></strong>

C'est pas aux humain·es de s'adapter à l'outil

C'est à l'outil d'être adapté aux les humain·es
</center>

---

## Faire société : le pouvoir aux utilisateur⋅ices

- Croire que les gens vont s'émanciper en les transformant en développeur⋅euse est une vision libérale, individualiste, complètement perchée
- L'émancipation, c'est collectif, ça demande de **travailler ensemble, de faire société**
- **Les utilisateur⋅ices devraient avoir le pouvoir sur l'outil, au travers des développeur⋅euses**
- Les développeur⋅euses ne peuvent pas être des bénévoles qui échangent leur temps libre contre du pouvoir
- **Casser les frontières : devs et users devraient être des collègues, des amis, des camarades de luttes**


<center>
<img src="https://md.globenet.org/uploads/296fd933-3bb2-4643-8598-d07427be633e.png" style="height: 17em;" />
</center>

- Toute une culture à inventer. Une bonne vibe dans des projets-communautés comme [YesWiki](https://yeswiki.net/), [TiBillet](https://tibillet.coop/)
- (Pour que tout ça arrive, encore faut-il que les users se sentent légitimes, et que les devs soient proactifs...)


---

## Arrêter de sacraliser la technique, et plutôt sacraliser l'humain

<em>« Un système est le reflet de la structure du collectif qui l'a concu. »</em> ([loi de Conway](https://fr.wikipedia.org/wiki/Loi_de_Conway))

<br/>
<center>
Les plateformes de dev actuelles sont <strong>centrées sur la technique</strong> :<br/>
le code, les issues, les PR, les pipelines

<br/>

Quid de plateformes qui seraient centrées sur
<strong>les usages, les besoins, les retours d'expérience, le design, prendre des décisions collectivement, ... ?</strong>
</center>
<br/>

(Toute une culture à inventer...)

Arrêter de faire l'autruche sur le modèle économique
- Le plus gros coût d'un projet, ce n'est pas son développement, c'est le travail invisible de maintenance
    - (tiens-donc ça rappellerait pas les luttes féministes ça ?)
- Au diable la logique "projet"
- Certains outils sont tellement essentiels qu'ils devraient être financés au même titre qu'un service public
- ...
- (Mais est-ce que tout ça peut exister dans un monde capitaliste et turbolibéral ?)

---

## Conclusion

<center>
<img src="https://md.globenet.org/uploads/86ae9535-a8c0-4def-b45f-e6dc32fd468d.png" style="height: 2.5em;" />
</center>

**Le logiciel libre né il y a 40 ans. Il est obsolète politiquement. Depuis 10-15 ans au moins.** (Allo)

**Le logiciel libre, la social-démocratie (social-technocratie?) numérique ?**
- Pas censé être une finalité en soi, juste un marche-pied vers des "vrais communs"
- À trop accepter d'être copain ou phagocyté par le capital / les GAFAMs, il n'y a plus aucune substance politique ou émancipatrice
- Dominé par les mecs blancs cis hétéro, une bonne partie à côté de la plaque sur les questions de genre, d'antivalidisme, d'inclusivité... "La technologie est neutre" (au secours)
- Les oeillères de la pureté militante stérile empêchent d'avancer <small>(... cf. SSPL, schisme autour de la charte CHATONS, licences post-libres, ...)</small>

<br/>

**Il est grand temps de trouver un autre ancrage (une charte ?..) pour un alternumérisme "éthique", "convivial", "bienveillant", inclusif, écolo, acceptable, bienveillant, émancipateur, libertaire, ...**
- gouvernance transparente, horizontale, *collective*, ***avec*** les utilisateur⋅ices
- respect de tous les humains impactés
- accessible, internationalisé, ...
- soutenable, utilisation raisonnable des ressources
- sans interfaces trompeuses ou autre fonctionnalités toxiques
- ...

**De l'argent ? 👏👏👏🎵 Il y'en a ! 👏👏👏🎶 Mais il est fléché vers l'IA ! 👏👏👏🎵**



---

<div style="display: flex; margin: 0.5em auto; width: 75%;">
    <img src="https://md.globenet.org/uploads/2e3113ec-a195-4cc8-a0c5-90aeacf35257.png"  style="height: 6em;" />
    <div style="display: inline-block; flex-grow: 1;"></div>
    <img src="https://md.globenet.org/uploads/fb49da48-482d-4bd3-a022-844b748c512a.png" style="height: 6em;" />
</div>

<center>
<img src="https://md.globenet.org/uploads/2cfaac48-5f42-4a0f-9b53-3bfd1a08cb9d.png" style="height: 12em;" />

<h4>URL des slides : <a href="https://link.infini.fr/imposture">link.infini.fr/imposture</a></h4>
</center>

<div style="display: flex; margin: 0.5em auto; width: 75%;">
    <img src="https://md.globenet.org/uploads/ed91a340-cdbd-4c59-9b7a-7c4f1114ab22.jpg" style="height: 6.5em;" />
    <div style="display: inline-block; flex-grow: 1;"></div>
    <img src="https://md.globenet.org/uploads/b1fd12ad-0801-4523-b51e-f6a7a6461d5c.jpg" style="height: 6.5em;" />
</div>

---

## Références (1/2)

- [Les drones de combat américains basculent sous Linux](https://linuxfr.org/news/les-drones-de-combat-americains-basculent-sous-linux)
- [FOSS Dystopia](https://idiomdrottning.org/foss-dystopia)
- [Conférence gesticulée : Informatique ou libertés ?](https://informatique-ou-libertes.fr/)
- [Les Communs numériques sont-il condamnés à devenir des « Communs du capital » ?](https://scinfolex.com/2018/06/24/les-communs-numeriques-sont-il-condamnes-a-devenir-des-communs-du-capital/)
- [Peut-on faire du libre sans vision politique ?](https://www.canalc2.tv/video/15197)
- [Low tech : face au tout-numérique, se réapproprier les technologies](https://www.ritimo.org/Low-tech-face-au-tout-numerique-se-reapproprier-les-technologies-8264)
- [Pas de sexisme chez les Libristes ?](https://framablog.org/2013/05/24/pas-de-sexisme-chez-les-libristes/)
- [On FOSSbros](https://adrian.geek.nz/fossbros)
- [À quoi servent les libristes ?](https://blog.cyphergoat.net/blog/a-quoi-servent-les-libristes/)
- [Logiciel libre et anarchisme](https://framablog.org/2023/10/09/logiciel-libre-et-anarchisme/)
- [The Telekommunist Manifesto](https://media.telekommunisten.net/manifesto.pdf)
- [Le logiciel libre : simple, basique](https://bzg.fr/le-logiciel-libre-simple-basique/)
- [Forum CHATONS - Faut-il des exceptions à la clause 100% libre ?](https://forum.chatons.org/t/faut-il-des-exceptions-pour-la-clause-100-libre/5015) et aussi [celui-ci](https://forum.chatons.org/t/que-vous-soyez-dans-le-brouillard-ou-profondement-contre-le-texte-au-vote/5162) et aussi [ce pad](https://pad.sans-nuage.fr/p/whishlist-exceptions)
- [Compte-rendu du Forum ouvert « Faut-il en finir avec le Libre ? »](https://dérivation.fr/compte-rendu-du-forum-ouvert-faut-il-en-finir-avec-le-libre/)
- [Technoféminisme - Comment le numérique aggrave les inégalités](https://www.grasset.fr/livre/technofeminisme-9782246828822/)

---

## Références (2/2)

- [Dépasser le fonctionnement en silo, la "tragédie du LSD, Libre, Solidaire et Durable"](http://www.cooperations.infini.fr/spip.php?article11428)
- [Outil convivial](https://fr.wikipedia.org/wiki/Outil_convivial)
- [Manifest Cyborg](https://fr.wikipedia.org/wiki/Manifeste_cyborg)
- [Post Open-Source](https://www.boringcactus.com/2020/08/13/post-open-source.html)
- [Copyfarleft](https://wiki.p2pfoundation.net/Copyfarleft)
- [Licence anti-capitaliste](https://anticapitalist.software/acsl_french)
- [The exploitation paradox in open source](https://lwn.net/Articles/1058031/)
- [Pour un numérique acceptable et d'intérêt général](https://techologie.net/episodes/80-pour-un-numerique-acceptable-et-dinteret-general/)
- [Le numérique acceptable](https://louisderrac.com/numerique-acceptable/)
- [Vers un design convivial des communs numériques](https://www.conviviel.org/manifeste/)
- [Le manifest de La Spirale](https://spiralecoop.notion.site/Manifeste-de-la-spirale-cc2e27bc71224c4aad049435bc0ee29b)
- [Coup de gueule sur LinkedIn à propos des entreprises qui "consomment" le libre](https://www.linkedin.com/posts/guillaume-ch%C3%A9ramy-%F0%9F%90%A7-01039226_glissade-du-jour-o%C3%B9-coup-de-gueule-activity-7401575872908128258-469k)
- [Les Communs numériques sont-il condamnés à devenir des « Communs du capital » ?](https://scinfolex.com/2018/06/24/les-communs-numeriques-sont-il-condamnes-a-devenir-des-communs-du-capital/)
- [Collectif Designers Éthiques](https://designersethiques.org/)
- [Collectif Limites Numériques](https://limitesnumeriques.fr/)


---

## Quelques exemples de licences post-libre


- [Creative Common "sans utilisation commerciale"](https://creativecommons.org/2016/09/09/why-were-fighting-to-protect-noncommercial-uses/)
- [Licence Coopyleft](https://wiki.coopcycle.org/en:license) → droit d'utilisation réservé aux coopératives (et individus)
- [Licence Anti-Capitaliste](https://anticapitalist.software/) → droit d'utilisation, sauf pour le capital
- [i'm so tired license](https://olmewe.com/notes/istsl/)
- [Licence Hyppocratic](https://firstdonoharm.dev/) → interdire les trucs déguelasses : atteintes aux droits de l'homme, écocides, exploitation des travailleur·euse·s, ...
- [Licence Non-violente (NPL)](https://thufie.lain.haus/NPL.html) et CNPL
- [Licenses à réciprocité](https://scinfolex.com/2014/09/22/comprendre-le-principe-des-licences-a-reciprocite-en-5-minutes/)<br/>
  - [Peer Production License](https://scinfolex.com/2012/11/10/peer-production-licence-une-licence-concue-pour-les-biens-communs/) → commercialisation possible seulement en échange d'une contribution financière
  - CopyFair


Discussion générale:
- [Post open-source](https://www.boringcactus.com/2020/08/13/post-open-source.html)
- [Copyfarleft](https://wiki.p2pfoundation.net/Copyfarleft)
