# Reading
The following reading is required for psychological safety talk:

- [What Google Learned From Its Quest to Build the Perfect Team](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html)
Read the following articles and/or review the following examples on CSS animations:

- [Read this article on CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)
- [Read this article on CSS Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
- [8 simple CSS3 transitions that will wow your users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)
- [6 Buttons animated](http://codepen.io/retyui/pen/ByoaXV)
- [CSS3 Animations: Keyframes](http://codepen.io/akshaychauhan/pen/oAfae)
- [404](http://codepen.io/kieranfivestars/pen/MYdQxX)
- [Pure CSS Bounce Animation](http://codepen.io/dp_lewis/pen/gCfBv)



 - studies show that groups tend to innovate faster, see mistakes more quickly and find better solutions to problems


 - Studies also show that people working in teams tend to achieve better results and report higher job satisfaction

-  nothing showing that a mix of specific personality types or skills or backgrounds made any difference


- If a company wants to outstrip its competitors, it needs to influence not only how people work but also how they work together.


- As long as everyone got a chance to talk, the team did well. But if only one person or a small group spoke all the time, the collective intelligence declined.


 **2D Rotate**


  - The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.


  - transform: rotate(20deg);


  **2D Scale**


  - allows you to change the appeared size of an element.


  - The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger



 - transform: scale(.75);

  **2D Translate**

   - pushing and pulling an element in different directions without interrupting the normal flow of the document.

   - transform: translate(-10px, 25%);


   **2D Skew**

   - is used to distort elements on the horizontal axis, vertical axis, or both.

   - transform: skew(5deg, -20deg);

   **Transform Origin**

-  transform: rotate(15deg);
  transform-origin: 0 0;


**Perspective** 


  - Using the perspective value within the transform property works great for transforming one element from a single

  - transform: perspective(200px) rotateX(45deg);

  **Backface Visibility**



  -.fade:hover
{
      1- opacity:1;-------Fade in
 background:#53a7ea;------- Change color

2-
 -webkit-transform: scale(1.3);--------
        -ms-transform: scale(1.3);--------Grow & Shrink
        transform: scale(1.3);--------

3-  -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);---------Rotate elements
        transform: rotateZ(-30deg);

4- border-radius:50%;-------Square to circle


5-   box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,----------3D shadow
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);

6- box-shadow: inset 0 0 0 25px #53a7ea;-------- Inset border
}