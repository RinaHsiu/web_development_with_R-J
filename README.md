# web_development_with_R-J
in this repository, we are going to take you along with us on our journey with Dr Angela Yu who is going to teach us all about web development!


Welcome to the web_development_with_R-J wiki!
in this repo, we are going to be learning about web development!

# Day 1 06/09/25

## Udemy
- udemy is the new website we are going to use to learn coding on. 
- it is run by Dr Angela Yu who is going to teach us
- Lets Go!

## the 12 rules of Coding
- the 12 rules of coding is 12 different rules that Angela has made for us!
- we will learn 1 every lesson

### Rule 1: Trick your Brain with the 20 minutes rule

**step 1: Task Switching**
task switching is a <ins>very hard</ins> thing to do! Why should I stop watching TV do to coding?

this is why the moment you step into your house and change the environment is so <ins>crucial</ins>! If you decide now to just do <ins>20</ins> mins of coding, you might end up doing <ins>more</ins>!

**step 2: Develop a habit**
try to choose a time where you just sit down and do coding. keep doing that for a month. to make it easier, you can keep a streak!

## the Internet
think of the internet as a long wire that connects computers together!
client => Internet service provider(e.g. BT, EE) => Domain Name system

---

# Day 2 07/09/25

## Udemy

### Code files

there are 3 types of code files:
- HTML </>
- CSS {...}
- JS </>
but why have all three? 

think of it this way, you are building a house.
- HTML would be the bricks that make the house
- CSS would be the paint and decorations of the house
- JS would be the electricity and water and the other functions of the house that makes it ok to live in.
or
- HTML is the human body though not alive
- CSS is the clothing and makeup that we wear to look prettier
- JS would be life
it is the same in programing! take google for example,
- HTML is the home page
- CSS is the color and design
- JS is the functions that allows you to search and click buttons

### How to get the most out of courses?

**1. the 10 mins rule**
instead of coding with the tutorial, just watched for 10 mins and try to understand the code and then try to recreate that code.

**2. Don't skip lessons**
skipping lessons could mean you miss out on some important imformation and could get stuck.

### How to get help when your stuck?
getting stuck is natural in coding! Everyone gets stuck, even the best programers! 

1. ask google or ai
2. go to Q&A section
   how to ask
      - what did you expect
      - what actually happened
      - screenshot of you code
      - screen shot of the debugging console

---

# Day 3 12/09/25

## Udemy

### HTML 

**The Heading element**
there are only <ins>6 heading</ins>. H1 to H6

<h1>Hello World!</h1>
<h6>Hello World!</h6>

h1 is the tag and the whole thing is the element
- don't have more than <ins>one</ins> h1
- don't skip levels

**Paragraph element**
<p> This is a paragraph </p>

without the paragraph element, everything will just look like this:

this is a paragraph this is a paragraph this is a paragraph
bad right?

with it though, it will look like this:

this is a paragraph

this is a paragraph

Lorem Ipsum - place holder text
when you are making a website, you don't have time to write what you actually want so we use Lorem Ipsum as a place holder. it will generate latin text that looks like a real paragraph. for more fun things, go to Bro Ipsum or Pirate Ipsum!

### Vs Code
this was also the first time I used Vs Code! Yay! it was really easy to understand and use

## what are my feelings
happy
proud
yay!

## What's next?
more!

---

# Day 4 14/09/25

## Udemy

### Void Elements
A void element has NO content

**Horizontal Rule**
<hr/> 
this is a void elemet because it has no content.
this creates a line

**Breack Element**
<br/>
this is also a c=void element because it has no content
this crates a new line is sometimes used in poems.

### Best Movies Project

MY FIRST WEBSITE!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
YAYAYAYAYAYAYAYAYAYAYAYAYAYAYAYAYAYAYAYAYAY

this is a simple webpage combining everything we've learnt so far.

## What are my feelings 
Happy
Proud
Yay!!!!!!!!!!!!!

## What's next?
More!

---

# Day 5 19/09/25

## Udemy

### List Element 

**Unordered list**
<ul>
   <li>Milk</li>
   <li>Eggs</li>
   <li>Flour</li>
</ul>

an unordered list uses bullet points

**Ordered list**
<ol>
   <li>Milk</li>
   <li>Eggs</li>
   <li>Flour</li>
</ol>

an ordered list uses numbers

### Nesting and indentation
we can actually nest a list insode another list! this is where indentation becomes important.

**E.G**
<ul>
   <li>A</li>
   <li>B
      <ul>
         <li>B1</li>
      </ul>
   </li>
</ul>

**Life Hack**
Do the first list first then start to add the nested ones. it makes life SO MUCH EASIER!

## What are my feelings
- happy
- tired
- annoyed cause i had to type all this in twice

## Whats next?
MORE!

---

# Day 6 21/09/25

### Anchor Element
The Anchor element allows us to create HyperLinks!

