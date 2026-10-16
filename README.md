# arcfpga-neptunoplus-db

Auto-generated neptUNO+ release catalog — `Arcade/` and this table are rebuilt from scratch from
[arcfpga-cores](https://github.com/bmo00/arcfpga-cores) on every rebuild, which also squashes this
repo's entire history down to that one commit.

Every `.arc` file's name is normalized to its set's own current MAME/HBMAME description, derived
from its `setname` against the latest MAME/HBMAME release — not a fixed name, so it can change
across rebuilds if MAME/HBMAME renames a set.

See [game_list.md](game_list.md) for the full list of supported arcade games, and
[arcfpga-cores/doc/generating-rom-files.md](https://github.com/bmo00/arcfpga-cores/blob/main/doc/generating-rom-files.md)
for how the `.rom`/`.ram` files here are generated from your own legally obtained MAME ROM dumps.

## Release table

| Core | Platform | Ported from | Release date | Notes |
| --- | --- | --- | --- | --- |
| 1942 | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| 1943 | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-26 |  |
| aerofgt |  | [jlrh/videosystem-fpga](https://github.com/jlrh/videosystem-fpga) | 2026-10-15 |  |
| ajax | Konami Ajax hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-06 |  |
| aliens | Konami Aliens based, Konami Thunder X hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| aligator |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 | ⚠️ Issues — Bad sprites. CRT misaligned. Appears to be shifted off-center on the CRT |
| altair |  | [jlrh/cidelsa-fpga](https://github.com/jlrh/cidelsa-fpga) | 2026-10-15 |  |
| asterix | Konami Asterix hardware | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 | EEPROM bit check bad |
| bbusters |  | [jlrh/snk-fpga](https://github.com/jlrh/snk-fpga) | 2026-10-15 |  |
| bigkarnk |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 | Black screen |
| biocom | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| biomtoy |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 | Black screen |
| blkout |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | Beta |
| blswhstl | Konami TMNT 2 based | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 |  |
| btiger | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| bubl | Taito Bubble Booble based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| bucky |  | [meathax/Bucky](https://github.com/meathax/Bucky) | 2026-08-26 | Enable `Test Mode`, `Save NVRAM` and disable `Test Mode` |
| cal50 |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | ❌ Doesn't work — Beta |
| castle | Konami 6309 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| chequeredflag |  | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 |  |
| circus | Konami Unique | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| commnd | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| comsc | Konami 6309 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| contra | Konami Contra based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| cop | Data East MEC-M1 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| cps1 | Capcom CPS-1, Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| cps15 | Capcom CPS-1.5 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| cps2 | Capcom CPS-2 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-06 |  |
| cps3 |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 | Untested on hardware — Beta. 64MB required |
| dd | Technos 6309 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| dd2 | Technos 6309 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| ddrbl |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| deadang |  | [jlrh/seibu-fpga](https://github.com/jlrh/seibu-fpga) | 2026-10-15 |  |
| destroyer |  | [jlrh/cidelsa-fpga](https://github.com/jlrh/cidelsa-fpga) | 2026-10-15 |  |
| draco |  | [jlrh/cidelsa-fpga](https://github.com/jlrh/cidelsa-fpga) | 2026-10-15 |  |
| empirecity |  | [jlrh/seibu-fpga](https://github.com/jlrh/seibu-fpga) | 2026-10-15 | Delete .arc:  Empire City (US, Bootleg) |
| exed | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-26 |  |
| flane | Konami Contra based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| flstory | Taito N.Y. Captor hardware, Taito The FairyLand Story hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| fround | Konami Twin16 hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| gae1 |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | Beta |
| gaiden | Tecmo Ninja Gaiden hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| gals |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 | Beta |
| glass |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 | ❌ Doesn't work — It launches and is playable, but it keeps freezing |
| gng | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-26 |  |
| grad3 |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-02 | Beta |
| gunsmk | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-26 |  |
| gwar | SNK Triple Z80 | [jlrh/snk-fpga](https://github.com/jlrh/snk-fpga) | 2026-10-15 |  |
| harier |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-06 |  |
| hotchase |  | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 |  |
| karnov | Data East Karnov hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| kchamp | Data East Z80 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| kicker | Konami 6809 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| kiwi | Taito The NewZealand Story hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | ⚠️ Issues — Arkanoid II (parent and clones) "Security Error" on boot. Kabuki-Z sprites missing |
| konamigt |  | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 |  |
| kunio | Technos 6309 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| labrun | Konami Contra based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | ⚠️ Issues — Labyrinth Run (Japan) wrong sprites |
| mariobros | Mario Bros. hardware | [MiSTer-devel/Arcade-MarioBros_MiSTer](https://github.com/MiSTer-devel/Arcade-MarioBros_MiSTer) | 2026-08-26 | The audio doesn’t sound quite right |
| mechatt |  | [jlrh/snk-fpga](https://github.com/jlrh/snk-fpga) | 2026-10-15 |  |
| midres | Data East MEC-M1 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| mikie | Konami 6809 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| momoko |  | [javi-ivaj/momoko120-fpga](https://github.com/javi-ivaj/momoko120-fpga) | 2026-08-28 |  |
| moomesa |  | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 | Enable `Test Mode`, `Save NVRAM` and disable `Test Mode` |
| mtlchamp |  | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 |  |
| mx5k | Konami 6309 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 |  |
| mystston |  | Original | 2026-08-26 | Bug: Flickering horizontal lines |
| mystwarr |  | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 |  |
| ninja | Data East MEC-M1, DATA EAST MEC-M1 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-21 |  |
| opwolf |  | [jlrh/taito-fpga](https://github.com/jlrh/taito-fpga) | 2026-10-15 | ❌ Doesn't work — Freeze on boot |
| outrun | Sega Out Run hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-02 | ⚠️ Issues — Sprites with glitches |
| paclan | Namco Unique | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-06 |  |
| pang | Capcom Mitchell | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | ⚠️ Issues — Adventure Quiz 2, Quiz, Sangokushi, Quiz Tonosama: Bad graphics. Mahjong Gakuen: No video |
| paroda | Konami TMNT 2 based, Konami Surprise Attack hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| pinpon | Konami Z80 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| pktgal |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | Beta |
| prmr | Konami TMNT 2 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | ❌ Doesn't work — Bad ROM/RAM check. No sound (jt539 module is missing and not publicly available) |
| rastan | Taito 68000 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-06 | Beta |
| riders | Konami TMNT 2 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | ⚠️ Issues — Missing obj sprites in Sunset Riders |
| roadf | Konami 6809 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-26 |  |
| roc | Konami 6809 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| rumble | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-26 |  |
| rungun | Konami Run and Gun hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 | ⚠️ Issues — No sound (jt539 module is missing and not publicly available) |
| s16 | Sega System 16 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-06 |  |
| s16b | Sega System 16 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| s18 | Sega System 18 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| sarms | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-26 | ⚠️ Issues — Keyboard doesn't work. No OSD |
| sbaskt | Konami 6809 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| sectnz | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| sf | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| shadfrce |  | [jlrh/technos-fpga](https://github.com/jlrh/technos-fpga) | 2026-10-15 |  |
| shanon | Sega Out Run hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| shouse | Namco System-1 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | Enter `Service Mode`, change `Flip` setting , `Save NVRAM` and `Reset` |
| simson | Konami Vendetta hardware, Konami The Simpsons hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 | ⚠️ Issues — Escape Kids: Black screen |
| slyspy | Data East MEC-M1 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| splash |  | [javi-ivaj/splash-fpga](https://github.com/javi-ivaj/splash-fpga) | 2026-08-28 |  |
| squash |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 |  |
| ssriders | Konami TMNT 2 based | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 | Only parent boots without EEPROM CRC OK. |
| systemc2 |  | [Mezzow/Arcade-SystemC2_MiSTer](https://github.com/Mezzow/Arcade-SystemC2_MiSTer) | 2026-09-06 |  |
| taitox |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-06 | Beta |
| thoop |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 |  |
| thoop2 |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 |  |
| thundr | Namco System 86, Namco Baraduke hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| tmnt | Konami TMNT based, Konami TMNT 2 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | Thunder Cross 2: Enter `Service Mode` , `Save NVRAM` and `Reset` |
| toki | Seibu Toki hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| tora | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| track | Konami 6809 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | Track & Field (NZ bootleg?): Clone doesn't boot |
| trojan | Capcom CPS-0 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-10-16 | ⚠️ Issues — Avengers (and clones) Some background sprites are missing |
| twin16 | Konami Twin16 hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| vigil | Irem M75 | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| vlfied |  | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-09-02 | Beta |
| wc | Tecmo Tehkan hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| wrally |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 |  |
| wrally2 |  | [jlrh/gaelco-fpga](https://github.com/jlrh/gaelco-fpga) | 2026-10-15 | ❌ Doesn't work |
| wwfss | Technos Unique | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |
| xexex |  | [jlrh/konami-fpga](https://github.com/jlrh/konami-fpga) | 2026-10-15 |  |
| xmen | Konami X-Men hardware | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 | ⚠️ Issues — No sound (jt539 module is missing and not publicly available) Clones bad EEPROM. |
| yiear | Konami 6809 based | [jotego/jtcores](https://github.com/jotego/jtcores) | 2026-08-31 |  |

## Credits

- [Jose Tejada (jotego)](https://github.com/jotego) — [JTFRAME](https://github.com/jotego/jtframe) and [jtcores](https://github.com/jotego/jtcores), the framework and core collection this project builds on (81 ported cores in this database).
- [Antonio Villena](https://antoniovillena.com) — creator of neptUNO+, the FPGA board this project targets as the successor to neptUNO.
- [somhi](https://github.com/somhi) — reference work on JTFRAME-based neptUNO+ targets, used alongside other public sources when building this project's own neptUNO+ target.
- [javi-ivaj](https://github.com/javi-ivaj) — 2 ported cores in this database.
- [jlrh](https://github.com/jlrh) — 30 ported cores in this database.
- [meathax](https://github.com/meathax) — 1 ported core in this database.
- [Mezzow](https://github.com/Mezzow) — 1 ported core in this database.
- [MiSTer-devel](https://github.com/MiSTer-devel) — 1 ported core in this database.
- The MiSTer/MiST/SiDi open-source FPGA arcade community.
