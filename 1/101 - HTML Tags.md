# 1.0.1 - HTML Tags

HTML files are generally built out of HTML *elements*, also known as *tags*. An HTML element/tag looks like this:

    <p>Hello World</p>

This is a paragraph element, denoted by an opening tag (`<p>`) and a closing tag (`</p>`). The contents of the tag is the text 'Hello World'. The browser uses the tag to know how to display that element. 

Websites are built out of such elements and we will become used to them. Some common tags are:

    <span>A span - the 'simplest' element.</span>
    <div>A div - like a span, but starts a new line.</div>
    <p>A paragraph tag - similar to a div, but has some space around it.</p>
    <h1>A large header.</h1>
    <h6>A small header.</h6>

Paste the above list of tags into your index.html and inspect the result in Chrome. You can see the browser renders the content in different ways. 

Tags can also be nested. For example we might have the following:

    <div>
      <h1> Header </h1>
      <p> First paragraph </p>
      <p> <span>Second</span> <span>paragraph</span> </p>
    </div>

In this case the `<div>` element has an `<h1>` and two `<p>`s inside it; the second `<p>` has two `<span>`s inside it. Try the above in your own index.html.

## Exercises

So far we have learned about a few HTML tags, such as `<p>, <div>, <span>, <h1>, <h6>`. 

Use a few of them in an HTML file of your own, and create the following result: https://jsfiddle.net/sellarafaeli/a6764bqa/4/

1. Make sure you are able to create the same result in your own HTML file. 

2. Note the difference in the result between different tags.