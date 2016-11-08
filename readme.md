## get-files
[![Dependency Status][david-dm-image]][david-dm-url] [![Dev Dependency Status][david-dm-dev-image]][david-dm-dev-url] [![NSP Status][nsp-image]][nsp-url]

directory files helper

## setup
```bash
npm install dan-nl/get-files
```

## use
see [express-http-skeleton][skeleton-url] for an example of use in an application context.

```javascript
var getFiles = require( 'get-files' );
var files = getFiles( __dirname );
```

## license
[MIT License][mit-license]

[david-dm-image]: https://david-dm.org/dan-nl/get-files.svg
[david-dm-url]: https://david-dm.org/dan-nl/get-files
[david-dm-dev-image]: https://david-dm.org/dan-nl/get-files/dev-status.svg
[david-dm-dev-url]: https://david-dm.org/dan-nl/get-files?type=dev
[generator-url]: http://expressjs.com/en/starter/generator.html
[mit-license]: https://raw.githubusercontent.com/dan-nl/get-files/master/license.txt
[nsp-image]: https://nodesecurity.io/orgs/githubdan-nl/projects/2b2775c2-124c-4ea8-b3fd-5964d5b834a1/badge
[nsp-url]: https://nodesecurity.io/orgs/githubdan-nl/projects/2b2775c2-124c-4ea8-b3fd-5964d5b834a1
[skeleton-url]: https://github.com/dan-nl/express-http-skeleton/blob/master/app/middleware/default/index.js
