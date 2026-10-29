# Marathon Year

A 52-week, knee-aware marathon programme and training log. It runs as a web app on GitHub Pages, and you can add it to your phone's home screen.

- The plan ends on the race date you choose (Dublin Marathon, Sunday 31 October 2027, by default). Change the date and the whole plan shifts with it.
- Six phases: Rebuild (run-walk), Base, Build, Endurance, Marathon, Taper. Every 4th week is lighter.
- Log each session with minutes, effort (RPE), early/late and a next-morning knee score. The knee score sets the traffic-light rules.
- Works offline once installed.

## Your data

Your log is stored in the browser on your phone (localStorage). Nothing is sent anywhere. Use **Back up log** every few weeks and keep the file safe. **Restore** loads it back, for example on a new phone.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app: plan, log and guide |
| `manifest.webmanifest` | Name, colours and icons for the installed app |
| `sw.js` | Offline caching |
| `icons/` | App icons |

Not medical advice. If your physio gives you different limits, follow theirs.
