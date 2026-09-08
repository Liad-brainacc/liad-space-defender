LIAD Space Defender V7.7.1 — Boss Hotfix

FIXED
• Boss immortality from V7.7.
  Cause: boss HP was multiplied by a non-existent DIFF.hp property, producing NaN.
• Added a defensive finite-HP check so an invalid boss HP can no longer enter combat.
• Boss HP scaling:
  CADET x1.00
  PILOT x1.15
  ACE   x1.35

UI
• Level progress bar moved from the top HUD to the bottom-center.
• On iPhone the bar is narrower and thinner so it does not cover score, level, lives,
  credits, frame information, pause or weapon controls.
• Progress label shortened to LV / BOSS.

All V7.7 boss ladder and weapon systems retained.
