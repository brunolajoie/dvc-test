Tuturial following the [blog post](https://towardsdatascience.com/data-and-machine-learning-model-versioning-with-dvc-34fdadd06b15)

We have the following git history
```bash
* b9125e6 - data_and_model_v2 (4 minutes ago) Bruno Lajoie  (HEAD, tag: data_model_v2)
* 4b1dad8 - data_model_v1 (6 minutes ago) Bruno Lajoie  (tag: data_model_v1)
* c545a4c - Dataset V2.0 (38 minutes ago) Bruno Lajoie  (tag: v2.0, master)
* c9f2bd6 - Dataset V1.0 (45 minutes ago) Bruno Lajoie  (tag: v1.0)
* 980d9f7 - add google drive folder remote (48 minutes ago) Bruno Lajoie 
* 5930171 - dvc init (48 minutes ago) Bruno Lajoie 
```

## 1) Alternate datasets
```bash
git checkout v1.0
dvc pull
```

```bash
git checkout v2.0
dvc pull
```

## 2) Alternate model pipelines

```bash
git checkout data_model_v1
dvc pull

# OR
git checkout data_model_v2
dvc pull
```
