+++
title = "Portfolio"

+++

<h2>Portfolio</h2>
  {{- range first 10 .Data.Pages -}}
    {{- if eq .Type "article"}}
      <h4><a href="{{ .Permalink }}">{{ .Title }}</a></h4>
    {{- end }}
  {{- end }}
