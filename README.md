# Event Gate V6

Separate event-day module for Event Ticketing Platform V6.

Upload this folder as:

```text
event-gate-v6/
```

Configure `site-config.js` with the SAME Apps Script `/exec` endpoint used by `event-ticketing-v6`.

Public Gate URL:

```text
https://greenprofessionals.github.io/event-gate-v6/
```

Gate Staff: scan/search/check-in assigned Active events.
Gate Supervisor: adds walk-ins, payment exceptions, internal guest notes, contact actions, and undo check-in.

Gate check-in continues during Emergency Read-Only mode; non-gate mutations remain blocked by the backend.
