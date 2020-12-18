---
title: About the Pro-Life History Project
layout: about
permalink: /about.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Pro-Life History Project
The Pro-Life History Project was created as an “alternative timeline” from research that works alongside a history of reproductive justice but focuses on the pro-life movement. This website was made for scholars of reproductive justice, to explore the various tactics of people in the pro-life movement in the United States. Explore this virtual archive through people, tactics, dates, and places specifically pertinent to the Pro-Life Movement. The Pro-Life History Project was launched in 2020.
 
## History
My work concerns white women’s roles in the pro-life movement since the instantiation of Roe v. Wade in the United States. My research includes ethnographic as well as archival work that will foreground the historical research that is lacking and needs to be completed in the scholarly areas of feminism and reproductive justice. I aim to unearth the histories of the grassroots pro-life movement and their discourses and tactics in order to understand the consequences of women’s involvement for larger discourses surrounding reproductive rights and abortion. The problem with unearthing this rich history of the pro-life movement and its impact on reproductive laws and rights in the United States is the lack of archival material that has been collected since the start of these movements. This website is my attempt to publicize this forgotten and hidden history specifically in Iowa and the Midwest region of the United States.
 
## Team
Micki Burdick is a PhD Student at the University of Iowa. They study the rhetorical history of the pro-life movement through the bodies of the women who mainly lead these groups. They attempt to understand the pro-life movement through images, narratives, and videos that can tell the stories of these bodies and how they affect other bodies.
They would like to thank the Iowa Women’s Archive for the images and archival resources.

## old stuff (instructions that will be cut)
This site is generated using [`collectionbuilder-gh`](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPEG images or PDF documents

The base site features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

We want to make About pages exciting, and easy to build. 

The CollectionBuilder about page features a narrowed column with its own (optional) menu, featured content, and some technical information. 

To build one, a user writes in [Markdown](https://guides.github.com/features/mastering-markdown/) and includes  content from the site, as well as typical [Bootstrap](https://getbootstrap.com/) features like cards and modals, using code snippets like those detailed below. 

(Each included file has several options, which are documented in the files themselves. I've given the content widths of 25% and 50% to save space, but you can feature the entire image or document.) 

- Image --> `{% raw %}{% include feature/item-figure.html objectid="demo_001" width="25" %}{% endraw %}`

{% include feature/item-figure.html objectid="demo_001" width="25" %}

- PDF -- > `{% raw %}{% include feature/item-pdf-embed.html objectid="demo_002"  width="25" %}{% endraw %}`

{% include feature/item-pdf-embed.html objectid="demo_002" width="25" %}

- Video: `{% raw %}{% include feature/item-video-embed.html objectid="demo_004" %}{% endraw %}`

{% include feature/item-video-embed.html objectid="demo_004" %}

- Card -- > `{% raw %}{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}{% endraw %}`

{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}

- Buttons -- > `{% raw %}{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}{% endraw %}`

{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" centered=true %}
  
- Alerts -- > `{% raw %}{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}{% endraw %}`

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

- Modals -- > `{% raw %}{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}{% endraw %}`

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}

We hope this makes it easier for site builders to develop the collection AND add interesting and engaging contextual information.  
