# Dataset Download API

## COCO

`http://cocodataset.org/#download`

Download COCO 2014

```
# 指定下载目录，默认： ~/data/
sh data/scripts/coco2014.sh /data/dl/
sh data/scripts/coco2017.sh /data/dl/
```

# Problem

`Syntax error: end of file unexpected (expecting "then")`

```
vim coco2017.sh
:set fileformat=unix
:wq
```
