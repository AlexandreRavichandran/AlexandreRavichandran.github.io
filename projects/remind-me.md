---
layout: project
permalink: /remind-me
title: Remind me
description: Application "Pense-bête" pour se constituer une liste de films à voir, livres à lire et musique à écouter.

---

<h3>Présentation</h3>
<p>Ce projet est ma troisième experience avec Symfony. Ce projet est une application permettant de se constituer une liste de films à regarder, de livres à lire, et de musique à écouter, un peu comme un pense-bête. L'utilisateur pour s'inscrire et aura accès a une bibliotheque de films, livre et musique et pourra les ajouter à sa liste.</p>
<p>Ce projet m'a permis de travailler sur la version API de Symfony, mais cela a également été l'occasion de me confronter à API Platform, un framework permettant de faciliter la création d'un API avec Symfony. J'ai également pu constuire un front avec Jekyll, un générateur de site web statiques (D'ailleurs, le site ou vous êtes actuellement a été construit avec Jekyll). Enfin, j'ai pu mettre en place la consommation de certains API officiels, comme celui de Deezer et celui de Google Books.</p>
<p>Durant ce projet, j'ai pu apprendre le fonctionnement d'API Platform, et egalement pu mettre en place des tests unitaires afin de verifier le bon fonctionnement de chaque fonctionnalité de l'API. J'ai également tenu, comme <a href="/quiver"> mon précédent projet</a>, à respecter les standards de Symfony au niveau de la syntaxe.</p>
<p>Merci à <a target="_blank" href="https://www.behance.net/samitcourt5917">Samir Abdi</a> pour la réalisation du logo de ce projet.</p>
<h3>Liens</h3>
<p>Lien du code source de ce projet:</p>
<p>Le projet etant encore en cours, les liens seront disponibles prochainement.</p>
<!-- <ul>
    <li>
        <p><i class="icon solid fa-desktop"></i>  Partie front-end : <a href="https://github.com/AlexandreRavichandran/Remind-me-frontend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
    <li>
        <p><i class="icon solid fa-server"></i> Partie back-end : <a href="https://github.com/AlexandreRavichandran/Remind-me-backend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
</ul>
<p>Lien du projet: <a href="https://alexandreravichandran.github.io/Remind-Me-frontend" target="_blank" class="icon brands"><i class="fas fa-rocket"></i></a></p>
<p>Lien de la partie back du projet: <a href="https://remind-me-api.herokuapp.com/" target="_blank" class="icon brands"><i class="fas fa-rocket"></i></a></p> -->

<h3> Fonctionnalités </h3>
<ul>
    <li>Recherche d'un film, album, musique, livre</li>
    <li>Accès en détail aux info du média cherché (extrait d'une musique recherchée, resumé d'un film, résumé d'un livre...)
    </li>     
    <li>Ajout/Suppression de médias dans sa liste personnelle de film, musique ou livre</li>
    <li>Authentification/inscription via JWT</li>
</ul>

<h3> Technologies utilisés </h3>
<div style="display:flex;justify-content:space-around;flex-wrap:wrap;">
    <ul>
        <h5>Intégration/Front-end</h5>
        <li>Jekyll</li>
        <li>HTML/CSS</li>
        <li>Framework Bootstrap</li>
        <li>Javascript</li>
    </ul>
    <ul>
        <h5>Back-end:</h5>
        <li>Symfony 5</li>
        <li>API Platform</li>
        <li>Base de donnée MySQL</li>
    </ul>
    <ul>
        <h5>API utilisés: </h5>
        <li>API de Deezer</li>
        <li>API de Google Books</li>
        <li>API de OMDB</li>
    </ul>
    <ul>
        <h5>Deploiement:</h5>
        <li>Github-pages pour le front-end</li>
        <li>Heroku pour le back-end </li>
    </ul>
</div>