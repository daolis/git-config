# GIT Configuration

This repository contains a sample git configuration like ...

* Collection of aliases
* Tool configuration 
* Console color settings
* ...

## Installation

Clone the repository directly into your home directory

    git clone ssh://git@stash.netconomy.net:7999/~sbechter/gitconfig.git .git-config

Copy the file ```gitignore-sample``` to you home directory, rename it to ```.gitconfig``` change your name, email and line-endings setting.

Add own configuration directly to the ```.gitconfig``` file.

If you do not want to use the pre-defined settings uncomment the ```path=file``` setting in ```[include]``` section.

     [include]
        path = .git-config/common
        path = .git-config/colors
        path = .git-config/tools
        path = .git-config/aliases

