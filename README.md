# hexo-include

A [Hexo](https://github.com/hexojs/hexo) plugin for including the raw content of a text file into a post directly from its markdown. Easily insert pre-written HMTL, JS, or the contents of _any_ text file into the body of your post or page.

## Usage

Insert the following into the post's markdown where you want the contents of the external file inserted. All file paths are relative to your `source` directory.
```
{% include path/to/file.bar %}
```

## Install

Install with [npm](https://www.npmjs.com/) from the base directory of your Hexo site:

```
$ npm install --save hexo-include
```

## License

MIT (c) 2016 Robert Pirtle.
