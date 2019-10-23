---
layout: post
title: Remove/Disable ligature usage for chrome on android
categories: Blog Code
---
Adding this to CSS code solved the problem of ligatures being automatically used in headings
<br>
```
h1 {text-rendering: optimizeSpeed;
    font-feature-settings: unset;
    font-variant: normal;
    }
```
<br>
Some might require adding spacing between letters via 
<br>
```
letter-spacing: 0.1px;
```
Source: [Stackoverflow](https://stackoverflow.com/questions/37702864/disabling-ligatures-and-text-figures-in-open-type-font)
