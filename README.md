# Webpage

Repo for my personal website and blog. 

This website uses [**Beautiful Jekyll**](https://github.com/daattali/beautiful-jekyll) which is built on top of [Jekyll](http://jekyllrb.com/). Jekyll lets you create blog posts from markdown files. 

## Mathjax usage
Add these lines to `head.html`

```html
 <!-- config for equation numbering -->
 <script type="text/x-mathjax-config">
MathJax.Hub.Config({
  TeX: { equationNumbers: { autoNumber: "AMS" } }
});
</script>
  <!-- Script for MathJax-->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
```

