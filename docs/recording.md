# Recording and finishing

[Home](../README.md) · [Controls](controls.md) · [Crafting](crafting.md) · [Help](troubleshooting.md)

## How saving works

Recording starts automatically once you confirm your participant ID; there is no record button.

- An **episode** is one game: from a new world until you die, win or stop. One launch of the recorder is a **recording session** and can contain many episodes.
- Gameplay is written to disk continuously while you play, so finishing is quick and a crash loses at most the last few seconds.
- When an episode ends, the console prints **Saved episode N**.
- Episodes shorter than 100 game steps are discarded (the console says **skipped**). This only filters accidental starts; don't pad recordings to reach it.

## Finish safely

1. Close the **game window**.
2. Wait for **All saves completed safely.** in the console. This usually takes a few seconds.
3. Press **Enter**.

Pressing Ctrl+C in the console also stops safely. Don't close the console or shut down the computer while it's finishing.

## Find your files

The console prints the output folder at startup. It is `recordings\YOUR_ID\session_DATE_TIME_ID\` inside the `CraftaxRecorder` folder, or `Documents\Craftax Recorder\recordings\` if that folder can't be written to.

| File | Meaning |
|---|---|
| `episode_0001_xxxxxxxx.pkls.zst` | One finished episode |
| `episodes.csv` | One line per saved episode |
| `….pkls.zst.tmp` | An episode being recorded. Left behind after a crash, it still holds the game up to a few seconds before; send it too |

Don't rename files. Gaps in episode numbers are skipped short episodes.

## Submit your recordings

Zip your participant folder inside `recordings` (right-click → **Send to → Compressed (zipped) folder**) and send it as described in [Your assignment](study-details.md#submitting-recordings). Include any `.tmp` files. Keep your copy until the organizer confirms it arrived.

---

[Back to home](../README.md)
