# 100 Days Of Code - Log


### Day 1: June 28, 2017

**Today's Progress**: Since it's been awhile since I first began the Front End Developer Certificate curriculum in Free Code Camp, I decided to pick u from the beginning, redoing some of the basics and completing the exercises I missed the first time around.

**Thoughts**: Though I'd prematurely run through the Bootstrap section, looking forward to reviewing the CSS portion of the track. My goal is to become undeniably proficient at CSS. I also noticed how comfortable I felt reviewing the older exercises. A good indicator I've grasped those basics (easy peasy).

**Link(s) to work**:
* [My Activity](https://www.freecodecamp.com/ceciliaconsta3)


### Day 2: June 29, 2017

**Today's Progress**: Finished the remaining 18 exercises in the HTML/CSS portion of the Front End Development Certificate (FEDC). Subsequently researched  HTML/CSS/JS/PHP best practice reference material.

**Thoughts**: Adding negative margins to an element popped up in one of the FCC exercises, funny I discovered that's a thing just earlier this week at work!

From what I understand and to simplify my findings, we use negative margins when you want to bring one element into the space of another. 

<strong>Use case #1:</strong> You enter in additional text the div will expand – to prevent that use negative margin on heading – make value same as the padding inside the div. [Here's an example.](http://css-101.org/negative-margin/index.php)
    <pre>
    In IE6, styling static elements with negative margin may clip them. The fix for this bug is to use position:relative.
    </pre>

<strong>Use case #2:</strong> If you set all margin values to  a negative value, <pre>margin: -15px;</pre> your element will fill that container. [FCC reference] (https://www.freecodecamp.com/challenges/add-a-negative-margin-to-an-element)

**Link(s) to work**:
* [Free Code Camp Activity Board](https://www.freecodecamp.com/ceciliaconsta3)

**References**:
* [HTML for beginners](https://code.tutsplus.com/tutorials/30-html-best-practices-for-beginners--net-4957)
* [CSS](https://code.tutsplus.com/tutorials/30-css-best-practices-for-beginners--net-6741)
* [JS](https://code.tutsplus.com/tutorials/24-javascript-best-practices-for-beginners--net-5399)
* [PHP](https://code.tutsplus.com/tutorials/30-php-best-practices-for-beginners--net-6194)


### Day 3: June 30, 2017

**Today's Progress**: Updated My Academy project with some of the CSS knowledge picked up during FCC exercises and best practice links from yesterday.

**Thoughts**: I introduced some Javascript to the landing page. Have an issue with displaying my Bootstrap alert using JS/Jquery. Noticed that sometimes the page refreshes without displaying the alert after clicking submit, while at other times the alert makes a brief appearance. My goal is just to create some sort of follow up action for the users that submit an email, without using PHP or creating a database to hold their data. I'll revisit this once I learn more about forms and finish a few more JS exercises.

**Link(s) to work**:
* [ASF Project](https://github.com/ceciliaconsta3/The-Academy-of-South-Florida-Student-Project)


### Day 4: July 1, 2017

**Today's Progress**: Added Bootstrap, fixed CSS, added Task List, and cleaned up NCT project file system

**Thoughts**: Rather than using media queries for every screen size, decided to utilize the different column size options already integrated within Bootstrap, revisiting media queries at project completion for final responsiveness check


### Day 5: July 2, 2017

**Today's Progress**: Swapped out navigation images and Task List

**Thoughts**: Not much time to code today 

**Link(s) to work**:
* [NCT Commits](https://github.com/ceciliaconsta3/NCT/commits?author=ceciliaconsta3&since=2017-07-02T04:00:00Z&until=2017-07-03T04:00:00Z
)
* [Potree Project Commits](https://github.com/ceciliaconsta3/Potree-Custom-UI/commits?author=ceciliaconsta3&since=2017-07-02T04:00:00Z&until=2017-07-03T04:00:00Z
)


### Day 6: July 3, 2017

**Today's Progress**: JQuery exercises in FCC, moved unecessary comments into Task Lists in multiple projects

**Thoughts**: After some quick research I think a better way to keep track of pending TODO items in a project, aside from code comments, stickies, or Outlook tasks, is creating a TODO or Task List in the ReadMe.md like such:<br>
<pre>
### Task List / TODO
- [ ] App needs to do this
- [x] Finished!
</pre>

**Link(s) to work**:
* [JQuery](https://www.freecodecamp.com/ceciliaconsta3)


### Day 7: July 4, 2017

**Today's Progress**: Happy Fourth of July! Fixed CSS, organized current projects, and removed irrelevant or broken code

**Thoughts**: Decided to go through and clean up my code in a few projects with information I've gleamed. At the time I had about 14 repositories open. Seemed a bit munch and I googled what my peers opinions are on this and found a good answer in the link below. Consequently, I realized the quote generator wasn't working! Goes to show how important it is to revisit older projects.

**Link(s) to work**:
* [Multiple or Few repositories](https://softwareengineering.stackexchange.com/questions/206668/using-multiple-git-repositories-instead-of-a-single-one-containing-many-apps-fro3)


### Day 8: July 6, 2017

**Today's Progress**: Page redirect using JavaScript

**Thoughts**: Kept having issues with the splash page not recognizing the scripts added in main.js. After sifting through Stack Overflow,jsfiddles, Developer tools,and a JS validator and after correcting any relative linking discrepancies, I realized that the issue most likely involved scope. The page couldn't access the method inside the code block. I troubleshooted by triple checking syntax, refactoring my own code, and putting the script directly onto the page to see if it truely was a scope issue. I'm left with a working product and much fewer lines of JS.

**Link(s) to work**:
* [Potree Custom UI](https://github.com/ceciliaconsta3/Potree-Custom-UI
)


### Day 9: July 9, 2017

**Today's Progress**: CSS Loaders

**Thoughts**: Creating a loader was surprisingly simple and allowed me to practice keyframes and making linear-gradients. Next time around, I'd like to create a full page loader with text (i.e. the kind you get when you look yourself up on one of those suspicious yellow-page sites that tell you they're running a report before they tell you that report cost money). Also, had an issue with turning some directories into submodules. Viewed and removed the hidden git files, recommitted, and pushed it all. That didn't do the trick, but deleting and re-uploading the repository worked fine.

**Link(s) to work**:
* [Simple loader](https://github.com/ceciliaconsta3/NOC-wall)


### Day 10: July 11, 2017

**Today's Progress**: Tribute page

**Thoughts**: Decided to fully utilize bootstrap for the FCC Tribute page project. My second time using a carousel slider went much faster this time around. Looking into the documentation to understand exactly what's the function of each class.


### Day 11: July 12, 2017

**Today's Progress**: Updated CSS, posted loader to Codepen.io, and changed layout of Tribute page

**Thoughts**: Was requested by a member of the Twitter community to see the linear gradient that I worked on yesterday. I obliged and tweaked what I coded so it looks much more presentable. Noticed that I spend a lot of time iterating through and refactoring my CSS. A solution: incorporate more time into the brainstorming/planning stage.

**Link(s) to work**:
* [Simple loader Updated](https://codepen.io/ceciliaconsta3/full/MoLwBW/)






<!--**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)

Task List:
// When user opens a page, grab their location
// Send a request to the weather API site with the location
// Receive data
// Display the degrees on the page
// Change background image of the page to reflect the current weather
-->