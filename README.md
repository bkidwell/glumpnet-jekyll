# glumpnet-jekyll

Glump.net site/blog implemented in Jekyll. This is my own personal project to port my web site to Jekyll; you are welcome to look at my code/data, but I will not provide any support at this time.

In the future I might create Jekyll plugins and external code to implement features not handled by Jekyll and hopefully I will package those as standalone repositories separate from this one.

## Development Setup

In Ubuntu/Linux Mint...

1. Install `rvm`. Make sure this is in your `.bashrc`:

        [[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # Load RVM$

2. Install latest Ruby 2.x.

3. Install system package `libyaml-2.0`.

4. Install Ruby gem `jekyll`.

5. Serve the site locally:

        cd $PROJECTPATH
        jekyll serve
