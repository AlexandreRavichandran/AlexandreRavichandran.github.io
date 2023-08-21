---
layout: project 
permalink: /bank-account-manager
title: Bank account manager
image: non 
description: Application to manage your different bank accounts
image: bank-account-manager
---

<h3>Presentation</h3>
<p>This project is an application to manage your bank accounts. When you have several bank accounts, sometimes it can be complicated to manage them all, even more if they are on differents applications. This project can help you to get datas about all your bank accounts only in one application. You can add your bank accounts, add your follow ups and see their current situation.</p>
<p>This project is the second project made in Spring Boot and Angular. Working on this project helped me to upgrade my skills on Spring boot, Angular, and most of all I learnt a famous state management system for Angular called <a href="https://ngrx.io/">NgRx</a> based on <a href="https://redux.js.org/">Redux</a>. I found this state management very useful, so I will use NgRx for my future projects (if they are large).</p>
<p>Note: One of the limits of this project is the fact that, first of all, you have to create all your bank account's follow-up manually, and secondly when you do a payment of a transfer you also have to add it manually. The thing is that, to have automatically all datas created when you do a payment, I had to use Bank APIs, but theses API requires to had a DSP right, which I don't have.</p>

<h3>Links</h3>
<p>Link of the project's source codes:</p>
<ul>
    <li>
        <p><i class="icon solid fa-desktop"></i>  Front-end section : <a href="https://github.com/AlexandreRavichandran/bank-accounts-manager-frontend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
    <li>
        <p><i class="icon solid fa-server"></i> Back-end section : <a href="https://github.com/AlexandreRavichandran/bank-accounts-manager-backend" target="_blank" class="icon brands fa-github"><span class="label">Github</span></a></p>
    </li>
</ul>
<div style="display:flex;justify-content:center;margin-top:10px;margin-bottom:10px">
    <em style="margin-bottom:0px;margin-top:6px;margin-right:8px" class="fas fa-exclamation-triangle"></em>
    <p style="margin-bottom:0px;">Since Heroku has stopped his free tier, this application is no more available. </p>
</div>
<hr />
<h3> Features </h3>
<ul>
    <li>Create your bank accounts and create their follow-ups (payments, transfers..)</li>
    <li>Create payments and transfers for each bank accounts</li>
    <li>See the current situation of your bank account and your global financial situation (total of all your bank accounts etc)</li>
    <li>Authentication with JWT token</li>
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
        <li>Spring boot 2.6</li>
        <li>MySQL</li>
    </ul>
    
</div>