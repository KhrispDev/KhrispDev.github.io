---
layout: post
title: Javascript Testing
categories: testing
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
tags: testing
---

<h1>Hello!</h1>

<h2>This Button Hides and Shows Text</h2>

<p id="demo">Boop!</p>

<button id="hide" type="button" onclick="document.getElementById('demo').style.display='none'; document.getElementById('hide').style.display='none'; document.getElementById('show').style.display=''">Hide Text</button>

<button id="show" type="button" onclick="document.getElementById('demo').style.display=''; document.getElementById('show').style.display='none'; document.getElementById('hide').style.display=''" style="display:none">Show Text</button>
