# Setara Constellation Images

Star-chart images used by the Setara Discord bot for constellation
identification practice.

## Structure
- `identification/` — one image per constellation. The filename (minus
  extension) is the answer, e.g. `Orion.png` → "Orion".

## Adding more
Drop new `.png` files into `identification/`, commit, then run `s.refresh`
in Discord to load them.

## Image credits
These charts are from the official IAU constellation charts, created by the
IAU and Sky & Telescope magazine (Roger Sinnott & Rick Fienberg), released
under a Creative Commons Attribution 4.0 International license (CC BY 4.0):
https://creativecommons.org/licenses/by/4.0/

Changes made: the constellation name labels have been removed from the
original charts for use as a guessing game.
