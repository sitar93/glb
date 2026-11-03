# Module lite GLBs — Compress (aggressive)

Baked with `npm run bake:module-lites-light` (Compress on / viewport default). Aggressive: panel ~0.8% keep, soft-protect ~3%, chrome ~25% keep, knobs 80%, quantize 12/8 + meshopt high. Avalith never-simplifies knobs + switches; Ocelot never-simplifies case + speaker (not chrome).

Used when View → **Compress** is on (`moduleGlbLiteUrl(def, { compressed: true })`).
Toggling Compress reloads rack module meshes. Same viewport default as Light
(on ≤800px).

Strip lites stay in `public/models/modules-lite/` (Compress off / teach-ports).
