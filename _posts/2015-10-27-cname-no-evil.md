---
layout: page
title: CNAME no evil...
tags : [programming, internet, learning]
---

Setting up this blog has been an interesting journey.  I've redone the thing about 5 times and finally settled on using a combination of [Jekyll](https://jekyllrb.com/) and [Hyde](https://github.com/poole/hyde) (almost funny considering it took me so long to decide).  

Some of the frustrations I've run into so far:

* Instructions seem sparse and as a result setup took a few tries
* Switching between different setups can cause a major headache (<b>protip</b>: pick one before pushing to Github or fear the repo-moster)
* Markdown is a completely new language to me. While people seem to love the simplicity of it, it seems to lack features.  I am hoping that I will get used to using it as I blog more.
* Getting my domain hosted by 1&1 to point to my Github URL has proven to be rather difficult.  I've been researching this setup most of the evening and have yet to come up with a solution.  Current setup as follows:

	* Subdomain created for www
	* Set www Subdomain CNAME to point to username.github.io
	* Set main domain to redirect to www Subdomain
	* Create CNAME file with domain_name.com in it and push to Github

<b>Current status</b> my domain and blog are experiencing redirect loops and I hope it is just that the DNS changes have not fully propagated.

<img src="https://media.giphy.com/media/MmweDMiYqaBl6/giphy.gif"  height="180">


<b>Future plans</b>

1. validate and fix domain issues for the blog
2. enable Tag view of posts being created
3. drink a celebratory beer when complete or when a good effort has been detected 

