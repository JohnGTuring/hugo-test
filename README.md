baseURL = "https://gohugo.io"
title = "Hugo Themes"
author = "Steve Francia"
copyright = "Copyright © 2008–2019, Steve Francia and the Hugo Authors; all rights reserved."
paginate = 3
languageCode = "en"
DefaultContentLanguage = "en"
enableInlineShortcodes = true
# prevent build failures when using Hugo's Instagram shortcode due to deprecated Instagram API.
# See https://github.com/gohugoio/hugo/issues/7228#issuecomment-714490456
ignoreErrors = ["error-remote-getjson"]

[menu]

  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"
    weight = 10

[taxonomies]
category = "categories"
tag = "tags"
series = "series"

[privacy]

  [privacy.vimeo]
    disabled = false
    simple = true

  [privacy.twitter]
    disabled = false
    enableDNT = true
    simple = true

  [privacy.instagram]
    disabled = false
    simple = true

  [privacy.youtube]
    disabled = false
    privacyEnhanced = true

[services]

  [services.instagram]
    disableInlineCSS = true

  [services.twitter]
    disableInlineCSS = true
