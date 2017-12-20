Pixivly-Data
============

Daily top illustration with images and json format meta data on [Pixiv][pixiv].

### Where comes the data?

All data are from [Pixiv][pixiv]. We use the tool of [Pixivly/get_pixivly][gp] to get all these data, you can crawl the data by yourself if needed.

### What the data offers?

We organize the data by year. Every year is a folder and has `image` and `json`. All pictures are under `image` with id in its file name. Meta data information are all under `json`.

```
|-- 2015
|    |-- image
|    |    |-- pixiv_xxxxxx.jpg
|    |    |-- pixiv_xxxxxx.jpg
|    |    |-- ...
|    |-- json
|    |    |-- 20150101_01.json
|    |    |-- 20150101_02.json
|    |    |-- 20150102_01.json
|    |    |-- 20150102_02.json
|    |    |-- ...
```

`20150101_01.json` stands for top 1-50 of date `20150101` and `20150101_02.json` stands for top 51-100.

There's something you should notice, since some links/images are invalid, so there might have no picture under `image` with some ids. What's more, we only provide the small version of the illustrations with average size is 240x480.

### Where to download the data?

We provide the data through [Baidu Driver][bd-share], and we will update the data every year.

### Why provide this data?

Since I am a Big Anime Fan and [Pixiv][pixiv] is a great community where people share their best works, I think it's a good idea to do something like Data Mining or Machine Learning stuff with top illustrations provided by [Pixiv][pixiv].

### Applications

- [Pixily][pixivly]

**Welcome to do something interesting :)**


[pixiv]: http://www.pixiv.net/
[gp]: https://github.com/Pixivly/get_pixivly
[bd-share]: http://pan.baidu.com/s/1hsyIGHA
[pixivly]: http://pixivly.luoyetx.com/
