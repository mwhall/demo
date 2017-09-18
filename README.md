<a href="https://freesewing.org"><img src="https://freesewing.org/img/logo/logo-black.svg" align="right" width=200 /></a>
# Freesewing stand-alone demo

This is a stand-alone version of [the freesewing demo](https://demo.freesewing.org/).

## Why a stand-alone demo?
The online demo is part of the documentation, but that is a Jekyll-based site.
Which means that running your own instance is going to require some work.

If you want your own demo without the hassle, you can simply clone this into a web-accessible directory.

## Configuration

You should only configure the `api` value in the demo.js. Default is:

```
var api = 'https://core.freesewing.org';
```

You should change that to your own freesewing instance. **Note**: No trailing slash
