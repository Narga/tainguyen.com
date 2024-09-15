---
title: "Danh sách bài viết"
---
{{ range .Pages }}
  <h2><a href="{{ .Permalink }}">{{ .Title }}</a></h2>
  <p>{{ .Summary }}</p>
{{ end }}
