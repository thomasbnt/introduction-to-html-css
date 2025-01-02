# Introduction to learn HTML/CSS

This repository is a tutorial for learning HTML/CSS with a example in `src` (source) folder.

## Table of Contents

- [How to create a basic HTML page](#how-to-create-a-basic-html-page)
- [HTML](#html)
- [CSS](#css)
- [Basics HTML page](#basics-html-page)
- [Example](#example)


## How to create a basic HTML page

To create a basic HTML page, you need to create a file with the `.html` extension. You can use any text editor to create this file. For example, you can use Visual Studio Code, Sublime Text, Atom, Notepad++, etc. Don't forget to save your file with the `.html` extension.

Here is a basic HTML page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

That's it! You have created a basic HTML page with a title and a heading.

> [!NOTE]
> Don't forget to add the `<!DOCTYPE html>` declaration at the beginning of your HTML file. This declaration is used to tell the browser that the document is an HTML5 document.
> Also, don't forget to add the `<html>`, `<head>`, and `<body>` tags. The `<html>` tag is used to define an HTML document. The `<head>` tag is used to define the head of the document. The `<body>` tag is used to define the body of the document.

You can see the preview of your HTML page by opening it in a web browser.

## HTML

### Introduction to HTML

HTML stands for Hyper Text Markup Language. It is used to design web pages using markup language. HTML is the combination of Hypertext and Markup language. Hypertext defines the link between the web pages. A markup language is used to define the text document within tag which defines the structure of web pages.

### HTML Tags

HTML tags are composed of three things: an opening tag, content and ending tag. Some tags are unclosed tags. For example, the `<img>` tag.
Other tags are closed tags. For example, the `<p>` tag, for example : 

```html
<p>This is a paragraph</p>
```

```html
<img src="image.jpg" alt="image">
```

> [!NOTE]
> The `<img>` tag is an unclosed tag. It doesn't have an ending tag.
> Also, for accessibility, it is important to add the `alt` attribute to the `<img>` tag.

### HTML Attributes

HTML attributes provide additional information about HTML elements. Attributes are always specified in the start tag. Attributes usually come in name/value pairs like: name="value".

```html
<a href="https://www.google.com">This is a link</a>
```

### HTML Headings

HTML headings are defined with the `<h1>` to `<h6>` tags. `<h1>` defines the most important heading. `<h6>` defines the least important heading.

> [!NOTE]
> Headings are important for SEO (Search Engine Optimization), so it is a good idea to use them properly to the h1 to h6 tags. Don't avoid using them and skip a level.

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6 and the last</h6>
```

### Accessibility in HTML

Accessibility is the practice of making your websites usable by as many people as possible. We traditionally think of this as being about people with disabilities, but the practice of making sites accessible also benefits other groups such as those using mobile devices, or those with slow network connections.
Don't hesitate to use `section`, `article`, `nav`, `header`, `footer` tags to structure your HTML page.


## Basics HTML page

In this section, we will create a basic HTML page with the following structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <header>
        <h1>My website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <section>
        <article>
            <h2>Article 1</h2>
            <p>This is the content of the article 1</p>
        </article>
        <article>
            <h2>Article 2</h2>
            <p>This is the content of the article 2</p>
        </article>
    </section>
    <footer>
        <p>&copy; 2021 My website</p>
    </footer>
</body>
</html>
```

We have created a basic HTML page with a header, a navigation bar, two articles and a footer without CSS for the moment.

## CSS

