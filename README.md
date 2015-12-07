# yt-mp3

Download a list of MP3 musics from YouTube at command-line.

### Instalation

#### Dependencies

The `yt-mp3` script use this apps and libs:

- [cURL](http://curl.haxx.se/)
- [JSON node CLI tool](https://github.com/trentm/json),
- For that, also [Node JS](https://nodejs.org/en/)
- And [youtube-dl](https://github.com/rg3/youtube-dl)

So, install then on your system before install and run `yt-mp3`.

#### Manual Mode

To install `yt-mp3` manually, first get the script on your system:

    curl -L http://github.com/brendaw/yt-mp3/raw/master/yt-mp3 > yt-mp3

Then make it executable and put it somewhere in your path:

    chmod 755 yt-mp3 && mv yt-mp3 ~/.bin/

#### By Install Script

Coming soon...

### Usage

Simply pass a file name as a arg, like that:

```bash
$ yt-mp3 musics.txt
```

_musics.txt_
```
Little Black Submarines - The Black Keys
True Doesn't Make A Noise - The White Stripes
Love Reconnected - Fire Department Club
```

And the script will find the first video on youtube with the content of each line, using the Youtube API, and download the mp3 version of then. Simple as that.


### Changelog

See [Changelog file](https://github.com/brendaw/yt-mp3/blob/master/CHANGELOG.md) for more details about versions changes.

### License

This script is licensed under a MIT license. See [LICENSE](https://github.com/brendaw/yt-mp3/blob/master/LICENSE) for more information.

### Help Improve

Feel free to send [Issues](https://github.com/brendaw/yt-mp3/issues) and [Pull Requests](https://github.com/brendaw/yt-mp3/pulls) and help improve yt-mp3 script.
