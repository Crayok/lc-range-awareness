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

Hosting options
  GitHub Pages     Create a repository, upload both files, then Settings > Pages >
                   deploy from the main branch. The site appears at
                   https://<account>.github.io/<repository>/
  Netlify Drop     Drag this folder onto https://app.netlify.com/drop for an
                   instant public link.
  Range network    Copy the folder to any machine on the Starlink LAN and run
                   "python3 -m http.server 8080" in it. Others browse to
                   http://<that machine's IP>:8080/  (give the machine a DHCP
                   reservation so the address does not change).
  No hosting       Email or share the folder; open index.html in any browser.
