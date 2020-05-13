# Potato salad

Potato + privileges = salad


## Papers

https://labs.f-secure.com/archive/incognito-v2-0-released/

https://itm4n.github.io/printspoofer-abusing-impersonate-privileges/

https://movaxbx.ru/2020/05/13/abusing-seloaddriverprivilege-for-privilege-escalation/


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
