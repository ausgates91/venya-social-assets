# Venya social assets

Rendered Instagram cards for [@houseofvenya](https://www.instagram.com/houseofvenya/),
served over GitHub Pages so Instagram's Content Publishing API can fetch them.

The API has no upload endpoint — `POST /{ig-user-id}/media` takes an `image_url`
and Meta's servers fetch it. That is the only reason this repository is public:
these exact images are published to Instagram anyway.

Nothing else lives here. Captions, strategy, logs, code, and credentials stay in
the private repository.

Images are 1080×1350 (feed) or 1080×1920 (stories), rendered from design tokens
lifted from venyatherapeutics.com and verified against WCAG AA contrast.
