---
title: "Changelog for Video Introduction to Web Accessibility and W3C Standards"
title_html: 'Changelog for <a href="https://www.w3.org/WAI/videos/standards-and-benefits/">Video Introduction to Web Accessibility and W3C Standards</a>'
nav_title: "Changelog"
lang: en
permalink: /videos/standards-and-benefits/changelog/
ref: /videos/standards-and-benefits/changelog/
layout: default
github:
   repository: w3c/wai-video-standards-and-benefits
   path: 'changelog.md'
changelog: /videos/standards-and-benefits/changelog/
---

<!-- _This changelog includes some Markdown and HTML syntax to facilitate updating translations._ -->

## For Translators - VTT files

Here is the latest list of subtitles:

```
subtitles="W3C_INTRO_SFHI.ar.vtt|ar,W3C_INTRO_SFHI.de.vtt|de,W3C_INTRO_SFHI.es.vtt|es,W3C_INTRO_SFHI.fr.vtt|fr,W3C_INTRO_SFHI.gu.vtt|gu,W3C_INTRO_SFHI.hi.vtt|hi,W3C_INTRO_SFHI.kok.vtt|kok,W3C_INTRO_SFHI.ko.vtt|ko,W3C_INTRO_SFHI.ml.vtt|ml,W3C_INTRO_SFHI.mr.vtt|mr,W3C_INTRO_SFHI.nl.vtt|nl,W3C_INTRO_SFHI.pt-BR.vtt|pt-BR,W3C_INTRO_SFHI.te.vtt|te,W3C_INTRO_SFHI.zh.vtt|zh,W3C_INTRO_SFHI.ja.vtt|ja,W3C_INTRO_SFHI.it.vtt|it,W3C_INTRO_SFHI.hu.vtt|hu,W3C_INTRO_SFHI.el.vtt|el,W3C_INTRO_SFHI.ru.vtt|ru,W3C_INTRO_SFHI.cs.vtt|cs,W3C_INTRO_SFHI.id.vtt|id,W3C_INTRO_SFHI.fa.vtt|fa"
```

**To set the video subtitles to default to your language:**
1. Delete ```|default``` from: ``` captions="W3C_INTRO_SFHI.vtt|en|default" ``` so it's:<br><code>captions="W3C_INTRO_SFHI.vtt|en"</code>
2. Add ```|default``` after your language vtt. For example:<br><conde> ,W3C_INTRO_SFHI.ar.vtt|ar|default, </code>

## May 2021 updates

* Added to end of footer text (in the frontmatter near the top):
  ```Video clips developed with support from the <a href="https://www.w3.org/WAI/DEV/">WAI-DEV project</a>, co-funded by the European Commission. Translations managed with support from the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a>, funded by the Ford Foundation.```
  <br>(Put it inside the closing ```</p>``` )
  * Shawn to check:
    * ... list which ones...
  * Added to: ... list which ones...
  * Already had: ... list which ones...
* Added changelog:
  1. Added "changelog: /videos/standards-and-benefits/changelog/" between ref and layout:
   ```
   ref: /videos/standards-and-benefits/   # Do not change this
   changelog: /videos/standards-and-benefits/changelog/
   layout: default
   ```
  2. Added "CHANGELOG." after date:<br>
   ```First published 4 December 2017. CHANGELOG.```
    * Shawn to do: ... list which ones...

* Updated date:<br>
  ```last_updated: 2021-05-10```
  
_Thanks to Tolu Adegbite for work on May 2021 updates!_
