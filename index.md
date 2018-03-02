---
title: About Amazon Web Services
comments: true
---

> **NOTE**: In case you've come across this site via a Google search, I'm still writing this. I'll be finished soon, honest!

A short history of Amazon Web Services is contained in this [TechCrunch article](https://techcrunch.com/2016/07/02/andy-jassys-brief-history-of-the-genesis-of-aws/). Amazon was expanding fast and their infrastructure was struggling to cope. Inadvertently they became experts on data centre technology and the darlings of cloud computing.

## What does this mean for normal folk?

AWS is cheap, powerful and extremely flexible. Unfortunately the interface and documentation are aimed at developers and it's  difficult for the average person to set up and configure, which is why I've written this site—I made all the mistakes so you don't have to.

Here are some useful things you can do with AWS:

* Hosting your websites
* Storing files online
* Managing web domains and subdomains
* Sending and receiving email through a custom domain (à la <paul@example.com>). You can also configure GMail as your email client
* Use Amazon's free SSL service, which means you get an encrypted secure connection, `https://` in your URL, that nice padlock in your address bar and better Google page rankings.<sup><a href="#fn1" id="ref1">1</a></sup>

The elephant in the room here is WordPress (and maybe Drupal and Joomla), which relies on server-side scripting and databases to function—the methods described here are for static websites only. 

Although you *can* use AWS to host a WordPress site, setting this up and maintaining it is simply too complicated for me.
___
<sup id="fn1">1. If you *only* need secure hosting, then check out [Cloudflare](https://www.cloudflare.com), who offer free certificates. It's also easier to set up than the AWS flavour<a href="#ref1" title="Jump back to footnote 1 in the text.">↩</a></sup>
