# html-and-css
<pre>
<h1>This repo is used for understanding basics of html and css</h1><br>
In html and css we are not going to use all the functions in our project. <br>
Hence, In this repository we are going to learn and use some of thr most common and most used tags and function important for out projects.<br>

<h1>HTML</h1>
HTML is used to define the structure and content of web pages, making it the foundational language of the internet. It tells browsers how to display text, images, links, and other elements.

To start first we need to know how an html file is created-
    For creating an html file we simply have to create a new file with extension ".html".
    for example, i want to create a file with name "index", so for that i will open a new file name it as "index" with extension ".html" and save it - "index.html".
html has a fixed stucture without that we cannot run the file,since we use "vs code" for coding. vs code have a shortcut for getting the structure or we can also call it as the boiler plate code of html-
    simply type 
    "shift+! and enter"
    this will give us the boiler plate code
now you can use this code and do further development in it.
<h2>Important tags that we usually use -</h2>
1)h1 to h6 - these are heading tags used to show heading in this h1 is the biggest and h6 is the smallest tag
    for example- 
        <h1>see text size, here we used h1 tag</h1>
        <h2>see text size, here we used h2 tag</h2>
        <h3>see text size, here we used h3 tag</h3>
        <h4>see text size, here we used h4 tag</h4>
        <h5>see text size, here we used h5 tag</h5>
        <h6>see text size, here we used h6 tag</h6>
2)p tag - This tag is used to write long sentenses or used to write paragraphs.
    for example-
        <p>here we used paragraph tag,this is how a paragrph tag look, i am writing a paragraph in it.</p>
3)br tag - This tag is also called as break tag we use it to break a line or go to next line.
    for eg- in this line i placed a br tag <br>    see now you can see these words come on next line.
4)div tag - div is a rectangle which has no hight but full width. Height of main div tag is equal to total height of its childrens.
    for eg - see the file div.html its a perfect example of div tag.
5)id - id is an attribute in html it provides an unique identifier for an element.
In css we use id to target an element.
    for eg - see index.html file there we have used id to target in that file we used inline css.
6)class - class is also an attribute which we use to target an element like id.
The key difference is that class is like a category which we can assign to multiple elements and id is unique for each element.
    for eg - see index .html there we used class to target more than one element.
7)img tag - It is used to include or add images in html file. It have alt attribute in that we give info about image this is shown if the image is not shown properly by browser.
    for eg - see index .html there we used image tag to add image in html file.
8)a tag - It is used to link a page with our page.
    for eg - you can see "index.html" file. In the file we have link "link.html" file with "index.html" file by using "a tag".

<h1>CSS</h1>
CSS is used to style and visually enhance web pages, making them more attractive, responsive, and easier to maintain.<br>
To start first we need to know how an css file is created-
    For creating an css file we simply have to create a new file with extension ".css".
    For example, i want to create a file with name "style", so for that i will open a new file name it as "style" with extension ".css" and save it - "style.css".<br>
A css file cannot run independently like html file,we use css to make our website look nice and websites are made by html.
So we have to link our css file to the html file which we want to design.
Once you link the files you can do further development in them.

<h2>Important terms that we usually use in css -</h2>
1)linking - Understanding linking css with html
as mentioned above we cannot run css independently so for linking it steps-
    step 1-make html file in which you want to link the css file
    step 2-make the css file which you want to link with the html file
    step 3-In the html file under the head tag after title tag before closing head tag 
    write this - < link rel="stylesheet" href="name of the css file you want to link">
2)CSS boilerplate -
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html,body{
    width:100%;
    height: 100%;
}

Above is is often called a CSS boilerplate because it's a foundational set of styles that helps ensure consistency and predictability across different browsers.
- It solves common layout issues that developers face when starting a new project.
- * { margin: 0; padding: 0; box-sizing: border-box; }
- margin: 0; padding: 0;: Removes default spacing that browsers apply to elements. This gives you a clean slate to style from.
- box-sizing: border-box;: Changes how width and height are calculated so that padding and borders are included inside the element’s dimensions. This makes layout calculations much easier and more intuitive.
- html, body { width: 100%; height: 100%; }
- Ensures that the root elements (html and body) take up the full viewport. This is especially useful when you're building layouts that rely on full-height sections or want to use 100vh units effectively.
3)Targeting an element in css - To target an element we use two methods either By using id of the element or class of element.
    id is targeted by using "#" .
    for eg - I want to target a div with id main then in css i will type" #main{ in these braces i will style div as i want } " .
    class is targeted by using "." .
    for eg - i want to target a div with class main then in css i will type .main{ in these braces i will style div as i want } " .
4)width and height -
see file style.css and link.html file.
in that we used width and height for div tag with id main try to change the values and see change in output.
5)Units like px and % - 
see file style.css and link.html file. 
in these files we have used different div tags with different pixel and percentage values 
6)margin and padding - 
see file style.css and link.html file.
In these files we have used different div tags with id "mar" and "padd" to understand different functions of margin and padding respectively.

</pre>
