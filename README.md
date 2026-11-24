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
  Google Calendar month, week, and day views with event create/edit and sync.
- [**Chores**](https://github.com/SchrodingerEQ/Rootboard.me/tree/main/client/src/widgets/chores) —
  Per-person daily chore checklists with a live open-chore nav badge.
- [**Dinner**](https://github.com/SchrodingerEQ/Rootboard.me/tree/main/client/src/widgets/dinner) —
  Weekly dinner planner with meal voting and a saved-meals list.
- [**What to Wear**](https://github.com/SchrodingerEQ/Rootboard.me/tree/main/client/src/widgets/what-to-wear) —
  Kid-friendly weather and what to wear to school, morning and afternoon.

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

Rootboard has a theme system (since v1.6.0). Two themes are built in,
**Default** and **Deep Space**, and you switch between them from the
kiosk's Settings menu. Themes change colours today.

Community themes are not supported yet:
they are a later slice of the
[theme engine spec](https://github.com/SchrodingerEQ/Rootboard.me/blob/main/docs/plans/theme-system/THEME-ENGINE-SPEC.md)
(see "Out of scope (later slices)"), with the wider direction in the
[theme system plan](https://github.com/SchrodingerEQ/Rootboard.me/blob/main/docs/plans/theme-system/THEME-SYSTEM-PLAN.md).
When they arrive, this section will list them the same way the
sections above list widgets. No dates, no promises.

## License

[CC0 1.0 Universal](LICENSE) — this list is public domain. Copy it,
fork it, build your own from it.
