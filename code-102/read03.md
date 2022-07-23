# Read: 03 - Structure web pages with HTML

## An introduction to wireframing

### What is a wireframe?

Wireframing is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product. This process focuses on how the designer or client wants the user to process information on a site, based on the user research already performed by the UX design team.

When designing for the screen you need to know where all the information is going to go in plain black and white diagrams before building anything with code—**whether that’s a developer coding it, or you the designer**.

> Wireframing is also a great way of getting to know how a user interacts with your interface, through the positioning of buttons and menus on the diagrams.

### Wireframe examples

![wireframe-ex1](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/versions/samuel-student-wireframe---x----972-715x---.png)

![wireframe-ex2](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/fitted-lowfi.jpg)

![wireframe-ex3](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/fitted-midfi.png)

![wireframe-ex4](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/inflection-lowfi.png)

![wireframe-ex5](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/fiscal.jpg)

![wireframe-ex6](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/sundayz-lowfi.jpg)

![wireframe-ex7](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/sundayz-midfi.jpg)

📓 **[what-is-a-wireframe](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/#what-is-a-wireframe)**

## HTML basics

HTML (**H**yper**t**ext **M**arkup **L**anguage) is the code that is used to structure a web page and its content. For example, content could be structured within a set of paragraphs, a list of bulleted points, or using images and data tables.

![HTML element](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

The main parts of our element are as follows:

1. **The opening tag**: This consists of the name of the element (in this case, p), wrapped in opening and closing **angle brackets**. This states where the element begins or starts to take effect — in this case where the paragraph begins.

2. **The closing tag**: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

3. **The content**: This is the content of the element, which in this case, is just text.

4. **The element**: The opening tag, the closing tag, and the content together comprise the element.

Elements can also have attributes that look like the following:

![attribute](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-attribute-small.png)

Attributes contain extra information about the element that you don't want to appear in the actual content. Here, `class` is the attribute name and `editor-note` is the attribute value. The `class` attribute allows you to give the element a non-unique identifier that can be used to target it (and any other elements with the same `class` value) with style information and other things.

An attribute should always have the following:

1. A space between it and the element name (or the previous attribute, if the element already has one or more attributes).

1. The attribute name followed by an equal sign.

1. The attribute value wrapped by opening and closing quotation marks.

> **_NOTE :_** Simple attribute values that don't contain ASCII whitespace (or any of the characters **" ' ` = < >** ) can remain unquoted, but it is recommended that you quote all attribute values, as it makes the code more consistent and understandable..

### Nesting elements

You can put elements inside other elements too — this is called nesting.

```html
<p>My cat is <strong>very</strong> grumpy.</p>
```

You do however need to make sure that your elements are properly nested. In the example above, we opened the `<p>` element first, then the `<strong>` element; therefore, we have to close the `<strong>` element first, then the `<p>` element.

### Empty elements

Some elements have no content and are called empty elements. Take the `<img>` element that we already have in our HTML page:

```html
<img src="images/firefox-icon.png" alt="My test image" />
```

This contains two attributes, but there is no closing `</img>` tag and no inner content. This is because an image element doesn't wrap content to affect it. Its purpose is to embed an image in the HTML page in the place it appears.

📓 **[HTML_basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)**

📓 **[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)**
