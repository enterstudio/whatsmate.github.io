---
layout: post
title: How to send WhatsApp Messages from PHP
subtitle: Using the WhatsMate WA Gateway REST API
published: true
---

This article shows you how to send a WhatsApp message from PHP.

Before the recipient can receive your WhatsApp message, she will need to register with the WhatsMate WA Gateway. Instructions are available on the [official site](http://www.whatsmate.net/whatsapp-gateway.html). *Unregistered users will never receive messages from the Gateway.*


To send a WhatsApp message from PHP, do this:

1. Copy the following source code to your script.  <script src="https://gist.github.com/whatsmate/39d45c6a0b8a1ce946a4.js"></script>
2. Specify your target recipient on line 6. Remember to include the country code.
3. Specify your message on line 7.
4. Visit the PHP page your just created to send your message.


The free trial account allows you to send up to 10 messages per day. [Upgrade to the Premium Account](http://www.whatsmate.net/premium-account.html) to send unlimited number of messages.

