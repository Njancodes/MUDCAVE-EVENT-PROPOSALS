# the <???>ring

## how to join
1. pr this repo:
https://github.com/galisma/webring
2. add this code to your site
```html
<script src="https://galisma.github.io/webring/links.js"></script>
<script src="https://galisma.github.io/webring/script.js"></script>
```
3. add those links:
```html
<a id="ring_previous">prev</a>
<a id="ring_next">next</a>
```

## site links
[static file](https://galisma.github.io/webring/links.json)
[github repo](https://github.com/galisma/webring)

## name ideas
- mudring
- Jerkweb
- webring for the mud ppl
- webringjerk
- jerkring
- pseudo intellectual webring
- Webjerk
- Jebreck
- webjerkring
- Jerkwebring
- Ringjerkweb
- cyberspace jerk
- cyberjerk

## code
https://allium.house/garden/onionring/
https://lambchapel.neocities.org/resources/webstring
https://en.wikipedia.org/wiki/Webring
https://www.youtube.com/watch?v=BpRXwk6_xN8&pp=ygUHd2VicmluZw%3D%3D
https://allium.house/garden/onionring/

## examples of sites with webrings
https://lambchapel.neocities.org/resources/webstring
https://larsfrommars.neocities.org/

## fix for neocities
https://corsfix.com/blog/fix-neocities-content-security-policy

# buttons
- everyone makes a button (galisma wants to see some juicy programmer art)
- provide default button
- anti AI button (made with AI)

## generators
https://88x31.datakra.sh/
https://hyperlinkarchive.neocities.org/addbutton

# idk why it was in the thread
https://github.com/stevearc/conform.nvim

# sphere
https://youtu.be/AGh5LM7Jmfk
<img width="2584" height="2572" alt="image" src="https://github.com/user-attachments/assets/ce0819b5-3307-4d2a-9610-c1a475217d9b" />

## explanation
we add one dimention to a webring, we get a webshere. The reason its a 2d sphere is that we are looking at the sphere's area which is 2d.
The shpere is made by taking a one dimentional array that we project onto the sphere. Every time a member joins, the sphere changes. Your neighbords may change.
The sphere is created from top to bottom, the first element of the array will be the north pole and the newest addition, the south pole.
Sites are not placed by real life geographic location.
Because it is a sphere, the closer you are to the emisphere, more your website will be seen. That gives newcommers and veterans the advantage and is part of why this idea is so cool.
We do not need to really draw a sphere, all we need is to get an algorithm that can get a link in 4 directions relative to the current link and it has to wrap around itself. This means that if we visualize it, it will form a sphere but nothing more.

We need some sort of data structure that has those attributes, I'm trying to find what it could be but feel free to pr if you know any.

if we want to put something on the south pole, we can insert new members at position -2 instead of -1, no need to do fancy stuff.

## name ideas
- Spherering
- Sphering
- jerksphere
- cybershpere
- Vestisphere
- websphere

we can play on the fact it’s a globe
- circumsphere
- hemisphere

## north pole
this is the main site of the webring, because its at the north pole it would be santa/christmas themed.
it would contain this:
- information about the sphere
- how to join
- the git repos
- a list of all participants (or a link to the json)
- possibly a [3d viewer of the sphere](#website-viewer)

for differents moments in the year, the site theme may change.  

## website viewer
This is to be done once the normal shpere is finished.
a webviewer just like google earth of the sphere.
we can click on the links and rotate the globe around.
Every site is assigned a patch of land.
You may draw on your land, there is no moderation on what you can draw, if you descide to draw a dick, you can, but I wont click on your site.
if the user doesnt provide a drawing, either words extracted from the site will be shown or leave it blank or something.
The countries shape are probably just simple squares although we could make some function with some perlin noise or something to make prettier borders.
when the sphere has new members, it would either make the distance between sites smaller or the planer bigger. That doesnt change anything about the structure only about the visualisation.
