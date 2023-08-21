# HTML_CSS-Coding

 ### I have completed all the requirements of the task, but I would like to point out several things:

1. For readability, I created multiple CSS files. Each section has its own css file.

2. The web design is responsive.

3. In **section 5**, the left side is auto scrolling and when the scroll reach the bottom, it automatically goes to the top. 
Also, when you enter the left side region, the auto scrolling stops, and when you leave, it keeps scrolling. When you click on one of the 
menus in the left part, its own recipes appear in the right side.

     4.The Javascript code is as simple as possible, so that it fulfills all the requirements without having to write longer code to put in certain details.
  For example, if the total number of slides is smaller than the available space, it makes sense to remove the previous and next buttons,
  but I didn't go into these details so the code wouldn't get bigger.

5. I opened the site on different browsers and everything works fine except the scroll bar because I designed it to be smooth and thin. After debugging, the problem
was because the *auto scrolling in section 5* and if I use javascript code instead of *scroll-behavior: smooth*, the auto scrolling stops, so I used jQuery
for this purpose only.

6. For icons, instead of using *font-awesome library*, I used HTML Entities.
