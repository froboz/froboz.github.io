---
layout: post
title:  "Pre-compiling CSS"
headline:  "Blogs"
date:   2018-11-19 11:57:56 -0600
categories: Blogs
comments: true
---


**Well.. What do I say about pre-compiling css?** I'm afraid my first impression is that I want to turn away and run from it as far as I can.

The point is supposed to be to make it easier to write css as far as I understand but just the setup required to get started is daunting.
Once you have that down you now need to implement css in a way that you haven't before, as someone who as written css for a very long time
yes css absolutely has drawbacks in how it works and I understand that precompiling attempts to fix these potholes but the problem is that
this old dog is used walking around the potholes already. I do honestly not feel that I need anything that precompiling adds or that it
makes my life easier.

In fact for this project precompiling has cost me several hours, for a paid project I would've abandoned using
it within the first 20 minutes. I'm sure once you learn it well you get used to it but I have no idea how much time that will take and
as CSS is beginning to support more and more of the functionality that precompiling has added directly I do not feel motivated to learn
more about it in the slighest.

I used a few variables just to use them, yes variables can be useful in larger projects (in this one with the few variants of color and such
as there is, no not really.) since this is now supported in CSS - again what is the point of precompiling?

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://examination-1-1.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}