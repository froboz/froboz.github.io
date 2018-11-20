---
layout: post
title: "The open graph protocol"
headline:  "Blogs"
date:   2018-11-19
categories: Blogs
comments: true
---

Now this is something I like! I have used the OGP before on various sites for sharing content on facebook and other social media. The professional looking and quick results of using this is well worth the effort. Open graph uses meta tags to sort out what parts of your website you would like to show in a preview link, you can have a link title, a description and even if an image if you like. I have included the Open graph I used in this sites template below:

      <meta name="og:description" content="{ desc }">
      <meta name="og:title" content="{ site.title }">
      <meta name="og:url" content="{ url }">
      <meta name="og:type" content="article">
      <meta name="og:image" content="{ site.og_image }">

Normally I would not use something like jekylls desc for the description part of the open graph, you want this to relate to the content that you are linking to
a nice little apetizer that will tempt the reader to click your link to read more on your website.
Likewise I would also have set up the articles that I want to link with main image with a fallback default image if none had been set for that particular article.

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