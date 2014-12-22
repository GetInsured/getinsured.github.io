---
layout: 				post
title: 					"Contribute to this Repository"
description: 			""
category: 				lessons
tags: 					[]
permalink: 				/contribute
date:   				2014-12-01
---
{% include JB/setup %}

<h3>Contribute to this repository:</h3>

<ul>
	<li>Go to the <a href="//github.com/GetInsured/getinsured.github.io">GI Github Repository</a></li>
	<li>git clone <code>https://github.com/GetInsured/getinsured.github.io.git</code></li>
	<li>If you have permission issues, make sure the Github Administrator adds you as a contributor.</li>
	<li>To rewrite the permissions: <code>chmod -R 0777 gi-elizabeth.github.io</code></li>
</ul>

<h3>Create a post:</h3>

<ul>
	<li><code>rake post title="HELLO WORLD"</code></li>
	<li>A file is automatically created under <code>_posts</code>.</li>
	<li>The proper formatted filename and YAML front matter is already included.</li>
	<li>Specify your own title.</li>
	<li>This rake task will never overwrite existing posts unless you tell it to.</li>
</ul>

<h3>Relative links:</h3>

Use the following path for relative links: 
<pre>&lt;a href="&#123;&#123; BASE_PATH &#125;&#125;/test"&gt;test&lt;/a&gt;</pre>

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)