<a>This is a link</a>
this does NOT work!!!

you need to add an ATTRIBUTE

<a href="http://www.google.com">This is a link</a>

it will always be like this:

<tag then attribute then = then value>content</tag>

fun fact! 
- you can have more than one attribute!
- just seperate them with a space

**href**
<a href="dfhjakjhdfakhjgdsf">this link is created using href!</a>
- stands for "Hypertext Reference"
- used to go to other addresses(web pages, websites)

## What are my feelings
- tired
- happy because i made my first website with HyperLinks!
- ye

## What's Next?
- more!

---

# Day 7 28/09/25

## Udemy

### Image Element
the image element allows us to add images onto our website!

<img scr="url"/>
- scr is the source of image
- url is the location of the image
- it is a void element

  <img scr="url" alt="description"/>
  - we sometimes need to add a description for the image for blind people or people who need a screen reader.

  **Fun Fact**
  - url stands for
  - Uniform Resource Locator!

### Birthday Invitation program
using everything we learned in section 3!

## What are my feelings
- tired
- happy cause we finished section 3!!!!!
- ye...
  
## What's Next?
- more!
  
---

# Day 8 03/10/25

## Udemy

### File paths
there are two types of file paths
- Absolute
- Relative
a file path is basically
- DIRECTIONS TO A SPECIFIC LOCATION

**Absolute file path**
- windows: c:/project/images/cat.png
- mac: /project/images/cat.png

this is useful as you can navigate to the specific location from anywhere on your computer

