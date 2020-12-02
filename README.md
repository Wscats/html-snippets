# Using

Just enter the tag name of `html`, and the complete code snippet of the tag will be automatically completed.

```html
div -> <div></div>
p   -> <p></p>
doc -> <!DOCTYPE html>
a   -> <a href=""></a>
```

|Prefix|Snippets|
|-|-|
| doctype |`<!DOCTYPE>$1`|
| a |`<a href="$1">$2</a>$3`|
| abbr |`<abbr title="$1">$2</abbr>$3`|
| address |`<address>$1</address>`|
| area |`<area shape="$1" coords="$2" href="$3" alt="$4">$5`|
| article |`<article>$1</article>`|
| aside |`<aside>$1</aside>$2`|
| audio |`<audio controls>$1</audio>`|
| b |`<b>$1</b>$2`|
| base |`<base href="$1" target="$2">$3`|
| bdi |`<bdi>$1</bdi>$2`|
| bdo |`<bdo dir="$1">$2</bdo>`|
| big |`<big>$1</big>$2`|
| blockquote |`<blockquote cite="$2">$1</blockquote>`|
| body |`<body>$1</body>`|
| br |`<br>`|
| button |`<button type="$1">$2</button>$3`|
| canvas |`<canvas id="$1">$2</canvas>$3`|
| caption |`<caption>$1</caption>$2`|
| cite |`<cite>$1</cite>$2`|
| code |`<code>$1</code>$2`|
| col |`<col>$2`|
| colgroup |`<colgroup>$1</colgroup>`|
| command |`<command>$1</command>$2`|
| datalist |`<datalist>$1</datalist>`|
| dd |`<dd>$1</dd>$2`|
| del |`<del>$1</del>$2`|
| details |`<details>$1</details>`|
| dialog |`<dialog>$1</dialog>$2`|
| dfn |`<dfn>$1</dfn>$2`|
| div |`<div>$1</div>`|
| dl |`<dl>$1</dl>`|
| dt |`<dt>$1</dt>$2`|
| em |`<em>$1</em>$2`|
| embed |`<embed src="$1">$2`|
| fieldset |`<fieldset>$1</fieldset>`|
| figcaption |`<figcaption>$1</figcaption>$2`|
| figure |`<figure>$1</figure>`|
| footer |`<footer>$1</footer>`|
| form |`<form>$1</form>`|
| h1 |`<h1>$1</h1>$2`|
| h2 |`<h2>$1</h2>$2`|
| h3 |`<h3>$1</h3>$2`|
| h4 |`<h4>$1</h4>$2`|
| h5 |`<h5>$1</h5>$2`|
| h6 |`<h6>$1</h6>$2`|
| head |`<head>$1</head>`|
| header |`<header>$1</header>`|
| hgroup |`<hgroup>$1</hgroup>`|
| hr |`<hr>`|
| html |`<html>$1</html>`|
| html5 |`<!DOCTYPE html><html lang="$1en"><head><title>$2</title><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1"><link href="$3css/style.css" rel="stylesheet"></head><body>$4</body></html>`|
| i |`<i>$1</i>$2`|
| iframe |`<iframe src="$1">$2</iframe>$3`|
| img |`<img src="$1" alt="$2">$3`|
| input |`<input type="$1" name="$2" value="$3">$4`|
| ins |`<ins>$1</ins>$2`|
| keygen |`<keygen name="$1">$2`|
| kbd |`<kbd>$1</kbd>$2`|
| label |`<label for="$1">$2</label>$3`|
| legend |`<legend>$1</legend>$2`|
| li |`<li>$1</li>$2`|
| link |`<link rel="$1" type="$2" href="$3">$4`|
| main |`<main>$1</main>`|
| map |`<map name="$1">$2</map>`|
| mark |`<mark>$1</mark>$2`|
| menu |`<menu>$1</menu>`|
| menuitem |`<menuitem>$1</menuitem>$2`|
| meta |`<meta name="$1" content="$2">$3`|
| meter |`<meter value="$1">$2</meter>$3`|
| nav |`<nav>$1</nav>`|
| noscript |`<noscript>$1</noscript>`|
| object |`<object width="$1" height="$2" data="$3">$4</object>$5`|
| ol |`<ol>$1</ol>`|
| optgroup |`<optgroup>$1</optgroup>`|
| option |`<option value="$1">$2</option>$3`|
| output |`<output name="$1" for="$2">$3</output>$4`|
| p |`<p>$1</p>$2`|
| param |`<param name="$1" value="$2">$3`|
| pre |`<pre>$1</pre>`|
| progress |`<progress value="$1" max="$2">$3</progress>$4`|
| q |`<q>$1</q>$2`|
| rp |`<rp>$1</rp>$2`|
| rt |`<rt>$1</rt>$2`|
| ruby |`<ruby>$1</ruby>`|
| s |`<s>$1</s>$2`|
| samp |`<samp>$1</samp>$2`|
| script |`<script>$1</script>`|
| section |`<section>$1</section>`|
| select |`<select>$1</select>`|
| small |`<small>$1</small>$2`|
| source |`<source src="$1" type="$2">$3`|
| span |`<span>$1</span>$2`|
| strong |`<strong>$1</strong>$2`|
| style |`<style>$1</style>`|
| sub |`<sub>$1</sub>$2`|
| sup |`<sup>$1</sup>$2`|
| summary |`<summary>$1</summary>$2`|
| table |`<table>$1</table>`|
| tbody |`<tbody>$1</tbody>`|
| td |`<td>$1</td>$2`|
| textarea |`<textarea rows="$1" cols="$2">$3</textarea>$4`|
| tfoot |`<tfoot>$1</tfoot>`|
| thead |`<thead>$1</thead>`|
| th |`<th>$1</th>$2`|
| time |`<time datetime="$1">$2</time>$3`|
| title |`<title>$1</title>$2`|
| tr |`<tr>$1</tr>$2`|
| track |`<track src="$1" kind="$2" srclang="$3" label="$4">$5`|
| u |`<u>$1</u>$2`|
| ul |`<ul>$1</ul>`|
| var |`<var>$1</var>$2`|
| video |`<video width="$1" height="$2" controls>$3</video>`|


## License

[HTML Snippets](https://marketplace.visualstudio.com/items?itemName=Wscats.html) is released under the [MIT](http://opensource.org/licenses/MIT).

