# Droid Font Family

These are copies of the droid font family, from the [Android Project](http://www.android.com/). Also included are `droid.css` and `droid.sass` files with CSS3 @font-face declarations. I use this font frequently in projects and find it convenient to have them alone in a git repository suitable for use as a submodule.

## Sass Mixins

Included in the [Sass](http://sass-lang.com/) file are some mixins that declare a few font-family properties.

* `sans-serif-font`, `droid-sans-font`:
  > 'Droid Sans', 'Helvetica Neue', Helvetica, sans-serif

* `serif-font`, `droid-serif-font`:
  > 'Droid Serif', Georgia, Times, serif

* `monospace-font`, `droid-mono-font`:
  > "Droid Sans Mono", 'Lucida Console', Monaco, monospace

So, you can use Droid in your own sass declarations right away:

    body
      font-size: 10pt
      +sans-serif-font

    code
      +droid-mono-font

## Links

  * [Source Repository](http://android.git.kernel.org/?p=platform/frameworks/base.git;a=tree;f=data/fonts;hb=HEAD)
  * [Ascender's Info Site](http://www.droidfonts.com/)

The fonts are copyright (c) 2005-2008, [The Android Open Source Project](http://source.android.com/) and licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).