![demo](images/904.jpg)

Download random images with no download limit or tokens.
You have 1000 jpg images with 1000px width.

The range is from **1 to 1000**. If I wanted the first one I would use `1.jpg`.

```
https://cdn.jsdelivr.net/gh/tanrax/place-image-random/images/1.jpg
```

Only Bash.

``` bash
curl "https://cdn.jsdelivr.net/gh/tanrax/place-image-random/images/$((1 + $RANDOM % 1000)).jpg" -o random-image.jpg
```


Images downloaded thanks to [Place image](https://github.com/tanrax/place-image).
