---
author: admin
date: 2013-06-12 18:52:55+00:00
draft: false
title: When I just can't, Just Type
type: post
url: /archives/just_type_github/
categories:
- Featured
- Perspective
tags:
- AppleScript
- GitHub
- iA Writer
- Workflow
- Zen Mode
---

This spring has been an [interesting season](http://zachbeauvais.com/archives/all-change/). Often, I put words up on a screen to make my thoughts make sense. If I can organise the paragraphs into something resembling a coherent piece of writing, maybe my own plans and priorities can follow.

I use a [tumblr blog](http://tumblr.zachbeauvais.com) for many of these unpolished pieces, and I give myself a simple rule: Just Type.

I allow for correcting misspellings, and a light pass for punctuation, but I don't allow myself the chance to edit the actual content. If it's potentially libellous or too personal: it's deleted.

Today, I couldn't even just type. I couldn't organise my thoughts into words.

[![Screenshot of iA Writer Zen Mode](http://zachbeauvais.com/wp-content/uploads/2015/09/Screen-Shot-2013-06-12-at-18.31.53_sxwbht-300x197.png)
](http://zachbeauvais.com/wp-content/uploads/2015/09/Screen-Shot-2013-06-12-at-18.31.53_sxwbht.png)I did manage to procrastinate, and create an automated workflow for my Mac. From now on, whenever I feel ready to just type, I press: ⇧ ⌘ J. I am greeted with the beautiful [iA Writer](https://ia.net/writer/)'s Zen Mode asking me to "Just Type."

It's a simple [Alfred 2](http://www.alfredapp.com) workflow I've made [available on github](https://github.com/beauvais/just_type). It's a hotkey and AppleScript, which opens iA Writer, inserts the text "Just Type," and puts iA into Zen mode, giving me a big, blank space to type into.

The Workflow is only two steps, and it's trivial to change the hotkey. By modifying the AppleScript, it would also be very simple to change the application, the prompt text, and the zen-mode.

So, instead of trying to organise my thoughts, I organised a few files on my hard drive and pushed them to github.

If you're interested, the AppleScript goes:

https://gist.github.com/beauvais/5767998#file-just_type-scpt
