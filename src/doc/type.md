---
layout: doc
title: Type

active: type
---

<p class="lead">
	Headings, body text copy and some default inline elements.
</p>

<h3 class="panel-doc__heading">Headings</h3>
{% include examples/_headings.html %}
{% highlight html linenos %}
	{% include examples/_headings.html %}
{% endhighlight %}


<h3 class="panel-doc__heading">Body text</h3>
{% include examples/_p.html %}
{% highlight html linenos %}
	{% include examples/_p.html %}
{% endhighlight %}

<h3 class="panel-doc__heading">Inline elements</h3>
{% include examples/_inline.html %}
{% highlight html linenos %}
	{% include examples/_inline.html %}
{% endhighlight %}



<h3 class="panel-doc__heading">Lead</h3>
Use <code>.lead</code> to make lead text bigger than normal text.

<p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. At neque, nulla repellendus.</p>
{% highlight html linenos %}
	<p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. At neque, nulla repellendus.</p>
{% endhighlight %}