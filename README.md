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

### PRESENTATION: Dan Brockman & Andy Fogarasi

#### TUESDAY PRESENTATION: Devin Gibbons

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

* `git checkout master` OR `gh-pages`
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

### Work on Checkpoint 1, Chrome Dev Tools, Merge Conflicts

#### Chrome Dev tools follow along

#### Merge Conflicts

All students should configure their git: `git config --global core.editor "code --wait"`

This will open VS Code every time you have a merge conflict. A merge conflict is when git is confused as to which code you want to be the "source of truth" and you have to manually go through the file and delete the code you don't want, and save the code you do want. After editing your files, do `git add .`, `git commit -m "resolving merge conflict"`, `git push` to update git and GitHub with the most recent code that you want to keep as your source of truth.

#### Work on Checkpoint 1
