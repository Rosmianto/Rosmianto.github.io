---
title: Be A Better Embedded Engineer
parent: Blogs
nav_order: 2
---

A great engineer is the one who pursue to better him/herself. For sure we cannot
wait until we make mistakes to learn from. Internet is full of wisdom, especially
technical wisdom, but unfortunately they are too scattered making they hard to find.

I tried to compile such wisdom for embedded systems, because, well, I'm embedded engineer. This compilation is actually from my browser bookmarks that I've been collecting for almost 7 years. I created this firstly as a personal reminder for myself, and secondly to anyone out there. Hope this will benefit you who read this.

### Embedded Software
We know that firmware is still mainly written in C/C++, with Rust gaining traction lately. Decades old, C has proved itself to be a reliable and versatile language, but still, many people tink that they can cutcorner by doing some fancy tricks. Avoid tricks, because at the end, programming is about readability.

[Principles for C programming](https://drewdevault.com/2017/03/15/How-I-learned-to-stop-worrying-and-love-C.html)

Software is hard, but embedded software is harder. We are talking about tight timing, 
constrained resources (RAM, CPU speed, non-volatile memory size). Many young engineers still code firmware just like as they write desktop application. I think if we change our perspective to a lower level abstraction, we will be able to appreciate how many aspects of embedded software that we need to take care.

[Top 5 Embedded Software Problem Areas](https://betterembsw.blogspot.com/2016/05/top-5-embedded-software-problem-areas.html)