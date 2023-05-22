To execute the web locally, you need `hugo`
install `hugo`
```
apt-get
```

execute the source files
```bash
hugo --themesDir themes/ server
```

The information is written in markdown and json.


To public changes.
```bash
hugo -d ssjshirley.github.io
```

To update the submodule.
```bash
cd ssjshirley.github.io
git add .
git commit -m "web update"
git push
cd ..
## then commot the submodule change with git add, commit, push
```

The updated web can be access by [ssjshirley.github.io](https://ssjshirley.github.io/)