### Hey there 👋

Look... What is this? It's my nice about me page? But... Hey, my name is **Felix**. I'm mostly developing in python (as you may see in my most used languages ^^). I live in germany near Nuremberg (bavaria :beers:).
<div style="display: flex; flex-direction: row">
<img align="left" style="margin-right: 1rem" src="https://github-readme-stats.vercel.app/api?username=Feluxerich&theme=dark&show_icons=true&count_private=true">
<img align="right" style="margin-left: 1rem" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Feluxerich&theme=dark">
</div>
<br style="visibility: hidden" />

### :construction_worker: Check out what I'm currently working on
{{range recentContributions 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{ with .Repo.Description }} - {{ . }}{{ end }} ({{humanize .OccurredAt}})
{{- end}}

### :seedling: My latest projects
{{range recentRepos 5}}
- [{{.Name}}]({{.URL}}){{ with .Description}} - {{ . }}{{ end }}
{{- end}}
