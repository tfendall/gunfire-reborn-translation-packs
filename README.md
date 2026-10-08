# Gunfire Reborn Translation Packs

Community language extension packs for Gunfire Reborn. These change displayed text using the game's built-in language-pack support.

## Available packs

| Pack | Language | Purpose |
| --- | --- | --- |
| [English Improved](packs/EnglishImproved/) | English | Clearer descriptions of abilities, upgrades, items, and combat mechanics. |

## Install English Improved

1. Download [`#GF_EnglishImproved.csv`](packs/EnglishImproved/%23GF_EnglishImproved.csv). On GitHub's file page, use **Download raw file** to save the CSV itself.
2. Copy the file into your game's language folder. For a standard Windows Steam installation:

   ```text
   C:\Program Files (x86)\Steam\steamapps\common\Gunfire Reborn\Gunfire Reborn_Data\StreamingAssets\language
   ```

3. Keep the filename exactly `#GF_EnglishImproved.csv`.
4. Restart the game, then select **EnglishImproved** under **Settings → Language Extension Pack**. The option may appear as **English Improved** depending on the game version.

For another Steam library, use **Steam → Gunfire Reborn → Manage → Browse local files**, then open `Gunfire Reborn_Data\StreamingAssets\language`.

To update, replace the existing CSV and restart the game. To revert, select the default language extension pack.

## Report unclear text

Open an issue with the item's or ability's name, the exact wording, and the relevant upgrade level or enhanced variant. Describe what happened in-game if the text appears to describe the wrong behavior.

## Editing and adding packs

- Put each pack in its own folder under `packs/` with a short README.
- Preserve the `#GF_` filename prefix.
- Edit only the **Local Language Text** column. Keep keys, the English source column, row order, and section markers intact.
- Preserve dynamic placeholders, skill-icon tags, and formatting tags.
- Keep this CSV's UTF-8 BOM, CRLF line endings, and quoting. Spreadsheet programs can alter these on save.
- Preserve numbers, conditions, durations, resource costs, drawbacks, and level differences. Explain ambiguous mechanics without inventing missing values.
- Name the owner of an effect explicitly: the player, a summon, the target, or a teammate.

New game updates may add text or change mechanics. Packs need review against a fresh game export; this pack does not automatically track updates.

## References

The game supplies language-pack instructions in `StreamingAssets/language/ReadMe.txt`. The [Gunfire Reborn Wiki](https://gunfirereborn.fandom.com/wiki/Gunfire_Reborn) and official update notes help clarify mechanics. Installed game exports supply this pack's balance values.

This repository is an unofficial community project. See [NOTICE.md](NOTICE.md) for attribution.
