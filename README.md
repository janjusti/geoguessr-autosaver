# GeoGuessr AutoSaver
Also available on [GreasyFork](https://greasyfork.org/en/scripts/545737-geoguessr-autosaver)

## Disclaimers
- **Use at your own risk.** I’ve done my best to avoid any abuse of GeoGuessr’s API by using cooldowns, but I can’t guarantee anything.

## How to use
- Install the script on Tampermonkey and enable it.
- Go to <https://www.geoguessr.com/>.
- Click on anything to ensure your browser won’t reject file read/save requests in the next step.
- Go to <https://www.geoguessr.com/multiplayer>.
- Your browser will ask which folder you’d like to use for storing your game JSON files.
  - Allow it to read from and write to the selected folder.
- The script will run each time a leaderboard is visible (duels or team duels), downloading new JSON files (if any).
