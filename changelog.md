---
title: "Changelog for Video Introduction to Web Accessibility and W3C Standards"
title_html: 'Changelog for <a href="https://www.w3.org/WAI/videos/standards-and-benefits/">Video Introduction to Web Accessibility and W3C Standards</a>'
nav_title: "Changelog"
lang: en
last_updated: 2019-12-20 
permalink: /videos/standards-and-benefits/changelog/
ref: /videos/standards-and-benefits/changelog/
layout: default
github:
   repository: w3c/wai-video-standards-and-benefits
   path: 'changelog.md'
changelog: /videos/standards-and-benefits/changelog/
footer: >   # Translate all the words below, including "Date:" and "Editor:". Do not change these dates.
   <p><strong>Date:</strong> Updated 20 February 2019. First published 4 December 2017. CHANGELOG.</p>
   <p>Project lead: <a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>, <a href="https://www.w3.org/People/Brewer/">Judy Brewer</a>, <a href="https://www.w3.org/People/yatil/">Eric Eggert</a>. Videographer and video editor: Ulrich Grimm, av-design GmbH.</p>
---

## 20 February 2019

### Added:

* Added `nav_title` to meta-data to be used in navigation and when a shorter title is needed: 
  
  `nav_title: "Video Introduction" # A short title that is used in the navigation`

* This changelog, adding a reference to the changelog file to the meta-data and also making modifications to the footer:
  
  ```html
  <p><strong>Date:</strong> Updated 20 February 2019. First published 4 December 2017. <a href="./changelog/">Changelog</a>.</p>
  ```

  (Note: Translators don't need to implement this change, it is automatically added with the translated link text.)

### Changed:

* Clarified how to find media files on the W3C server, including subtitles:

  ```markdown
  {% raw %}{% comment %}On the W3C website: http://media.w3.org/@@.mp4 {% endcomment %}{% endraw %}
  ```
  to: 

  ``` markdown
  {% raw %}On the W3C website — video: http://media.w3.org/wai/accessibility-intro/intro.mp4, English captions/subtitles file (VTT): http://media.w3.org/wai/accessibility-intro/W3C_INTRO_SFHI.en.vtt, list of other language VTT files: http://media.w3.org/wai/accessibility-intro/ 
  {% comment %}# For translations, replace: "English captions/subtitles file (VTT): http://media.w3.org/wai/accessibility-intro/W3C_INTRO_SFHI.en.vtt", with: "[language] captions/subtitles file (VTT): http://media.w3.org/wai/accessibility-intro/W3C_INTRO_SFHI.[lang code].vtt" {% endcomment %}{% endraw %}
  ```
 
