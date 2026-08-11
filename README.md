# CozAlyze — Fresh Repo Deploy (e20, void waits at the reveal)

Stamps: SCENE 1 v19.61 graceful exit, SIDEREAL v19.31 void waits,
TROPICAL v18.38 void waits. Routes ?v=1931 / ?v=1838. Engine ?v=20.

CHANGED vs the set you just uploaded (5 files to swap in):
  emerge-sound.js            (e20)
  index.html                 (v19.61)
  sidereal-reveal.html       (v19.31)
  tropical-reveal.html       (v18.38)
  01b_void_atmosphere.wav    (NEW — the void returns for one moment)

Everything else in the new repo stays exactly as uploaded.

What changed:
- Card tap no longer cuts the sound dead: choice bed and ambient field breathe
  out together over ~0.7s, THEN the page turns. No abrupt silence.
- The reveal waiting screen ("the sky has always been here / tap to reveal")
  now plays the void atmosphere as its bed — the ambient field holds back.
- The reveal tap: void fades out over 1.5s, the ambient field rises underneath,
  and the chart timeline plays over it. Exactly: void while waiting, tap,
  back into the ambience.

iPhone note (Apple's rule, same as always): a page can't make sound until it
has been touched once. So on iPhone the void begins at the first touch of the
reveal screen — a touch in the first ~5s (before the gate arms) starts the
void while the person keeps waiting; a touch after that goes straight into
the reveal. On desktop the void plays the waiting screen from the start.

Verify stamps v19.61 / v19.31 / v18.38 before judging.
