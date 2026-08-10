# Qwen Image Studio fixed entry

This public GitHub Pages project contains only a static redirect page and the
current Cloudflare Quick Tunnel URL in `target.json`. It does not contain model
outputs, prompts, credentials, authentication cookies, or application code.

The GPU server updates `target.json` automatically whenever `cloudflared`
assigns a new hostname. Users can therefore keep sharing the same Pages URL
across server shutdowns and restarts.
