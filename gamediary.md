---
layout: page
title: Game Diary
subtitle: Game I have played
css: "/css/index.css"
---

<div>
  {% for game in site.games %}    
    <h2>{{ game.game }}</h2>
  {% endfor %}
</div>