An absolute file path is like you asking a stranger to go get you something from your house(don't do this in real life. its dangerous)
You need to tell them the postcode and loads of directons for them to know where to go

**Relative file path**
this is used more in web development
- images/cat.png
- shorter
- move folders arround(doesn't matter)

  you can think of this as asking your family to go get you something from your house, they know where you live so you don't need to tell them the directions

  **Special Characters**
  ../
  up a level

  ./
  current directory

## What are my feelings
- tired
-  happy

## What's Next?
- MORE!

---

# Day 9 05/10/25

## Udemy

### Webpages
<a href="./about.html">About Page<a/>

**Watch out!**
if a folder has no files but has folders, it is shown like this:
- asset/images
think of it like this
- assets
-    images
-       cat.png

**Tips**
if you want to put a link in an image, just put the image where you would normally put the word.
e.g.
- <a href="./aelkfjldfhksajdfhk"><img src="kfhksjfhsdf"><a/>

## What are my feelings
- tired
- ye
  
## What's Next?
- more
  
---

# Day 10 10/10/25

## Udemy

### HTML Boilerplate
A bit like a letter it has many structures

<!doctype html>
<html lang="en">
   <head>
      <meta charset="UTF-8">
      <title>My Website</title>
   </head>
   <body>
      <h1>Hello World!</h1>
   </body>
</html>

more in notebook

## What are my feelings
- happy
- tired
- excited for newxt time!
- ye

## What's Next?
- more!
- first portfolio!
  
---

# Day 11 12/10/25

## Udemy

### Portfolio Project
made a portfolio that contains everything we've learnt so far.
we also made it a real live website on the internet!!!
https://rinahsiu.github.io/rina_portfolio/

## What are my feelings
- tired
- annoyed cause i wamnt to GO TO BED!!!!!
- happy
- ye
  
## What's Next?
- CSS!!!!
- more

---

# Day 12 18/10/25

## Udemy

### Css
there are 3 different types of adding css
- inline
- internal
- external

**Inline**
- goes into the same line as the html element
- used to add a single element
- only for specific sections

**Internal**
- useful to apply to one html document/webpage
- not sutable for multi page websites

**External**
- lives in a different file
- used for multi page websites
- used most commonly

### DNS
we also learnt what dns was and fixed my website

- dns stand for domain name system
- its like a phone book on the internet

how to trouble shoot
1. add your domain in git hub pages settings
2. so to go daddy and set DNS records
3. enable HTTPS
next time, just use GPT

## What are my feelings
- tired
- happy
- mad at my dad
- ye
  
## What's Next?
- more

---

# Day 13 19/10/25

## Udemy

### CSS Selectors
there are 5 different ways of applying CSS to your code:
- element selector
- class selector - .khfsdkjfhskd
- id selector - #lsjdfhskfh
- attribute selector - [ksdfhskd]
- universal selector - *

## What are my feelings
- happy
- tired
- ye
  
## What's Next?
- more!
  
---

# Day 14 30/10/25 (Day before HALLOWEEN!!!!!!!!!!)

## Udemy

### project
learnbt spanish words that i already knew!
just kidding!
changed the font weight and the colour od the h2s and changed the six=ze of the images (use img)

### CSS Color Proterties
**Hex Numbers**
to find our more colours, go to ColorHunt.co!
all the colors are made up of fractions of red, green and blue.

#5d3891 is purple

## What are my feelings
- happy because i made a very pretty webpage!
- excited cause tomorrow is halloween!
- soooooo hungry and thirsty
- ye

## What's Next?
- more!!!!
  
---

# Day 15 31/10/25 A.K.A HALLOWEEN!!!!!!!!

## Udemy

### Font Properties
changes appearance of text

types:
- font-weight
- font-size
- font-family

**font-size**
1px = 1/96th inch or 0.26mm
1pt = 1/72nd inch or 0.35mm
these two are both static

1 em = 100% of parent
1rem =- 100% of root
these two are relative

**font-weight**
a font can be normal or bold

number:
100-900
light-bold

**font family**
what the ftext look like
 to search for fonts, go to fonts.google .com!

 **Text-align**
 text align is where the text starts.
 left, right, start,end

## What are my feelings
- headache
- tired
- excited cause its halloween!!!!!!!!!!!
- happy
- ye

## What's Next?
- more!!!
  
---

# Day 16 2/11/25

## Udemy

### the box model
margin, border and padding

**border**
no matter the border, the original shape doesn't change

**padding**
pushes border out
adds space between shape and border

**margin**
adds space between next element and shape

All three of these can take 4 values
4 values: different on all 4 sides
2 values: top/bottom left/right
1 value: all sides

**content division element (HTML)**
this element is invisible
it is used to group differnt elemtns together.

## What are my feelings
- happy
  
## What's Next?
- more
- project
  
---

# Day 17 07/11/25

## Udemy

### Motivation Meme Project
created a project that had a funny motivation mem on it
used:
- css
- html boilerpate

end of section6. intermediate CSS!

## What are my feelings
- tired
- headache
- thristy
- happy cause the prohect was fun
- need sleep because its 10pm
  
## What's Next?
- more!
- start section 7
  
---

# Day 18 09/11/25

## Udemy

### CSS Cascade
**Position**
ther lower down the file the rule is, the more important it is

**Specificity**
element selector ---> class selector ---> attriubute selector ---> id selector

**Type**
external ----> internal -----> inline

**Importance**
if it has !importnat in it, it doesn't matter if there are other rules.
THIS IS THE TOP TRUMP!!!!

## What are my feelings
- tired
- happy
- ssad cause tomorrow is Monday
- ye
  
## What's Next?
- More!
  
---

# Day 19 15/11/25

## Udemy

### Combining CSS Selectors
**Group**
- apply to both selectors
- separate with a comma

**Child**
- apply to direct child of left side
- separate with greater than symbol

**Descendant**
- apply to a descendant pf left side
- separate with a space

**Chaining**
- apply when all selectors are true
- no space between

**Combining Coknbiners**
-  this is where you can combine different types of combiners for a specific element

## What are my feelings
- happy
- tired
- excited cause im going to watch little shop of horrors after!

## What's Next?
- more!
  
---

# Day 20 16/11/25

## Udemy

### CSS positioning

**Static Positioning**
- HTML default flow

**Relative Positioning**
- position relative to default position

**Absolute Positioning**
- position relative to nearest positioned ancester OR top left corner of webpage
- z-index
  - when an object has a larger z-index, it will go be shown front

**Fixed positioning**
- position relative to top left corner of BROWSER window

### CSS flag project
- learnt how to use all of the skills that we've learnt in this section.

## What are my feelings
- annoyed
- tired
- happy
- sad cause tomorrow is school
  
## What's Next?
- more
- advanced CSS
  
---

# Day 6 21/11/25

## Udemy

### CSS Display
there are 3 typoes of CSS Displaying.
- inline
- block
- inline-block

**Block**
block is the default
it takes up all the space width wise

**Inline**
makes things on the same line
can't change size

**Inline-block**
a mixture of the two.
can change size
will go onto the same line if there is space

## What are my feelings
- happy
- tired
- thirsty
- ye
  
## What's Next?
- more!!!!!!

---

# Day 22 23/11/25

## Udemy

### CSS Float
makes the image able to wrap text
- float
- clear

### Responsive Websites
making websites look good on all screen sizes
there are 4 ways of achieving this
- Media Query
- CSS grid
- CSS Flexbox
- Bootstrap Framework

section 9-11 is dedicated to learning these.

## What are my feelings
- confused
- happy
- tired
- ye
  
## What's Next?
- more!!!!
  
---

# Day 24 28/11/25

## Udemy

### Media Query
**Max-width**
- targets smaller screens

**Min-width**
- targets bigger screens

**combine**
- targets screens between flkjasfkshfd and akssjdfkasjf
- OR
- targets screens less than alskfjlsakfjd and more than lskdfjlsdkfj

## What are my feelings
- tired
- happy
- ye

## What's Next?
- more!
- project

---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?

---


# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?

---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?

---
# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?
---

# Day 6 21/09/25

## Udemy

## What are my feelings

## What's Next?

---
