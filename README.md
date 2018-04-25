# How to make Right-to-left in amp-story

1. Set `dir` attribute to the body.

```html
<body dir="rtl">
```

2. Flip horizontal the pager.

```css
      .next-container,.prev-container {
        transform: scale(-1, 1);
      }
```