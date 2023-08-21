---
layout: project 
permalink: /user-data-generator
title: User data generator 
image: non 
description: Application to generate standard user datas 
image: job-search-manager
---

<h3>Presentation</h3>
<p>This project is a data generator which can generate data about a random user. The datas can be general (name, birth date, email...), physical(height, weight..), his preferences or his social network links. It can also generate different types of credit card numbers (Visa, Mastercard, American Express) followed by an expiration date and CVV. Credit card datas are fake BUT are valid, it means that you can use them to test the development mode of the Paypal payment API for example, thanks to the respect of the Luhn algorithm when generating the credit card number. API routes has been made to be fully customized to get exactly the type of datas you want. It can also generate a fake picture depending on the gender and age of the generated user.</p>
<p>This project was a turning point of my developper's path. Indeed, it's my first project since I learnt Java. Therefore, this project was a real challenge to me. The main advantage was the fact that Spring boot work almost like Symfony framework (MVC architecture, annotations are almost the same, ORM on both works almost the same), so I was able to adapt to this new framework quickly. I was a little scared about going from PHP to Java (which is a typed language) but finally it was relatively easy for me to to the transition.</p>
<p>In addition to increasing my Java development skills, this project helped me a lot to understand <a target="_blank" href="https://en.wikipedia.org/wiki/Luhn_algorithm">the Luhn algorithm</a> (algorithm that I knew before) and the way that credit card are generated/validated.</p>
<p>The random pictures generated when you generate a user comes from <a target="_blank" href="https://thispersondoesnotexist.com/">Thispersondoesnotexist API</a>.</p>

<h3>Links</h3>
<p>Link of the project's source code: <a href="https://github.com/AlexandreRavichandran/fake-user-data-generator" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>

<div style="display:flex;justify-content:center;margin-top:10px;margin-bottom:10px">
    <em style="margin-bottom:0px;margin-top:6px;margin-right:8px" class="fas fa-exclamation-triangle"></em>
    <p style="margin-bottom:0px;">Since Heroku has stopped his free tier, this application is no more available. </p>
</div>
<hr />
<h3> Features </h3>
<ul>
    <li>Generate single or list of customized user datas (general, physical, preferences..)</li>
    <li>Generate valid credit card numbers and related datas (expiration date & CVV)</li>
    <li>Generate QR code with either custom datas or generated user datas</li>
    <li>API documentation by SwaggerUI</li>
</ul>

<h3> Used technologies </h3>
<div style="display:flex;justify-content:space-around;flex-wrap:wrap;">
    <ul>
        <h5>Back-end: </h5>
        <li>Spring boot 2.6</li>
    </ul>
</div>

