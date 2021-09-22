# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screen reader is a form of assistive technology (AT) that renders text and image content as speech or braille output. Screen readers are essential to people who are blind, and are useful to people who are visually impaired, illiterate, or have a learning disability.

https://en.wikipedia.org/wiki/Screen_reader


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

img

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

ul
li
a


c) You want to sell designer hats. You need to receive orders from the user.

form


## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

no, a 'button' can't be a child of a 'button', because it is an 'inline' element, if we change the context of the 'button' to 'block', it would be possible in that case, but it is not valid:

https://stackoverflow.com/questions/39386497/can-i-nest-button-inside-another-button#:~:text=It%20is%20not%20valid%20to,be%20no%20interactive%20content%20descendant.


## Q5 - What is the most generic tag you can use?

div

## Q6 - What do the following achronyms stand for?

a) `a` Anchor

b) `ol` Ordered list

c) `ul` Unordered list

d) `li` List Item

e) `tr` Table row

f) `th` Table head

g) `td` Table data

## Q7 - Usually, `td` elements are children of what kind of elements?

tr

## Q8 - What is the difference between td and th?

'td' is a table cell, 'th' is a table cell also but it is placed in the first row.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

usually 'h1' is bigger, but with CSS the size could be changed as needed.



## Q10 - In which situation can you use self closing tags?

When the element doesn't have children, for example <p> element.


## Q11 - What is autofilling and why is it important?

is when the browser enter data automatically in the web form.
It help respondents to fill out forms faster and by the way have a smooth browsing experience.


## Q12 - Which attributes are always present in an img element?

'src' attribute to indicate the location of the image on the Internet.

## Q13 - Which attribute is always present for an anchor tag?

href attribute which corresponds to the destination address.
