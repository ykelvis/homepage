---
title: qBittorrent
description: qBittorrent Widget Configuration
---

Learn more about [qBittorrent](https://github.com/qbittorrent/qBittorrent).

Uses the same username and password used to login from the web.

Allowed fields: `["leech", "download", "seed", "upload", "total", "error",
"checking", "moving", "activeDl", "activeUl", "active", "paused", "queued",
"stalled"]`.

```yaml
widget:
  type: qbittorrent
  url: http://qbittorrent.host.or.ip
  username: username
  password: password
```
