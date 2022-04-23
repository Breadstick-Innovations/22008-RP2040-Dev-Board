# RP2040 Dev Board

Hey Everyone,

I wanted to get myself more aquainted with JLCPCB's SMT assembly service, so I designed a board to their specs and tried to use their basic parts wherever possible, to minimize $3 loading fees for extended parts. My hope is to save time for others who are also interested in the RP2040 and JLCPCB's assembly service. If you put this design in your KiCad templates folder, it'll be quick and easy to iterate from.

I started this project a before making a git repository, so there's some missing history. If you're interested in the early prototyping, [here's a link to the thread on Twitter.](https://twitter.com/RangenMichael/status/1517001765425623040)

---

# Current Status - Work In Progress
### I haven't ordered a board with these latest changes yet - Soon!
### Reminder - Generate new gerbers before ordering!

* I've routed the 1.1V rail that was missing from the inital prototype
* I fixed the 0805 LEDs that I had sitting on 0603 footprints
* Pins 43 and 44 are now routed to the closest decoupling capacitor
* U205's silkscreen has been hidden
* ADC Silkscreen has been improved
* Still need to replace the current crystal (extended part) with C9002 (basic part) 
