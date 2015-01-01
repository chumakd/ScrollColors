ScrollColors
=====

Initially this is a mirror of http://www.vim.org/scripts/script.php?script_id=1488, but I've made some changes to the script and to make the documentation better.
This version should be simpatico with the spf13-vim bundle packages.

## Synopsis
   This is colorscheme Scroller/Chooser/Browser.
   With this plugin, you walk through installed colorschemes using arrow keys.

## Short Usage Description
1. Drop ScrollColors.vim into your plugin directory.
2. Type `:ScrollColor`
3. Use arrow keys to walk through colorschemes, ? for help, Esc to exit.

## Detailed Description
1. `source ScrollColors.vim`  " or drop ScrollColors.vim into your `~/.vim/plugin` directory.
2. Type `:ScrollColor`
3. Use arrows to scroll thgough colorschemes.
4. When done, press Esc to exit. You will be prompted whether to confirm your selection.

spf13-vim comes loaded with lots of color schemes, but you can get more (if they aren't already included) by downloading a 140 colorscheme pack from http://www.vim.org/scripts/script.php?script_id=625

Having 140 installed colorschemes is in no way prerequisite for ScrollColors. But with ScrollColors you can preview 140 colorschemes in couple of minutes. Have fun.

## CUSTOM KEY MAPPINGS
You can map two keys of your choice to NextColor and PrevColor actions. Choose pair of shortcut keys (for example <F8> and <S-F8>, or \n and \p) and map them as follows:
```
      map <silent><F8> :NextColor<cr>
      map <silent><S-F8> :PrevColor<cr>
```

Vim should have the F8 key mapped for this task by default, but it doesn't work in spf13-vim probably because of all the keys they remapped.  Hopefully this script will re-enable that.

I was thinking, F8 would prompt this script if the key was held down.  Tapped `F8` would move to the next scheme, `SHIFT+F8` would move to the previous scheme, and `CTRL+F8` would pick something random.

## Projects you should check out
* [SPF13-Vim](https://github.com/spf13/spf13-vim) includes a bundle of great plugins like [NERDTree](https://github.com/scrooloose/nerdtree) and [Airline](https://github.com/bling/vim-airline).  Even if you don't like bundles, I still recommend those two plugins they include.
* [Pathogen](https://github.com/tpope/vim-pathogen) for installing things like SPF13-Vim.  ScrollColors shouldn't be that complicated.
* [tmux](http://tmux.sourceforge.net/) Terminal Multiplexer
* [urxvt](http://software.schmorp.de/pkg/rxvt-unicode.html) Terminal Emulator with all sorts of settings!  Visit [this page](http://www.askapache.com/linux/rxvt-xresources.html) for some idea as to how to set it up.
* [fluxbox](http://fluxbox.org/) (on [GitHub](https://github.com/fluxbox/fluxbox)!) a light-weight very stylish desktop environment. A classic that is way better than the modern LXDE! There's an old-style [style manager](https://github.com/michaelrice/fluxStyle) for it.

I'll have dotfiles for all that in a `dotfiles` repo later to show you what I use so that you can edit them to fit your taste.
