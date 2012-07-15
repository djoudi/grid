##grid##

Inspired and based on [960 Grid System](http://960.gs) by [Nathan Smith](https://github.com/nathansmith) and [Twitter Bootstrap](http://twitter.github.com/bootstrap) by [Mark Otto](https://github.com/markdotto) & [Jacob Thornton](https://github.com/fat). Grid is just a compilation of their great work for my small needs.

###files###

There are only four files. Two of them are minified and more convenient for live website. And there are two files for workaround. grid.css (grid.min.css) file contains reset and 12-columns layout. styles.css (styles.min.css) file includes basic typography and is intended for other cool stuff.

So, Grid is required only 2 files in the `<head>` of the page:
```html
<link rel="stylesheet" href="css/grid.min.css">
<link rel="stylesheet" href="css/styles.min.css">
```

###layout###

If you are familiar with 960 Grid System or Twitter Bootstrap, there is nothing to say more, other than the Grid's classes are differ just by their names. E.g.:

* **960 Grid System**: container_12 - grid_N - prefix_N - suffix_N
* **Twitter Bootstrap**: container - row - spanN - offsetN
* **Grid**: grid - colN - prefN - sufN

###example###

```html
<div class="grid">
	<div class="col12">
		<div class="col4 first">
			...
		</div>
		<div class="col3 suf1">
			...
		</div>
		<div class="col4 last">
			<div class="col1 pref1 first">
				...
			</div>
			<div class="col2 last">
				<div class="col2 full">
					...
				</div>
			</div>
		</div>
	</div>
</div>
```
