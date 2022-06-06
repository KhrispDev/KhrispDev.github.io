---
layout: post
title: Javascript Testing
categories: testing
banner:
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
tags: testing
sidebar: []
---

# Hello!

<style>
	* {
    font-family: nunito;
    }
</style>
<body>
<h2>This Button Hides and Shows Text</h2>

<p id="demo">Boop!</p>

<button id="hide" type="button" onclick="document.getElementById('demo').style.display='none'; document.getElementById('hide').style.display='none'; document.getElementById('show').style.display=''">Hide Text</button>

<button id="show" type="button" onclick="document.getElementById('demo').style.display=''; document.getElementById('show').style.display='none'; document.getElementById('hide').style.display=''" style="display:none">Show Text</button>

</body>
