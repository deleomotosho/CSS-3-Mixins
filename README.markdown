[Sass makes CSS fun again -- in doubt?](http://sass-lang.com/)
---------------------------------------------------------------

$ gem install sass
$ mv style.css style.scss
$ sass  --watch style.scss:style.css
$ clone git@github.com:delomos/CSS-3-Maxins.git .

This file contains commonly used CSS3 styling @maxin. In your 'style.scss' file add the declaration:

@import "maxin_template"
