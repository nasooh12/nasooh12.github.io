---
widget: map
headless: true
weight: 25
title: 위치

# ⬇️ 핵심: 위젯 옵션은 content: 블록 안에!
content:
  # apple | google | mapbox | openstreetmap
  provider: openstreetmap
  zoom: 15
  center:
    latitude: 35.846
    longitude: 127.129
  markers:
    - title: Jeonbuk National University
      latitude: 35.846
      longitude: 127.129

# (선택) 레이아웃 조정
design:
  columns: '1'
---
