# Image ratio
by Tibor Sándor
Included Sass, css and default example files.
## Default ratios
- 1:1
- 3:2 (and automatic 2:3)
- 4:3 (and automatic 3:4)
- 16:9 (and automatic 9:16)
If you need other ratios, then add this line end of the sass file, and compile new css:
```sh
@include img-ratio(2, 1);
```
This is the result of the above example:
- 2:1
- 1:2
## Use
Include css file in head
```sh
<link rel="stylesheet" type="text/css" href="image-ratio.css">
```
and use imd-ratio class
```sh
<div class="img-ratio-2-1">
    <img src="http://placehold.it/350x150">
</div>
```
**Free Software, Hell Yeah!**
## License
MIT
