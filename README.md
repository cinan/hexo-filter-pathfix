# hexo-filter-pathfix

using absolute path for assets in posts

[![build status](https://secure.travis-ci.org/wayou/hexo-filter-pathfix.svg)](http://travis-ci.org/wayou/hexo-filter-pathfix)
[![dependency status](https://david-dm.org/wayou/hexo-filter-pathfix.svg)](https://david-dm.org/wayou/hexo-filter-pathfix)

## Installation

```
npm install --save hexo-filter-pathfix --save
```

## Usage
- install package
- enable `post_asset_folder` in your hexo config file `_config.yml`
- reference assets in relative path in your post

## Example

```markdown
![this is the cover](cover.jpg)
```
the above will produce:
```html
<img title="this is the cover" src="/2015/01/18/post-title/cover.jpg">
```

## Credits
[wayou](https://github.com/wayou/)

## License

MIT
