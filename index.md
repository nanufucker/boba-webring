---
layout: default
---

Welcome to {{site.title}} webring: presently a tech demo for a webring hosted on GitHub pages.

Here are the [list of member sites]({{'/sites' | relative_url}}).

Here's how to [submit a new site]({{'/about#to-join' | relative_url}}) to this webring.

To create your own, fork [this repo]({{site.repository}}), customize `_config.yml`, clobber any existing files in `_websites` with your own list of sites, then enable GitHub pages on your fork!

<style type="text/css">
  iframe {
    border: none;
  }
</style>
<iframe src="{{'/sites/haddock' | absolute_url}}?stylesheet={{'/assets/alternate-embed.css' | absolute_url}}">
</iframe>
<script src="{{'/assets/parent.js' | absolute_url}}"></script>