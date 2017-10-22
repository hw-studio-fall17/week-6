# WEEK 6: Practice

#### Look at the HTML in `index.html`
* Look at the `id` on the `<body>`
* Inside the `<body>` there is a `<div>` with the `id` "box" on it

#### Look at the style in `style.css`
* Answer the question in `style.css`

#### In `script.js` 
###### Let's make our box slowly fade in to the page!
* Select the box by it's `id` using jQuery and save it as a variable called `box`. Look at the example below:
  ` var exampleVariable = $("#example-id") `
* In order to make the box fade in we first have to hide it. Use the jQuery `hide()` function to hide your `box`. It will look something like this example below.
  ` exampleVariable.hide() `
* Now we can use the jQuery function `fadeIn()`. Your javascript will look something like this:
  ``` exampleVariable.hide()
      exampleVariable.fadeIn()
  ```
* To make it fade in very slowly try passing a number in the () of the `fadeIn()` function. This number represents how many miliseconds it takes for the box to fadeIn(). Try `fadeIn(4000)`.

### BONUS in `style.css`
* What does the .7 do in `rgba(250, 250, 250, .7)`? What happens if you change it to .3?
* How did we make the background color transparent? 
* Try to make it a transparent blue instead (or any other color!). 
  * You will be able to pick an rgb value here [hex color picker](https://www.google.com/search?q=hex+color+picker&oq=hex+color+picker&aqs=chrome..69i57j0l5.4535j0j4&sourceid=chrome&ie=UTF-8)
* What does the padding line do? What happens if you make the number bigger? What happens if you make the number smaller?

