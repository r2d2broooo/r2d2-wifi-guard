# r2d2-wifi-guard

Linux Wi-Fi watchdog with a desktop status window, outage history and optional Telegram notifications.

Keep a Linux workstation reachable using its existing NetworkManager saved connection.

## Features

- Reconnect saved Wi-Fi
- Offline outage history
- Desktop status/control window
- Pause/resume controls
- Optional queued Telegram notifications

## Use

See README; bash -n bin/wifi-guard; configure NetworkManager before installing the optional service.

Run `python3 check.py` for read-only source checks. These checks are not a claim
that external accounts, market feeds, hardware or a deployed service are configured.

## Snapshot and updates

Created on 2026-11-05 from the local R2D2 workspaces. This is a private source
snapshot; the original local workspaces remain the working copies. The catalogue
repo records every source and omission. Updates happen only on explicit operator
request; there is no automatic sync, push, hook or publishing timer.

Credentials, private chats/memory, live paper books, game saves, models, caches,
virtual environments and proprietary application binaries are not included.
Use a separate environment for this repo. Read USAGE.md/SETUP.md or the original
README where present. Existing integrations are documented rather than silently
starting account actions.
