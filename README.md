# lc-range-awareness
Launch Canada Range Awareness - standalone web package

Contents
  index.html   Range Awareness System: flow diagrams, board trace, tabletop scenarios
  board.html   Range Status Board (interactive tabletop tool, all 19 scenarios)

No accounts, no server code and no internet connection are required. Both pages
work from a web host, from a laptop on the range network, or opened directly
from the folder. When offline, the board falls back to system fonts.

How the board keeps its state
  Each browser keeps its own copy of the board (saved in that browser only).
  For a tabletop, one person drives the board on a shared screen or projector
  while the role holders call their reports. Two people on two devices will not
  see each other's changes.
