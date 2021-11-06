This is just files for a blogpost: https://www.markhansen.co.nz/pprof-tagroot/

Just because I can't easily upload static files to Ghost blog. So I'm using
github pages to host them.

The files are generated with pprof -http :8080, then saving the generated page
(it's just one HTML page), then replacing `.header` CSS with `display: none;`
so the header doesn't show.
