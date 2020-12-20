# <i class="fas fa-infinity"></i>

Welcome to my homepage! I'm a US-based abstract artist specializing in fractals designed by Apophysis 7X and Mandelbulb 3D. Below you'll find links to my storefronts, social media accounts, and a gallery. I'm slowly adding my art to these storefronts, so be sure to check back!

<!-- section break -->

## Merchandise

{%
  include card.html
  size="small"
  image="images/amazon.jpg"
  link="https://www.amazon.com/s?rh=n%3A7141123011%2Cp_4%3ARecursive+Diversions"
  heading="Amazon Store"
  row1="Here you can find clothing (t-shirts, hoodies, and sweatshirts) using my designs with all the convenience of Amazon printing & shipping. This will have the smallest selection but best prices."
%}

{%
  include card.html
  size="small"
  image="images/redbubble.jpg"
  link="https://www.redbubble.com/people/RecursiveStore/explore?asc=u&page=1&sortOrder=top%20selling"
  heading="Redbubble"
  row1="This site will print on practically anything! You can purchase my designs as wall art, shirts, laptop covers, dressed, shower curtains (why would you want that), clocks, posters, pillows, and more!"
%}

{%
  include card.html
  size="small"
  image="images/teepublic.jpg"
  link="http://tee.pub/lic/recursivediversions"
  heading="Teepublic"
  row1="Another print on demand service which allows you to purchase my artwork as shirts, hoodies, and posters. Since the upload time is very fast, you'll be able to find my newest designs here."
%}

<!-- section break -->

## Gallery

A small gallery of recent artwork.

{%
  include gallery.html
  image1="images/distortion.jpg"
  tooltip1="Distortion"
  image2="images/infinite-wave.jpg"
  tooltip2="Infinite Wave"
  image3="images/outside-the-box.jpg"
  tooltip3="Outside the Box"
  image4="images/identity.jpg"
  tooltip4="Identity"
  image5="images/transport.jpg"
  tooltip5="Transport"
  image6="images/transcend.jpg"
  tooltip6="Transcend"
  image7="images/pentagram.jpg"
  tooltip7="Pentagram"
  image8="images/hidden-glynnia.jpg"
  tooltip8="Hidden Glynnia"
  image9="images/rainbow-exerain.jpg"
  tooltip9="Exerain"


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
