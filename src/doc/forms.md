---
layout: doc
title: Forms

active: forms
type: doc
---

<p class="lead">
	Style individual form controls and utilize common layouts. 
</p>

<h3 class="panel-doc__heading">Default</h3>
{% include examples/forms/_forms.html %}
{% highlight html linenos %}
	{% include examples/forms/_forms.html %}
{% endhighlight %}


<h3 class="panel-doc__heading">Input groups</h3>
{% include examples/forms/_input-group.html %}
{% highlight html linenos %}
	{% include examples/forms/_input-group.html %}
{% endhighlight %}


<h3 class="panel-doc__heading">Form layout example</h3>
<div class="notice-message">
	<div class="notice notice--warning">
		<p>Always set the form's <code>width</code> to <code>100%</code>, and control the layout with grids or columns.</p>
	</div>
</div>
{% include examples/forms/_forms-layout.html %}
{% highlight html linenos %}
	{% include examples/forms/_forms-layout.html %}
{% endhighlight %}