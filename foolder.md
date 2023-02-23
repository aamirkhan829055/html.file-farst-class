# LIST OF HTML tag 
## html tag
### 1 a href: tag
#### Example:

```
<a href="#">x y z</a>

```
### 2 abbr title: tag 
#### Example:
```
<abbr title="World Health Organization">x y z</abbr>

```

### 3 address a: tag 
#### Example:

```
<address>
Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

```

### 4 area map:tag 
#### Example:

```
<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
  </map>

```

### 5 article: tag 
##### Example:

```
<article>
  <h2>Google Chrome</h2>
  <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
</article>

```

### 6 aside :tag
##### Example:

```
<aside>
  <h4>Epcot Center</h4>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside>

```
### 7 audio controls:tag
#### Example:


```
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

```

### 8 b bold:tag
#### Example:

```
<p>This is normal text - <b>and this is bold text</b>.</p>

```



### 9 base :tag
#### Example:

```
<head>
  <base href="https://www.w3schools.com/" target="_blank">
</head>

<p><img src="images/stickman.gif" width="84" height="89" alt="Stickman"> - Notice that we have only specified a relative address for the image. Since we have specified a base URL in the head section, the browser will look for the image at "https://www.w3schools.com/images/stickman.gif".</p>

```

### 10 bdi:tag
#### Example:

```
<ul>
 <li>User <bdi>hrefs</bdi>: 60 points</li>
 <li>User <bdi>jdoe</bdi>: 80 points</li>
 <li>User <bdi>إيان</bdi>: 90 points</li>
</ul>

```

### 11  bdo =rtl: tag  
#### Example:  

```
<p><bdo dir="rtl">This paragraph will go right-to-left.</bdo></p>  

```

### 12 blockquote:tag
#### Example:

```
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.
</blockquote>

```


### 12 body:tag
#### Example:

```
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>

```
### 12 br break:tag
#### Example:

```
<p>To force<br> line breaks<br> in a text,<br> use the br<br> element.</p>

```

### 13 button :tag
#### Example:

```
<button type="button" onclick="alert('Hello world!')">Click Me!</button>

```

### 14 canvas :tag
#### Example:

```
<canvas id="myCanvas">Your browser does not support the canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.fillStyle = "#FF0000";
ctx.fillRect(0, 0, 80, 100);
</script>

```

### 15 caption :tag
#### Example:

```

<table>
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>


```
### 16 cite :tag
#### Example:

```
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>

```

###  17 code :tag
#### EXample:

```
<p>The CSS <code>background-color</code> property defines the background color of an element.</p>

```

###  18 col :tag
#### EXample:

```
<table>
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
  <tr>
    <td>5869207</td>
    <td>My first CSS</td>
    <td>$49</td>
  </tr>
</table>

```

### 19 colgroup :tag
#### EXample: 

```
<table>
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
</table>

```

### 20 data :tag
#### EXample: 

```
<table>
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
</table>

```

### 21 data :tag
#### EXample:

```
<ul>
  <li><data value="21053">Cherry Tomato</data></li>
  <li><data value="21054">Beef Tomato</data></li>
  <li><data value="21055">Snack Tomato</data></li>
</ul>

```

### 22 data :tag
#### EXample:

```
<ul>
  <li><data value="21053">Cherry Tomato</data></li>
  <li><data value="21054">Beef Tomato</data></li>
  <li><data value="21055">Snack Tomato</data></li>
</ul>

```
### 23 datalist :tag
#### EXample: 

```
<form action="/action_page.php" method="get">
  <label for="browser">Choose your browser from the list:</label>
  <input list="browsers" name="browser" id="browser">
  <datalist id="browsers">
    <option value="Edge">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
  <input type="submit">
</form>

```


### 24 dd  Definition :tag
#### EXample: 

```
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

```

### 25 del :tag
#### EXample: 

```
<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>

```



### 26 details :tag
#### EXample: 

```
<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>

```

### 27  dfn :tag
#### EXample: 

```
<p><dfn>HTML</dfn> is the standard markup language for creating web pages.</p>

```


### 28  dfn :tag
#### EXample: 

```
<p><dfn>HTML</dfn> is the standard markup language for creating web pages.</p>

```
### 29  dialog :tag
#### EXample: 

```
<p>This is some text.</p>

<p>This is some text.</p>

<dialog open>This is an open dialog window</dialog>

<p>This is some text.</p>

<p>This is some text.</p>

```


### 30 div :tag
#### EXample: 

