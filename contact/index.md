---
layout: contacto-edu
title: Eduardo Cabrera Blázquez
description: "Contacto Eduardo Cabrera Blázquez"
permalink: /contact.html
image: images/foto-edu.png
---


<style>
form.wj-contact input[type="text"], form.wj-contact textarea[type="text"] {
    width: 100%;
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: monospace, sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #444;
    outline-color: #2e83e6;
    border-width: 1px;
    border-radius: 3px;
    transition: box-shadow .2s ease;
}
form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    background-color: #2e83e6;
    border-radius: 3px;
    padding: 0.5em;
    margin: 0.25em 0 0 0;
    border: 1px solid transparent;
    height: auto;
}
</style>

<div style="padding-top: 5%;color:white;width: 85% ">


   
<form class="wj-contact" action="https://formspree.io/{{site.email}}" method="POST">
    <input type="text" name="email" placeholder="Email Address">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="https://eduardo-cabrera.github.io/contact.html">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" style="color:green;background-color:yellow" value="Pulse aqui para enviar su mensaje">
</form>

</div>

<center>
    {% include top-links-about.html %}
</center>