---
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
author: FelicianoTech
date: "{{ .Date }}"
# Choose one, delete the others
categories:
  - "Organizing"
  - "Attending"
  - "EventHunt"
tags:
  - ""
# Belongs in assets/img/feature
feature: "something.png"
# featureHide will show image on social but not in actual blog post
featureHide: true
---

Introduction paragraph to the post.
The more HTML tag below can be used to manually set a summary (before the tag) for the post.
Otherwise, the first seven words will be used by default.

<!--more-->

Each sentence should be its own line in the text editor.
The rendered blog will still appear in paragraphs like normal, but one line-per-line allows for better merge reviews with git.
