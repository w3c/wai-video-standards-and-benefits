---
title: "Changelog for Video Introduction to Web Accessibility and W3C Standards"
title_html: 'Changelog for <a href="https://www.w3.org/WAI/videos/standards-and-benefits/">Video Introduction to Web Accessibility and W3C Standards</a>'
nav_title: "Changelog"
lang: en
last_updated: 2019-12-21
permalink: /videos/standards-and-benefits/changelog/
ref: /videos/standards-and-benefits/changelog/
layout: default
github:
   repository: w3c/wai-video-standards-and-benefits
   path: 'changelog.md'
changelog: /videos/standards-and-benefits/changelog/
footer: >   # Translate all the words below, including "Date:" and "Editor:". Do not change these dates.
   <p><strong>Date:</strong> Updated 21 February 2019. First published 4 December 2017. CHANGELOG.</p>
   <p>Project lead: <a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>, <a href="https://www.w3.org/People/Brewer/">Judy Brewer</a>, <a href="https://www.w3.org/People/yatil/">Eric Eggert</a>. Videographer and video editor: Ulrich Grimm, av-design GmbH.</p>
doc-note-message: >
  <p>Note: Text color in this page will be fixed before it is published in early March 2019.</a></p>
---

_This changelog includes Markdown syntax to faciliate updating translations._

## 21 February 2019

* **Changed all 4 bullets under the video, after "This video information is available"** to:

  ```markdown
  * **In different languages** — [Instructions to see subtitles and transcripts](#translations) are below
  * As a **[Text Transcript with Description of Visuals](#transcript)** below
  * [On YouTube](https://www.youtube.com/watch?v=20SHvU2PKsM)
  * On a W3C server — [video (file format: MP4, file size: 28MB)](http://media.w3.org/wai/accessibility-intro/intro.mp4), [English captions file (VTT)](http://media.w3.org/wai/accessibility-intro/W3C_INTRO_SFHI.en.vtt), [list of other language files](http://media.w3.org/wai/accessibility-intro/)
  {%raw%}{% comment %}# For translations, replace:
  "[English captions file (VTT)](http://media.w3.org/wai/accessibility-intro/W3C_INTRO_SFHI.en.vtt)", with translation of:
  "[[your language] subtitle file (VTT)](http://media.w3.org/wai/accessibility-intro/W3C_INTRO_SFHI.[lang code].vtt)".
  {% endcomment %}{%endraw%}
  ```

* **Changed paragraph under [Translate into Other Languages heading](https://www.w3.org/WAI/videos/standards-and-benefits/#translate-into-other-languages)** to:

  ```markdown
  We welcome additional translations. If you translate the [VTT file]({{ "/content-images/wai-video-standards-and-benefits/W3C_INTRO_SFHI.vtt" | relative_url }}), please send it to <public-wai-translations@w3.org>. If you might want to translate this entire web page or others, please see [Translating WAI Resources](https://www.w3.org/WAI/about/translating/).
  ```

* **Added sentence/paragraph under [Translations heading](https://www.w3.org/WAI/videos/standards-and-benefits/#translations)**:

  ```markdown
  Translations are available as subtitles and transcripts.<br>
  {%raw%}{% comment %}# For translations: The sentence above will change when we publish the translations. In your translation, please replace the paragraph above with: "There are some translations of this entire web page. They are linked at the top of this page.<br>There are **more translations of just the video**. They are available as subtitles and transcripts."<br>
  {% endcomment %}{%endraw%}
  ```

* **Added to meta-data**: `nav_title: "Video Introduction" # A short title that is used in the navigation`<br>(Translators: Please provide a transation of "Video Introduction", or confirm the one we put in there.)

* Added link to changelog in the page footer.<br>(Translators: You do not need to do anything for this; it is added automatically.)
