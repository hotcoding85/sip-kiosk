# Sip — machine display

The consumer-facing touchscreen UI for a smart beverage machine, built in
Flutter from a Google Stitch design project.

**Open it: https://hotcoding85.github.io/sip-kiosk/**

| URL | |
|---|---|
| `/` | Splash, then the machine running the Redesigned flow |
| `/?gallery=1` | Index of all 14 screens |
| `/?flow=barista` | Run a flow: `redesigned`, `barista`, `vertical` |
| `/?screen=<id>` | One screen on its own — ids listed in the gallery |

Fourteen screens across six design directions, connected into three walkable
machine flows: standby → awake → pouring → post-pour. Choosing a drink starts a
real pour on that flavour's own duration; it advances on its own when the pour
completes, and returns to standby on a timer.

Works on a phone: below 768px the layout reflows using the designs' own
`md:`/`lg:` rules rather than shrinking the 1280px board down.

This branch holds only the compiled site. The Flutter source and the raw design
exports are not published here.
