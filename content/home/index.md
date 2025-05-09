---
# Page type is a Widget Page
type: landing

# THIS LINE IS ESSENTIAL for homepage
# headless: true

# 其他元数据
title: ""        # 让站点名称当作标题
date: 2025-05-09

sections:
  - block: people
    content:
      filter: admin
    design:
      view: card
      show_social: true
      columns: "4"

  - block: hero
    content:
      title: "Welcome to the Intelligent Systems Lab!"
      subtitle: "Research in intelligent systems for maritime and robotics"
      text: |
        Our research group is based under the MOVE research framework...
      image:
        filename: together.jpg
        alt: "Group Photo"
    design:
      view: split
      columns: "8"
---
