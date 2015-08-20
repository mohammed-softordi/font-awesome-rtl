# font-awesome-rtl

A fork of [font-awesome-rtl](https://github.com/fisharebest/font-awesome-rtl) to add support for font-awesome from 3.2 up 4.4 and register font-awesome-rtl on bower

[Demo](https://fisharebest.github.io/font-awesome-rtl)

# How to use

1. Load font-awesome.css
2. Load font-awesome-rtl.css
3. Add `dir="rtl"` to a suitable parent, such as `<html dir="rtl">`

# What is supported

All features of the original font-awesome-rtl (https://github.com/fisharebest/font-awesome-rtl) and more...

## Reversible glyphs are reversed:

```html
<i class="icon icon-bullhorn"></i> points left-to-right
<i class="fa fa-star-half"></i> left half of a star
<div dir="rtl">
	<i class="icon icon-bullhorn"></i> points right-to-left
	<i class="fa fa-bullhorn"></i> right half of a star
</div>
```

## List icons appear in the correct place

```html
<ul class="icon-list-ul">
	<li><i class="icon-list-li">test</i>
	<li><i class="fa-list-li fa fa-spinner fa-spin"></i> Spins clockwise
</ul>
<div dir="rtl">
	<ul class="fa-list-ul">
		<li><i class="icon-list-li"></i> Check!
		<li><i class="fa-list-li fa fa-spinner fa-spin"></i> Spins anti-clockwise
	</ul>
</div>
```

## Start and end versions of all left and right arrows

```html
<i class="fa fa-chevron-right"></i> points left-to-right
<i class="icon icon-chevron-left"></i> points right-to-left
<i class="fa fa-chevron-right"></i> points left-to-right
<i class="icon icon-chevron-left"></i> points right-to-left
<div dir="rtl">
	<i class="fa fa-chevron-right"></i> points left-to-right
	<i class="icon icon-chevron-left"></i> points right-to-left
	<i class="fa fa-chevron-right"></i> points right-to-left
	<i class="icon icon-chevron-left"></i> points left-to-right
</div>
```
