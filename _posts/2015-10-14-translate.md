---
layout: post
title: "非固定宽度元素的垂直居中方式"
description: "应用 translate 实现垂直居中对齐处理"
headline: "应用 translate 实现垂直居中对齐处理"
categories: personal
tags:
  - blogging
  - jekyll
image:
  feature: "website-speed.jpg"
  credit: spreadeffect.com
  creditlink: "http://www.spreadeffect.com/blog/improve-website-speed/"
comments: false
mathjax: null
featured: true
published: true
---

>&quot;应用 translate 实现垂直居中对齐处理&quot;
><small><cite title="Plato">galaxybing</cite></small>

    <style>
		html, body {
			margin: 0;
			padding: 0;
			width: 100%;
			height: 100%;
		}
		#demo {
			position: absolute;
			left: 50%;
			top: 50%;
			-webkit-transform: translate(-50%, -50%);
			transform: translate(-50%, -50%);
		}
	</style>

<div id="demo" style="border:1px solid red;width:200px;height:500px;background-color:#eee;"></div>


[^1]: This domain previously hosted a Wordpress blog.
