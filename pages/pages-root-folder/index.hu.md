---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: Főoldal
lang: hu
site_title_localized: 'Tóth Ferenc – Személyes oldal' # <-- Új kulcs a magyar címnek

header:
  image_fullwidth: main_header.png

widget1:
  title: "A Kód: Értelmezhető Rendszerek"
  url: '/mernokember/' # Még emberibb URL-nek nevezd át az aloldalt
  image: engineer_human.png
  text: 'A Mérnökember belső logikája: A világ komplex folyamatait adatelemzéssel, optimalizálással és matematikai modellekkel térképezem fel. Mérés és precizitás az emberi célok szolgálatában.'
widget2:
  title: "Az Ember: Alkalmazott Megértés"
  url: '/embermernok/' # Még emberibb URL-nek nevezd át az aloldalt
  image: human_engineer.png
  text: 'Az Embermérnök gyakorlata: A rendszerszintű megértés átültetése a vezetésbe, a kommunikációba és a fejlesztésbe. Hogyan hozzunk jobb, kiszámíthatóbb döntéseket?'


#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: '/organikus-manifesto/'
  text: 'Olvassa el a teljes Organikus Leadership Manifesztót ›'
  style: success # Zöld gomb
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


# Organikus Leadership: Az Építkezés Taoja
## Hol a Rendszer Növekszik – A Projekt Alapú Fejlesztés Alternatívája.

Több induló gyár és projekt tapasztalata vezetett ahhoz a felismeréshez, hogy a nyugati "megcsinálom" szemlélet helyett a Távol-Keleti "megyek az úton" elv hoz fenntartható és emberközpontú eredményeket.

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
