## David's HTML5 Template ##

This is a skeleton HTML5 project based on [HTML5 Boilerplate][h5bp] and [Initializr][init] that I use to get new sites started off right.

This differs from the Initializr base project in a couple of ways:

* All CSS styles have been converted to [SCSS][sass], with various modular bits (reset, media queries, base fonts and styles) moved out into partials. Some features (like the base styles) are disabled by default. I've also included several frequently-used mixins.

    When designing/developing, you can use the `sass --watch` command to automatically generate static CSS files from the SCSS sources:
    
        sass --watch css/scss:css --style compact

* For Ruby fans, a [Gemfile][bund] (including Rake and Sass 3.1) is included. The Rakefile doesn't do anything just yet, but it will.

* [jQuery][jqry] has been updated to 1.5.1, and [Modernizr][mdzr] has been updated to 1.7.

[h5bp]:http://html5boilerplate.com/
[init]:http://initializr.com/
[sass]:http://sass-lang.com
[bund]:http://gembundler.com
[jqry]:http://jquery.com
[mdzr]:http://modernizr.com