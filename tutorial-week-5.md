Website Layout Using HTML5
Or
How to Avoid Using Divs

Step 1: Know your containers and their purpose
header Defines a header for a document or a section
nav Defines a container for navigation links
section Defines a section in a document
article Defines an independent self-contained article
aside Defines content aside from the content (like a sidebar)
footer Defines a footer for a document or a section details Defines additional details
summary Defines a heading for the details element

Step 2: Know where they best fit together
I like to use this picture to help me visualise it
<find that picture>

Step 3: Style it in css
This example uses `<header>`, `<nav>`, `<section>`, and `<footer>` to create a multiple column layout:
Example:
```
<body>

<header>
<h1>City Gallery</h1>
</header>

<nav>
London<br>
Paris<br>
Tokyo<br>
</nav>

<section>
<h1>London</h1>
<p>
London is the capital city of England. It is the most populous city in the United Kingdom,
with a metropolitan area of over 13 million inhabitants.
</p>
<p>
Standing on the River Thames, London has been a major settlement for two millennia,
its history going back to its founding by the Romans, who named it Londinium.
</p>
</section>

<footer>
Copyright © W3Schools.com
</footer>

</body>

<style>
header {
    background-color:black;
    color:white;
    text-align:center;
    padding:5px; 
}
nav {
    line-height:30px;
    background-color:#eeeeee;
    height:300px;
    width:100px;
    float:left;
    padding:5px; 
}
section {
    width:350px;
    float:left;
    padding:10px; 
}
footer {
    background-color:black;
    color:white;
    clear:both;
    text-align:center;
    padding:5px; 
}
```
