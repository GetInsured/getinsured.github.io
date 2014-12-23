---
layout: 			page
title: 				Contribute
permalink: 			/dev/contribute/
showheader: 		true
---

<ul>
	<li>Go to the <a href="//github.com/GetInsured/getinsured.github.io">GI Github Repository</a></li>
	<li>git clone <code>https://github.com/GetInsured/getinsured.github.io.git</code></li>
	<li>If you have permission issues, make sure the Github Administrator adds you as a contributor.</li>
</ul>

<h3>Run the branch locally in 3 easy steps:</h3>
<ol>
	<li>Simply cd into the <code>dev</code> folder</li>
	<li>Run <code>jekyll serve --watch</code>.</li>
	<li><span class="cheat">If you change some YAML configurations and you don't see it locally, restart the server.</span></li>
</ol>

<h3>Create a post:</h3>

<ul>
	<li>To create a post in the command line go to the dev folder.</li>
	<li><code>touch dev/_posts/2014-12-01-test.markdown</code></li>
	<li>A file is automatically created under <code>_posts</code>.</li>
	<li>The proper formatted needs <code>YYYY-MM-DD</code>.</li>
	<li>Specify your own front matter.</li>
	<li><span class="cheat">To have all the front matter already there, copy and paste an existing post and change the title and permalink yourself.</span></li>
</ul>

<h3>Relative links:</h3>

Use the following path for relative links: 
<pre>&lt;a href="&#123;&#123; BASE_PATH &#125;&#125;/test"&gt;test&lt;/a&gt;</pre>

<h3>Grunt.js</h3>

We've put Grunt.js in this workspace. Simply run Grunt within the <code>dev</code> folder. We've only included the most minimal grunt tasks. <span class="cheat">You only need grunt if you're changing styles.</span>

<ul>
	<li>Follow these <a href="http://24ways.org/2013/grunt-is-not-weird-and-hard/">super easy instructions</a> to install grunt in this project.</li>
	<li><code>npm install grunt-contrib-sass --save-dev</code></li>
	<li><code>npm install grunt-contrib-watch --save-dev</code></li>
	<li>The node_modules folder is already in the <code>.gitignore</code> file.</li>
</ul>

<h3>Jekyll</h3>

We are powering this documentation with <a href="http://jekyllrb.com/">Jekyll</a>. 

<h3>Troubleshooting</h3>

<ul>
	<li>
		<h4>I don't see my post.</h4>
		<p>Make sure you've specified the <code>permalink</code> in the front matter.</p>
	</li>
	<li>
		<h4>My header isn't showing up.</h4>
		<p>There should be an attribute in the front matter <code>showheader: true</code>.</p>
	</li>
</ul>