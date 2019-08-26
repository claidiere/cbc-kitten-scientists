# Kitten Scientists

<p align="center"><img src="https://i.imgur.com/AWHGIGH.jpg" /></p>

Kitten Scientists (KS) is a simple automation script for the complex [Kittens Game](http://bloodrizer.ru/games/kittens/).

## Basic Usage

Create the following JavaScript bookmarklet (create a new bookmark and past this as the URL):

    javascript:(function(){var d=document,s=d.createElement('script');s.src='https://cdn.jsdelivr.net/gh/cameroncondry/cbc-kitten-scientists@master/kitten-scientists.user.js';d.body.appendChild(s);})();

### Alternative Installation

You can also permanently install Kitten Scientists with a userscript manager.

- On **Firefox**, you'd want to use [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/).
- On **Chrome** and **Opera**, you'd want to use [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).

Now simply [open the script](https://raw.githubusercontent.com/cameroncondry/cbc-kitten-scientists/master/kitten-scientists.user.js) and you should be prompted to install it. 

## Functionality

- Several UI adjustments (depending on selected theme).
- Automates:
    - Building (Bonfire, Space, Religion, and Time Buildings)
    - Crafting
    - Upgrading
    - Trading
    - Hunting
    - Praising
    - Holding Festivals
    - Observing Astronomical Events
    - Trading Cryptocurrency
    - Autofeeding Necrocorns
    - Exploring (Deprecated)

### Building

By default, buildings are built if their required resources are at 75% of their storage capacity. For space structures,
the default threshold is 95%.

### Crafting

Craftable resources are crafted when the resources required for the craft are at 95% of their storage capacity.
 
Additionally, you can set a *consumption rate* (60% by default). This defines how much of the available resources can be
used for crafting.

### Trading

Trades happen when the traded resource is at 95% of the storage capacity. The trades are optimized to only happen during
seasons when the trade is most effective.

### Hunting

Hunts when catpower is at 95% capacity and builds luxury items before the hunt is sent.

### Praising

Praises when faith is at 99% capacity.

### Game Log

Automatically observes astronomical events.

## Contributors

If you would like to contribute to the Kitten Scientists, then you can do so in these ways:

- Submit issues or bugs you find, or functionality that would improve the project.
- Fork the repository, add some functionality, then submit a pull request.

Thanks to these past and present contributors!

- [adituv](https://github.com/adituv)
- [amaranth](https://github.com/amaranth)
- [Azulan](https://www.reddit.com/user/Azulan)
- [carver](https://github.com/carver)
- [coderpatsy](https://github.com/coderpatsy)
- [cokernel](https://github.com/cokernel)
- [DirCattus](https://www.reddit.com/user/DirCattus)
- [DrGaellon](https://github.com/DrGaellon)
- Eliezer Kanal
- [enki1337](https://github.com/enki1337)
- [FancyRabbitt](https://www.reddit.com/user/FancyRabbitt)
- [gnidan](https://github.com/gnidan)
- [Hastebro](https://github.com/Hastebro)
- [hypehuman](https://github.com/hypehuman)
- Iris Ward
- ironchefpython
- [jacob-keller](https://github.com/jacob-keller)
- Jason Carver
- [jcranmer](https://github.com/jcranmer)
- [KMChappell](https://github.com/KMChappell)
- [Kobata](https://github.com/Kobata)
- [magus424](https://github.com/magus424)
- [mammothb](https://github.com/mammothb)
- [markuskeunecke](https://github.com/markuskeunecke)
- Meleneth
- [Mewnine](https://www.reddit.com/user/Mewnine)
- [mjdillon](https://github.com/mjdillon)
- [mmccubbing](https://github.com/mmccubbing)
- [NoobKitten](https://github.com/NoobKitten)
- [oliversalzburg](https://github.com/oliversalzburg)
- [pefoley2](https://www.reddit.com/user/pefoley2)
- [Phoenix09](https://github.com/Phoenix09)
- [poizan42](https://github.com/poizan42)
- [riannucci](https://github.com/riannucci)
- [romanalexander](https://github.com/romanalexander)
- [sapid](https://github.com/sapid)
- [sjdrodge](https://github.com/sjdrodge)
- [SphtMarathon](https://www.reddit.com/user/SphtMarathon)
- [TeWeBu](https://github.com/TeWeBu)
- Tom Rauchenwald
- [toadjaune](https://github.com/toadjaune)
- [trini](https://github.com/trini)
- [woutershep](https://github.com/woutershep)
- [Wymrite](https://github.com/Wymrite)
- [Xanidel](https://github.com/Xanidel)
- [zelenay](https://github.com/zelenay)
