+++
title = 'Hugo GitHub Issue #13280'
linkTitle = 'Home'
date = 2025-01-20T20:04:57-08:00
draft = false
details = 'https://github.com/gohugoio/hugo/issues/13280'
description = "Add Support for Embedding Mastodon and Fediverse Content"
+++

## Mastodon post

```text
{{</* mastodon url="https://socel.net/@BGP/113805114250504687" */>}}
```

{{< mastodon url="https://socel.net/@BGP/113805114250504687" >}}

## PeerTube video

```text
{{</* peertube url="https://toobnix.org/w/5jBegFpNbffA1nhmp32kqR" */>}}
```

{{< peertube url="https://toobnix.org/w/5jBegFpNbffA1nhmp32kqR" >}}

## PeerTube parameters

url
: (`string`) The URL of the PeerTube video.

start
: (`string`) The time, from the start of the video, when the player should start playing the video (e.g., `42s`, `6m7s`).

stop
: (`string`) The time, from the start of the video, when the player should stop playing the video (e.g., `42s`, `6m7s`).

loading
: (`string`) The loading attribute of the `iframe` element, either `eager` or `lazy`. Default is `eager`.

width
: (`int`) The width of the video in pixels. Responsive if `0`. Default is `0`.

allowFullScreen
: (`bool`) Whether to allow full screen playback. Default is `true`.

autoplay
: (`bool`) Whether to automatically play the video. Forces `mute` to `true`. Default is `false`.

controls
: (`bool`) Whether to display the video controls. Default is `true`.

displayLink
: (`bool`) Whether to display the video link. Default is `true`.

displayTitle
: (`bool`) Whether to display the video title. Default is `true`.

displayWarning
: (`bool`) Whether to display the privacy warning. Default is `true`.

loop
: (`bool`) Whether to indefinitely repeat the video. Default is `false`.

mute
: (`bool`) Whether to mute the video. Always `true` when `autoplay` is `true`. Default is `false`.

p2p
: (`bool`) Whether to enable peer-to-peer bandwidth sharing. Default is `true`.
