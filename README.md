<section id="about">
  <div class="about-container">
    <h2>About Me</h2>
    <p>
      Hello! I'm [Tu Nombre], a passionate web developer who loves creating clean, responsive websites and learning new technologies. I enjoy turning ideas into real products and solving challenges with code.
    </p>
    <p>
      When I'm not coding, you can find me reading, hiking, or playing video games. I'm currently exploring more about React and backend development.
    </p>
  </div>
</section>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi Web</title>
  <style>
    header {
      background-color: #28a745; /* Verde */
      color: white;
      padding: 20px;
      text-align: center;
      font-family: Arial, sans-serif;
    }
  </style>
</head>
<body>

  <header>
    <h1>Bienvenido a Mi Página</h1>
  </header>

  <section>
    <p>Este es el contenido de mi sitio web.</p>
  </section>

</body>
</html>

<style>
  .animated-text {
    font-size: 32px;
    animation: colorChange 2s infinite;
  }

  @keyframes colorChange {
    0%   { color: green; }
    25%  { color: orange; }
    50%  { color: blue; }
    75%  { color: purple; }
    100% { color: green; }
  }
</style>

<h2 class="animated-text">¡Bienvenido a mi sitio!</h2>

# site settings
title: Forty
subtitle: by HTML5 UP
email: youremailaddress@gmail.com
description: A responsive site template designed by HTML5 Up<br /> and released under the Creative Commons.
baseurl: "/forty-jekyll-theme" # the subpath of your site, e.g. /blog
url: # the base hostname & protocol for your site
author:
street_address: 1234 Somewhere Road
city: Nashville
state: TN
zip_code: 55555
country: United States of America
phone: (716) 555-5555

# homepage tiles
tiles-source: pages # accepts "posts" or "pages"
tiles-count: 6

# social settings (key must match name of font awesome icon)
# see https://fontawesome.com/icons?d=gallery&p=2&s=brands
# Icons are not shown if value is empty
# You need to restart jekyll for changes to have an effect
socials:
  GitHub: https://github.com/andrewbanchich
  GitLab:
  Google-Plus: https://plus.google.com/u/0/+AndrewBanchich
  Instagram:
  LinkedIn: https://www.linkedin.com/in/andrew-banchich-a4ba1195
  Twitter: https://twitter.com/andrewbanchich
  Facebook:
  Slack:

# build settings
markdown: kramdown

sass:
  style: compressed

exclude:
- "*.gemspec"
- LICENSE.md
- CONTRIBUTING.md
- README.md 
