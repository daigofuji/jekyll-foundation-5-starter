---
layout: default
title: Welcome!
description: This is my site. Welcome.
keywords: github pages, Jekyll, foundation 5
---

<h1 class="mvl">Whoa! Jekyll, Foundation 5, HTML5 boilerplate and github pages!</h1>


<div class="row">
	<div class="medium-9 large-7 small-centered column">
		<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
		<p class="mbm">I've combined my locally installed <a href="http://foundation.zurb.com/docs/sass.html">libsass/grunt version of foundation 5</a>, <a href="http://html5boilerplate.com/">html5 boilder plate</a>, and Jekyll to be used for github pages! See <a href="http://jekyllrb.com/docs/home/">Jekyll's documentation</a>, <a href="http://foundation.zurb.com/docs/">the foundation documentations</a>, and <a href="https://help.github.com/categories/20/articles">GitHub pages help pages</a>.</p>

		<p class="mbl">You can see all <a href="https://github.com/daigofuji/jekyll-foundation-5-starter/tree/gh-pages"><i class="fa fa-github"> 	
		</i> my sources here</a>. I created this for my personal use, but if you'd like to use it, please feel free. Shout out <a href="http://daigo.org">daigo.org</a> or <a href="http://twitter.com/DaigoFuji">@DaigoFuji</a> are appreciated, but not required.</p>

		<div class="panel radius mvl">
			<p>You should probably update the <samp>_config.yml</samp> file, and edit <samp>scss/_setting.scss</samp> file. As well as <samp>scss/_custom.scss</samp>, where most the overrides are happening.</p>
		</div>



	</div>
</div>


<div class="row"> 

	<div class="large-4 columns">
		<p><a href="page-html-unit-test.html">foundation-example.html</a> shows how all the html tags are rendered. Foundation takes care of those out of the box.</p>
	</div>

	<div class="large-4 columns">
		<p>Another example are shown in <a href="page-foundation-example.html">foundation-example.html</a>. </p>
	</div>

	<div class="large-4 columns">
		<p>And finally, foundation's grid system, <a href="page-template-example.html">page-template-example</a> You can also <a href="http://foundation.zurb.com/templates.html">get more templates</a> from foundations home.</p>
	</div>

</div>

<div class="row">
	<div class="medium-9 large-7 small-centered column">
	
		<p class="mvl">And out of the box, this supports <a href="http://fortawesome.github.io/Font-Awesome/">
		<i class="fa fa-flag fa-lg">	
		</i>
		font awesome</a>, so you can go crazy with <a href="http://fortawesome.github.io/Font-Awesome/icons/">the icons</a>: <i class="fa fa-bitcoin fa-lg">	
		</i> <i class="fa fa-cog fa-spin fa-lg">
		</i>. </p> 

	</div>
</div>
