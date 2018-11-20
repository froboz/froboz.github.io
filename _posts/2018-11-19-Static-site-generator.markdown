---
layout: post
title: "What I think about Static Site Generators"
headline:  "Blogs"
date:   2018-11-19
categories: Blogs
comments: true
---

**To go through such trouble to generate a static website..**

Did this save me any time? No. The extra formatting and filestructure required of jekyll, just to get jekyll to run at all which was a big problem for me because I was already running other stuff on port 4000... Who is markdown for? People that don't know HTML? Are you going to save time not writing tags? I didn't, I found myself looking up things I otherwise could've written straight away becuase I know it by heart. Because a knowledge of HTML is required to use
markdown in the first place we are learning to do something we already know how to do with a shorter syntax and it just dosen't give that much use here. Its not intuitive to me like HTML is.

As far as the functionality of templating html I don't think this works very well either, using javascript or php is cleaner faster and platform independant. Sure now I can make a static site with jekyll, does that translate to other static site generators? How much differes between them? Does it teach me anything that I can use for other things like javascript and php does? I don't think the answer to any of these questions is yes and therefor the answer to if I think its worthile to use static site generators is no.

Yes there is some power here with navigation generation and looping through files in a directory (posts) that is the one 'aha' moment I've had with jekyll but
what about if its not mainting this site? What if its a client that has no coding knowledge and needs a editor tool? This is 100% of customers that I've sold
websites to. Therefor I cannot financially defend using this. This is why content management systems power a great deal of websites today.

The type of project I see these being used for is maybe if I needed a website for a project that i'm going to maintain myself, but honestly I won't.


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