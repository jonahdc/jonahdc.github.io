---
layout: post
title:  "Prestashop Error: Server 500"
date:   2016-02-02 12:12:12 +0800
categories: Linux
excerpt_separator: <!--more-->
---
Came across an Internal Server `500` upon clicking `Add Product` on Prestashop Catalog page. The message wasn't as helpful as I hoped - *will post a photo if I get the time to replicate it*.

The solution is to make sure you have proper permissions set for relevant directories. To get a hint on what these relevant directories are, simply click on `Advanced Parameters` and under `Check Your Configuration` panel you would find any configurations that require fixing. 
