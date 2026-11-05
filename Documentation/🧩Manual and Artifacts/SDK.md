# SDK — INSTRUMENT.Counter

Every Counter model this library drives, and how to drive it. Each model answers the same five verbs over HTTP (its own port), WebSocket, a Unix socket and the bus; one page per model below lists its routes and every command.

← [Manual and Artifacts](INDEX.md)

| Verb | What it does |
|---|---|
| `get` | reads one value |
| `set` | writes one value |
| `nab` | reads more than one thing (observation, telemetry) |
| `rig` | configures several arguments at once |
| `do` | executes an action; takes no value |

| Model | Maker | get | set | nab | rig | do | Port |
|---|---|---:|---:|---:|---:|---:|---:|
| [53131A](SDK/53131A.md) | HP / Agilent / Keysight | 10 | 9 | 10 | 3 | 5 | 15600 |
| [53132A](SDK/53132A.md) | HP / Agilent / Keysight | 10 | 9 | 10 | 3 | 5 | 15601 |
| [53181A](SDK/53181A.md) | HP / Agilent / Keysight | 10 | 9 | 10 | 3 | 5 | 15602 |
| [53210A](SDK/53210A.md) | HP / Agilent / Keysight | 10 | 9 | 10 | 3 | 5 | 15603 |
| [53220A](SDK/53220A.md) | HP / Agilent / Keysight | 10 | 9 | 10 | 3 | 5 | 15604 |
| [53230A](SDK/53230A.md) | HP / Agilent / Keysight | 10 | 9 | 10 | 3 | 5 | 15605 |