```
<div class="myDiv">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>

```

### 31 dl  :tag
#### EXample: 

```
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

```

### 32 dt  :tag
#### EXample: 

```
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

```
### 33 em :tag
#### EXample: 

```
<p>We <em>cannot</em> live like this.</p>
<embed type="image/jpg" src="pic_trulli.jpg" width="300" height="200">
```

### 34 embed :tag
#### EXample: 

```

<embed type="image/jpg" src="pic_trulli.jpg" width="300" height="200">

```


### 35 fieldset :tag
#### EXample: 

```
<form action="/action_page.php">
 <fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
 </fieldset>
</form>

```


### 36 figcaption :tag
#### EXample: 

```
<figure>
  <img src="pic_trulli.jpg" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>

```

### 37 figure :tag
#### EXample: 

```
<figure>
  <img src="pic_trulli.jpg" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>

```

### 37 footer :tag
#### EXample: 

```
<footer>
  <a href="mailto:hege@example.com">hege@example.com</a></p>
</footer>

```

### 38 form :tag
#### EXample: 

```
<form action="/action_page.php">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Submit">
</form>

```

### 39 h1 tp h6  :tag
#### EXample: 

```

<h1> x y z</h1>
<h2> x y z</h2>
<h3> x y z</h3>
<h4> x y z</h4>
<h5> x y z</h5>
<h6> x y z</h6>

```

### 40 head :tag
#### EXample: 

```

<head>
  <title>Title of the document</title>
</head>

```

### 41 hadeer  :tag
#### EXample: 

```
  <header>
    <h1>A heading here</h1>
    <p>Posted by John Doe</p>
    <p>Some additional information here</p>
  </header>

```

### 42 hr line :tag
#### EXample: 

```
hr_______

```


### 43 html hayper :tag
#### EXample: 

```
<html lang="en">

```
### 44  i / :tag
#### EXample: 

```
<p>

<i>Lorem ipsum</i> 

is the most popular filler text in history.</p>

```



### 45  iframe :tag
#### EXample: 

```
<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe>

```

### 46  img  :tag
#### EXample: 

```
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">

```


### 47  input :tag
#### EXample: 

```
<input type="button"> : <input type="checkbox">
_________________________________________________
<input type="color"> : <input type="date">
_________________________________________________
<input type="datetime-local"> : <input type="email">
_________________________________________________
<input type="file"> : <input type="hidden">
_________________________________________________
<input type="image"> : <input type="month">
_________________________________________________
<input type="number"> : <input type="password">
_________________________________________________
<input type="radio"> : <input type="range">
_________________________________________________
<input type="reset"> : <input type="search">
_________________________________________________
<input type="submit"> : <input type="tel">
_________________________________________________
<input type="text"> (default value) : <input type="time">
_________________________________________________
<input type="url"> : <input type="week">

```

### 48  ins  :tag
#### EXample: 

```
<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>

```

### 51  kbd :tag
#### EXample: 

```

<p>Press <kbd>Cmd</kbd> + <kbd>C</kbd> to copy text (Mac OS).</p>

```
### 52  label :tag
#### EXample: 

```

 <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">

```

### 53  label :tag
#### EXample: 

```

 <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">

```


### 54 li :tag
#### EXample: 

```

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```

### 53 link :tag
#### EXample: 

```

<head>
  <link rel="stylesheet" href="styles.css">
</head>

```

### 54 main :tag
#### EXample: 

```
<main>
  <article>
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
  </article>
</main>

```
### 55 map :tag
#### EXample: 

```
<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>

```

### 56 mark :tag
#### EXample: 

```
<p>Do not forget to buy <mark>milk</mark> today.</p>

```
### 57 meta  :tag
#### EXample: 

```
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>


```
### 58 meter :tag
#### EXample: 

```
<label for="disk_c">Disk usage C:</label>
<meter id="disk_c" value="2" min="0" max="10">2 out of 10</meter><br>

<label for="disk_d">Disk usage D:</label>
<meter id="disk_d" value="0.6">60%</meter>


```
### 59 nav :tag
#### EXample: 

```
<nav>
  <a href="/html/">HTML</a> |
  <a href="/css/">CSS</a> |
  <a href="/js/">JavaScript</a> |
  <a href="/python/">Python</a>
</nav>

```

### 60 noscript :tag
#### EXample: 

```
<script>
document.write("Hello World!")
</script>
<noscript>Sorry, your browser does not support JavaScript!</noscript>

```


<!-- -----///,;;;; -->

















