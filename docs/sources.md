# Sources and versions

[Home](../README.md) · [Controls](controls.md) · [Crafting](crafting.md) · [Help](troubleshooting.md)

- **Craftax 1.6.1** (full game). Gameplay numbers were checked against the package's source code.
- **Craftax Recorder 0.3.1** (`craftax_recorder.py`, packaged as `CraftaxRecorder.exe`), episode file format 3.
- Reviewed 9 October 2026.

Game source: [Craftax repository](https://github.com/MichaelTMatthews/Craftax) at [v1.6.1](https://github.com/MichaelTMatthews/Craftax/tree/v1.6.1/craftax/craftax): `game_logic.py` (crafting, mining, survival, enchanting, floors), `util/game_logic_utils.py` (damage, resistances), `constants.py`, `world_gen/world_gen_configs.py` (ores).

Notes:

- Damage values follow the code's formulas. A code comment claims +25% sword enchantment damage at intelligence 5; the formula gives +20%.
- Floors are numbered from 1 here; the game's internal level index starts at 0 (Overworld 0, Graveyard 8).

Update this page and the affected guides if the game version, recorder, controls or minimum episode length change.

---

[Back to home](../README.md)
