# Atom setting

## Installation 

If you don't have it already, [download the Atom editor](https://atom.io/). 
Install it, run it at least once and be sure to quit it then.

```
cd ~
# If you have an atom config already:
mv .atom .atom-bak
git clone https://github.com/Nirperm/atomfiles.git .atom
cd .atom && bin/update-packages
```

## Packages
### How to install a new package
#### At the command prompt

1. Install new-package:   
`~/.atom/bin/install-package new-package`  
2. Change to packages.txt


### How to upgrade packages
#### At the command prompt
1. Run:  
`~/.atom/bin/update-packages`  
2. Change to package.txt

## Key Bindings

## Installed
* [color-picker](color-picker) - Adds a color picker.
* [Linter](https://atom.io/packages/linter) - Enable displaying lint (code style) warnings
