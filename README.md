# 20-11-12 CSS HTML Forms Primary

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode

### Linking files
1. create an HTMl file called `index.html`
2. create a css file called `style.css`
3. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
4. check that the file is linked by setting the `background-color` property of the body to any color other than white/gray and open the HTML file using `ctrl o` in the browser

### Assignment
Recreate the wireframe provided by following th steps below. Use CSS grid to layout elements on the page.

#### Content
1. Create a heading with the text `Pine Co-Working` and a smaller heading with the text `Create You Account`
1. Render [this](https://images.unsplash.com/photo-1504297050568-910d24c426d3?ixlib=rb-1.2.1&auto=format&fit=crop&w=334&q=80)
1. Render the form mimicking the wireframe
    - submit to `postman-echo.com/get`
    - required first and last name text inputs with associated labels
    - required email input with associated label
    - business text input with associated label
    - select element with six options (unselected, instagram, facebook, YouTube, word of mouth, and print ad) and associated label
    - text above checkbox inputs with associated labels
    - required date input with associated label
    - text above radio inputs with appropriate name attributes and associated labels
    - submit button and reset button

#### Styling
1. use grid layout to position the image to the left slightly less wide than the form, 100% of the parent's width and with space to the left
1. use grid layout to position the form to the right slightly wider than the image and with space to the right
1. optionally use a google font to style the text `Pine Co-Working`
1. center align both headings above the image and form
1. style the form with a black border and space between the content and the border
1. style each grouping of inputs/labels with space on the top and bottom, mimicking wireframe
1. style each input with a gray rounded border and padding on the top and bottom, mimicking wireframe
1. center align the radio button grouping and the submit and reset buttons using a class selector
1. style the submit and reset buttons background color and font color using id selectors mimicking wireframe 

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)
