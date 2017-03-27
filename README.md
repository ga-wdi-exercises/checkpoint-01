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

--- full link code added into the html document "  <link rel="stylesheet" type="text/css" href="style.css""

### #2

Identify one non-semantic tag and replace it with a semantic one.

 ---- replaced the non-semantic div tag with a semantic table tag

### #3

Something about the image tag is incorrect. Fix the error.

--- alt tag was added to describe what the image was of the tag

### #4

Change the title of the page. Specifically, change what shows in the tab of the page (i.e., at the top of the browser).

--- a title tag was added to the site.

### #5

Set the margin to 0 for each direct child of:

- `header`
- `footer`
- `.main`
- `aside`

--- a css code was added that changes the margin of the direct child tags for the elements listed above:
""}
header, footer, aside, .main > span{
  margin: 0;
} ""


### #6

If you inspect the `.left` and `.right` elements, you will see that they have `width: 50%;` and `float: left`. However, they are not sitting next to each other.

Fix this issue without modifying any of `.left` and `.right`'s `padding`, `border`, or `width`.

--- "a css code was added to the .left and .right "  display:inline-block;""

### #7

When the page is fewer than 600px wide, the background of `.main` turns red.

Instead of making `.main` red, reorder the elements to...

1. Header
2. Main
3. Aside
4. Aside
5. Footer

Do this using only CSS -- do not rearrange the HTML.

--- In the css "media element" the red effect was removed and a width and margin setting was added so all the html elements will populate in order.


### #8

Open up `workflow.txt`

Rearrange the lines to identify the correct workflow for submitting a pull request on a non-master branch.

Remove the lines that are not required in this workflow.

--- the following steps were re-ordered and remained:
fork on github
git clone
git add .
git commit -m ""
git push origin my-solution
