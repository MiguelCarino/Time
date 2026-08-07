# Time

Local time, UTC, Unix epoch and ISO — a searchable world-clock with pinned
zones, plus live countdowns you can add and share. Runs entirely in the browser
(`time.carino.systems`).

Three sections:

- **Now** — big local clock with a 12/24-hour toggle, and click-to-copy readouts:
  UTC, Unix epoch (s + ms), ISO 8601, ISO week, and day-of-year.
- **Zones** — a **day/night world map** (live terminator + subsolar sun) with your
  pinned cities plotted on it, above a region-filtered, continent-grouped list. Each
  zone card shows local time, UTC offset, offset relative to you, and a day/night
  indicator. Pin favourites (saved locally); click a map marker to unpin.
  The map is a self-contained inline SVG — land outlines from Natural Earth (public
  domain) projected equirectangularly, marker coordinates from the IANA `zone1970.tab`
  (public domain). No tiles, no CDN, fully offline.
- **Countdowns** — a live hero countdown for the soonest event, a searchable grid
  of cards (upcoming / passed), a few removable built-ins, plus **add your own**
  events and **share** a set by link (`?c=` encoded).

Everything persists in `localStorage` (format, pinned zones, your events). No
server, no tracking. Absorbs the former **SimpleCountdown** app (`countdown.`).

## Licensing

**Mine — GNU Affero General Public License v3.0 or later.** Everything in this
repository *except* the paths listed below. Copyright © 2026 Miguel Carino.
Full terms in [LICENSE](LICENSE).

**Not mine.** The files below are third-party works redistributed here. This
project's licence does not cover them and could not: they are not mine to
relicense. Each keeps its own terms, and each carries its own notice.

| Path | What it is | Licence | Notice |
| --- | --- | --- | --- |
| [`fonts/`](fonts/) | IBM Plex Mono, IBM Plex Sans, Red Hat Display | SIL OFL 1.1 | [`fonts/OFL.txt`](fonts/OFL.txt) |

Those files travel with any fork, mirror or repackaging of this repository, and
their notices must travel with them.
