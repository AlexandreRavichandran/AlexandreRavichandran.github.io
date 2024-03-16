---
layout: project 
permalink: /media-list-maker
title: Media list maker
image: non 
description: Application to create a list of movie to watch and music to listen
image: media-list-maker
---

<h3>Presentation</h3>
<p>This project is the 2nd version of the project <a href="/remind-me">Remind-me</a> that I did with Symfony and API Platform. Since I started to be interested about movies recently, and loving rap music since always, I decided to do this project again with a better architecture and better UI to use it to set me a list of movies to watch and musics to listen.</p>
<p>This project was my second turning point on web development. I tried to master some of my skills and also tried to learn a lot of new things. It is also the first project where I took time to create a Figma before starting the front-end, and worked a lot of time to make a responsive and esthetical front-end. I also learned how to perform unit tests in angular, and upgrade my skills in NgRx (and learned also NgRx testing).</p>
<p>This project was also a turning point because it was the first project that I have made with microservice architecture. This architecture includes Eureka server, Gateway, and 4 fonctionnal microservices. One of my struggling issues were on the gateway, and especially the filter and JWT verification.</p>
<p>Finally, this is the first project available as Docker images in Docker Hub.</p>
<p>Like the V1 project, I have used 2 external apis; OMDB and Deezer. I have already worked with this apis so I was familiar with them.</p>

<h3>Links</h3>
<p>Link of the project's source codes:</p>
<ul>
    <li>
        <p><i class="icon solid fa-desktop"></i>  Front-end section : <a href="https://github.com/AlexandreRavichandran/media-list-maker-frontend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
    <li>
        <p><i class="icon solid fa-server"></i> Back-end section : <a href="https://github.com/AlexandreRavichandran/media-list-maker-backend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
</ul>
<p>There is also a Docker compose file to test this project in your computer (Docker required)</p>
<hr />
<h3> Features </h3>
<ul>
    <li>Search Movies and Music based on query and specific criterias (year, artist name...)</li>
    <li>Add item to your list</li>
    <li>Change item order in list</li>
    <li>Authentication</li>
    <li>Getting random element in your list</li>
</ul>

<h3> Used technologies </h3>
<div style="display:flex;justify-content:space-around;flex-wrap:wrap;">
    <ul>
        <h5>Front-end: </h5>
        <li>Angular</li>
        <li>NgRx</li>
    </ul>
    <ul>
        <h5>Back-end: </h5>
        <li>Spring boot 3.2 with microservice architecture</li>
        <li>PostgreSQL</li>
    </ul>
    <ul>
        <h5>Used API: </h5>
        <li>Deezer's API</li>
        <li>OMDB API</li>
    </ul>
    <ul>
        <h5>Deployment:</h5>
        <li>Docker</li>
    </ul>
</div>