# Elina Go! — website

The public pages for the app **Elina Go!**: start page, privacy policy and support, each in
German, English, French and Polish. Plain static HTML, no build step.

Both app stores require a reachable privacy URL, and Apple additionally a support URL — that is
what this repository exists for. It is public only because GitHub Pages needs it to be; the app's
source lives in a private repository.

**Do not edit here.** The source of truth is `docs/legal/site/` in the app repository, and
`scripts/publish-site.sh` there copies the files over and pushes them. An edit made here is
overwritten by the next publish.
