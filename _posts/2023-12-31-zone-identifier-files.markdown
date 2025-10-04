---
layout: post
title:  "Zone Identifier Files"
date:   2023-12-31
---
Windows shocked the developer world in recent years by investing deeply in open source. They produced the most popular open source code editor in the world, Visual Studio Code, bought GitHub, bought NPM, and have a first class Linux solution on Windows called the Windows Subsystem for Linux (WSL). Impressive!

One thing that I haven’t figured out is why copy and pasting files to WSL leaves a copy of files with a Zone.Identifier extension. This litters the file directory and is an annoyance. To remove thise files recursively, you can use the following command from the root directory of your project.

{% highlight ruby %}
find . -name "*:Zone*" -type f -delete
{% endhighlight %}

Cheers!

