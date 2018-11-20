---
layout: post
title: "Robots VS Humans"
headline:  "Blogs"
date:   2018-11-19
categories: Blogs
comments: true
---

**Robots.txt**

A simple textfile in the root of your domain that instructs search engine "spiders" (bots that crawl websites for information to add to their search engines) what parts of your website they are allowed to access.
I decided to write a robots.txt that only allows googles robot and allows it anywhere. If you have a website you most likely want google to know as much about it as possible, if you can avoid some spambots on the other hand that would be nice.

**Humans.txt**

This is sort of a credits file, it lets you know who has worked on the website doing what, possible contact information for them etc. This was my first time using one of these. I don't know, even the page where this is presented it dosen't take itself seriously. Is anyone going to look at this ever? Possibly maybe some very serious headhunters looking for new staff and I suppose those are the ones you'd want to look at it. Though honestly since usually HR is the ones hiring and they have no clue about this sort of thing I don't see the point.

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