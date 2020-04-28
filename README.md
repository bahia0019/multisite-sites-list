# Multisite Sites List

> Replace that useless WordPress Multisite site list with something far better!

-   If you manage lots of sites in a Multisite network, you'll know how frustrating using the Sites List can be. You can't scroll, so if you have more than 30 sites, you are forced to go to the Sites screen. The flyout submenus can be bit hard to navigate, and there are options in there that are kinda pointless (comments???).

-   That said, the Sites List has a lot of potential, and I wanted to improve upon it. The ideas I had were:
-   It should scroll through ALL the sites.
-   It should have useful links without submenus.
-   It should have a search feature like the very cool plugin [My Sites Search](https://github.com/trepmal/my-sites-search) by [Kailey Lampert](https://github.com/trepmal)

[![Demonstration of Multisite Sites List in action](multisite-sites-list.gif)]()

-   This is my first project I'd like to open source. So PLEASE feel free to contribute. I'd like to eventually see this, or an improved upon version of this, in Core.
-   The majority of work was done in Javascript. Mostly because the WordPress functions for adding items in the Admin Bar return a very rigid sub-nav, and it was easier for me to figure that out in JS.
-   A PHP refactor would probably be more elegant though. If you can help with this aspect, please do.

---

## Installation

-   This is a WordPress plugin that will only work in a Multisite environment (if you don't know what that means, you don't have it).

### Download the zip file

-   Download the zip file.
-   In WordPress, from the Network Admin:
-   Install new plugin.
-   Click on upload file.
-   Select the zip file you just downloaded.
-   Network Activate the plugin.

### Setup

-   There is no setup. It is plug and play.

---

## Contact

-   Create issues here, or hit me up on Twitter [@williambay](https://twitter.com/williambay)
