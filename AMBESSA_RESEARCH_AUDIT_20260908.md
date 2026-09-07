# Ambessa Top matchup research audit - 2026-09-08

## Scope
- 68 champions in the current database roster, including Ambessa itself.
- 67 Ambessa-vs-enemy matchups are populated.
- Existing database structure is preserved.
- Ambessa is now selectable as a researched champion in matchup mode.

## Source policy
1. PC high-ELO matchup theory is the baseline.
2. MOBAFire high-ELO Top guides are the primary matchup-strategy source.
3. Onetricks.gg Masters+ is used for actual OTP tendencies and lane statistics.
4. WR-specific sources are used for WR mechanics, item/rune/spell availability, and WR-only changes.
5. Raw win rate is not used as the sole matchup verdict.
6. Low-evidence matchups are explicitly marked low confidence rather than presented as verified facts.

## WR conversion rules
- PC level 6 references are converted to WR level 5 because Ambessa gets R at level 5 in WR.
- Doran Blade/Shield and potion starts are not copied directly. Starter recommendations are translated to WR-available 500G purchases by function.
- Standard Ambessa core is treated as Eclipse / Spear of Shojin in concept, represented by the database's current Japanese item names.

## Current classification in the database
- Advantage: 15
- Even: 29
- Disadvantage: 16
- Extreme disadvantage: 6

## Highest-confidence danger matchups
Renekton, Irelia, Tryndamere, Kennen, Teemo, Warwick, Gwen, Vayne, Jayce, Camille, Trundle, Yone.

## Explicitly low-confidence matchups
Sylas, Zaahen, Swain, Skarner, Tristana, Twisted Fate, Naafiri, Nautilus, Ryze, Rek'Sai, LeBlanc, Rengar, Smolder is not part of the current 67-champion database roster and therefore was not added.

## Validation
- `node --check database.js` passes.
- Current roster contains 68 champions.
- Ambessa detail map contains exactly 67 enemy entries.
- Every current non-Ambessa roster champion has an Ambessa detail entry.


## 2026-09-08 Poppy / Anivia追加監査
- PoppyをWR正式ロスターへ追加。Ambessa対Poppyを正式登録。
- AniviaはPC側対面研究を実施したが、2026-09-08時点でWild Rift未実装のため正式ロスターには追加しない。
- Smolderは正式ロスター外のまま。
- 詳細: POPPY_ANIVIA_RESEARCH_20260908.md
