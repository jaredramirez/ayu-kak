This is a fork with some modifications from the original. It just changes the mirage style BufferPadding and Prompt/StatusLine stuff. Here's a screenshot of this used with it's [companion powerline plugin](https://github.com/jaredramirez/ayu-kak-powerline):

<img width="1440" alt="Screen Shot 2021-03-12 at 6 06 20 PM" src="https://user-images.githubusercontent.com/8095741/111015457-ab0ec080-835d-11eb-8bde-18c8ecc58d83.png">


Below is the original README:

# ayu-kak
[Ayu](https://github.com/dempfi/ayu) colorscheme ported to the [Kakoune](https://github.com/mawww/kakoune) editor.

> If you can think of a better assignment of the colors; feel free to open an issue / PR.

## Install

If you have use [plug.kak](https://github.com/andreyorst/plug.kak) then you can simply add to your config 

```
plug "jaredramirez/ayu-kak" theme
```

Otherwise just link the theme files into your config's color sub-folder.

```bash
ln -s $XDG_CONFIG_HOME/kak/colors/ $PWD/colors/*
```

## Thanks!
- Ayu colorscheme : [dempfi/ayu](https://github.com/dempfi/ayu)
- Kakoune editor : [mawww/kakoune](https://github.com/mawww/kakoune)
