Responsible Images
==================

**Simple & minimal recipes of creating responsible images. Must have in Responsive Web Design and modern HTML5 websites.**

HOW-TO
------

Insert this code to your CSS file

```css
img {
    max-width: 100%;
    height: auto;
}
```

Thats all :)


Doing this manually...
----------------------

You can also apply styles for every img tag manually like

```html
<img src="img/myimage.png" alt="alternate text" style="max-width:100%;height:auto;">
```

\<picture\> element
-----------------

In the near future we will propably use \<picture\> element often.

> The picture element is a markup pattern that allows developers to declare multiple sources for an image. By using media queries, it gives developers control as to when and if those images are presented to the user.


More info

* [Responsive Images Community Group](http://responsiveimages.org)
* [HTML Documentation](http://www.w3.org/html/wg/drafts/html/master/embedded-content.html#the-picture-element)
* [Picturefill project](http://scottjehl.github.io/picturefill)
* [Images in Markup — Web Fundamentals (Google)](https://developers.google.com/web/fundamentals/media/images/images-in-markup)

Already Picturefill 2.2.0-beta provide backwards compatibility for browsers that do not support the <picture> element.


List of examples
----------------

* [minimal](https://github.com/lszeremeta/responsible-images/tree/master/minimal) - minimal example \[[DEMO](https://lszeremeta.github.io/responsible-images/minimal)\]
* [rubal-example](https://github.com/lszeremeta/responsible-images/tree/master/rubal-example) - real life example \[[DEMO](https://lszeremeta.github.io/responsible-images/rubal-example)\]
* [picturefill-minimal](https://github.com/lszeremeta/responsible-images/tree/master/picturefill-minimal) - minimal example using Picturefill project \[[DEMO](https://lszeremeta.github.io/responsible-images/picturefill-minimal)\]
* [rubal-picturefill-example](https://github.com/lszeremeta/responsible-images/tree/master/rubal-picturefill-example) - real life example using Picturefill project \[[DEMO](https://lszeremeta.github.io/responsible-images/rubal-picturefill-example)\]


Łukasz Szeremeta 2014
