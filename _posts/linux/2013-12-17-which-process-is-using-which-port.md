---
layout: post
title: Which process is using which port
date: '2013-12-17T12:14:00+03:30'
tags:
- netstat
- linux
tumblr_url: http://yottanami.tumblr.com/post/70277421785/which-process-is-using-which-port
---
Easy way to figure out which process is using specific port in GNU/Linux :netstat -anpt | grep :PORTChange the PORT with port number like :netstat -anpt | grep :80
