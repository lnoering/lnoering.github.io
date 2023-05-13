---
title: Doing one Brooder
author: lnoering
date: 2023-05-09 12:30:00 +0800
categories: [Microcontroller, Project]
tags: [software, arduino, c++]
render_with_liquid: false
---

## The Brooder Project

<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
<script>
    fetch('https://raw.githubusercontent.com/lnoering/chocadeira/master/README.md')
    .then(response => response.text())
    .then(data => document.getElementById('git-data').innerHTML = marked.parse("### Plataforma/Platform"+data.split("### Plataforma/Platform")[1]));
</script>
<div>
    <div id="git-data" markdown="1"></div>
</div>


> The code is here: [Brooder](https://github.com/lnoering/chocadeira)