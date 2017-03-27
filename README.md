# Checkpoint 01

## Instructions

1. Fork this repo.
2. Clone your fork.
3. Follow the instructions.
4. Make one commit for each question.
5. Open a pull request to this repo.

If you finish early, try tackling the [Moonrise Kingdom exercise](https://github.com/ga-wdi-exercises/moonrise_kingdom/blob/master/sam_registration.jpg).

--------------

## HTML

### #1

Open up `index.html` in a text editor and browser. Link to the provided stylesheet.

> Commit

### #2

Identify one non-semantic tag and replace it with a semantic one.

> Commit

### #3

Something about the image tag is incorrect. Fix the error.

> Forgot the alt tag

### #4

Change the title of the page. Specifically, change what shows in the tab of the page (i.e., at the top of the browser).

> Commit

### #5

Set the margin to 0 for each direct child of:

- `header`
- `footer`
- `.main`
- `aside`

> Commit

### #6

If you inspect the `.left` and `.right` elements, you will see that they have `width: 50%;` and `float: left`. However, they are not sitting next to each other.

Fix this issue without modifying any of `.left` and `.right`'s `padding`, `border`, or `width`.

> Commit

### #7

When the page is fewer than 600px wide, the background of `.main` turns red.

Instead of making `.main` red, reorder the elements to...

1. Header
2. Main
3. Aside
4. Aside
5. Footer

Do this using only CSS -- do not rearrange the HTML.

> Commit


### #8

Open up `workflow.txt`

Rearrange the lines to identify the correct workflow for submitting a pull request on a non-master branch.

Remove the lines that are not required in this workflow.

> Cofork on github
git clone
git checkout -b my-solution
git checkout master
git add .
git commit -m ""
git push origin my-solution
git fetch --all
git pull upstream master
git merge my-solutionmmit
