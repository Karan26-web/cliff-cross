# Cliff Cross

A driving game where the road breaks and the only way across is to work out the
distance between the two ends — on a coordinate plane. Built for classroom
devices: one `index.html`, no build step, no server needed.

- **Play**: open `index.html` in a browser, or serve the folder as a static site.
- **Language**: `?lan=hi` for Hindi (English is the default). All on-screen text
  is in `i18n/strings.json`.
- **Jump to a stage**: `?stage=3`.

This is the game on its own. At the first chasm the road is explained in three
spoken lines and the question is asked straight away; the *Distance Formula*
lesson that the development build opens there is not included.

Everything here is runtime: `assets/` (sprites and the embedded sound) and
`i18n/` (the string table). The art sources, tools and design notes live in the
development repository.
