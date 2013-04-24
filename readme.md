#finale

Finale is a [WordPress](http://wordpress.org) child theme for [fin](https://github.com/ascottmccauley/fin).

##Features

All the same goodies as [fin](https://github.com/ascottmccauley/fin) with the added benefit of not fighting with its parent. 

* WordPress will look for all styles, scripts and images in finale first and then fallback to fin.

* If you use SCSS the app.scss, admin.scss, and editor-styles.scss will import from fin and output a single file instead of having browsers download 2 styles.

* If you want to use the benefits of [Foundation](http://foundation.zurb.com) without the styles added to fin, you can also set `$include-parent-classes: false` and use any mixins that you like.

* Woocommerce Ready - You can also toggle the woocommerce styles included in fin by setting `$include-woo-classes: true/false;`

MIT Open Source License
=======================

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.