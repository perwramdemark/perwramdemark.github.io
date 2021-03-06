---
layout: post
title: HTTPS on GitHub Pages over custom domains
tags: github ssl https
---

Noticed that GitHub Pages gained support for [HTTPS over customer domains](https://blog.github.com/2018-05-01-github-pages-custom-domains-https/). Actually quite a few months ago. 

Adding HTTPS was a breeze. I just needed to update my DNS editor with four new IP address found [here](https://help.github.com/articles/troubleshooting-custom-domains/#dns-configuration-errors). 

Wait five minutes for your newly configured DNS settings to spread around the Internet. Then reconfirm the DNS configuration with below command in the terminal window.

<code class="js">
dig wramdemark.se +nostats +nocomments +nocmd
</code>

The above mentioned IP addresses should appear. After that I went into the Settings page on my GitHub Pages repository and re-added the custom domain. Voila, HTTPS spot on.

GitHub Pages are working together with the great organization [Let's Encrypt](https://letsencrypt.org) who is working for securing the Internet. I have already used Let's Encrypt in other projects, for instance when running my home automation system, [Home Assistant](https://www.home-assistant.io/demo/).