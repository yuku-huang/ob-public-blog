---
title: RoamFlavoredMarkdown
tags:
  - plugin/transformer
---

This plugin provides support for [Roam Research](https://roamresearch.com) compatibility. See [[Roam Research Compatibility]] for more information.

> [!note]
> For information on how to add, remove or configure plugins, see the [[Configuration#Plugins|Configuration]] page.

This plugin accepts the following configuration options:

- `orComponent`: If `true` (default), converts Roam {% if or == "ONE" or or == "TWO" or or == "THREE" %} shortcodes {% endif %} into HTML Dropdown options.
- `TODOComponent`: If `true` (default), converts Roam {% raw %}{{ TODO }}{% endraw %} shortcodes into HTML check boxes.
- `DONEComponent`: If `true` (default), converts Roam {% raw %}{{ DONE }}{% endraw %} shortcodes into checked HTML check boxes.
- `videoComponent`: If `true` (default), converts Roam {% raw %}{{ video_url }}{% endraw %} shortcodes into embeded HTML video.
- `audioComponent`: If `true` (default), converts Roam {% raw %}{{[[audio]]:URL}}{% endraw %} shortcodes into embeded HTML audio.
- `pdfComponent`: If `true` (default), converts Roam {% raw %}{{[[pdf]]:URL}}{% endraw %} shortcodes into embeded HTML PDF viewer.
- `blockquoteComponent`: If `true` (default), converts Roam {% raw %}{{[[>]]}}{% endraw %} shortcodes into Quartz blockquotes.

## API

- Category: Transformer
- Function name: `Plugin.RoamFlavoredMarkdown()`.
- Source: [`quartz/plugins/transformers/roam.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/transformers/roam.ts).
