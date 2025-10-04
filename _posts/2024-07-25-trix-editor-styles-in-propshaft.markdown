---
layout: post
title:  "Trix Editor Styles in Propshaft"
date:   2024-07-25
---
We have moved our company's Rails apps as well as our clients to either 7.2.0.beta3 or 8 alpha. Using Propshaft has been great as it is one less thing to 'build' and has simplified our mental model even further.

That said, there is a change for getting Trix styling to work.
{% highlight css %}
<%= stylesheet_link_tag "trix", "actiontext", "application", "data-turbo-track": "reload" %>
{% endhighlight %}

That's it.

Cheers!
