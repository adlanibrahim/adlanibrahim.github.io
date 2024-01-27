---
title:  "Uploading a CV"
mathjax: true
layout: post
categories: media
---

While I didn't face much troubles tweaking my profile, uploading and showing my CV as I wanted was a frustrating job, however. The uploading part was an easy one. Linking it to my page required a little effort.

## Uploading a CV as a pdf

In your github code page just click uploading a file as this screenshot shows after you choose your pdf don't forget to commit these changes.
![Screenshot](/assets/Screenshot.png)

Next step is creating a html file in your github main page, and it should bear your cv name, like: mine was AdlanCV.pdf so my html file will be named as: AdlanCV.html
once you've created a html file, next step is to open it to edit it in place, final step is to write these lines of codes: 

{ % highlight %}

<object data="{{ your_website_name.github.io }}{{ site.baseurl }}/AdlanCV.pdf" type="application/pdf"></object>

{% endhighlight %}

that's it! don't forget to replace AdlanCV.pdf with your cv name.

In future I may change how my cv page behave, like instead of downloading it, I want to open and display it in a new tab.
