<a href="https://freesewing.org"><img src="http://docs.freesewing.org/img/logo-black.svg" align="right" width=200 /></a>
# Freesewing stand-alone demo

This is a stand-alone version of [the freesewing demo](http://docs.freesewing.org/demo).

## Why a stand-alone demo?
The _real_ demo is part of the documentation, but that is a Jekyll-based site.
Which means that running your own instance is going to require some work.

If you want your own demo without the hassle, you can simply clone this into a web-accessible directory.

## Configuration

You should only configure the `api` value in the demo.js. Default is:

```
var api = 'https://api.freesewing.org';
```

You should change that to your own freesewing instance. **Note**: No trailing slash
