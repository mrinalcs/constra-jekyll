<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }}</title>
  <meta name="description" content="{{ page.description }}">
    <!-- Bootstrap -->
  <link rel="stylesheet" href="/plugins/bootstrap/bootstrap.min.css">
  <!-- FontAwesome -->
  <link rel="stylesheet" href="/plugins/fontawesome/css/all.min.css">
  <!-- Animation -->
  <link rel="stylesheet" href="/plugins/animate-css/animate.css">
  <!-- slick Carousel -->
  <link rel="stylesheet" href="/plugins/slick/slick.css">
  <link rel="stylesheet" href="/plugins/slick/slick-theme.css">
  <!-- Colorbox -->
  <link rel="stylesheet" href="/plugins/colorbox/colorbox.css">
  <!-- Template styles-->
  <link rel="stylesheet" href="/css/style.css">
  <!-- Favicon -->
  <link rel="icon" href="favicon.png">
  <!-- Other meta tags -->
  <meta property="og:title" content="{{ page.og_title }}">
  <meta property="og:description" content="{{ page.og_description }}">
  <meta property="og:image" content="{{ page.og_image | absolute_url }}">
  <!-- Other OG tags -->
</head>
<body>
<div class="body-inner">
    <!-- Topbar -->
    {% include top-bar.md %}
    <!-- Header navigation menu -->
  <header id="header" class="header-two">
    {% include header.md %}
  </header>
   
  <!-- Content -->
  
    {{ content }}
   
    <footer id="footer" class="footer bg-overlay">
    <!-- Footer -->
    {% include footer.md %}
   </footer>


   
  <!-- initialize jQuery Library -->
  <script src="/plugins/jQuery/jquery.min.js"></script>
  <!-- Bootstrap jQuery -->
  <script src="/plugins/bootstrap/bootstrap.min.js" defer></script>
  <!-- Slick Carousel -->
  <script src="/plugins/slick/slick.min.js"></script>
  <script src="/plugins/slick/slick-animation.min.js"></script>
  <!-- Color box -->
  <script src="/plugins/colorbox/jquery.colorbox.js"></script>
  <!-- shuffle -->
  <script src="/plugins/shuffle/shuffle.min.js" defer></script>


  <!-- Google Map API Key-->
  <script src="" defer></script>
  <!-- Google Map Plugin-->
  <script src="/plugins/google-map/map.js" defer></script>

  <!-- Template custom -->
  <script src="/js/script.js"></script>
      </div><!-- Body inner end -->
</body>
</html>
