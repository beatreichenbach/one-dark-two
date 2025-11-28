# Contributing to One Dark Two

## Create a Screenshot

```shell
magick assets/term.png \
    \( +clone -background black -shadow 50x8+0+4 \) \
    +swap -background none -layers merge +repage \
    assets/preview.png
```

## Create Circles

```shell
./create_circles.sh
```
