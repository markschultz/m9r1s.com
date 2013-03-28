---
layout: post
title: "literate_haskell"
date: 2013-03-15 14:51
comments: true
categories: test
---

This is a literate haskell test

Recursion
---------

This recursive fib function was written using guards

> fibr :: Integer -> Integer
> fibr n
>   | n == 0 = 0
>   | n == 1 = 1
>   | n > 1 = fibr (n-1) + fibr (n-2)

Now lets test a gist:

{% gist 3141563 %}
