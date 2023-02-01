---
title: "Layout: Header Video"
header:
  # video:
  #   id: -PVofD2A9t8
  #   provider: youtube
categories:
  - Layout
  - Uncategorized
tags:
  - video
  - layout
---

This post should display a **header with a responsive video**, if the theme supports it.


## ADIO
{% include video id="QflAEJzDn5A" provider="youtube" %}

Although audiobooks are increasingly being used, people tend to perceive audiobook experiences as ’not real reading’ due to its in- tangibility and ephemerality. In this paper, we developed ADIO, a device augmenting audiobook experience through representing personal listening state in the form of an interactive physical book- shelf. ADIO displays a user’s listening progress through a pendant’s changing length and the user’s digital audiobook archive titles. The result of our four-week in-feld study with six participants revealed that ADIO provided proof of the user’s listening-to, which brought a sense of reading and gave a trigger for recalling the listened-to audiobook content. Additionally, audiobooks’ improved visibility reminded participants to listen to them, and ADIO’s physical inter- action allowed participants to form personal patterns for listening to audiobooks. Our fndings proposed new methods for augmenting the audiobook listening experience at three stages and further im- plications for designing physical curation on users’ digital archives.





| Parameter  | Required     | Description |
|----------  |---------     | ----------- |
| `id`       | **Required** | ID of the video |
| `provider` | **Required** | Hosting provider of the video, either `youtube` or `vimeo` |


## Settings

| Parameter  | Required     | Description |
|----------  |---------     | ----------- |
| `id`       | **Required** | ID of the video |
| `provider` | **Required** | Hosting provider of the video, either `youtube` or `vimeo` |

### YouTube

To embed the following YouTube video at url `https://www.youtube.com/watch?v=-PVofD2A9t8` (long version) or `https://youtu.be/-PVofD2A9t8` (short version) into a post or page's main content you'd use: 

```liquid
{% raw %}{% include video id="-PVofD2A9t8" provider="youtube" %}{% endraw %}
```

{% include video id="-PVofD2A9t8" provider="youtube" %}

To embed it as a video header you'd use the following YAML Front Matter

```yaml
header:
  video:
    id: -PVofD2A9t8
    provider: youtube
```

### Vimeo

To embed the following Vimeo video at url `https://vimeo.com/212731897` into a post or page's main content you'd use: 

```liquid
{% raw %}{% include video id="212731897" provider="vimeo" %}{% endraw %}
```

{% include video id="212731897" provider="vimeo" %}

To embed it as a video header you'd use the following YAML Front Matter

```yaml
header:
  video:
    id: 212731897
    provider: vimeo
```