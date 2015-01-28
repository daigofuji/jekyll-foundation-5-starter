jekyll-foundation-5-starter
===========================

Start [a github pages](https://pages.github.com/) website powerd by [Jekyll](http://jekyllrb.com/docs/quickstart/) using [Foundation/SCSS](http://foundation.zurb.com/docs/sass.html) in under 5 minutes! 

### What it is.

Ever wanted a simple but nice looking responsive website as your project page or page for your repo? Are you in [a hackathon](http://baseballhackday.com) needing to put up a working website in munites? I do. Here is what I do, and I am sharing for you to use it, free. Free as in free speach AND free beer.

You can see [the working example site here](http://daigofuji.github.io/jekyll-foundation-5-starter/)

### For User & Organization Pages
See [documentation](https://help.github.com/articles/user-organization-and-project-pages/)

1. Fork this repo to your user or project
2. From the `settings` rename the repo to `username.github.io` naming scheme.

### For Project Pages
See [documentation](https://help.github.com/articles/user-organization-and-project-pages/#project-pages)

1. Create a `gh-pages` branch, i.e. `git checkout -b gh-pages`
2. [Download the contents of this repo](https://github.com/daigofuji/jekyll-foundation-5-starter/archive/master.zip)
3. Replace the entire branch contents with unzipped stuff
4. Add, Commit then Publish the branch to github, i.e. `git push --set-upstream origin gh-pages`

### To edit contents:
1. edit `_config.yml`
2. edit html/md files (hint: `_layouts/default.html` is the base)
3. edit sass and run `grunt` (hint: Try [editing `scss/_stettings.scss`](http://foundation.zurb.com/docs/using-sass.html))
4. edit `_include/nav.html` 

Use at your own resk, and follw licence restriction of each products used. Most are MIT (OK to use commercially).

### Useful command:

Run grunt to compile css from sass by simply run 

`grunt`

from your terminal. It will launch watch. <code>control-c</code> to stop.

You need to have grunt installed. <a href="http://daigo.org/2013/11/installing-npm-on-mavericks-macbook-pro/">This blog post</a> may be useful if you are like me and running Mac OS X.

To run jekyll locally, run 

`bundle exec jekyll serve --watch`

Your website should be viewable by going to [localhost:4000](http://localhost:4000/)

If you want to make sure foundation is up to date, try 

`foundation update`

(requires bower)

Github's doc on <a href="https://help.github.com/articles/using-jekyll-with-pages">how to use Jekyll on Github Pages</a>. 


### Special Thanks

Special thanks to <a href="https://github.com/h5bp/html5-boilerplate">HTML 5 Boilerplate</a> whose code I have based this on.

@kionoshp's <a href="https://github.com/kianoshp/SASS-CSS-Boilerplate">padding-margin</a>. Because it has become part of every site that I manage. 

and <a href="http://fortawesome.github.io/Font-Awesome/">Font Awesome</a> for bing awesome. 

