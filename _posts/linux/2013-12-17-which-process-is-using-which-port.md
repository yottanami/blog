---
layout: post
title: Which process is using which port
date: '2013-12-17T12:14:00+03:30'
tags:
- netstat
- linux
author: yottanami
---
Easy way to figure out which process is using specific port in GNU/Linux :netstat -anpt | grep :PORTChange the PORT with port number like :netstat -anpt | grep :80
