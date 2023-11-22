# Video Introduction to Web Accessibility and W3C Standards

[![Netlify Status](https://api.netlify.com/api/v1/badges/86246365-26f1-4745-b693-797fa249a221/deploy-status)](https://app.netlify.com/sites/wai-video-standards-and-benefits/deploys)

## Translation Notes

1. Check if the [player is available in your translated language](https://github.com/ableplayer/ableplayer/blob/master/README.md#user-content-supported-languages).

2. Translate the "Translations" section of the page accordingly:
* **If the player _is_ available in the translated language**:
  * Translate the following words from the video player interface:
    * "Captions"
    * "Show transcript"
    * "Language"
  * Please also update the image per the instructions below.<br>_If you are not able to update the image, let us know._
     * Make a new image to replace [show-language.png](https://www.w3.org/WAI/content-images/wai-video-standards-and-benefits/show-language.png). The circle is 7px #eed009 / rgb(238,208,9).
     * Name it `show-language.[language shortcode].png`\
    For example: `show-language.fr.png`
     * Upload it to the [content-images folder](https://github.com/w3c/wai-video-standards-and-benefits/tree/master/content-images/wai-video-standards-and-benefits)
        * Select "Upload files"
        * Drag or choose the file
        * Select "Commit changes"
     * In your translation, add the language shortcode to the image path.
* **If the player is _not_ available in the translated language**:
   * Do not translate the following words from the video player interface; leave them in English:
     * "Captions"
     * "Show transcript"
     * "Language"
   * Mark up the English words with the lang attribute:\
  `<span lang="en">Captions</span>`.