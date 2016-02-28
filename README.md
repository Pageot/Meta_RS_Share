# Pense-bête des meta-données pour les principaux réseaux sociaux

```html
<h2>Fondamentaux</h2>

<title>Page Title. Maximum length 60-70 characters</title>
<meta name="description" content="Page description. No longer than 155 characters." />

<h2>Facebook</h2>

<meta property="og:title" content="Title Here" />
<meta property="og:type" content="article" />
<meta property="og:url" content="http://www.example.com/" />
<meta property="og:image" content="http://example.com/image.jpg" />
<meta property="og:description" content="Description Here" />
<meta property="og:site_name" content="Site Name" />
<meta property="fb:admins" content="Facebook numeric ID" />

<h2>Twitter</h2>

<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@publisher_handle">
<meta name="twitter:title" content="Page Title">
<meta name="twitter:description" content="Page description less than 200 characters">
<meta name="twitter:creator" content="@author_handle">
<meta name="twitter:image:src" content="http://www.example.com/image.jpg">

<h2>Google + / Pinterest</h2>

<meta itemprop="name" content="The Name or Title Here">
<meta itemprop="description" content="This is the page description">
<!-- Facebook image must be at least 600x315px -->
<meta itemprop="image" content="http://www.example.com/image.jpg">

<h2>Google authorship</h2>

<link rel="author" href="https://plus.google.com/[Google+_Profile]/posts"/>
<link rel="publisher" href="https://plus.google.com/[Google+_Page_Profile]"/>

```

Quelques outils pour tester vos meta-données de réseaux sociaux

[Facebook Debugger](https://developers.facebook.com/tools/debug)
[Twitter validation tool](https://dev.twitter.com/docs/cards/validation/validator)
[Google Structured Data Testing Tool](http://www.google.com/webmasters/tools/richsnippets)
[Pinterest Rich Pins Validator](http://developers.pinterest.com/rich_pins/validator/)