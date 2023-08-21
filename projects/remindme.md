---
layout: project
permalink: /remind-me
title: Remind me
description: Reminder application to set a list of movie to watch, books to read and music to listen
image: remindme

---

<h3>Presentation</h3>
<p>This project is my third experience with Symfony. It's an application which permits to set a list of movies to watch, books to read and music to listen, like a reminder. The user can register and will have access to movie, music and book library and add them to their list</p>
<p>This project allowed me to work on the API version of Symfony, but it was also an opportunity to discord API Platform, a Symfony based framework which permits to facilitate Symfony API creation. I also made the front-end page with Jekyll, a static website generator (by the way, the website where you are currently is made with Jekyll). Finally, I have implemented the consumption of external official API like Deezer and Google books.</p>

<p>During this project, I learned a lot about the working of API Platform and I have also made unit tests to check the good working of each API features. I also wanted, like <a href="/quiver"> my previous project </a>, to respect Symfony syntax standards.</p>
<p>On the front section, like my previous projects, I didn"t spend much time working on the design part of the website, but I was focused on the features.</p>
<h3>Links</h3>
<p>Link of the project's source codes:</p>
<ul>
    <li>
        <p><i class="icon solid fa-desktop"></i>  Front-end section : <a href="https://github.com/AlexandreRavichandran/Remind-me-frontend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
    <li>
        <p><i class="icon solid fa-server"></i> Back-end section : <a href="https://github.com/AlexandreRavichandran/Remind-me-backend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
</ul>

<div style="display:flex;justify-content:center;margin-top:10px;margin-bottom:10px">
    <em style="margin-bottom:0px;margin-top:6px;margin-right:8px" class="fas fa-exclamation-triangle"></em>
    <p style="margin-bottom:0px;">Since Heroku has stopped his free tier, this application is no more available. </p>
</div>
<hr />
<h3> Features </h3>
<ul>
    <li>Search a movie, book, album or music</li>
    <li>Access to data of the searched media (extract of a music, summary of a movie...)
    </li>     
    <li>Manage user's personnal list of media (add a media, delete, reorder...)</li>
    <li>Authentication/registration with JWT</li>
</ul>

<h3> Used technologies </h3>
<div style="display:flex;justify-content:space-around;flex-wrap:wrap;">
    <ul>
        <h5>Integration/Front-end</h5>
        <li>Jekyll</li>
        <li>HTML/CSS</li>
        <li>Framework Bootstrap</li>
        <li>Javascript</li>
    </ul>
    <ul>
        <h5>Back-end:</h5>
        <li>Symfony 5</li>
        <li>API Platform</li>
        <li>MySQL database</li>
    </ul>
    <ul>
        <h5>Used API: </h5>
        <li>Deezer's API</li>
        <li>Google Book's API</li>
        <li>OMDB API</li>
    </ul>
    <ul>
        <h5>Deployment:</h5>
        <li>Github-pages for the front-end</li>
        <li>Heroku for the back-end </li>
    </ul>
</div>