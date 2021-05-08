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

_This changelog includes some Markdown and HTML syntax to facilitate updating translations._

**Note: Some code-level fixes are missing below, and will be added in May 2021.**


{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## VTT files

Translators: Here is the latest list of subtitles. You can use this and not need to find all the VTT additions below.

```
subtitles="W3C_INTRO_SFHI.ar.vtt|ar,W3C_INTRO_SFHI.de.vtt|de,W3C_INTRO_SFHI.es.vtt|es,W3C_INTRO_SFHI.fr.vtt|fr,W3C_INTRO_SFHI.gu.vtt|gu,W3C_INTRO_SFHI.hi.vtt|hi,W3C_INTRO_SFHI.kok.vtt|kok,W3C_INTRO_SFHI.ko.vtt|ko,W3C_INTRO_SFHI.ml.vtt|ml,W3C_INTRO_SFHI.mr.vtt|mr,W3C_INTRO_SFHI.nl.vtt|nl,W3C_INTRO_SFHI.pt-BR.vtt|pt-BR,W3C_INTRO_SFHI.te.vtt|te,W3C_INTRO_SFHI.zh.vtt|zh,W3C_INTRO_SFHI.ja.vtt|ja,W3C_INTRO_SFHI.it.vtt|it,W3C_INTRO_SFHI.hu.vtt|hu,W3C_INTRO_SFHI.el.vtt|el,W3C_INTRO_SFHI.ru.vtt|ru,W3C_INTRO_SFHI.cs.vtt|cs,W3C_INTRO_SFHI.id.vtt|id,W3C_INTRO_SFHI.fa.vtt|fa"
```

To set the video subtitles to default to your language:
1. Delete |default from: ``` captions="W3C_INTRO_SFHI.vtt|en|default" ``` so it's: ```captions="W3C_INTRO_SFHI.vtt|en" ```
2. Add |default after your language vtt. for example: ``` ,W3C_INTRO_SFHI.ar.vtt|ar|default, ```

## 2021-04May

* Added video subtitle files: ``` ,W3C_INTRO_SFHI.id.vtt|id,W3C_INTRO_SFHI.fa.vtt|fa ```

## 2020-08August

* Added video subtitle file: ``` ,W3C_INTRO_SFHI.cs.vtt|cs ```

## 2019-02Feb through 2019-05May

* Fixed typo "quite"->"quiet":<br>from: <q>For example, captions benefit anyone in a loud or in a quite environment.</q><br>&nbsp;&nbsp;&nbsp;&nbsp;to: <q>For example, captions benefit anyone in a loud or in a quiet environment.</q>
* Added to footer: <blockquote>Video clips developed with support from the <a href="https://www.w3.org/WAI/DEV/">WAI-DEV project</a>, co-funded by the European Commission. Translations managed with support from the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a>, funded by the Ford Foundation.</blockquote>
* Added quotes around "Language" in the [Translations section](https://www.w3.org/WAI/videos/standards-and-benefits/#translations).

## 2019-02Feb-21

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

* **Added to meta-data**: `nav_title: "Video Introduction" # A short title that is used in the navigation`<br>(Translators: Please provide a translation of "Video Introduction", or confirm the one we put in there.)

* Added link to changelog in the page footer.
