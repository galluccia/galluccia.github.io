---
title:  "Julia vs. Pandas"
categories: example
mathjax: true
---

DataFrame constructor in Julia

{% highlight julia %}

#!/Applications/Julia-1.1.app/Contents/Resources/julia/bin/julia
println("Hello word")

using DataFrames
df = DataFrame(
    A = 1:4,
    B = ["M", "F", "F", "M"]
)
println(df)

{% endhighlight %}


## MathJax

You can enable MathJax by setting `mathjax: true` on a page or globally in the `_config.yml`. Some examples:

[Euler's formula](https://en.wikipedia.org/wiki/Euler%27s_formula) relates the  complex exponential function to the trigonometric functions.

$$ e^{ix}=cos(x)+isin(x) $$

The [Euler-Lagrange](https://en.wikipedia.org/wiki/Lagrangian_mechanics) differential equation is the fundamental equation of calculus of variations.

$$ \frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac{\partial L}{\partial \dot{q}} \right ) = \frac{\partial L}{\partial q} $$

The [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) describes how the quantum state of a quantum system changes with time.

$$ i\hbar\frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2\mu}\nabla^2 + V(\mathbf{r},t)\right ] \Psi(\mathbf{r},t) $$

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

The `.large` wrapper can be used to increase the width of an image or iframe.

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

<div class="large" markdown="1">
![Swiss Alps](https://user-images.githubusercontent.com/4943215/55412536-edbba180-5567-11e9-9c70-6d33bca3f8ed.jpg)
</div>

[Swiss Alps](https://unsplash.com/photos/u0DmxB76uF4) by René Reichelt

## Embedded content

You can also embed a lot of stuff, for example from YouTube. To scale the video to full width use the `<div class="embed"></div>` wrapper around the iframe.

<div class="embed"><iframe src="https://www.youtube.com/embed/_C0A5zX-iqM" frameborder="0" allowfullscreen></iframe></div>
