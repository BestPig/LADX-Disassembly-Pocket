# Links Awakening DX Disassembly

Disassembly of one of my favorite games. Taking it easy for now.

It builds the following ROMs for Analogue Pocket GB Studio mode:

- azlj.pocket (Japanese, v1.0) `
md5: 5947f5d03a2629b492e316b19db76d75`
- azlj-r1.pocket (Japanese, v1.1) `
md5: 02f286d17b9709bce289d27c2244a852`
- azlj-r2.pocket (Japanese, v1.2) `
md5: 607b2999502b0b8c9faa5e4d84601c8c`
- azle.pocket (English, v1.0) `
md5: e7c00c86a14da1297ead6fc1e9c8c8f1`
- azle-r1.pocket (English, v1.1) `
md5: 557b463359dc0649c29f07e119f0986c`
- azle-r2.pocket (English, v1.2) `
md5: c80f781e100b17347e8c15b4bc544f6d`
- azlg.pocket (German, v1.0) `
md5: 4f0ef5707ae9c34957648e2f1e70909a`
- azlg-r1.pocket (German, v1.1) `
md5: ccda6d3e26e0f3281dcc734df41b9ed1`
- azlf.pocket (French, v1.0) `
md5: 14e5ab8ece90ec66b725322a52074f9e`
- azlf-r1.pocket (French, v1.1) `
md5: 25e363c1c0eb64d515c942edf05dda52`

Additionnaly, a wiki includes a [high-level overview of the game engine](https://github.com/zladx/LADX-Disassembly/wiki/Game-engine-documentation), and technical informations on the [data formats used](https://github.com/zladx/LADX-Disassembly/wiki/Maps-data-format) throughout the game.

## Usage

1. Install Python 3 and [rgbds](https://github.com/rednex/rgbds#1-installing-rgbds) (version >= 0.4.0 required);
2. `make all`.

This will build both the games and their debug symbols. Once built, use [BGB](https://github.com/zladx/LADX-Disassembly/wiki/Tooling-for-reverse-engineering#bgb) to load the debug symbols into the debugger.

## How to contribute

1. Fork this repository;
2. Find a little piece of code to improve:
  - Maybe a typo, a missing constant, an obvious label that could be renamed;
  - Or start following a thread (Link's animations? The island fade-out special effect? Trading items constants?) and document some details along your read;
  - You can also look at the [known improvements](https://github.com/zladx/LADX-Disassembly/issues) – especially [good first issues](https://github.com/zladx/LADX-Disassembly/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22good+first+issue%22);
3. Submit a pull request.

Having questions, or do you need help? Join the discussion on [Discord](https://discord.gg/sSHrwdB).
You can also read [disassembling How-Tos](https://github.com/zladx/LADX-Disassembly/wiki) in the Wiki, for some infos about the tools and disassembling processes.

## Resources

- [Artemis251's Link's Awakening Cache](http://artemis251.fobby.net/zelda/index.php): ROM map, maps data format
- [Xkeeper's Link's Awakening depot](https://xkeeper.net/hacking/linksawakening/): maps tilesets and save format infos
- [LALE](https://github.com/anotak/LALE): level editor, notes on maps data format
- [The Legend of Zelda Link's Awakening /DX Speedrunning Wiki](http://spiraster.x10host.com/LADXWiki/index.php/) : infos on wrong warps and map data format
- [Zelda III Disassembly](http://www.zeldix.net/t143-disassembly-zelda-docs) ([archive](https://web.archive.org/web/20180315181518/http://www.zeldix.net/t143-disassembly-zelda-docs)): good source on Zelda SNES source code, which has many similarities to LADX
- [Disassembling Link's Awakening](https://kemenaran.winosx.com/posts/category-disassembling-links-awakening/): a series of blog posts and progress reports
- Discord: [LADX](https://discord.gg/sSHrwdB)

## Contributors

Thanks to these people for contributing:

* mojobojo - https://github.com/mojobojo
* kemenaran - https://github.com/kemenaran
* Drenn1 - https://github.com/Drenn1
* Sanqui - https://github.com/Sanqui
* Kyle McGuffin - https://github.com/kcmcg
* Marijn van der Werf - https://github.com/marijnvdwerf
* samuel-flynn - https://github.com/samuel-flynn
* Xkeeper - https://github.com/Xkeeper0
* Vextrove - https://github.com/Vextrove
* daid - https://github.com/daid
* stephaneseng - https://github.com/stephaneseng
* zelosos - https://gitlab.com/zelosos

([See contribution details here](https://github.com/zladx/LADX-Disassembly/graphs/contributors))
