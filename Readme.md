# genoset-228
[![Build Status](https://travis-ci.org/calweb/genoset-228.png?branch=master)](https://travis-ci.org/calweb/genoset-228)

Use this module to help determine if [affected by sickle cell anemia](http://www.snpedia.com/index.php/Gs228).

## Information

<table>
<tr>
<td>Package</td><td>genoset-228</td>
</tr>
<tr>
<td>Description</td>
<td>Affected by sickle cell anemia</td>
</tr>
<tr>
<td>Node Version</td>
<td>~ 5.5</td>
</tr>
</table>

## Compatibility

This genoset is to be used with DNA-JSON. See [dna2json](https://github.com/genomejs/dna2json) for more information.

## Usage

```js
var hasSickleCell = require('genoset-228')
var dna = require('./dna.json')

console.log(hasSickleCell(dna))
// → `true` or `false`
```

## Contributions

This Project follows the StandardJS style guide.

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

To Contribute:

- Clone Repo
- `npm install`
- Write Code
- Write Test(s)
- Submit Pull Request

## License

_genoset-228_ is available under the [MIT](https://mths.be/mit) license.
