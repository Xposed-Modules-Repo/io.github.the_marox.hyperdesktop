
HyperDesktop Unlock
Turns an external USB-C monitor into a separate desktop display (not a mirror) on Xiaomi phones running HyperOS 4 (Android 17), where Xiaomi ships Android's connected-display / desktop code but keeps it disabled.

Features
Brings back the hidden Computer (Desktop) button in the "Connect to external display" dialog
The monitor gets its own status bar and mouse cursor; apps opened there stay there
Neutralises Xiaomi's mirroring enforcer (SecondaryDisplayPolicy)
Starts SmartDock (or Taskbar) on the monitor and turns off the phone screen
Optional touchpad mode: the phone controls the monitor's pointer (tap, two-finger scroll and right click, pinch to zoom, edge swipe for Back), with the on-screen keyboard on the phone
Desktop keyboard shortcuts: Alt+Tab with preview bar, monitor screenshots, Win+Shift+Arrow to move apps between displays, Alt+F4, Win+D, Win+P…
Quick Settings tiles (Computer ↔ Mirroring, Touchpad), monitor density/resolution/refresh settings, diagnostic report
Requirements
Xiaomi phone with DisplayPort Alt Mode over USB-C (tested: Xiaomi 15, Xiaomi 14)
HyperOS 4 / Android 17
Scope: System Framework, System UI, Settings, then reboot
Limits
No resizable windows or title bars: HyperOS doesn't expose AOSP's desktop windowing, so apps run full screen on the monitor.

Full documentation, troubleshooting and source code: https://github.com/the-marox/HyperDesktopUnlock

