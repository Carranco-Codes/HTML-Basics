# HTML Basics | Adding Text to HTML

## Why is learning how to implement text important?
The text on a website is probably the most essential part of any website, and it’s often the most overlooked feature. In my experience, one of the biggest mistakes I encounter is developers not implementing font correctly. I mean, in a way, I get it. In the world of web development, we spend so much time trying to build things. We want to build animations, pages, forms, and all sorts of components! However, correctly implementing text on a website can be the difference between having a successful site… and a site that no one will ever see.

## <title>Title Tag</title>
The first text we are going over is the Title. We will talk more about the head element in the SEO portion of this series, but the Title element is the first part of the text on every HTML page.  Imagine the title similar to the chapter of a book. Chapter names are concise and informative.  The `<title>` tag goes in the `<head>` portion of the website, and because it is located in the head, this is metadata that gets sent to browsers. Though there  isn’t a limit to how many characters a title should contain, if you keep your title tag under 60 characters, it will appear correctly in most browsers.

![indesign-59 characters](https://github.com/Carranco-Codes/HTML-Basics/assets/10298176/87817e56-8733-4a5b-9a13-14eae0d310bb)

## <p>Paragraph Tag</p>
The most basic way to add text to a website is to use the paragraph tag(`<p>`). To use a paragraph tag wrap the `<p>` tag around the text you want to structure as a paragraph.

### Code Sample
```
<p>This is a paragraph<p>
```

### Code Sample - Result
This is a paragraph

## Breaking up text
There are two ways to break up text: 

1) You can create multiple `<p>` tags

### Code Sample
```
<p>This is a paragraph</p>
<p>This is a second paragraph</p>
```

### Code Sample - Result
<p>This is a paragraph</p>
<p>This is a second paragraph</p>


### Second Way to break up text
2) Add a breaking tag `<br>` to break up text

### Code Sample
```
<p>This is a paragraph<br>
This is a second paragraph</p>
```

### Code Sample - Result
<p>This is a paragraph<br>
This is a second paragraph</p>

The usage of `<p>` or `<br>` depends on what you are trying to acheive. If you need a new paragraph then use the `<p>` tag. If you simply want to move text to a new line or add a space then use the `<br>` tag.

## Rules for headings
1. Each heading should have an opening and closing tag.
2. Use headings as titles on a specific section of your website.
3. Each HTML page should have one `<h1>` tag.
4. Each heading should be used consistently throughout your website.

`<h1>` tags should give information to the user about what the page is about. `<h2>` tags should give more information about major information about website. From there `<h3>` to `<h6>` tags are a little bit more flexible, but they should be used consistently throughout your website.

## Make Lists in HTML
The two most common lists are ordered lists (`<ol>`) and unordered list (`<ul>`). Ordered lists make bulleted lists in numerical format. To make an ordered list you wrap your entire list inside the `<ol>` element. Each list item is created by writing `1. `2

### Code Sample - Ordered List
```
<ol>
    <li>First List Item</li>
    <li>Second List Item</li>
    <li>Third List Item</li>
</ol>
```

### Result - Ordered List
1. First List Item
2. Second List Item
3. Third List Item

### Code Sample - Unordered List
```
<ul>
    <li>First List Item</li>
    <li>Second List Item</li>
    <li>Third List Item</li>
</ul>
```

### Reult - Unordered List
<ul>
    <li>First List Item</li>
    <li>Second List Item</li>
    <li>Third List Item</li>
</ul>

### Emphasize/Italicize text
To emphasize text on a webpage using HTML wrap the word(s) around the `<em>` tag. You may come across the `<i>` tag that will also italicize text, but this was the old way on how to italicize text. The `<em>` tag was created to replace the `<i>` tag because `<em>` gives more the impression of structure where `<i>` gives more the impression of styling.

### Code Sample - Emphasize Text

```
<p>I <em>want</em> to emphasize one word.</p>

<p>I <em>want to emphasize</em> multiple 
words.</p>
```

### Result - Emphasize Text

<p>I <em>want</em> to emphasize one word.</p>
     
<p>I <em>want to emphasize</em> multiple 
words.</p>


## Strong/Bold text
To bold text on a webpage using HTML wrap the word(s) around the `<strong>` tag. You may come across the `<b>` tag that will also bold text, but this was the old way on how to bold text. Like the `<em>` tag, `<strong>` was created to replace the `<b>` tag because `<strong>` gives more the impression of structure where `<b>` gives more the impression of styling.


### Code Sample - Bold text
```
<p>I <strong>want</strong> to bold one word.</p>

<p>I <strong>want to bold</strong> multiple 
words.</p>
```

### Result - Bold text
<p>I <strong>want</strong> to bold one word.</p>

<p>I <strong>want to bold</strong> multiple 
words.</p>

## Resources

### YouTube
* [Add Text to HTML Video](https://youtu.be/_18LiXiiU6A)

### GitHub
* [HTML Basics](https://github.com/Carranco-Codes/HTML-Basics)
* [Adding Text Repository](https://github.com/Carranco-Codes/HTML-Basics/tree/adding-text-to-html)
* [Front End Development Roadmap](https://github.com/Carranco-Codes/Front-End-Development-Roadmap)

### W3Schools
* [Headings](https://www.w3schools.com/html/html_headings.asp)
* [HTML Lists](https://www.w3schools.com/html/html_lists.asp)
* [Emphasize Text](https://www.w3schools.com/tags/tag_em.asp)
* [Strong Tag](https://www.w3schools.com/tags/tag_strong.asp)
