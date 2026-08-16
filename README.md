
To autoload, add `/addon load dps` to your Ashita startup script.

---

## Commands

| Command       | Description                                   |
|---------------|-----------------------------------------------|
| `/dps`        | Toggle the DPS window                         |
| `/dps reset`  | Clear all damage totals and restart the timer |
| `/dps clear`  | Alias for `reset`                             |
| `/dps help`   | Show help                                     |

---

## Notes & limitations

- Lightweight Lua addon focused on a clean DPS popup.
- Uses action packet `0x28`. Covers most melee / WS / magic / ability damage.
- For full meters (bars, skill breakdowns, filters, etc.) see [Deeps](https://github.com/relliko/Deeps).

---

## License

Free to use, modify, and share. No warranty.
