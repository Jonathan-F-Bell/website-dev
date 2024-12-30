---
layout: post
title: Website Theory
date: 2024-12-28 18:32 -0500
---

> Design is not art. It's not about making things pretty or beautiful. Design is about conveying information to the viewer as efficiently and clearly as possible. If the end result happens to also look nice, that's just a bonus, not the goal. "

## Past Methods

As I embark on this redesign, it occurs to me that it may be interesting to let the code and accessibility goals inspire the design, rather than the other way around. Almost every site I've developed has started the same way - a design is created first, either by myself or a colleague, sometimes with pen and paper, often fully designed in Adobe XD or Figma.

Thus, the following development process tends to appear:
1. Create the design (or see the design someone else created)
2. Sanity check - do all the visuals and features seem doable in the requested development platform?
3. Start development, try to keep best practices and accessibility in mind
4. Twist the code to do what I need it to do, based on the design. Often leading to many hacky methods of doing things, because the client was already promised a certain design element or feature and we're limited to a requested platform (Wordpress, web flow, hubspot, etc.)
5. Make sure that everything is still accessible - try to fix anything that the hacky features, theme, or platform broke

## A New Theory

What if, instead of starting with the design, I start with the Web. Forget visuals, design, etc.. First, figure out what I need the website to do for me, what content it needs to include, what content it may need to include in the future. Then, start to build the website, using ONLY HTML - let the limitations lead to a usable and accessible design by default, since HTML, on its own, is [functional, high-performing, and accessible](https://motherfuckingwebsite.com/). 

Use this basic website to move into static site generation, which should create a website that is, technically, fully usable and intuitive without any CSS or JS (once generated), if not exactly pretty. 

Only then do I allow CSS to come in to play - as everything should already be semantically organized and accessible, my goal with the styling will be to improve USABILITY rather than "prettiness" - a better default font, color/contrast improvements, layout adjustments, etc.

I'm hoping JS will be unnecessary - but, we will try to avoid using any until the final stages, and only when absolutely needed. 

This method is likely not practical for any modern professional marketing website or web app. But, I am very curious to see what comes from a pure functionality first, visuals later design & development approach. 

One of my design professors once told me something to the following effect: Design is not art. It's not about making things pretty or beautiful. Design is about conveying information to the viewer as efficiently and clearly as possible. If the end result happens to also look nice, that's just a bonus, not the goal. This website redesign feels like my purest attempt at taking that advice to heart. 