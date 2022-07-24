```zsh
source /path-to-antigen/antigen.zsh

# Load the oh-my-zsh's library.
antigen use oh-my-zsh

# Bundles from the default repo (robbyrussell's oh-my-zsh).
antigen bundle git
antigen bundle heroku
antigen bundle pip
antigen bundle lein
antigen bundle command-not-found
# Turn on an Oh my Zsh plugin
antigen bundle plugin-name
antigen bundle git
antigen bundle command-not-found
antigen bundle docker

# Apply an Oh my Zsh theme
antigen theme theme-name
antigen theme robbyrussell
# Syntax highlighting bundle.
antigen bundle zsh-users/zsh-syntax-highlighting

# Load the theme.
antigen theme robbyrussell

# Tell Antigen that you're done.
antigen apply

# Load oh-my-zsh library
antigen use oh-my-zsh

# Load bundles from the default repo (oh-my-zsh)
antigen bundle git
antigen bundle command-not-found
antigen bundle docker
antigen bundle unixorn/autoupdate-antigen.zshplugin
antigen bundle ael-code/zsh-colored-man-pages
source colored-man-pages.plugin.zsh && man less
# Load bundles from external repos
antigen bundle zsh-users/zsh-completions
antigen bundle zsh-users/zsh-autosuggestions
antigen bundle zsh-users/zsh-syntax-highlighting

# Select theme
antigen theme denysdovhan/spaceship-prompt

# Tell Antigen that you're done
antigen apply
```

