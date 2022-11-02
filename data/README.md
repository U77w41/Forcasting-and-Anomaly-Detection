## To revert .dvc files to actual files:
```
git log --oneline
```

```
git checkout HEAD^1 data\processed\Storewise_data.zip.dvc
```

```
dvc checkout
```