# ACA Lessons

## TUESDAY - 22

### PRESENTATION: Jung Cho

#### THURSDAY PRESENTATION: David Cho

### Daily Logic
Parents with two children - a son and a daughter - came to a wide river. There was no bridge there. The only way to get to the other side was to ask a fisherman if he could lend them his boat. However, the boat could carry only one adult or two children.
How does the family get to the other side and return the boat to the fisherman?

### What's Due?

* Blog Post 2 (Instructions at the bottom of this lesson: https://web.austincodingacademy.com/_book/01Week/02DayClass.html): **Due Thursday 24th**

* PR of Portfolio: If you already have your Portfolio live, you can just link your portfolio URL in Campus Manager under `GitHub Link` (If you don't have your portfolio live, go back thru curriculum to "Host Your First Webpage On Github": https://web.austincodingacademy.com/_book/01Week/02DayClass.html) - **Due Thursday 24th**

* PR of Blog Website: I will go over how to make a PR so you all can get the link to the PR submitted in Campus Manager under `Blog Website PR Link` (Instructions are in Section 2 of 2: Making a Blog with CSS Selectors: https://web.austincodingacademy.com/_book/01Week/02DayClass.html) - **Due Tuesday 29th**

* Blog Post 3 (Instructions at the bottom of this lesson: https://web.austincodingacademy.com/_book/02Week/01DayClass.html): **Due Tuesday 29th**

#### Creating a PR:

* Create a new branch in git

* Make some changes in VS code, save

* git add and commit and push to GitHub

* Go to github.com and create a new Pull Request to compare your new branch with the master branch

* Copy the URL of the PR and paste it into Campus Manager

* Merge your own Pull Request, so the changes appear on your live website.

### Today's Lesson:

- [ ] Find a resume design.
- [ ] Find a person to build the resume for.
- [ ] Find lorem ipsum content
- [ ] Draw out the wireframe of the resume.
- [ ] Code Review with a classmate.
- [ ] Code it.
- [ ] Turn it in.

### If you finish early

**Work on your homework that's due Thursday**

## THURSDAY - 24

### Career Prep Action Item
* Share your Code Schedules on Rocket Chat

### PRESENTATION: David Cho

#### TUESDAY PRESENTATION: Ryan Delong

### Daily Logic
Another river crossing puzzle goes as follows. Three humans, one big monkey and two small monkeys are to cross a river:

Only humans and the big monkey can row the boat.
At all times, the number of humans on either side of the river must be greater or equal to the number of monkeys on that side. (Or else the humans will be eaten by the monkeys!)
The boat only has room for 2 (monkeys or humans).
Monkeys can jump out of the boat when it's banked.

### What's due?

* Medium Blog Post 2 (Instructions at the bottom of this lesson: https://web.austincodingacademy.com/_book/01Week/02DayClass.html): **Due TONIGHT by 11:59pm**

* Live Portfolio: If you already have your Portfolio live, you can just link your portfolio URL in Campus Manager under `GitHub Link` (If you don't have your portfolio live, ask me for help during tonights class!) - **Due TONIGHT by 11:59pm**

* Responsive Hero page - Instructions here: https://web.austincodingacademy.com/_book/02Week/02DayClass.html#: **Due Tuesday 29th**

* PR of Blog Website/Link to live blog: I will go over how to make a PR so you all can get the link to the PR submitted in Campus Manager under `Blog Website PR Link` (Instructions are in Section 2 of 2: Making a Blog with CSS Selectors: https://web.austincodingacademy.com/_book/01Week/02DayClass.html) - **Due Tuesday 29th**

* Medium Blog Post 3 (Instructions at the bottom of this lesson: https://web.austincodingacademy.com/_book/02Week/01DayClass.html): **Due Tuesday 29th**

* Medium Blog Post 4 (Instructions at the bottom of this lesson: https://web.austincodingacademy.com/_book/02Week/02DayClass.html): **Due Thursday 31st**

### We're having some problems with `gh-pages` branches, so please branch all branches off of `master` and delete `gh-pages`

1. Do: `git checkout master`
2. `git pull origin master` - This will grab all of your most recent code from GitHub and update your master branch on your laptop
3. `git branch -D gh-pages` - This permanently deletes the `gh-pages` branch
4. Make ALL additional branches for anything else we do in this class off of the `master` branch.
  a. **Every time you want to start a new branch:** `git checkout master`, `git pull origin master`, `git checkout -b new-branch`

### Eric's Git / GitHub presentation

### Responsive Hero Page

Follow the curriculum:

* Bring a piece of paper and pencil to class and begin drawing out the layout of boxes you see for your mobile design.
* Repeat for the tablet view.
* Make new branches
* Code it.
* add, commit, push, pr and copy/paste link to turn in.

## TUESDAY - 29

### PRESENTATION: Ryan Delong

#### THURSDAY PRESENTATION: Joe Hauger

### Daily Logic

A teacher says: I'm thinking of two whole numbers greater than 1. Try to guess what they are.

* The first student knows their product and the other one knows their sum.

**First**: I do not know the sum.

**Second**: I knew that. The sum is less than 14.

**First**: I knew that. And, now I know the numbers.

**Second**: And so do I.

What were the numbers?

### What's Due?

* Link to live blog: Section 2 of 2: Making a Blog with CSS Selectors: https://web.austincodingacademy.com/_book/01Week/02DayClass.html - **Due TONIGHT before 11:59pm**

* Medium Blog Post 3: https://web.austincodingacademy.com/_book/02Week/01DayClass.html - **Due TONIGHT before 11:59pm**

* Medium Blog Post 4: https://web.austincodingacademy.com/_book/02Week/02DayClass.html - **Due Thursday 31st**

* Medium Blog Post 5: https://web.austincodingacademy.com/_book/03Week/01DayClass.html - **Due Tuesday 5th**

* Link/PR to Widget Dashboard using CSS Grid: https://web.austincodingacademy.com/_book/03Week/01DayClass.html - **Due Tuesday 5th**

**Grading**: You need to get at least a 70% to continue with the course. Checkpoints are weighted higher than assignments. 
* **Links in Campus Manager before due-date with relevant assignment**: 100 points
* **Links in Campus Manager before due-date without relevant assignment**: 50 points
* **Links in Campus Manager corrected after due-date**: 75 points
* **Links in Campus Manager posted after due-date**: 0 points

### Instruction

1. Selena's Landing Page - has all links
2. Will be populating `Portfolio` link today
3. Show Selina's GitHub organization and explain `origin`
4. Show how CSS grid can relate to Selena's landing page

#### CSS Grid

* Examples: 

  * CodePen: https://codepen.io/karks88/pen/eWWaPg
  
  * CodePen: https://codepen.io/eamoses/pen/zeKMLm
  
  * My code

* Grid garden: http://cssgridgarden.com/

##### CSS Grid Widget

0. Go to your ACA folder in Terminal.
1. Make sure you have a `src` folder. `cd` into it. Open VS Code.
2. Make a new file called `portfolio.html` within your `src` folder and link it in the "portfolio" button on your portfolio landing page
3. Go to your origin branch (`master` or `gh-pages`) in git and do `git pull` and then create a `dashboard` branch off of it.
4. In VS Code, create a `dashboard.html` page. Create a `dashboard-style.css` file.
5. In order to link your `dashboard.html` into your `portfolio.html`, create an `<a href="dashboard.html"></a>` within `portfolio.html`

## THURSDAY - 31

### PRESENTATION: Joe Hauger

#### TUESDAY PRESENTATION: Dan Brockman

### Daily Logic

How many flowers do I have if all of them are red except two, all of them are purple except two, and all of them are blue except two?

### What's Due?

* Medium Blog Post 4: https://web.austincodingacademy.com/_book/02Week/02DayClass.html - **Due Thursday 31st**

* Medium Blog Post 5: https://web.austincodingacademy.com/_book/03Week/01DayClass.html - **Due Tuesday 5th**

* Link to Widget Dashboard using CSS Grid - **Due Thursday 7th**

* Medium Blog Post 6: https://web.austincodingacademy.com/_book/03Week/02DayClass.html - **Due Thursday 7th**

* NASA or Pintrest-like Page using CSS Flexbox - **Due Thursday 7th**

**Grading**: You need to get at least a 70% to continue with the course. Checkpoints are weighted higher than assignments. 
* **Links in Campus Manager before due-date with relevant assignment**: 100 points
* **Links in Campus Manager before due-date without relevant assignment**: 50 points (If you edit the link with the correct assignment after the due date, I will change your grade to a 75)
* **Links in Campus Manager posted after due-date**: 0 points (No chance to edit link or get more points)

### Story time

Reasoning behind grading my style.

Perfection isn't expected: The only way an employer knows you're making progress on a software engineering team, is if you show them something, even if it's uncompleted crap. Push things to GH before they are done, before you are ready. Accept help and suggestions on your work as you go. It's about progress and being flexible enough to make changes as you go, not about working in a silo until you've completed a job to perfection.

### Go over Checkpoint 1

* https://web.austincodingacademy.com/_book/checkPoints/01checkPoint.html

**Checkpoint 1 is due Thursday February 14th by 11:59pm**

### Adding everyone to my portfolio

* https://github.com/eamoses/aca-01-portfolio

* Short demo of how I built everything out in this repo, share code if anyone wants to use it/reference it while they're building their dashboards.

### NASA images page with CSS Flexbox

Flexbox is great when you want to line up a whole bunch of things in one direction, and make sure they "flex" to the changing of the size of the page.

* Flexbox reference: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

* Flexbox CodePen example: https://codepen.io/eamoses/pen/gqmPdw

* We'll start on a new page with a NASA **or** Pintrest theme using CSS Flexbox.

## TUESDAY - 5

### PRESENTATION: Andy Fogarasi

#### THURSDAY PRESENTATION: Devin Gibbons

### Daily Logic

The pattern 123451234512345... is continued to form a 2000 digit number. What is the sum of all 2000 digits?

### If coding was easy, everybody would be doing it!

* Using other software engineers' open-source code is great...if you already understand what it does.

### What's Due?

* Medium Blog Post 5: https://web.austincodingacademy.com/_book/03Week/01DayClass.html - **Due TONIGHT**

* Link to Widget Dashboard using CSS Grid - **Due Thursday 7th**

* Medium Blog Post 6: https://web.austincodingacademy.com/_book/03Week/02DayClass.html - **Due Thursday 7th**

* NASA or Pintrest-like Page using CSS Flexbox - **Due Thursday 7th**

* Blog Post 7: https://web.austincodingacademy.com/_book/04Week/01DayClass.html - **Due Tuesday  12th**

* Checkpoint 1: Widget Dashboard using CSS Grid AND a Media Query with an `Images` folder containing two wireframes (moble and tablet) - **Due Thursday 14th**

### Box Model

* Width & Height

* Padding

* Border

* Margin

Box model CodePen example: https://codepen.io/bigknell/pen/aqgzYp

  * Show how to Fork a CodePen so you can "mess with it"

#### Free Website Templates

* https://freewebsitetemplates.com/preview/hairstylesalon/index.html

* https://freewebsitetemplates.com/preview/mustacheenthusiast/index.html

#### Getting started

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b boxModel`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin boxModel` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## THURSDAY - 7

### PRESENTATION: Devin Gibbons

#### TUESDAY PRESENTATION: Selina Solis & Rekha Umashankar

### Daily Logic

![Daily logic](https://github.com/eamoses/aca-01-lessons/blob/master/logicfeb7.png?raw=true)

### What's Due?

* Link to Widget Dashboard using CSS Grid - **Due TONIGHT**

* Medium Blog Post 6: https://web.austincodingacademy.com/_book/03Week/02DayClass.html - **Due TONIGHT**

* NASA or Pintrest-like Page using CSS Flexbox - **Due TONIGHT**

* Blog Post 7: https://web.austincodingacademy.com/_book/04Week/01DayClass.html - **Due Tuesday  12th**

* Blog Post 8: https://web.austincodingacademy.com/_book/04Week/02DayClass.html - **Due Thursday 14th**

* Checkpoint 1: Widget Dashboard using CSS Grid AND a Media Query with an `Images` folder containing two wireframes (moble and tablet) - **Due Thursday 14th**

### SVG vs. PNG vs. JPG

* `.svg` and `.png` images can grow and shrink while keeping their dimensions and without getting pixelatd **lossless**

* `png`: Rastor preserves transparencies - used mainly for icons and smaller images that don't need as many colors

* `svg`: Vector preserves transparencies - for high quality images that need to be scaled to any size

* `jpg`: Rastor that will become more pixelated the more you zoom in, it does not preserve transparency but will use full color availability

* Convert `.jpg` to `.png` or `.svg` to use on your websites.

* Blog post for more info: https://www.pagecloud.com/blog/web-images-png-vs-jpg-vs-gif-vs-svg

### Work on Checkpoint 1, Chrome Dev Tools, Merge Conflicts

#### Chrome Dev tools follow along

* https://developers.google.com/web/tools/chrome-devtools/beginners/html

* https://developers.google.com/web/tools/chrome-devtools/beginners/css

* https://developers.google.com/web/tools/chrome-devtools/css/

#### Merge Conflicts

* How to check for your computers git configurations?

All students should configure their git: `git config --global core.editor "code --wait"`

This will open VS Code every time you have a merge conflict. A merge conflict is when git needs more information as to which code you want to be the "source of truth" and you have to manually go through the file and delete the code you don't want, and save the code you do want. After editing your files, do `git add .`, `git commit -m "resolving merge conflict"`, `git push` to update git and GitHub with the most recent code that you want to keep as your source of truth.

* https://github.com/eamoses/merge-conflict/tree/master/merge-conflicts-exercise

#### Work on Checkpoint 1

## TUESDAY - 12

### PRESENTATION: Selina Solis & Rekha Umashankar

#### THURSDAY: Lorianne Hutauruk

### Daily Logic

Walking up a steep hill, I pass 10 equally spaced street lamps. I take 5 seconds to walk from the first lamp to the second lamp, 6 seconds from the second lamp to the third, and so on, with each time increasing by 1 second as I slow down. How long do I take to walk from the first lamp to the last?

### What's Due?

* Blog Post 7: https://web.austincodingacademy.com/_book/04Week/01DayClass.html - **Due TONIGHT**

* Blog Post 8: https://web.austincodingacademy.com/_book/04Week/02DayClass.html - **Due Thursday 14th**

* Checkpoint 1: Widget Dashboard using CSS Grid AND a Media Query with an `Images` folder containing two wireframes (moble and tablet) - **Due Thursday 14th**

* Blog Post 9: https://web.austincodingacademy.com/_book/05Week/01DayClass.html - **Due Tuesday 19th**

### Portfolio.html Page

1. Draw your wireframes for both mobile and desktop
2. Dreate a new branch called `portfolio-page`
3. Be sure to include the use of: `<iframe/>` for your web pages and one youTube video (your preference)
4. Add a short video of you or something you like to a folder called videos
5. Use the `<video/>` tag to display the video
6. Build a banner for the top of this page with the <header/> tag
7. Build a `</form>` somewhere on the page that will take in:
  * email
  * name
  * location
  * message
  * with a reset button
  * with a submit button
8. Code for both mobile and desktop
9. Add, commit, push, PR and turn in.

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## THURSDAY - 14

### PRESENTATION: Lorianne Hutauruk

#### TUESDAY PRESENTATION: Austin Whitlock

### Daily Logic

A grocer places some oranges, peaches, apples and bananas in a row so that somewhere in the row each type of fruit can be found next to each other type of fruit. What is the smallest possible number of fruits in the row?

### What's Due?

* Blog Post 8: https://web.austincodingacademy.com/_book/04Week/02DayClass.html - **Due TODAY**

* Checkpoint 1: Widget Dashboard using CSS Grid AND a Media Query with an `Images` folder containing two wireframes (moble and tablet) - **Due TODAY**

* Blog Post 9: https://web.austincodingacademy.com/_book/05Week/01DayClass.html - **Due Tuesday 19th**

* Blog Post 10: https://web.austincodingacademy.com/_book/05Week/02DayClass.html - **Due Thursday 21st**

* Checkpoint 2: https://web.austincodingacademy.com/_book/checkPoints/02checkPoint.html - **Due Tuesday March 5th**

### Other Stuff

* I'll show my example code of getting files linked and images to show up regardless of where they exist in your file structure

* Checkpoint 2: https://web.austincodingacademy.com/_book/checkPoints/02checkPoint.html

### Creating our `aboutMe.html` and `contactMe.html` pages!

[Follow this link for instructions on creating your `About Me` and `Contact Me` html page](https://web.austincodingacademy.com/_book/05Week/02DayClass.html)

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## TUESDAY - 19

### PRESENTATION: Austin Whitlock

#### THURSDAY PRESENTATION: Juho Lee & Donald Morris

### Daily Logic

A pattern that repeats every six symbols starts as shown below:

♡ ♣ ♡ ♢ ♡ ♠ ♡ ♣ ♡ ♢ ♡ ♠ …

What are the 100th and 101st symbols in the pattern?

### What's Due?

* Blog Post 9: https://web.austincodingacademy.com/_book/05Week/01DayClass.html - **Due TONIGHT**

* Blog Post 10: https://web.austincodingacademy.com/_book/05Week/02DayClass.html - **Due Thursday 21st**

* Blog Post 11: https://web.austincodingacademy.com/_book/06Week/01DayClass.html - **Due Thursday 21st**

* Checkpoint 2: https://web.austincodingacademy.com/_book/checkPoints/02checkPoint.html - **Due Tuesday March 5th**

### CSS Animations

* (CodePen Animations Example)[https://codepen.io/emilyannemoses/pen/rPReOB]

* Keyframes hold what styles the element will have at certain times.

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## THURSDAY - 21

### PRESENTATION: Juho Lee & Donald Morris

#### TUESDAY PRESENTATION: Jessica Carvahal

### Daily Logic

Leonard writes down a sequence of numbers. After the first two numbers, each number is the sum of the previous two numbers in the sequence. The fourth number is 6 and the sixth number is 15. What is the seventh number in the sequence?

### What's Due?

* Blog Post 10: https://web.austincodingacademy.com/_book/05Week/02DayClass.html - **Due TONIGHT**

* Blog Post 11: https://web.austincodingacademy.com/_book/06Week/01DayClass.html - **Due TONIGHT**

* Blog Post 12: https://web.austincodingacademy.com/_book/06Week/02DayClass.html - **Due Tuesday 26th**

* Checkpoint 2: https://web.austincodingacademy.com/_book/checkPoints/02checkPoint.html - **Due Tuesday March 5th**

### CSS Transitions and Transformations

* Follow the curriculum instructions: https://web.austincodingacademy.com/_book/06Week/02DayClass.html

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## TUESDAY - 26

### PRESENTATION: Jessica Carvahal

#### THURSDAY PRESENTATION: Nurzat Nijat

### Daily Logic

In a sequence of positive integers, every term after the first two terms is the sum of the two previous terms in the sequence.

If the fifth term is 2004, what is the maximum possible value of the first term?

### What's Due?

* Blog Post 12: https://web.austincodingacademy.com/_book/06Week/02DayClass.html - **Due TONIGHT**

* Blog Post 13: https://web.austincodingacademy.com/_book/07Week/01DayClass.html - **Due Thursday 28th**

* Checkpoint 2: https://web.austincodingacademy.com/_book/checkPoints/02checkPoint.html - **Due Tuesday March 5th**

### JavaScript and the DOM

* `The Document`: In HTML, we type `doctype` to set the `document type declaration`. This is the `document` we're going to be manupulating with JAVASCRIPT!

* `DOM`: Document Object Model. This terminology refers to the way JavaScript will manipulate our HTML document using `class` and `id` within the HTML document.

* Yes, JavaScript *is* a programming language!

* Modern day browsers are built to be able to *enable* use of JavaScript within the HTML `document`. **Yes, it is possible to disable JavaScript in your browser!**

* Built-In JavaScript DOM methods: https://web.austincodingacademy.com/_book/07Week/01DayPrep.html

```
When constructing a website, consider the root functionality of HTML, CSS and JavaScript.

HTML: The bones of the site - the foundation, the wood framing, the shingles on the roof

CSS: The style of the site. What color are we painting the house? Will it be a round house or a square house? Will there be shutters and what color will they be? 

JavaScript: The functionality of the website. Are we going to install an automatic garage door? Will Alexa be able to turn on all of the lights in the house with one command? Will we install a Ring Doorbell to video record whomever is at our front door?
```

* What can we do in the Chrome Developer Console with JavaScript?

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## THURSDAY - 28

### PRESENTATION: Nurzat Nijat

#### TUESDAY PRESENTATION: Kyle Curtis & Alysia Lopez 

### Daily Logic

Pegs numbered 1 to 50 are placed in order in a line, with number 1 on the left. They are then knocked over one at a time following these rules:

Of the pegs which are still standing, alternate pegs are knocked down, starting with the one on the left.
Each time the end of the row is reached, repeat the previous rule.
What is the number of the last peg to be knocked down?

### What's Due?

* Blog Post 13: https://web.austincodingacademy.com/_book/07Week/01DayClass.html - **Due TONIGHT**

* Blog Post 14: https://web.austincodingacademy.com/_book/07Week/02DayClass.html - **Due Tuesday March 5th**

* Checkpoint 2: https://web.austincodingacademy.com/_book/checkPoints/02checkPoint.html - **Due Tuesday March 5th**

### jQuery: A JavaScript Libaray

* jQuery offers us "short cuts" to writing JavaScript for the DOM.

* You must include the jQuery CDN in your HTML file of your project in order for the DOM to recognize jQuery syntax (just like we did for Animate CSS and Font Awesome)

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## TUESDAY - 5

### PRESENTATION: Kyle Curtis & Alysia Lopez

#### THURSDAY PRESENTATION: Ju Hun Lee & Dan Brockman

### Daily Logic

Granny's watch gains 30 minutes every hour, whilst Grandpa's watch loses 30 minutes every hour. At midnight, they both set their watches to the correct time of 12 o'clock. What is the correct time when their two watches next agree?

### What's Due?

* Blog Post 14: https://web.austincodingacademy.com/_book/07Week/02DayClass.html - **Due TONIGHT**

* Checkpoint 2: https://web.austincodingacademy.com/_book/checkPoints/02checkPoint.html - **Due TONIGHT**

* Blog Post 15: https://web.austincodingacademy.com/_book/08Week/01DayClass.html - **Due Thursday March 7th**

### APIs: Geolocation

### Using Forms

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## THURSDAY - 7

### PRESENTATION: Ju Hun Lee & Dan Brockman

#### TUESDAY PRESENTATION: Did I miss anybody?

### Daily Logic

Luis writes down seven consecutive positive integers. The sum of the three smallest numbers is 33. What is the sum of the three largest numbers?

### What's Due?

* Blog Post 15: https://web.austincodingacademy.com/_book/08Week/01DayClass.html - **Due TONIGHT**

* Blog Post 16: https://web.austincodingacademy.com/_book/08Week/02DayClass.html - **Due Tuesday March 12th**

### Introduce Checkpoint3

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## TUESDAY - 12

### PRESENTATION:

### Daily Logic

Build a function that when given two numbers will return the sum and which of the two inputs is greater.

### What's Due?

* Blog Post 16: https://web.austincodingacademy.com/_book/08Week/02DayClass.html - **Due TONIGHT**

* Blog Post 17: https://web.austincodingacademy.com/_book/09Week/01DayClass.html - **Due Thursday March 14th**

### JavaScript Data Types

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...

## THURSDAY - 14

### PRESENTATION:

### Daily Logic

Given an array of numbers, return the array in reverse order

```javascript
const myArr = [6, 5, 2, 1]

reverseOrder(myArr) => 1, 2, 5, 6
```

### What's Due?

* Blog Post 17: https://web.austincodingacademy.com/_book/09Week/01DayClass.html - **Due TONIGHT**

* Blog Post 18: https://web.austincodingacademy.com/_book/09Week/02DayClass.html - **Due Tuesday March 19th**

### JavaScript Conditional Statements and Loops

### Git Flow Reminder

* `git checkout master` OR `gh-pages` (whichever is your origin)
* then `git pull` changes,
* create a new branch `git checkout -b new-branch`
* make changes in VS code & save,
* `git add .` then...
* `git commit -m "add a detailed message"`
* `git push -u origin new-branch` them up to the remote repo on GitHub
* `git checkout master` OR `gh-pages` to switch back to origin branch
and do it all over again...
