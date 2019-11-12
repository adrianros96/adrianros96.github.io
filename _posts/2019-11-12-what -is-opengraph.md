---
layout: post
title:  "Vad är Open Graph?"
categories: generally
author: "Adrian Rosales"
permalink: /post/what-is-opengraph
comments: true
image: /image/programming2.jpg
---
![code](/image/programming2.jpg){: .center-postImg }

Open Graph lägger man i html-head. Dessa läggs som meta-taggar, och man kan bestämma vilken information som ska synas när du delar en länk.
Informationen kan bestå av bild, beskrivning och titel. Problemet med detta kan vara att man vilseleder folk genom falsk information för att generera 
fler besökare till sin sida.

Jag har valt följande inställingar till min webbplats. Dessa har jag lagt till i min head.html som finns i  _includes katalogen.

`<meta property="og:title" content="" />` - Sidans titel

`<meta property="og:description" content="" />` - Sidans beskrivning

`<meta property="og:url" content="" />` - Sidans fullständiga URL

`<meta property="og:type" content="" />` - typ av sida 

`<meta property="og:image" content="" />` - Bild som tilldelats sidan
