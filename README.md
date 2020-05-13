# potato-salad

Potato + privileges = salad


## Submodule actions

Initial clone
```
git clone --recursive https://github.com/0x90/potato-salad
```


Update and pull submodules

```
git submodule update --init --recursive -j 8
```

pull all changes in the repo including changes in the submodules

```
git pull --recurse-submodules
```

pull all changes for the submodules

```
git submodule update --remote
```

Remove submodule

```
git submodule deinit <path_to_submodule>
git rm <path_to_submodule>
git commit-m "Removed submodule "
rm -rf .git/modules/<path_to_submodule>
```
