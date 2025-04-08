# Frontend Mentor - Time tracking dashboard solution

This is a solution to the [Time tracking dashboard challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/time-tracking-dashboard-UIQ7167Jw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Switch between viewing Daily, Weekly, and Monthly stats

### Screenshot

Desktop design:
![](./design/desktop-design.jpg)

Mobile design:

![](./design/mobile-design.jpg)

Active states:
![](./design/active-states.jpg)

### Links

- Solution URL: [solution URL here](https://github.com/ernur-burshak/Time-tracking-dashboard)
- Live Site URL: [live site URL here](https://ernur-burshak.github.io/Time-tracking-dashboard/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS grid
- Flexbox
- Mobile-first workflow
- JS
- Data in json format

### What I learned

In this tutorial, I've been learning a lot of things, especially extracting data from json

```js
let data = [];

async function loadData() {
  const response = await fetch("data.json");
  const fetchedData = await response.json();
  data = fetchedData;
  buttons[1].click();
}
```

understood the difference between () []

```js
const timeframeData = activity.timeframes[clickedOption];
const previousTimeframe = calcTimeframe(clickedOption);
```

I found out about the append() method

```js
activityTracker.append(section);
```

### Continued development

In the future, I want to work with larger projects and study the React JS framework.

### Useful resources

- [resource 1](https://www.youtube.com/watch?v=l9Qw8y3LfCY) - This channel helped me to work with the project.
- [resource 2](https://chatgpt.com/) - Good AI for writing projects.

## Author

- Website - [Ernur](https://ernur-burshak.github.io/Time-tracking-dashboard/)
- Frontend Mentor - [@ernur-burshak](https://www.frontendmentor.io/profile/ernur-burshak)
- Linkedin - [Ernur Burshak](https://www.linkedin.com/in/ernur-burshak-7b6b0b31b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

## Acknowledgments

I would like to express my gratitude to the author of the channel @GrizhlieCodes. Without him, I suffered greatly from the task, the code is almost similar, but I made minor changes. Thank you!
