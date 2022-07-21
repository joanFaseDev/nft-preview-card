# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### The challenger

Hi everyone! First and foremost i want you to know that english isn't my first language and, even if i do try to make myself clear and explain my process as well as possible, there's still a high chance i'll do mispellings or grammatical errors. If that happen, please forgive me. 

That being said, this is my fourth project from Frontend Mentor. You should know i'm an aspiring front-end developper which means i'm not a very good source to learn web development. Yet, i do my best to tackle each project seriously and explain my thought process so that maybe one day it could be of some help to someone. It's also important to me because i want to be able to come back to these README files to see my progress / search references / take a different approach / etc

Sorry for the long introduction. Without further delay, let's dig in!

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Project on GitHub](https://github.com/joanFaseDev/nft-preview-card)
- Live Site URL: [Projet hosted through Vercel](https://nft-preview-card-beta-jet.vercel.app/)

## My process

### Planning

This challenge is about reproducing a card promoting some kind of NFT. There's two designs to display (mobile and desktop one) but, upon closer inspection, it appears that the two designs are almost identicals (some tiny changes in padding/margin but nothing more i could see). It's important because that means the page is almost non responsive and so there's no real need to use media queries and relative length units. Yet these units, rems, ems, percentages and the like, are the ones mostly used today (because they help building this responsive side every web page should have) and i don't want to lose an opportunity to handle them in a project so i'll go with it.

My plan is to use CSS Grid here. It's probably too much considering the simple design of the card but i really want to get better at using the grid and this kind of project seems perfect to get the hand of it. One grid made of one column and three rows. I'll change the second row in a flexbox container to align the various items inside.  

Not much more to say about the content; as for the card it seems to have a very large shadow. Not sure if we're supposed to reproduce that but i'll play a bit with the *shadow-box* property and see what i can do.

### Built with

- HTML
- CSS 
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [MDN Article focused on the aria role 'article'](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/article_role) - This helped me to further inquire about accessibility in web developpement and the various ways developpers can tweak their codes to improves the experience of people using assisting technologies.
- [Fundamental concepts of Aria, its purpose and how to use it](https://w3c.github.io/aria-practices/) - W3C's draft about accessibility and Aria's concepts. I obly read part of it but i put the link here because i feel most of my questions about accessibility have theirs answers inside.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
