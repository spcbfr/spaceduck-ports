# Spaceduck Ports 🏅
This is a collection of ports for the spaceduck theme, if you are looking for the main spaceduck repository you can find it [here](https://github.com/pineapplegiant/spaceduck)

# Currently available ports 🚀
- [Firefox](#firefox)
- [DuckDuckGo](#duckduckgo)
- [dwm](#dwm)
- [vsocde](#vscode)
- [Emacs](emacs)
- [Slack](#slack)
- [Terminals](#terminals)

## Firefox
you can add The spaceduck theme to firefox from the offical Firefox Browser Addons website (thanks to [Niels Gerritsen](https://nielsgerritsen.com/) for making the theme):
[https://addons.mozilla.org/firefox/addon/spaceduck/](https://addons.mozilla.org/firefox/addon/spaceduck/)

![Firefox Theme](https://raw.githubusercontent.com/YoussefBouzekri/spaceduck-ports/master/screenshots/firefox.png)

## DuckDuckGo
to add spaceduck to your ddg search results:
go to Settings > All Settings > find Cloud Save > Load Settings > type `spaceduck-ddg` > click Load

![Spaceduck Theme](https://raw.githubusercontent.com/YoussefBouzekri/spaceduck-ports/master/screenshots/duckduckgo.png)
## dwm
You can change the different window border colors in dwm to match the spaceduck theme, add the following to your `config.h` if you don't already have it:
```c
static char normbgcolor[]           = "#0f111b";
static char normbordercolor[]       = "#1b1c36";
static char normfgcolor[]           = "#ecf0c1";
static char selfgcolor[]            = "#000000";
static char selbordercolor[]        = "#e33400";
static char selbgcolor[]            = "#5ccc96"; 
static char *colors[][3] = {
       /*               fg           bg           border   */
       [SchemeNorm] = { normfgcolor, normbgcolor, normbordercolor },
       [SchemeSel]  = { selfgcolor,  selbgcolor,  selbordercolor  },
};
```

## vscode
you can find the source-code and the instuctions to install spaceduck in vscode [here](https://github.com/ctrl-dlahr/spaceduck-vscode) (thanks to [Dustin Lahr](https://github.com/ctrl-dlahr) for making this port)

## Emacs
you can find the source-code and the instuctions to install spaceduck in emacs [here](https://github.com/ctrl-dlahr/spaceduck-emacs) (thanks to [Dustin Lahr](https://github.com/ctrl-dlahr) for making this port)

## Slack
- Go to User Menu > Preferences > Sidebar Theme
- In the bottom of the window, look for a "customize your theme and share it with others" link
- Copy and paste the values below:
  - `#0f111b,#7A5CCC,#7A5CCC,#ffffff,#16172D,#ecf0c1,#5CCC96,#00A3CC,#0f111b,#ecf0c1`

## Terminals
You can find most terminal ports over in this [repo](https://github.com/pineapplegiant/spaceduck-terminal)
