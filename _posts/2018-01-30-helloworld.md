---
layout: default
title: testMathJax
category: BuildLog
usemathjax: true
---
### Hello World
Testing MathJax $$\mathrm{i}\mathcal{H}|\psi\rangle$$.

$$x_1^2=\alpha$$

```html
<!-- Add in _layouts/default.html, before {{ content }} -->
\{% if page.usemathjax %\}
<script type="text/javascript"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
\{% endif %\}
```