---
layout: post
title: "Zebrar Usando Apenas CSS"
description: ""
category: "Web"
tags: html,css
permalink: zebrar-usando-apenas-css
---

A pseudo class `:nth-child` pode ser utilizada para atribuir estilo aos elemento pares __odd__ ou ímpares __even__ eximindo o programador do trabalho de atribuir classes diferentes para estes elementos.

{% highlight html %}
<style>
    table tr:nth-child(even) { background-color: #CCC; }
</style>
<table>
    <tr><td>primeira</td><td>linha</td></tr>
    <tr><td>segunda</td><td>linha</td></tr>
    <tr><td>terceira</td><td>linha</td></tr>
    <tr><td>quarta</td><td>linha</td></tr>
</table>
{% endhighlight html %}

Demo:

<div id="example">
    <style>
        table tr:nth-child(even) { background-color: #CCC; }
    </style>
    <table>
        <tr><td>primeira</td><td>linha</td></tr>
        <tr><td>segunda</td><td>linha</td></tr>
        <tr><td>terceira</td><td>linha</td></tr>
        <tr><td>quarta</td><td>linha</td></tr>
    </table>
</div>

References:

[W3Scholls](http://www.w3schools.com/cssref/sel_nth-child.asp)