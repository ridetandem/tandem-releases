# tandem-releases


## v0.3.0 (Clickity Clack, alpha)

- Tandem-0.3.0.dmg (sha256: 2960ccd876907dc81bb30db74b9a81630cc3b2be5dca829d26a331a1b511addf)

### Features

- Richer mouse integration. Left/right/middle clicks are correctly recognised. You can scroll. You can drag. You can drop. *mic drop*
- Notification when updates are available (you must manually update, and automatic updates are coming soon).
- Switched to a lower latency video codec

### Bug fixes

- For some users with dual monitor setups, both screens were being shared. Now only the primary display (screen with the dock) will be shared.
- Pressing 'enter' to join/host would sometimes reload the page.
- After closing a session, Tandem would not accept a new connection.
- Some space key presses were not being transmitted. Also, pressing space would cause scrolling in joiner's video window.

### Misc

- Basic persistent logging to help debug future issues (at `~/Library/Application Support/Tandem/logs/`)


## v0.2.1 (Silk Raccoon, alpha)

- Tandem-0.2.1.dmg (sha256: c8822453ee6a1af47e4db8cde8b62cc00f1f5453c219ba6d4c573cece0ae89ac)

### Features

- Fix application menu bug that prevented quiting when connected.


## v0.2.0 (Silk Raccoon, alpha)

- Tandem-0.2.0.dmg (sha256: d1112a3be04b699ac3a036ebb3f0e01ad4c43a06abc201df99fdb7a3ad3424f8)

### Features

- On MacOS, Tandem will disable global shortcuts, allowing system key combinations (i.e. Cmd+Tab) to be captured. Enable accessibility for Tandem to use this.
- OS hooks used to listen for user keyboard actions.
- Some UI polish when entering a name.


## v0.1.0 (Maiden Voyage, alpha)

- Tandem-0.1.0.dmg (sha256: beb2a81fec3cf05f733627306416f7900b293fd35534fc388409ce533c669d71)

### Features

- Initial macOS release demonstrating remote screen sharing.
