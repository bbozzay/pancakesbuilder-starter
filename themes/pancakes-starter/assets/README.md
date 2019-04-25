Add to document `<head>`
```
<script>document.getElementsByTagName("html")[0].className += " js";</script>
```

## Breakpoints

```
@include breakpoint(md) {
    /* your code here */
}

xs: 30rem,   // ~480px
sm: 37.5rem, // ~600px
md: 64rem,   // ~1024px
lg: 80rem,   // ~1280px
xl: 90rem    // ~1440px
```

Spacing

```
margin-top--
margin-bottom--
padding-top--
padding-bottom--

xxxxs
xxxs
xxs
xs
sm
md
lg
xl
xxl
xxxl
xxxxl
```

Text

```
truncate // truncate text if it exceeds its parent

text--center

text--replace // replace text with img
```

Articles
Add `text-component__block` to div surrounding the markdown content to enable outset images.

Icons
Add `.icon-text` to the paragraph, then `.icon` to the `<svg>` or `<i>` so that the icon is the same size as the text and has the same line-height.

Icon sizes:
```
icon-xxs //12px;
icon-xs  //16px;
icon-sm  //24px;
icon-md  //32px;
icon-lg  //48px;
icon-xl  //64px;
icon-xxl //128px;
```