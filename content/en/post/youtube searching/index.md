---
title: YouTube Searching with specific country code
authors:
  - admin
tags:
  - API
  - WPF
date: 2024-09-22

summary: YouTube's search function uses the user's country code to search mainly for videos in the region.
---

<div style="text-align: justify; word-break: normal; text-justify: inter-word;">

<p>
YouTube's search function uses the user's country code to search mainly for videos in the region. Therefore, even if you want to search for foreign videos, the user's national video is recommended first. 
</p>

### GOAL

<p>
The goal is to implement a feature that searches for user-inputted keywords in a specific language and recommends videos from a specific country.
</p>

### APIs

<p>
First, I used the <a href="https://developers.naver.com/docs/papago/README.md">Papago API</a> to translate the words or sentences entered by the user into the specified language(It's not currently supported). The language detection feature identifies the language entered by the user and translates it into the specified language. 

Secondly, the <a href="https://developers.google.com/youtube">YouTube API</a> is utilized. The API is requested using the country code of the specified language and the translated text. The returned data is then presented as a list in the interface, including the video title, thumbnail, and video link.
</p>

### Result

<p>
This allows users to search for videos from their desired country in the language of their choice, without being limited by their own country.
</p>

### Attachment

{{% staticref "uploads/report.pdf" "newtab" %}}Download the report in Korean{{% /staticref %}}

</div>