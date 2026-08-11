# CozAlyze — Pricing Finale (Sidereal fix)

Stamps: SCENE 1 v19.70 pricing finale route, SIDEREAL v19.39, TROPICAL v18.45.
Reveal routes ?v=1939 / ?v=1845. Engine unchanged (e26, ?v=26, AUDIO_VER 18).

THE 404 FIX:
The Sidereal payment click was navigating to ascendant.html — a file that
does not exist in this repo. That navigation is retired. Sidereal now ends
exactly like Tropical: the payment click sinks the reading away and the
pricing page (pricing.jpg) rises in as the finale. Nothing navigates, so
nothing can 404, and the sound continues untouched.

SWAP INTO THE REPO (2 files):
  index.html             (v19.70 — route bump only)
  sidereal-reveal.html   (v19.39)

Everything else stays as deployed (e26 engine, tropical v18.45, all wavs).
pricing.jpg must be in the repo root — it already is if the Tropical
pricing page worked.

Verify stamps v19.70 / v19.39 and the payment click on the SIDEREAL path.
