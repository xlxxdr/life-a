---
title: "{{ replace .Name "-" " " | title }}"
description: "{{ .Name }}"
keywords: "{{replace .Name "-" ","}}"
date: {{ .Date }}
lastmod: {{ .Date }}
categories:
 - java 
 - test
tags:
  - a
  - b
---

### This is a test for github action
