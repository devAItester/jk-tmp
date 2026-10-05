---
title: Priority
layout: default
---
# {{ page.title }}
---
layout: default
title: Priority
---
```css
/* ========================================
   Base
   ======================================== */

*,
*::before,
*::after {
  box-sizing: border-box;
}

html {
  font-family:
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    "Noto Sans",
    Helvetica,
    Arial,
    sans-serif;

  font-size: 14px;
  line-height: 1.5;
}

body {
  margin: 0;
  color: #1f2328;
  background: #ffffff;
}


/* ========================================
   Page layout
   ======================================== */

body > nav,
body > main {
  inline-size: min(100% - 2rem, 70rem);
  margin-inline: auto;
}

body > nav {
  position: sticky;
  inset-block-start: 0;

  padding-block: 1rem;

  font-size: 1.125rem;

  background: #ffffff;
}

body > main {
  padding-block: 2rem 3rem;
}


/* ========================================
   Typography
   ======================================== */

a {
  color: #0969da;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  margin-block: 1.5rem 1rem;
  font-weight: 600;
  line-height: 1.25;
}

h1 {
  font-size: 2rem;
}

h2 {
  font-size: 1.5rem;
}

h3 {
  font-size: 1.25rem;
}

h4 {
  font-size: 1rem;
}

h5 {
  font-size: 0.875rem;
}

h6 {
  font-size: 0.75rem;
  color: #59636e;
}

```
