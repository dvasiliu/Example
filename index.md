<script type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS_CHTML">
</script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true},
      jax: ["input/TeX","input/MathML","input/AsciiMath","output/CommonHTML"],
      extensions: ["tex2jax.js","mml2jax.js","asciimath2jax.js","MathMenu.js","MathZoom.js","AssistiveMML.js", "[Contrib]/a11y/accessibility-menu.js"],
      TeX: {
      extensions: ["AMSmath.js","AMSsymbols.js","noErrors.js","noUndefined.js"],
      equationNumbers: {
      autoNumber: "AMS"
      }
    }
  });
</script>

# Ttitle

## Welcome to a simple example of a Github webpage

You can use the [editor on GitHub](https://github.com/dvasiliu/Example/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Hello world!

<img src="Assets/IMG_2469.jpeg" width="400" height="600" alt="hi" class="inline"/>

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List
...

**Bold** and _Italic_ and `Code` text
```

## **Math Equations**
![Math](https://render.githubusercontent.com/render/math?math=%5Csqrt%7B%5Csin(x%2B1)%2B3%7D)

<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">

**Some Math**

![\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?\Large&space;\left(\frac{-b\pm\sqrt{b^2-4ac}}{2a}\right)^2) 



$$\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$

**The Cauchy-Schwarz Inequality**

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$


## Python Code

{% highlight Python %}
import numpy as np
x = np.sqrt(2)
{% endhighlight %}

Other pages: <a href="Ex3.html">Ex3</a>

Test all.

## Diagrams

<!-- mermaid.js -->
<script src="https://unpkg.com/mermaid@8.1.0/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

<div class="mermaid">
graph TD;
    A[A]-->B[B];
    A[A]-->C[C];
    B[B]-->D[D];
    C[C]-->D[D];
</div>


<div class="mermaid">
pie title Key elements in Product X
  "Calcium" : 42.96
  "Potassium" : 50.05
  "Magnesium" : 10.01
  "Iron" :  5
</div>

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


## TikZ

<link rel="stylesheet" type="text/css" href="http://tikzjax.com/v1/fonts.css">
<script src="http://tikzjax.com/v1/tikzjax.js"></script>

<script type="text/tikz">
  \begin{tikzpicture}
    \draw (0,0) circle (1in);
  \end{tikzpicture}
</script>

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dvasiliu/Example/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
