---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: theme002
bg-img: /img/ci-bg.jpg

banner:
- image: /img/ci-subscribe.jpg
  title: Subscribe to our list
  url: /subscribe/
- image: /img/ci-c001-cover.jpg
  title: Browse Collection 001
  url: http://www.instagram.com/cultureintersects

mission:
- bg: /img/mission_bg.jpg
  subtitle: A News Platform
  title: Sharing the blueprints, partnerships + industry news for black culture + business
  cta_title: Follow our Journey

stream:
- bg: /img/ci-bg-003.png
  subtitle: Stream
  title: Culture Intersects x Sounds
  playlist: https://tidal.com/browse/playlist/976f21a5-3fd6-4e24-979e-06c396f33f46
  playlist_title_cta: Listen on Tidal
  playlist_img: /img/ci-stream.png
---

<!-- banner.html is in theme layout, variables provided above -->

<!-- data stored in /portfolio -->
{% include portfolio.html %}

<!-- data stored in variables above -->
{% include mission.html %}

<!-- data stored in variables above -->
{% include stream.html %}