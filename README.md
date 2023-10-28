# metapkgs
These metapackages are used to group packages together.

The criterion for which package belongs to what metapackage is kind of loose. I generally just put not-large packages and packages I won't touch in the metapackages.

Makes for a nicer `pacman -Qe` view, so I reduce my urge to reinstall arch. lol.

## Tips
- To install a package as a dependency, write:
```pacman -D --asdeps <package names>```
- To reverse the effect write:
```pacman -D --asexplicit <package names>```
