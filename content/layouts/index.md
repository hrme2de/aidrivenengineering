---
title: "Welcome to AI Driven Engineering"
---

# Latest Posts

<ul>
{{ range where .Site.RegularPages "Type" "posts" | first 10 }}
  <li><a href="{{ .RelPermalink }}">{{ .Title }}</a> — {{ .Date.Format "Jan 2, 2006" }}</li>
{{ end }}
</ul>
