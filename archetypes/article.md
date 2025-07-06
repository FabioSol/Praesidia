---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: article
weight: 10
draft: false
---

This is the article: {{ replace .Name "-" " " | title }}.
