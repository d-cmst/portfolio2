---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "{{ replace .Name "-" " " | title }}"
url: "/{{ .Name | title | urlize }}"
subtitle: ""
summary: ""
authors: [ dcmst ]
tags: []
categories: []
keywords: []
date: {{ now.Format "2006-01-02" }}
publishDate: {{ now.Format "2006-01-02" }}
lastmod: {{ now.Format "2006-01-02" }}
featured: true
draft: true


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

{{% toc %}}
