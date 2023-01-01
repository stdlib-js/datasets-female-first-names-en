<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Female First Names

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> A [list][@ward:2002a] of common female first names in English speaking countries.



<section class="usage">

## Usage

To use in Observable,

```javascript
names = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/datasets-female-first-names-en@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var names = require( 'path/to/vendor/umd/datasets-female-first-names-en/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/datasets-female-first-names-en@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.names;
})();
</script>
```

#### names()

Returns a [list][@ward:2002a] of common female first names (also known as [given][given-name] or personal names) in English speaking countries.

```javascript
var data = names();
/* returns
    [
        'Aaren',
        'Aarika',
        'Abagael',
        'Abagail',
        'Abbe',
        'Abbey',
        'Abbi',
        'Abbie',
        'Abby',
        ...
    ]
*/
```

</section>

<!-- /.usage -->

<section class="examples">

<!-- TODO: more creative example. -->

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-floor@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/random-base-randu@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/datasets-female-first-names-en@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var data = names();
var len = data.length;
var idx;
var i;

// Select random names from the list...
for ( i = 0; i < 100; i++ ) {
    idx = floor( randu()*len );
    console.log( data[ idx ] );
}

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->



* * *

<section class="references">

## References

-   Ward, Grady. 2002. "Moby Word II." <http://www.gutenberg.org/files/3201/3201.txt>.

</section>

<!-- /.references -->

<!-- <license> -->

## License

The data files (databases) are licensed under an [Open Data Commons Public Domain Dedication & License 1.0][pddl-1.0] and their contents are licensed under [Creative Commons Zero v1.0 Universal][cc0]. The software is licensed under [Apache License, Version 2.0][apache-license].

<!-- </license> -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/datasets/male-first-names-en`][@stdlib/datasets/male-first-names-en]</span><span class="delimiter">: </span><span class="description">A list of common male first names in English speaking countries.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/datasets-female-first-names-en.svg
[npm-url]: https://npmjs.org/package/@stdlib/datasets-female-first-names-en

[test-image]: https://github.com/stdlib-js/datasets-female-first-names-en/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/datasets-female-first-names-en/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/datasets-female-first-names-en/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/datasets-female-first-names-en?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/datasets-female-first-names-en.svg
[dependencies-url]: https://david-dm.org/stdlib-js/datasets-female-first-names-en/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/datasets-female-first-names-en/tree/deno
[umd-url]: https://github.com/stdlib-js/datasets-female-first-names-en/tree/umd
[esm-url]: https://github.com/stdlib-js/datasets-female-first-names-en/tree/esm
[branches-url]: https://github.com/stdlib-js/datasets-female-first-names-en/blob/main/branches.md

[pddl-1.0]: http://opendatacommons.org/licenses/pddl/1.0/

[cc0]: https://creativecommons.org/publicdomain/zero/1.0

[apache-license]: https://www.apache.org/licenses/LICENSE-2.0

[given-name]: https://en.wikipedia.org/wiki/Given_name

[@ward:2002a]: http://www.gutenberg.org/files/3201/3201.txt

<!-- <related-links> -->

[@stdlib/datasets/male-first-names-en]: https://github.com/stdlib-js/datasets-male-first-names-en/tree/umd

<!-- </related-links> -->

</section>

<!-- /.links -->
