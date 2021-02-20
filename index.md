---
layout: default
title: 'Ryan Choi: Canada SEO Digital Marketing & Advertising Expert'
cover: 'assets/images/volcanoes-sunset.jpg'
class: 'home-template'
navigation: true
logo: 'assets/images/blog-icon.png'
current: home
---
<!-- < default -->
<!-- The tag above means - insert everything in this file into the [body] of the default.hbs template -->

<!-- The big featured header  -->
<header class="main-header {% if page.cover %}"
        style="background-image: url({{ site.baseurl }}{{ page.cover }}) {% else %}no-cover{% endif %}">
    <nav class="main-nav overlay clearfix">
        {% if page.logo %}<a class="blog-logo" href="{{ site.baseurl }}"><img src="{{ site.baseurl }}{{ page.logo }}" alt="Blog Logo" /></a>{% endif %}
        {% if page.navigation %}
            <a class="menu-button icon-menu" href="#"><span class="word">Menu</span></a>
        {% endif %}
    </nav>
    <div class="vertical">
        <div class="main-header-content inner">
            <h1 class="page-title">{{ site.name }}</h1>
            <p class="page-description">My name is Ryan Choi, I am a Canadian internet entrepreneur who specializes in digital marketing, cryptocurrency, and search engine technologies. I am also an undergraduate student at one of Canada's top-rated research universities.
            </p>
        </div>
    </div>
    <a class="scroll-down icon-arrow-left" href="#content" data-offset="-45"><span class="hidden">Scroll Down</span></a>
</header>

<!-- The main content area on the homepage -->
<main id="content" class="content" role="main">

    <!-- The tag below includes the post loop - partials/loop.hbs -->
    {% include loop.html %}

</main>
