# fiveminutegaming



## Building the site


Builds the site, output HTML into the `docs/` directory
```bash
./bin/hugo_win.exe  -d docs/
```

Updates github pages

```bash
git add docs/
git commit --message="Update on `date +%s`"
git push origin master
```