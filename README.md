# Noctua's dotfiles

These are the dotfiles that I am currently using for my day-to-day work, with a focus on scientific computing and data science. I'll be constantly updating this repository as I find new ways to improve my workflow. These are tools that work for me, but I hope you can find something useful here as well.

## Setup

Clone the repository and use [GNU Stow](https://www.gnu.org/software/stow/) to symlink configuration files to your home directory:

```bash
git clone git@github.com:noctuaquanta/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
stow .
```

## Tools & Environment

These dotfiles are optimized for a macOS environment tailored for scientific computing, data visualization, programming, and a fast terminal experience.

### Shell & Terminal

- [zsh](https://www.zsh.org/) with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)  
- [starship](https://starship.rs/) (prompt)  
- [kitty](https://sw.kovidgoyal.net/kitty/) (GPU-accelerated terminal)  
- [tmux](https://github.com/tmux/tmux) (terminal multiplexer)  
- [stow](https://www.gnu.org/software/stow/) (dotfile management)  

### Editor & Dev Tools

- [neovim](https://neovim.io/) (Lua-configured with LSP and Treesitter)  
- [clang-format](https://clang.llvm.org/docs/ClangFormat.html), [cmake](https://cmake.org/), [fd](https://github.com/sharkdp/fd), [ripgrep](https://github.com/BurntSushi/ripgrep), [fzf](https://github.com/junegunn/fzf)  
- [git](https://git-scm.com/), [git-delta](https://github.com/dandavison/delta), [lazygit](https://github.com/jesseduffield/lazygit)  
- [jq](https://stedolan.github.io/jq/), [bat](https://github.com/sharkdp/bat), [eza](https://the.exa.website/), [tree](http://mama.indstate.edu/users/ice/tree/), [yazi](https://github.com/imsnif/yazi), [zoxide](https://github.com/ajeetdsouza/zoxide), [fastfetch](https://github.com/LinusDierheimer/fastfetch)  

### Programming & Data Science

- [pyenv](https://github.com/pyenv/pyenv), [pipenv](https://pipenv.pypa.io/en/latest/), [anaconda](https://www.anaconda.com/)  
- [R](https://www.r-project.org/), [RStudio](https://posit.co/products/open-source/rstudio/)  
- [node.js](https://nodejs.org/)  
- [hdf5](https://portal.hdfgroup.org/display/HDF5/HDF5), [gnuplot](http://www.gnuplot.info/), [imagemagick](https://imagemagick.org/), [poppler](https://poppler.freedesktop.org/)  
- [PostgreSQL 14](https://www.postgresql.org/docs/14/index.html)  
- [Docker Desktop](https://www.docker.com/products/docker-desktop)  

### Academic & Writing

- [MacTeX](https://tug.org/mactex/) (full LaTeX suite)  
- [Obsidian](https://obsidian.md/) (markdown knowledge base)  
- [Anki](https://apps.ankiweb.net/) (spaced repetition)  

### QOL & Miscellaneous

- [Spotify](https://www.spotify.com/), [Discord](https://discord.com/), [NordVPN](https://nordvpn.com/), [NordPass](https://nordpass.com/)  
- [Raycast](https://www.raycast.com/), [Mos](https://mos.caldis.me/), [AppCleaner](https://freemacsoft.net/appcleaner/)  
- [QMK Firmware](https://qmk.fm/), [QMK Toolbox](https://github.com/qmk/qmk_toolbox) (mechanical keyboard firmware)
