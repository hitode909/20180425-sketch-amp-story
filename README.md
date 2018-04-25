# How to make Right-to-left in amp-story

1. Set `dir` attribute to the body.

```html
<body dir="rtl">
```

2. Flip the pager horizontal.

```css
.next-container,.prev-container {
  transform: scale(-1, 1);
}
```

# Known issues

[![https://gyazo.com/86ccd556baa2dff1659d295734eaf8c9](https://i.gyazo.com/86ccd556baa2dff1659d295734eaf8c9.png)](https://gyazo.com/86ccd556baa2dff1659d295734eaf8c9)