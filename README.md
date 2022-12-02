Tuturial following the [blog post](https://towardsdatascience.com/data-and-machine-learning-model-versioning-with-dvc-34fdadd06b15)

## 1) Alternate datasets
```bash
# git lg
* c545a4c - Dataset V2.0 (4 minutes ago) Bruno Lajoie  (HEAD -> master, tag: v2.0)
* c9f2bd6 - Dataset V1.0 (11 minutes ago) Bruno Lajoie  (tag: v1.0)
* 980d9f7 - add google drive folder remote (14 minutes ago) Bruno Lajoie 
* 5930171 - dvc init (15 minutes ago) Bruno Lajoie 
```

```bash
git checkout v1.0
dvc pull
```

```bash
git checkout v2.0
dvc pull
```
