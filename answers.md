
Question 1: Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

var pandaPic = document.querySelector('img')
undefined
pandaPic.innerHTML
""
pandaPic
<img src=​"images/​self-portrait-grassbg.jpg" alt=​"Self Portrait" title=​"Self Portrait" class=​"profile-image">​
pandaPic.innerText
""
pandaPic.src
"file:///Users/nadia/Documents/Bitmaker/Projects/panda-the-bear-js/images/self-portrait-grassbg.jpg"
pandaPic.src = "images/self-portrait-snowbg.jpg"
"images/self-portrait-snowbg.jpg"
****
Question 2: Select the heading that says "Panda the Bear" and change it to your own name.

var nv = document.querySelector('h1')
undefined
nv
<h1 class=​"highlight">​Panda The Bear​</h1>​
nv.innerText
"Panda The Bear"
nv.innerText = 'NadiaIvanova'
"NadiaIvanova"

********

Question 3. Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

var ent = document.querySelector('#employment h3')
undefined
ent
<h3 class=​"info-title">​…​</h3>​
ent.innerText
"   Employment"
ent.innerText = 'Just Over Broke'
"Just Over Broke"

********

Question 4. Change the colour of the body.

var backDrop = document.body
undefined
backDrop
<body>​…​</body>​
backDrop.style.backgroundColor = 'pink'
"pink"

********

Question 5. Change the colour of each element using the highlight class. Use a for loop to do this.

var array = document.querySelectorAll('.highlight')
undefined
array.forEach(function(element){ element.style.color = 'blue'})
undefined

******

Question 6. Change the font family of the h1 to 'monospace'.

var MonoSpacing = document.body
undefined
MonoSpacing
<body>​…​</body>​
MonoSpacing.style.fontFamily = 'monospace'
"monospace"

*******

Question 7. Find a way to select the round icons in the sidebar and then change their colour.
var array = document.querySelectorAll('.action-icon-bg')
undefined
array
(2) [a.action-icon-bg, a.action-icon-bg]
array.forEach(function(circle){circle.style.background = 'purple'})
undefined

*********

Question 8. Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself"

document.querySelector('#name')
<input type=​"text" name=​"name" class=​"contact-info" id=​"name" placeholder=​"Name">​
var fomName = document.querySelector('#name')
undefined
fromNAme
VM7910:1 Uncaught ReferenceError: fromNAme is not defined
    at <anonymous>:1:1
(anonymous) @ VM7910:1
fomName
<input type=​"text" name=​"name" class=​"contact-info" id=​"name" placeholder=​"Name">​
fomName.placeholder = "identify yourself"
"identify yourself"

*****
Question 9. Change the placeholder attribute of the message field to "state your business".

var mindYourBusiness = document.querySelector('#message')
undefined
mindYourBusiness
<textarea name=​"message" id=​"message" placeholder=​"Message">​</textarea>​
mindYourBusiness.placeholder = 	'state your business'
"state your business"

*****
Question 10 Give the name field a "value" attribute of "your nemesis".

document.querySelector("#name")
<input type=​"text" name=​"name" class=​"contact-info" id=​"name" placeholder=​"Name">​
var nemesis = document.querySelector("#name")
undefined
nemesis
<input type=​"text" name=​"name" class=​"contact-info" id=​"name" placeholder=​"Name">​
nemesis.value = 'your nemesis'
"your nemesis"

****
Question 11. Change the value attribute of the email field to "koalathebear@gmail.com".

document.querySelector('#email')
<input type=​"email" name=​"email" class=​"contact-info" id=​"email" placeholder=​"Email">​
var callMe = document.querySelector('#email')
undefined
callMe.value = "koalathebear@gmail.com"
"koalathebear@gmail.com"

*****
Question 12. Change the value of the submit button on the contact form to "En garde!".

document.querySelector('#submit')
<input type=​"submit" name=​"submit" id=​"submit" value=​"Submit">​
var button = document.querySelector('#submit')
undefined
button
<input type=​"submit" name=​"submit" id=​"submit" value=​"Submit">​
button.name = "En garde!"
"En garde!"
button
<input type=​"submit" name=​"En garde!" id=​"submit" value=​"Submit">​
button.value = "En garde!"
"En garde!"

******
Question 13. We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).


*******
Question 14. We should help Panda protect their privacy by erasing their personal details from the sidebar.

document.querySelector('.bio-info')
<ul class=​"bio-info">​<li class=​"bio-info-item">​…​</li>​<li class=​"bio-info-item">​…​</li>​<li class=​"bio-info-item">​…​</li>​</ul>​
document.querySelector('.bio-info').remove
ƒ remove() { [native code] }
var goAway = document.querySelector('.bio-info')
undefined
go
VM10705:1 Uncaught ReferenceError: go is not defined
    at <anonymous>:1:1
(anonymous) @ VM10705:1
goAway
<ul class=​"bio-info">​…​</ul>​
remove(goAway)
VM10743:1 Uncaught ReferenceError: remove is not defined
    at <anonymous>:1:1
(anonymous) @ VM10743:1
goAway.remove('bio-info')
undefined
