---
layout: doc
title: Images

active: images
type: doc
---

<p class="lead">
	Image sizing, responsive and more.
</p>


<h3 class="panel-doc__heading">Responsive images</h3>
Default <code>img</code> tag is always set <code>width</code> to <code>100%</code> and <code>height</code> to <code>auto</code>. Then we wrap them with <code>.img--thumbnail</code>, <code>.img--small</code>, <code>.img--medium</code>, <code>.img--large</code>, <code>.img--xlarge</code>and css <code>object-fit: cover</code> for different sizing and responsive.
<br /><br />

{% include examples/images/_image-size.html %}
{% highlight html linenos %}
	{% include examples/images/_image-size.html %}
{% endhighlight %}


<h3 class="panel-doc__heading">Figures and captions</h3>
{% include examples/images/_figure.html %}
{% highlight html linenos %}
	{% include examples/images/_figure.html %}
{% endhighlight %}


<h3 class="panel-doc__heading">Zoom</h3>
<p><a href="https://github.com/fat/zoom.js" title="zoomjs" target="_blank">Zoomjs</a> - A simple jQuery plugin for image zooming; as seen on Medium.</p>


<div class="notice-message">
	<div class="notice notice--warning">
		Require javascript.
	</div>
</div>


{% include examples/images/_image-zoom.html %}
{% highlight html linenos %}
	{% include examples/images/_image-zoom.html %}
{% endhighlight %}