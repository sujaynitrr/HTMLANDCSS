Before html5 for header , body and footer
 we were use div 
 example:
 <div>
    <div id="header"></div>
    <div id="body"></div>
    <div id="footer"></div>
 </div>

 above one is known as non semantic tag

 But in html5 we got some features like for header we can use  like <header></header> that one is known as semantic tags

 example of semantic tags : <header/> <footer/><aside/> <section/>


//Meta tags

In meta tags we can set the description of our website
using meta tags
<meta>
</meta>

// &nbsp ==> it is use for white space



//Make image responsive

// There two ways for make image responsive

1.Art direction
2.Resolution switching

Art direction: 



HTML

1. HTML stands for hypertext markup language
2. Hypertext defines the link between the web pages
3. The markup language is used to define the text document within the tag.
4. Markup language is also define the layout ya structure of web page.
4. Whatever we want to display in ui we can write in html 

Difference between HTML and HTML5

HTML                                     |             

1. It didn’t support audio and video without the use of Flash player support.
2. It uses cookies to store temporary data.
3. Does not allow JavaScript to run in the browse
4. It does not allow drag-and-drop effects.
5. Vector graphics are possible in HTML with the help of various technologies such as VML,            Silver-light, Flash, etc.
6. Not possible to draw shapes like circles, rectangles, triangles, etc.


HTML5
1. It supports audio and video controls with the use of <audio> and <video> tags.
2. It uses SQL databases and application cache to store offline data.
3. Allows JavaScript to run in the background. This is possible due to JS Web worker API in HTML5.
4. Vector graphics is additionally an integral part of HTML5 like SVG and canvas.
5. It allows drag-and-drop effects and support target blank attribute.
6. HTML5 allows drawing shapes like circles, rectangles, triangles, etc.

Tags

1. Tags will start with less and greater than symbol
2. Whatever is written in side greater and less symbol that is called tag
example <div>, <b></b>

Element

1. The content between inside tags known as element
example 
<p>Hello</p>
In this example p is tag and hello is element

2. Collection of a start tag, end tag, and its attributes.

Void Element

1. Void elements, also known as self-closing or empty elements, don't have any content.
2. They are self-contained and do not need a closing tag

3. example <br/> <hr/>

Non void element

1. These elements require both an opening tag and a closing tag

example <div></div>, <p></p>


Block Element

1. Block  level element start with new line.
2. It stretches  out to the left and right as far as it can.
example:
   <div>,<p>,<header>

inline element
1. An inline element doesn't start with new line
2. Only takes up as much width as necessary

example
<span>,<button><img>

//Entities

1. HTML entities are special codes that represent characters that are reserved in HTML
2. Characters that are not present on the keyboard
 example 
 &lt, &gt

//List 

1. Html list is basically use to display similar type of data in web page

2. There are three type of list:
   Ordered List ==> An ordered list is used to create a list of items where the order matters.
   Unordered List ==> It will list the items using plain bullets
   Definition List ==> It arranges your items in the same way as they are arranged in a dictionary.

//Attributes

1. Html attribute provide additional information about element
2. I t  is also help in define behavior or appearance
3. Attributes can take two type of parameters i.e. name and value
4. example
   <div id="container"></div>
   in this example id is attribute name and container is attribute value


// class Attribute

1. The class attribute is used to define a group of elements that share the same styles or behaviors.
example 
2. If we want to give same style and behavior in this case we can use class level attributes
<div class="container">Group of element</div>

in this example class is name of attribute and container is value and group of element in side tag

// Id attribute

1. id attribute is used to uniquely identify a single element within the document
2. Each id must be unique and is often used for targeting specific elements with styles or scripts.


//Layout structure

1. It means arrange Html element in good way.
2. HTML5 introduce several semantic  element that help define the structure of web page more clearly.
3. semantic or structural element :

 <header> => It's represent header of document.
 <nav> => it's represent nav section of element
 <main> => it's represent main content of document.
 <section> => 
 <article> =>
 <aside> => Represents content indirectly related to the main content, such as sidebars 
 <footer>=> Represents the footer of a document or a section

 // explain head and body tag

 head
 1. <head> => It's contains  metadata about document and also link to document as per our requirement.
 2. Whatever we will write in side head tag it will not display directly on web page
 3. content of head tags
      <title>,<metadata>,<link>,<style>,<script>,<base>

 //body

 1. The <body>  element contains all the document which is display on webpage including text, image, video, link, and other html element also.

content of body tag:

Text Content ==> Paragraphs, headings, lists, etc.
Media ==> Images, videos, audio files.
Links==> Anchor tags for navigation.
Interactive Elements ==> Forms, buttons, etc.
Structural Elements ==> Divs, sections, articles, etc

example of head and body tags

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Body Content Example</title>
</head>
<body>
    <header>
        <h1>My Webpage Header</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Welcome to My Home Page</h2>
            <p>This is the main content of the home page.</p>
        </section>
        <section id="about">
            <h2>About Me</h2>
            <p>This section contains information about me.</p>
        </section>
        <section id="contact">
            <h2>Contact Information</h2>
            <p>Here is how you can contact me.</p>
        </section>
    </main>
    <footer>
        <p>Footer Content &copy; 2024</p>
    </footer>
</body>
</html>










