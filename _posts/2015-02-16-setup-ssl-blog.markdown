---
layout: post
published: false
title:  "A blog with Github Pages and Cloudflare in five minutes"
date:   2015-02-16 11:15:52
categories: blog
tags: git SSL DNS siteperf
---
## When the platform gets in the way
I have been motivated to publish a blog for years. I have a lot of ideas for content but the hurdle was having to negotiate a cumbersome blogging platform like [Wordpress][wordpress] or a wallet buster like [Typepad](http://www.typepad.com/pricing). Blogger and tumblr are a lot more streamlined but control over the look and feel is [exasperatingly constrained](https://www.tumblr.com/docs/en/custom_themes). I wanted more flexibility and simplicity. I wanted it to be free and I wanted it to get out of the way. A lot of [prominent](http://getbootstrap.com/) open-source projects were using [GitHub Pages][gh-pages] as their landing page with great success. They were engaging, simple designs that popped.

GitHub Pages has fantastic [documention][gh-docs]. Site generation is done with [Jekyll][jekyll-docs]: a straightforward template system that I already have some experience with working on [Gitlab][gitlab]. The notion that the act of pushing changes to the upstream remote completes the publishing process has incredible appeal.

Once I started working, my blog came together quickly. It was online and viable in five minutes. I'd love to share the steps I took to get the blog online.

## Requirements

I had some requirements requirements I was looking for in a blog and associated workflow:

+ Must be SSL terminated
+ Ease of local testing
+ Publishing content should be simple
+ Supports pure HTML, [SASS][sass]/CSS, and javascript
+ Support for custom domains

## Register a domain
Using a custom [domain](https://en.wikipedia.org/wiki/Domain_name) that you registered gives your blog identity and flair. You don't _have_ to perform this step---GitHub Pages are served at https://username.github.io/ out-of-the-box. I registered with [Google Domains][domains] because it's simple, has enough features, and gets out of the way. All I really need is the ability to forward the domain which really just boils down to a single feature.

### What is domain forwarding?

> <strong>Tip</strong> Domain forwarding is
{: .tip}

Don't worry about domain forwarding just yet, we'll set that up in the next few steps.

## If you have a Github you're 90% done

## Why SSL terminate?

## Cloudflare's site performance features

## Discussion
The idea of introducing the words of throbbing masses that is the Internet onto your newly minted blog might seem downright repellent. But here me out here.

Disqus is an interaction platform that allows visitors to leave comments on your posts with bare minimum installation. It simply involves creating a Disqus account and pasting some embedded javascript.

## It's important to analyze your traffic

## Custom 404 pages

[Building a blog with Jekyll and Github pages]:      http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/
[dns-basics]: https://support.google.com/a/answer/48090?hl=en
[domains]: https://domains.google.com/
[gh-docs]: https://help.github.com/categories/github-pages-basics/
[gh-pages]: https://pages.github.com/
[gitlab]: https://about.gitlab.com
[jekyll-docs]: http://jekyllrb.com/docs/home/
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[sass]: http://sass-lang.com
[wordpress]: https://wordpress.com/