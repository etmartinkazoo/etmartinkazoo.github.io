---
layout: post
title:  "Chatty Windows"
date:   2024-03-23
---
Windows is 'chatty'. Especially with its home base back in Redmond. You can shut that up by using the Chocolatey package manager to install O&O ShutUp10. I turn everything in Windows 11 off with the exception of my camera and microphone because I need them for video calls.

If you haven't installed Chocolatey, you will need to do the following:
{% highlight ruby %}
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
{% endhighlight %}

After that, you are ready with the following:choco install shutup10
Win+R and type OOSU10

Cheers!
