# Pi-Hole Sense Dashboard
A Sense HAT dashboard providing health, status and maintenance information for Pi-hole and Unbound.

## **Inclusive Community.**

This project is created and maintained by a transgender developer and proudly supports the LGBTQIA+ community.
Everyone is welcome to use, learn from, and contribute to this project. Respectful participation is expected regardless of gender identity, sexual orientation, race, religion, disability, or background.
Contributions are welcome from everyone. Please be respectful and help keep this a welcoming space.
This is a hobby project developed in my spare time. Progress will depend on my own time and the motivation I have available.

## Mission Statement
If the user has to open the Pi-hole web interface just to confirm everything is healthy, then the dashboard has failed its purpose.

## Inspiration

This project was born from the desire to know the health of a Pi-hole installation without needing to continually open a browser or SSH into the Raspberry Pi.

## Current development hardware

- Raspberry Pi 3 Model B+
- Official Raspberry Pi Sense HAT
- Raspberry Pi OS Lite x64, installed 4 August 2026
- Pi-hole v6
- Unbound

**Initial development started 4 August 2026.**

## Project Goals

The aim of this project is to build an unobtrusive hardware status display for Pi-hole using the Raspberry Pi Sense HAT.
Rather than requiring users to log into the web interface, the LED matrix provides immediate visual feedback on system health, maintenance requirements, and service status.
The dashboard is designed to inform rather than control. It reports system health and maintenance requirements but does not perform administrative actions.

## Design Philosophy

The dashboard is designed to be intentionally quiet.
If everything is healthy, it should simply reassure the user that all is well.
Only when maintenance is required or a fault occurs should it actively draw attention.
The display should be informative without becoming distracting.
The aim is to reduce the need to continually log into the Pi-hole web interface while avoiding unnecessary distraction.

## Why not just use the web interface?

This project is intended to complement Pi-hole, not replace it.

The dashboard provides immediate visual feedback without requiring a browser or SSH session.
Administrative tasks continue to be performed through the Pi-hole web interface.

## Screenshot
Coming soon

## Planned Features

- [ ] Pi-hole service status
- [ ] Unbound service status
- [ ] Gravity update notifications
- [ ] Pi-hole software update notifications
- [ ] Quiet Hours (Do Not Disturb)
- [ ] One-button diagnostics
- [ ] Service failure animation
- [ ] Boot animation
- [ ] System temperature monitoring
- [ ] Configurable display brightness
- [ ] YAML configuration file
...

## Installation

...

## Roadmap
### v0.1
- [ ] Project structure
- [ ] Configuration file
- [ ] Logging
- [ ] Basic Sense HAT output
- [ ] Green "OK" display
- [ ] Red fault display
- [ ] Boot animation

### v0.2
- [ ] Pi-hole status
- [ ] Unbound status
- [ ] Gravity notifications

### v0.3
- [ ] Quiet Hours
- [ ] One-button diagnostics
- [ ] Manual status check via joystick press
- [ ] Configurable brightness

### v1.0
- [ ] Stable release
- [ ] Installation guide
- [ ] Configuration guide

## Project History

**04 August 2026**

- GitHub account created.
- Repository created.
- Initial README written.
- Project scope defined.
