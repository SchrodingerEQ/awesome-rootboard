# awesome-rootboard

A curated list of widgets and resources for [Rootboard](https://github.com/SchrodingerEQ/Rootboard.me),
an open-source touchscreen family calendar kiosk. This list is where
Rootboard widgets — built-in and community — get discovered.

This list is young — there's one community widget on it so far. That's
the point: Rootboard's widget system is open from day one, not "open
once a community shows up." If you build something, it belongs here.

## Contents

- [Built-in widgets](#built-in-widgets)
- [Official resources](#official-resources)
- [Community widgets](#community-widgets)
- [Themes](#themes)

## Built-in widgets

Shipped with Rootboard itself — no install required.

- [**Calendar**](https://github.com/SchrodingerEQ/Rootboard.me/tree/main/client/src/widgets/calendar) —
  the core view: Google Calendar events on a touch-friendly day/week
  layout.
- [**Chores**](https://github.com/SchrodingerEQ/Rootboard.me/tree/main/client/src/widgets/chores) —
  a household chore tracker for the kiosk screen.
- [**Dinner**](https://github.com/SchrodingerEQ/Rootboard.me/tree/main/client/src/widgets/dinner) —
  a simple dinner-plan display for the week.

## Official resources

- [Rootboard](https://github.com/SchrodingerEQ/Rootboard.me) — the kiosk
  app itself.
- [CONTRACT.md](https://github.com/SchrodingerEQ/Rootboard.me/blob/main/docs/plans/widget-system/CONTRACT.md) —
  the normative widget contract: manifest fields, lifecycle, host
  services, and the trust model. The source of truth for building a
  widget.
- [rootboard-widget-template](https://github.com/SchrodingerEQ/rootboard-widget-template) —
  a starter template with a working hello-world widget. Copy the
  folder, edit two lines, drop it on your kiosk.
- [TUTORIAL.md](https://github.com/SchrodingerEQ/rootboard-widget-template/blob/main/TUTORIAL.md) —
  "Build your first widget in 30 minutes," from an empty folder to a
  working widget.
- [CONTRIBUTING.md](https://github.com/SchrodingerEQ/rootboard-widget-template/blob/main/CONTRIBUTING.md) —
  how to build and share a widget today, and the ground rules for
  doing so.

## Community widgets

- [**rootboard-widget-grocery-list**](https://github.com/SchrodingerEQ/rootboard-widget-grocery-list) —
  a local grocery list: add, check off, and clear items. No accounts,
  no network calls, nothing leaves the kiosk. MIT.

Built something? Yours could be here — submit a PR. Two things earn a
spot on this list: your widget installs via the current folder-drop
mechanism on a real Rootboard kiosk (copy into `widgets/`, no extra
setup), and its README states plainly what it does and doesn't do. See
[CONTRIBUTING.md](https://github.com/SchrodingerEQ/rootboard-widget-template/blob/main/CONTRIBUTING.md)
for the full rules, including the no-third-party-IP policy.

## Themes

Rootboard doesn't have a theme system yet — it's planned, not shipped.
When it exists, this section will list themes the same way the section
above lists widgets. See the
[theme system plan](https://github.com/SchrodingerEQ/Rootboard.me/blob/main/docs/plans/theme-system/THEME-SYSTEM-PLAN.md)
for current direction. No dates, no promises — just where the thinking
stands today.

## License

[CC0 1.0 Universal](LICENSE) — this list is public domain. Copy it,
fork it, build your own from it.
