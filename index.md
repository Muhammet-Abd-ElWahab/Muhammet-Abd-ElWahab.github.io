---
layout: default
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .top-bar {
            background-color: lightblue;
            padding: 20px;
            display: flex;
            align-items: center;
            border-bottom: 2px solid #000;
        }
        .top-bar img {
            height: 50px;
            margin-right: 20px;
        }
        .top-bar h1 {
            margin: 0;
        }
        .container {
            display: flex;
        }
        .sidebar {
            width: 25%;
            padding: 20px;
            border-right: 2px solid #000;
        }
        .content {
            width: 75%;
            padding: 20px;
        }
        .content, .sidebar {
            border: 2px solid #000;
            border-top: none;
            border-left: none;
        }
    </style>
</head>
<body>

<div class="top-bar">
    <img src="images/logo.png" alt="Image of fast.ai logo">
    <h1>Blog Title</h1>
</div>

<div class="container">
    <div class="sidebar">
        <h2>Information</h2>
        <p>Welcome to the sidebar. This is where you can put additional information.</p>
        <ul>
            <li><a href="#link1">Link 1</a></li>
            <li><a href="#link2">Link 2</a></li>
            <li><a href="#link3">Link 3</a></li>
        </ul>
    </div>

    <div class="content">
        <h2>Welcome</h2>
        <p>Hello and welcome to this blog. Edit the <code>index.md</code> file to change this content. All pages on the blog, including this one, use <a href="https://guides.github.com/features/mastering-markdown/">Markdown</a>. You can include images:</p>
        <img src="images/logo.png" alt="Image of fast.ai logo">

        <h2>This is a title</h2>
        <p>And you can include links, like this <a href="https://www.fast.ai">link to fast.ai</a>. Posts will appear after this file.</p>
    </div>
</div>

</body>
</html>




























Hello and welcome to this blog. Edit the `index.md` file to change this content. All pages on the blog, including this one, use [Markdown](https://guides.github.com/features/mastering-markdown/). You can include images:

![Image of fast.ai logo](images/logo.png)

## This is a title

And you can include links, like this [link to fast.ai](https://www.fast.ai). Posts will appear after this file. 
