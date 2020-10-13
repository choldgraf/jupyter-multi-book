# Jupyter Multi Book

A demonstration of embedding Jupyter Books and RISE slideshows into a Sphinx website. Each of the pages above **embeds** book content via an `<iframe>`. For example, with code like this:

````html
```{raw} html
<iframe class="book" src="internal-book" />
```
````

It uses [this `Makefile` to build the site](https://github.com/choldgraf/jupyter-multi-book/blob/main/Makefile) and [this `custom.css` file to control the layout](https://github.com/choldgraf/jupyter-multi-book/blob/main/_static/custom.css). It uses the [PyData Sphinx Theme](https://pydata-sphinx-theme.readthedocs.io/) as the base theme.

Click the links above to see how things look.

```{toctree}
book-internal
book-external
rise
```
