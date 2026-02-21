# Fortnite Game Mode Archive

![Game](https://img.shields.io/badge/Game-Fortnite-blue)
![Coverage](https://img.shields.io/badge/Coverage-ch1s0%20→%20ch7s1-success)
![Type](https://img.shields.io/badge/Archive-Playlists%20%26%20Formats-informational)

Comprehensive archive of Fortnite core modes, Arena/Ranked systems, LTMs and competitive formats.  
Includes internal Unreal Engine playlist paths and season support ranges.

---

# Navigation

- [Timeline Overview](#timeline-overview)
- [Core Battle Royale Modes](#core-battle-royale-modes)
- [Arena (ch1 -> ch4)](#arena-ch1---ch4)
- [Ranked (ch4s3 -> ch7s1)](#ranked-ch4s3---ch7s1)
- [Limited Time Modes (LTMs)](#limited-time-modes-ltms)
- [Competitive Formats](#competitive-formats)
- [Modern Expansion Modes (ch5 -> ch7)](#modern-expansion-modes-ch5---ch7)

---

# Timeline Overview

| Mode        | ch1 | ch2 | ch3 | ch4 | ch5 | ch6 | ch7 |
|------------|-----|-----|-----|-----|-----|-----|-----|
| Solos      | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| Duos       | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| Trios      | –   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| Squads     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| Creative   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| Arena      | ✓   | ✓   | ✓   | ✓   | –   | –   | –   |
| Ranked     | –   | –   | –   | ✓   | ✓   | ✓   | ✓   |
| Zero Build | –   | –   | ✓   | ✓   | ✓   | ✓   | ✓   |

---

# Core Battle Royale Modes

## Solos
```
/Game/Athena/Playlists/Playlist_DefaultSolo.Playlist_DefaultSolo
```

## Duos
```
/Game/Athena/Playlists/Playlist_DefaultDuo.Playlist_DefaultDuo
```

## Trios
```
/Game/Athena/Playlists/Playlist_DefaultTrios.Playlist_DefaultTrios
```

## Squads
```
/Game/Athena/Playlists/Playlist_DefaultSquad.Playlist_DefaultSquad
```

### Creative
`ch1s7 -> ch7s1`
```
/Game/Athena/Playlists/Playlist_Creative.Playlist_Creative
```

## Team Rumble
`ch1s6 -> ch7s1`
```
/Game/Athena/Playlists/Playlist_TeamRumble.Playlist_TeamRumble
```

## Zero Build
`ch3s2 -> ch7s1`
```
/Game/Athena/Playlists/Playlist_NoBuildSolo.Playlist_NoBuildSolo
/Game/Athena/Playlists/Playlist_NoBuildDuo.Playlist_NoBuildDuo
/Game/Athena/Playlists/Playlist_NoBuildSquad.Playlist_NoBuildSquad
```

---

# Arena (ch1 -> ch4)

Arena system active from `ch1s8 -> ch4s2`.

```
/Game/Athena/Playlists/Showdown/Playlist_Showdown_Solo.Playlist_Showdown_Solo
/Game/Athena/Playlists/Showdown/Playlist_Showdown_Duos.Playlist_Showdown_Duos
/Game/Athena/Playlists/Showdown/Playlist_Showdown_Trios.Playlist_Showdown_Trios
```

---

# Ranked (ch4s3 -> ch7s1)

Replaced Arena starting in Chapter 4 Season 3.

```
/Game/Athena/Playlists/Playlist_Ranked_Solo.Playlist_Ranked_Solo
/Game/Athena/Playlists/Playlist_Ranked_Duos.Playlist_Ranked_Duos
/Game/Athena/Playlists/Playlist_Ranked_Squad.Playlist_Ranked_Squad
/Game/Athena/Playlists/Playlist_Ranked_ZB.Playlist_Ranked_ZB
```

---

# Limited Time Modes (LTMs)

<details>
<summary>Expand LTM Archive</summary>

### 50v50  
`ch1s3 -> ch1s9, ch4sOG`
```
/Game/Athena/Playlists/LTMs/Playlist_50v50.Playlist_50v50
```

### Solid Gold  
`ch1s3 -> ch7s1 (rotational)`
```
/Game/Athena/Playlists/LTMs/Playlist_SolidGold.Playlist_SolidGold
```

### Sniper Shootout  
`ch1s2 -> ch3s4`
```
/Game/Athena/Playlists/LTMs/Playlist_Sniper.Playlist_Sniper
```

### High Explosives  
`ch1s4 -> ch7s1 (rotational)`
```
/Game/Athena/Playlists/LTMs/Playlist_HighExplosives.Playlist_HighExplosives
```

### Close Encounters  
`ch1s4 -> ch3s1`
```
/Game/Athena/Playlists/LTMs/Playlist_CloseEncounters.Playlist_CloseEncounters
```

### Food Fight  
`ch1s6 -> ch2s1`
```
/Game/Athena/Playlists/LTMs/Playlist_FoodFight.Playlist_FoodFight
```

### Air Royale  
`ch1s7 -> ch2s3`
```
/Game/Athena/Playlists/LTMs/Playlist_AirRoyale.Playlist_AirRoyale
```

### Floor Is Lava  
`ch1s8 -> ch1s9, ch2s8, ch4s1, ch5s1`
```
/Game/Athena/Playlists/LTMs/Playlist_Lava.Playlist_Lava
```

</details>

---

# Competitive Formats

## FNCS
`ch1sX -> ch7s1`
```
/Game/Athena/Playlists/Showdown/Playlist_FNCS.Playlist_FNCS
```

## Solo Cash Cup
`ch1s8 -> ch7s1`
```
/Game/Athena/Playlists/Showdown/Playlist_CashCup_Solo.Playlist_CashCup_Solo
```

## Duos Cash Cup
`ch1s8 -> ch7s1`
```
/Game/Athena/Playlists/Showdown/Playlist_CashCup_Duos.Playlist_CashCup_Duos
```

## Trios Cash Cup
`ch2s5 -> ch3s4`
```
/Game/Athena/Playlists/Showdown/Playlist_CashCup_Trios.Playlist_CashCup_Trios
```

## Zero Build Cash Cup
`ch3s2 -> ch7s1`
```
/Game/Athena/Playlists/Showdown/Playlist_ZBCashCup.Playlist_ZBCashCup
```

---

# Modern Expansion Modes (ch5 -> ch7)

## Rocket Racing
`ch5s1 -> ch7s1`
```
/Game/Racing/Playlists/Playlist_RocketRacing.Playlist_RocketRacing
```

## LEGO Fortnite
`ch5s1 -> ch7s1`
```
/Game/LEGO/Playlists/Playlist_LegoSurvival.Playlist_LegoSurvival
```

## Fortnite Festival
`ch5s1 -> ch7s1`
```
/Game/Festival/Playlists/Playlist_FestivalMain.Playlist_FestivalMain
```

---

End of Archive  
Maintained for documentation & historical reference.
