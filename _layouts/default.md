<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="apple-touch-icon" href="/apple-touch-icon.png" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
    <link rel="icon" href="/favicon.ico" />
    <title>{{ title }}</title>
    <meta
      name="description"
      content="{{ site.description }}"
    />
    <meta name="author" content="{{ site.author }}" />
    <meta property="og:title" content="{{ title }}" />
    <meta
      property="og:description"
      content="{{ site.description }}"
    />
    <meta property="og:locale" content="{{ site.locale }}" />
    <meta property="og:site_name" content="{{ site.site_name }}" />
    <link href="/assets/main.css" rel="stylesheet"/>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cutive+Mono&display=swap" rel="stylesheet">

  </head>
  <body>
      <nav class="">
        <a href="/" class="">Home</a>
        <a href="/#jobs" class="">Jobs</a>
  </nav>

<main class="">
        {{ content }}
</main>
    <footer class="">
      {% include footer.html %}
    </footer>
  </body>
</html>
