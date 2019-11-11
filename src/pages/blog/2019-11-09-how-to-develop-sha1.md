---
templateKey: blog-post
title: How to develop SHA1
date: 2019-11-09T11:21:12.886Z
description: |-
  This post describes how to develop SHA-1 function.

  I read RCF and explain how to develop SHA-1 function using by C language.
featuredpost: true
featuredimage: /img/apple-touch-icon.png
tags:
  - Security
  - Hash
---
This time I developed SHA-1 function and use C language.

SHA-1 stands for US Secure Hash Algorithm 1 (SHA1);

This is RFC about SHA-1.\
<https://tools.ietf.org/html/rfc3174>

I read RFC and describe how to develop SHA-1 by using C language.

# RFC for SHA-1



> When a message of any length < 2^64 bits is input, the SHA-1 produces a 160-bit output called a message digest. 

\
This is the purpose of using hash algorithm.

> Signing the message digest rather than the message often improves the efficiency of the process because the message digest is usually much smaller in size than the message.
>
> Any change to the message in transit will, with very high probability, result in a different message digest, and the signature will fail to verify.



# Algorithm
