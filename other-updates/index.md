---
layout: default
title: 기타 업데이트
---

{% assign other_updates_collection = site.collections | where: "label", "related_posts" | first %}
{% include update-archive.html title="기타 업데이트" updates=other_updates_collection.docs empty_text="기타 업데이트를 준비하고 있습니다." %}
