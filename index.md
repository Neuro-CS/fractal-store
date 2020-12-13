# <i class="fas fa-infinity"></i>

Welcome to my homepage! I'm an abstract artist specializing in fractals designed by Apophysis 7X and Mandelbulb 3D. Below you'll find links to my storefronts, social media accounts, and a gallery.

<!-- section break -->

## Merchandise

{%
  include card.html
  size="small"
  image="images/amazon.jpg"
  link="https://www.amazon.com/s?rh=n%3A7141123011%2Cp_4%3ARecursive+Diversions"
  heading="Amazon Store"
  row1="Here you can find clothing (t-shirts, hoodies, and sweatshirts) using my designs with all the convenience of Amazon printing & shipping."
%}

{%
  include card.html
  size="small"
  image="images/teepublic.jpg"
  link="http://tee.pub/lic/recursivediversions"
  heading="Teepublic"
  row1="This site will print on practically anything! You can purchase my designs as wall art, shirts, stickers, pillows, masks, and more."
%}

<!-- section break -->

## Gallery

A small gallery of recent artwork.

{%
  include gallery.html
  image1="images/cell.jpg"
  tooltip1="Fractal 1"
  image2="images/virus.jpg"
  tooltip2="Fractal 2"
  image3="images/cell.jpg"
  tooltip3="Fractal 3"
  image4="images/virus.jpg"
  image5="images/bacteria.jpg"
%}

<!-- section break -->

## Social Media

{% capture html %}
{%
  include portrait.html
  link="https://www.instagram.com/possiblyfractal/"
  image="images/instagram.jpg"
  name="Instagram"
  mini=true
%}
{%
  include portrait.html
  link="https://twitter.com/neuro_cam"
  image="images/twitter.jpg"
  name="Twitter"
  mini=true
%}
{%
  include portrait.html
  link="https://github.com/Neuro-CS"
  image="images/github.jpg"
  name="GitHub"
  mini=true
%}
{% endcapture %}

{% include centerer.html html=html %}
