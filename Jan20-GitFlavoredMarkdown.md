#Images

`![Andika](http://software.sil.org/media/site19/banner_image.jpg "Andika banner image")`

becomes:

`<img src="http://software.sil.org/media/site19/banner_image.jpg" alt="Andika" title="Andika banner image" />`

![Andika](http://software.sil.org/media/site19/banner_image.jpg "Andika banner image")

NOTE that the above is also a link to the actual full-size image on the Andika product site.

##Did you know you can also define image IDs in Markdown?

Suppose we define the following image IDs:

```
[BannerImgCharis]: http://software.sil.org/media/site14/banner_image.jpg "Charis banner image"
[BannerImgDoulos]: http://software.sil.org/media/site18/banner_image.jpg "Doulos banner image"
[BannerImgGentium]: http://software.sil.org/media/site20/banner_image.jpg "Gentium banner image"
[BannerImgLCG]: http://software.sil.org/media/site15/banner_image.jpg "LCG Fonts banner image"
```
[BannerImgCharis]: http://software.sil.org/media/site14/banner_image.jpg "Charis banner image"
[BannerImgDoulos]: http://software.sil.org/media/site18/banner_image.jpg "Doulos banner image"
[BannerImgGentium]: http://software.sil.org/media/site20/banner_image.jpg "Gentium banner image"
[BannerImgLCG]: http://software.sil.org/media/site15/banner_image.jpg "LCG Fonts banner image"

Now we can call the IDs wherever we like. And if you change the URL or Title of an image ID, it automatically reflects everywhere that ID is called! Saves mucho repetitive typing and keeps things up to date!

`![Here's Gentium][BannerImgGentium]`
![Here's Gentium][BannerImgGentium]

`![Here's Charis][BannerImgCharis]`
![Here's Charis][BannerImgCharis]

`![Here's Charis again!][BannerImgCharis]`
![Here's Charis again!][BannerImgCharis]
