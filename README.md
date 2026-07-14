# Primo Brand Book (external site)
Story-led brand book, generated FROM tokens.json in the primo-brand skill —
the single source of truth. Do not hand-edit values in pages.

Regenerate (run in order — later scripts override story/specimen pages):
  1. python3 generate.py            # base pages
  2. python3 generate_specimens.py  # social + templates specimen galleries
  3. python3 generate_motion.py     # motion page
  4. python3 generate_story.py      # story copy: index, logo, colour, rules

Renders: drop primo-motion loops into media/ (motion-45.mp4, motion-916.mp4,
motion-169.mp4 — see media/README.txt).

Deploy: separate GitHub repo (suggested name: brand) → Settings → Pages → main /(root).
