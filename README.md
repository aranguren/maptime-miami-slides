What will your money buy?
====

Slides from a presentation about the Miami Herald's [affordable housing tool](http://pubsys.miamiherald.com/static/media/projects/2015/affordable-homes/).


Who are we?
----

### Nicholas Nehamas ###
Reporter on the Miami Herald business desk. Covers real estate and the economy and contributes to ongoing 2016 presidential race. Previously covered health care.

Twitter: [@NickNehamas](http://twitter.com/NickNehamas)

Email: [nnehamas@miamiherald.com](mailto:nnehamas@miamiherald.com)


### Chris Alcantara ###
Interactive news developer. Specializes in building data visualizations, multimedia projects and interactive graphics.

Twitter: [@chrisalcantara](http://twitter.com/chrisalcantara)

Email: [calcantara@miamiherald.com](calcantara@miamiherald.com)

GitHub: [github.com/chrisalcantara](github.com/chrisalcantara)

Project purpose
----
Because wages are low and foreign investors snap up available properties, Miami is one of the least affordable housing markets in the United States. 

We wanted to make a tool that readers could see where exactly in South Florida they could afford a home – and how those areas matched up on schools and safety. 

What we found
----

Middle-class people are being pushed farther away from where they work and where the best schools and safest neighborhoods are.

Story also includes profiles of different neighborhoods around Miami-Dade County written by more than half-dozen reporters. 

Planning
----
We didn't just want to tell people our conclusions. We wanted to let them figure it out for themselves based on their income. 

A calculator works, but we wanted to show people where they can afford a home. 

We decided on a map, drawing inspiration from [previous](http://media.miamiherald.com/static/media/projects/2014/zipcode/) real estate coverage.

Development
---
Tools used: Leaflet, JavaScript, jQuery, Gulp, HTML and CSS/SCSS

Decided to use Leaflet because:

* We've [used](http://pubsys.miamiherald.com/static/media/projects/2015/bus-gripes/) [it](http://media.miamiherald.com/static/media/projects/2014/zipcode/map/?33126) [before](http://media.miamiherald.com/static/media/projects/2015/hospital-infections/). Plenty of code to reference. 

* Thorough documentation and big community on Stack Overflow.

* Plays nicely with other libraries, including D3.js. 

Meanwhile, Nick gathered data and compiled it into a format (JSON) used to feed the map. His first time using GitHub.


Challenges
----
We realized early on we weren't going to find perfect data. We had to compromise on what we could show and explain the decisions we made to readers. 

Also: Time. Inputting data was labor-intensive, more so than we expected.

Under the hood: Issues with function scoping for clearing layers off the map. 

Success
----
 
<img src='http://i.imgur.com/NSJUbjq.gif'>


And it works on mobile
----
<img src='http://i.imgur.com/7eXo8wP.gif'>


Reaction
----
This interactive was one of the most popular tools the Herald has published. 

We received a lot positive feedback from readers, although many lamented the fact they couldn't afford homes in the neighborhoods they wanted to live in. 

Our editors also thought the project was a success, meaning we hope to have the opportunity to create more map-based interactives in the coming months. 

What we learned
---
**Communication** between developer and reporter is crucial. Good for both to understand the goal.

**Compromising** on expectations and realities can lead to less stress and better results, especially while working in a small team. 

**Experimenting** with news ways to tell a story is always good but make sure to have backup plan when disaster strikes.  

**Seek help** when stuck. There's a lot the Internet can provide but sitting with another person and talking out the problem can be helpful. 

Like our work?
---
Check out other interactive projects and tools the Miami Herald has published this year:

* Jan. 20, 2015: [Did Medicare fine your local hospital for patient safety?](http://media.miamiherald.com/static/media/projects/2015/hospital-penalties/)

* Feb. 15, 2015: [Half of Florida counties meet state's vaccination goal](http://pubsys.miamiherald.com/static/media/projects/2015/vaccines/)

* Feb. 20, 2015: [Florida's tax fraud hot spots](http://pubsys.miamiherald.com/static/media/projects/2015/sofla-tax-fraud/index.html) 

* March 3, 2015: [One Herald Plaza: The last days of the former Miami Herald building](http://media.miamiherald.com/static/media/projects/2015/one-herald-plaza/)

* April 8, 2015: [Jailbird](https://github.com/chrisalcantara/jailbird)

* April 17, 2015: [How 5.2 million people fell into the health insurance coverage cap](http://pubsys.miamiherald.com/static/media/projects/2015/gap-explainer/index.html)

* April 17, 2015: [Low-cost healthcare finder](http://pubsys.miamiherald.com/static/media/projects/2015/findcare/index.html) 

* April 24, 2015: [Higher-Ed Hustle: A closer look at complaints](http://pubsys.miamiherald.com/static/media/projects/2015/higher-ed-hustle/complaints/)

* April 24, 2015: [Higher-Ed Hustle: Money, politics and Florida's career colleges](http://pubsys.miamiherald.com/static/media/projects/2015/higher-ed-hustle/contributions/)

* April 24, 2015: [Search Florida nursing programs](http://pubsys.miamiherald.com/static/media/projects/2015/higher-ed-hustle/nclex.html) 

* April 2015: [Cruel and Unusual](http://pubsys.miamiherald.com/static/media/projects/2015/cruel-and-unusual/)

* June 19, 2015: [License To Launder](http://pubsys.miamiherald.com/static/media/projects/2015/license-to-launder/)

* June 30, 2015: [Toll Calculator](http://media.miamiherald.com/static/media/projects/toll-calculator/) 

* July 13, 2015: [Titans of the Seas](http://pubsys.miamiherald.com/static/media/projects/2015/titans-of-the-seas/) 

* July 18, 2015: [A look at Miami-Dade responses to county issues, presidential race](http://pubsys.miamiherald.com/static/media/projects/2015/july-2015-poll/)

* Aug. 18, 2015: [Fins At 50](http://media.miamiherald.com/static/media/projects/2015/fins-at-50/index.html) 

* Sept. 18, 2015: [What will your money buy?](http://pubsys.miamiherald.com/static/media/projects/2015/affordable-homes/) 

* Oct. 16, 2015: [Jeb and Marco: The 2016 Money Race](http://pubsys.miamiherald.com/static/media/projects/2015/2016-money-race/)

* Nov. 5, 2015: [What's wrong with Miami-Dade's bus routes?](http://pubsys.miamiherald.com/static/media/projects/2015/bus-gripes/)

* Dec. 3, 2015: [Graphisize.js](https://github.com/chrisalcantara/graphisize.js) 

















