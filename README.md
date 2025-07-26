# Pokémon Trading Card Game, Version 2 (NL Translation)

This is a fan translation of Pokémon Trading Card Game for the Game Boy (Color) into Dutch/Nederlands, and includes many improvements. It's based on the rom base [poketcg_v2](https://github.com/Sha0den/poketcg_v2) by Shaoden.

Original description:
This is a modified disassembly of Pokémon Trading Card Game for the Game Boy Color. It was originally designed to be used as a base for future romhacks, but it can also be used as an improvement hack for people looking to replay the original game. A lot of the changes deal with more efficient code and better function comments and are therefore not likely to be noticed by prospective players, but there are plenty of other differences that are much easier to see. All displayed text is now mixed case instead of uppercase only, and the in-game keyboard was significantly expanded to offer more variety when naming both the protagonist and custom decks. Players can choose to play as either Mark or Mint, like in the sequel. The tutorial at the start of the game is now optional. Various text throughout the game was edited to better fit the 2-line display in the textboxes, and some of the menu screens were redesigned; the glossary in particular is almost entirely different from its original incarnation. It's also worth noting that numerous glitches present in the base game were fixed. For a full overview of the changes that were made to the original game, see [**CHANGELOG.md**](CHANGELOG.md).

Here are a bunch of screenshots showcasing the differences between the original Pokémon Trading Card Game and my translation:

![Comparison Screenshots](https://github.com/user-attachments/assets/2bf75ff7-a2bd-4aa4-bf4b-02efd191d0d4)
<br/>
## Building the rom file
To assemble, install cygwin (if you're using Windows) with packages **make**, **git** and **gcc-core** and then download the [latest version of RGBDS](https://github.com/gbdev/rgbds/releases) and extract it to **/usr/local/bin** (inside the folder where you installed Cygwin64 on Windows).<br/>
Open the (Cygwin64) Terminal (optionally go to the desired directory) and clone the repo with<br/>`git clone https://github.com/JappaWakka/poketcg_v2_nl.git poketcg_v2_nl`,<br/>then change directories to the root of the repo with `cd poketcg_v2_nl` and run `make` in your shell (or Cygwin64 Terminal on Windows).<br/>This will output a file named "poketcg_v2_nl.gbc".

For more detailed instructions about how to set up the repository, see [**INSTALL.md**](INSTALL.md).
<br/>
## Patching an official rom with a .bps from [Releases](https://github.com/JappaWakka/poketcg_v2_nl/releases)
If you don't want to build the rom yourself, you can also patch a .bps (latest version available [here](https://github.com/JappaWakka/poketcg_v2_nl/releases/latest)) onto a _legally_ obtained rom similar to **Pokemon Trading Card Game (USA, Australia) (SGB Enhanced) (GB Compatible).gbc**.
<br/>
If you want to be sure, the checksums are:
* SHA-1: 0F8670A583255CFF3E5B7CA71B5D7454D928FC48
* CRC32: 81069D53

You can use any patcher that supports .bps, like [Floating IPS](https://www.romhacking.net/utilities/1040/) or many online rom patchers.<br/>
An emulator that fully supports MBC30 is recommended to prevent issues, which includes:
* BGB (PC)
* RetroArch (SameBoy / mGBA / Mesen-S cores) (Android/iOS, PC, etc)
* Sameboy (PC, MacOS)
* mGBA (all platforms) (requires BIOS to run faster sometimes)
* SkyEmu (Browser)
* Bizhawk (Gambatte / SameBoy cores) (PC)
* Analog Pocket (Console/Flash Cart)
* ODroid-Go / Retro-Go (Console/Flash Cart)
* PizzaBoy Pro GBC (ver5.4.5+) (Android) [requires disabling Super Gameboy Mode]
* MBC3000 (by BenVenn) (Console/Flash Cart)

## See also:
- [Discord server for PokeTCG Hacking]
- [Discord server for pret]
- [Hacking Tutorials]
- [Unaltered Disassembly]

[Discord server for PokeTCG Hacking]: https://discord.gg/K2kfTx2xRf
[Discord server for pret]: https://discord.gg/d5dubZ3
[Hacking Tutorials]: https://github.com/pret/poketcg/wiki/Tutorials
[Unaltered Disassembly]: https://github.com/pret/poketcg
