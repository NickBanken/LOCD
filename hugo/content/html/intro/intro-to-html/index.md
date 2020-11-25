---
title: "Intro to HTML"
date: 2020-11-02T09:25:04+01:00
draft: false
---

# Intro to HTML

## Why use HTML

Computers and by extension web browsers are inherently dumb. We can't expect a computer to read a text document an make a distinction between titles, paragraphs, links, lists, etc.   

Let's put ourselves in the shoes of a computer and take a look at a document you most likely won't understand:

{{< addImage imageid="hebrew.png" alt="text in hebrew" >}}

Just like we can't give **meaning** to the text in the above example, computers can't give meaning to the data they get from the web. Therefore we use a **markup language** to add additional meaning to the text. On the web, the markup language we use is HTML or **hypertext markup language**.

{{< addImage imageid="hebrew-markup.png" alt="text in hebrew" >}}

By adding some `<tags>` to the document that describe the content, we have a better understanding of the meaning and structure of the text. The area of linguistics that is concerned with the meaning of text is called **semantics**.
When writing HTML it is important to use the correct HTML tags for your content. This is called writing semantic HTML, and it's importance can't be understated. 

## What is HTML?

HTML is not a programming language; it is a markup language that defines the structure and meaning of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on.  For example, take the following line of content:

```My cat is very grumpy```. 

If we wanted the line to stand by itself, we could specify that it is a paragraph by enclosing it in paragraph tags:

```<p>My cat is very grumpy</p>```

### Anatomy of an HTML element

Let's explore this paragraph element a bit further.

{{< addImage imageid="grumpy-cat-small.png" alt="html tag" >}}

The main parts of our element are as follows:

1. **The opening tag**: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
2. **The closing tag**: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
3. **The content**: This is the content of the element, which in this case, is just text.
4. **The element**: The opening tag, the closing tag and the content together comprise the element.

#### Nesting elements

HTML elements can be **nested** in other HTML elements. 
Let's continue with the HTML element from the previous example.

I would like to put emphasis on the word *grumpy*. To do this I will use the `<em>` element and wrap it around the word I want to emphasize. 

```<p>My cat is very <em>grumpy</em></p>```

In this example the `<em>` element is **nested** in the `<p>` element. 

> ! Important: When nesting html elements, make sure to close the nested element before closing the parent element

