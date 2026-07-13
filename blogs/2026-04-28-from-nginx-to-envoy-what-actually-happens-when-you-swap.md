---
title: "From nginx to Envoy: What Actually Happens When You Swap Your Proxy in Production"
url: "https://medium.com/alan/from-nginx-to-envoy-what-actually-happens-when-you-swap-your-proxy-in-production-8a6d0bae82d5?source=rss----b2cb698c4e73---4"
date: "2026-04-28"
author: "William Occelli"
feed_url: "https://medium.com/feed/alan"
---
At Alan , we run over a hundred services on Kubernetes managed through Qovery . For years, all our ingress traffic flowed through the nginx Ingress Controller , the de facto standard for routing HTTP traffic into Kubernetes clusters. In late 2025, Kubernetes announced it would be retiring its nginx Ingress Controller.
