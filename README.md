# Paris' About Me

## Motivation

Hello, World! I'm Paris. But, if you got this far, you probably knew that. Welcome to my readme.

As context, this is the first website I've custom designed and developed, and I'd like to take you through my process. This particular project was assigned by the talented instructors at General Assembly. I earned a scholarship from Adobe to attend their Digital Academy program in San Francisco, CA. It's a 12 week, full-time, full-stack coding bootcamp through General Assembly, and subsequent 3 month Adobe engineering apprenticeship. The future is bright and I couldn't be more thankful to work alongside a team of brilliant peers.

Cheers!

#### Project Requirements

- Use semantic markup for HTML and CSS, adhering to best practices.
- Use Flexbox/Grid to create a multi-column layout.
- Be completely responsive.
- Include separate HTML/CSS/JavaScript files.
- Stick with the KISS (Keep It Simple Stupid) and DRY (Don't Repeat Yourself) principles.
- Use JavaScript or jQuery for DOM manipulation.
- Be deployed and accessible online.

#### Project Deliverables

- Hosted on my personal GitHub
- GitHub includes a link to your hosted site and frequent commits dating back to the beginning of the project
- A README.md file with explanations of: process/approach, technologies used, biggest wins and challenges, unsolved problems
- Screenshots of the snippets of code used to solve particularly interesting problems 
- A carousel whose images slide to the side on a timer, along with indicators that the user can click to navigate to a particular project.
- Functionality that allows a carousel image to enlarge in a lightbox when the user clicks on it. Clicking anywhere on the screen when the lightbox is open should close the lightbox
- Nav bar functionality that allows the page to scroll smoothly to the correspending section when a nav item is clicked
- Nav bar functionality that highlights a nav item when the user scrolls to the corresponding section of the page
- A testimonials section in which testimonials rotate in and out on a timer
- A mobile nav that expands and collapses when a user clicks on the hamburger icon
- An in-class demo of the site

Personal Deliverables:
mobile: 
- 1 primary color and 2 accent colors
- Modern font 
- nav bar is hamburger menu or similar
  - shows or drops down menu when clicked
- Brief, concise, about me
- Carousel for project photos
- Testamonials
- Contact Form


Tablet & Desktop:
- - 1 primary color and 2 accent colors
- Modern font 
- Brief, concise, about me
- Carousel for project photos
- Testamonials
- Contact Form

## My Process

- Research
  - Sites of people I admire in the creative or developer space
- Low-fidelity wireframes in balsamiq
- Built containers and rows
  - addded borders to help visualize structure 
- Map out what tools will be required to make vision a reality
- Refine content strategy
- Build basic HTML with bootstrap
- Build basic CSS 
- Build basic javascript/jquery
- Refine design
- Finalize responsiveness 
- Interactivity
- Complete Readme
- Prep for possible presentation 


## Technology Used (with explinations)

- HTML, CSS, Javascript, bootstrap, jQuery, typed.js

```html
HTML was created mostly with bootstrap to provide basic structure and clean carousels and modals.

```

```css
I think the most interesting thing was the smooth scroll functionality achieved with css rather than js. 

```

```js
Lightbox was my most complex script but typed.js was the most interesting to me. 
```
## Features
- my website features clean scrolls, pleasant styling, and a few js libraries to manage animations and effects.


## Big Wins & Challenges
  - I decided to use both bootstrap and minified. Bootstrap for a quick overall structure and minified for it's carousel. Which meant conflicting css and javascript. So I extracted only the css that directly affected the carousel structure. Then I found every instance of `carousel` in the javascript and changed it's class to `carousel1`to give it a unique class that wouldn't interfere with any other code.

  After some consideration, I thought it best to remove the potentially conflicting libraries, to adhere to best practice

  It was both easier and harder using bootstrap. It wasn't an easy process to design and implement a website that I would stand behind. I'm proud of the way it turned out.


## Unsolved Problems
- Still learning how to submit emails via form. But email functionality wasn't an explicit deliverable, so I'd like to review that with the instructor.


## Code Snippets
- I really like the way this particular part of the about me turned out:
	<p >Recipient of the 2019 <a href="https://www.adobe.com/corporate-responsibility/education/digital-academy.html">
        <strong>Adobe Digital Academy</strong></a> scholarship; a competitive software bootcamp and apprenticeship for 
        exceptional minority talent across the nation.
      <br>
      <br>
  
## Credit and License
- lightbox - https://lokeshdhakar.com/projects/lightbox2/
- typed - https://github.com/mattboldt/typed.js
