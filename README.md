# Iron Lance: Pinnacle Age — web playtest

Play: https://brian2187.github.io/ironlance-playtest/ (best in Safari on iPad, landscape)

This repo holds only the exported Godot 4.7.2 web build (single-threaded, no source code).
`index.pck` / `index.wasm` are stored as base64 text parts in `parts/` and reassembled
in the browser by a small loader in `index.html` (see `manifest.json` for sizes and SHA-256).

First load downloads about 320 MB, so use Wi-Fi. Tap once to enable audio.
