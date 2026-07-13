---
title: "Alan Cache : the best caching library? (Part 4)"
url: "https://medium.com/alan/alan-cache-the-best-caching-library-part-4-bac372c34c0d?source=rss----b2cb698c4e73---4"
date: "2026-03-27"
author: "Damien 'dams' Krotkine"
feed_url: "https://medium.com/feed/alan"
---
Side Effects, Background Work, and Warm Caches In Part 3 , we covered partial and distributed invalidation : how to surgically purge stale data across 300+ workers. Now let’s handle the tricky cases: cached functions with side effects, computations too slow to block users, and keeping critical caches permanently warm. 12.
