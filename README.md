# IcarusX

![](https://img.shields.io/badge/version-5.0.0--rc.1-blue?style=for-the-badge)

A customized version of [icarus](https://github.com/ppoffice/hexo-theme-icarus) by oalieno.

- [Better code block](#better-code-block)
- [Admonition](#admonition)
- [Blurring readmore](#blurring-readmore)
- [Compact article meta](#compact-article-meta)
- [Lazy loading images](#lazy-loading-images)

## Better code block

~~~
```python run.py >3,6
import math

def main():
    print(f'test {math.factorial(5)}')

main()
```
~~~

`>3,6` means
* Line number starts with `3`
* Highlight line number 6

![](/screenshots/codeblock.png)

## Admonition

```
{% admonition abstract "abstract" %}
這是範例
{% endadmonition %}

{% admonition info "info" %}
這是範例
{% endadmonition %}

{% admonition tip "tip" %}
這是範例
{% endadmonition %}
```

![](/screenshots/admonition.png)

## Blurring readmore

If you do not set an excerpt, a blurring effect of readmore will be applied.

![](/screenshots/readmore.png)

## Compact article meta

More compact article meta, no more long long text.

![](/screenshots/meta.png)

## Lazy loading images

Using [lazysizes](https://github.com/aFarkas/lazysizes) on all images.
