# dotfiles

## Atom
Update atom package list with:

    apm list --installed --bare > atom.packages.list

Install atom packages with:

    apm install `cat atom.packages.list`
