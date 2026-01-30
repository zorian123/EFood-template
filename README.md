# 🍔 EFood template
- [👀 View the result](https://zorian123.github.io/EFood-template/)
- [🔗 Template](https://www.figma.com/design/FRgRLcPR6vraPfksLKFNNi/eFoodWebdesign) - if it doesn't work, download the [`template.fig`](template.fig) file

![image](https://github.com/user-attachments/assets/9867c70a-131a-4e7a-997b-79026c6ed289)

## Features
- ✅ a11y
  - convenient keyboard navigation
  - hidden content for **screen readers**: [`@mixin hidden`](styles/_mixins.scss#L58)
  - **adaptive layout** for mobile: `grid/flex`, [`clamp() fluid function`](styles/_mixins.scss#L2) and animated burger menu
  - Modern WOFF2 fonts for fast loading

  - **semantic tags**: `<article>`, `<time>`, `<blockquote>`, `<address>`
  - semantic attributes: `mailto: / tel:` for &lt;a&gt;, filled `alt`, `datetime=""`, `type="button"`
  - `width/height` attributes so that &lt;img&gt;s take up space before loading

  - expanded clickable area
  - reduced motion animation for people who prefer it
  - animated color SVG icons - see [_normalize.scss](styles/_normalize.scss#L29)
  - improved :hover for mobiles - using [`@media(hover: hover)`](styles/_media.scss#L46)

- ✅ Clear project structure
- ✅ Good commit history
- ✅ Explanatory comments in the code

- ✅ SCSS
- ✅ [Scroll-driven animations](https://www.youtube.com/watch?v=5noL_qFobm0&list=PLNYkxOF6rcICM3ttukz9x5LCNOHfWBVnn&index=1)
- ✅ Compatibility Chrome >115

- ❌ Dark theme
- ❌ JavaScript
