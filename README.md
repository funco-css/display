![blank.css](http://imgh.us/blank-logo.svg)

# [blank.css](http://github.com/blank-css) ‣ display
blank.css display utilities for displaying content

## configure

Like all of blank.css, the display utilites are completely configurable using
custom media queries, like so:

```css
@custom-media --bb (min-width: 22rem);
@custom-media --sm (min-width: 29rem);
@custom-media --md (min-width: 36rem);
@custom-media --lg (min-width: 45rem);
@custom-media --gg (min-width: 54rem);
```

## install

`npm i -D blank-css-display`

## use

now you have these classes at your disposal, where

identifier | available
---------- | -----------
`{type}`   | `show` or `hide`
`{query}`  | `bb` or `sm` or `md` or `lg`

```css
.blank-u-{query}-{type}
```

for example, if I wanted to show an a hidden element starting at the `sm`
	query, I'd do this:

```html
<div class="blank-u-sm-show">My small item</div>
```

If I wanted the now shown element to hide again at the `lg` query, I'd do:
```html
<div class="blank-u-sm-show blank-u-lg-hide">My small item</div>
```

Mix and match in whichever way you choose.
