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

- [![https://gyazo.com/86ccd556baa2dff1659d295734eaf8c9](https://i.gyazo.com/86ccd556baa2dff1659d295734eaf8c9.png)](https://gyazo.com/86ccd556baa2dff1659d295734eaf8c9)

# See also

- [Support RTL for amp-story · Issue #11647 · ampproject/amphtml](https://github.com/ampproject/amphtml/issues/11647)
