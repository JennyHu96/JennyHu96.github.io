---
layout: default
title: testMathJax
category: BuildLog
usemathjax: true
---
### Hello World
Testing MathJax $$\mathrm{i}\mathcal{H}|\psi\rangle$$.


$$\oint_\Sigma \mathbf{B}\cdot \mathrm{d}\mathbf{S} = 0$$

```html
<!-- Add in _layouts/default.html, before {{ content }}. With if page.usemathjax conditioned-->
<script type="text/javascript"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
```