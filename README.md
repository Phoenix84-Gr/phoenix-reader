# Phoenix Reader

The daily newsletter built from the links Babis shares to `@Phoenix_Reader_bot`
on Telegram. Built at 22:00, published at 10:00 the next morning.

**This repository is public.** It holds nothing else — no Phoenix code, no
notes, no credentials. Only the rendered editions.

- Latest and archive: <https://phoenix84-gr.github.io/phoenix-reader/>
- Only the last 30 editions are kept; older ones are pruned on each publish.
- Each page is self-contained: the thumbnails are embedded inside the file,
  because the Instagram urls they came from expire within hours.

Nothing here is written by hand. The generator lives in the Phoenix repo:
`tools/reader_build.py` → `tools/reader_news.py` → `tools/reader_site.py`.
