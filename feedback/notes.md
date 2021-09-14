# Feedback

_Right click on the file and click Open Preview or `ctrl/cmd + shift + v` to open preview_

## Goals

1.  Working portfolio:

    - For a working portfolio, you are pretty much done.
    - Consider moving your social media links above the form In terms of hierarchy they are more important.

2.  Practice using Git / Github Flow:

    - You got good practice creating branches and committing. Some of your commits could be more descriptive. That comes with more practice so keep it up.

3.  Application of morning topics
    - Yes so far I can see everything we have covered so far. You class naming conventions get a little bit messy towards the end but I will go into this more at the end.

---

## Specification

1. README - done

- Get use to adding these into all of your projects, you will want to add a little spiel about the project in there as well.
- If you are adding links in a md file you can do it like this [example link](https://www.markdownguide.org/basic-syntax/#links) rather than a URL.

2. BRANCHING - done

   - Try a focus on what you are doing once you are done add commit etc then move onto the next part.

3. SCSS - done

   - Keep on exploring SCSS, look at mixins and other features the pre processor will give you.
   - Put all of your SCSS files and folders in a SCSS folder to keep it organized.
   - You have broken down your SCSS files which is great you need to work on the split between layout and components though.

4. Mobile First - done

   - With your media queries you only need to target the properties that need to change. You do have some code duplication in your media queries.

5. 25 commits - done

6. BEM - to work on

---

## Overall

As I said during the demo I think you have relished the chance to apply what we covered in the morning into your project. It is pretty much done and looks great. I think the time pressure probably made you rush towards the end. I am sure you will be aware of this when you work on your next project. I am going to give you some constructive feedback to take on to this project and to take forward to your next projects.

---

## To work on

I think you just need to work naming with BEM, you are using well at the start of the file but towards the end probably because of time it gets a little bit messy.

For BEM:

- Have a read of the [BEM docs](http://getbem.com/naming/).
- Do a little refresher with [Kevin Powell](https://www.youtube.com/watch?v=SLjHSVwXYq4)

Your code below.

```html
<section class="mainbg contact-details">
  <h2>Details</h2>
  <a class =contact-me__email" href="mailto:hooper.rob@gmai.com">hooper.rob@gmail.com</a>
  <p class ="contact-me__phone">07796235237</p>
  <div class="contact-images">
    <a class="linked-in" href="https://www.linkedin.com/in/rob-hooper-74039519/"><img  src="/assets/linkedin-icon.svg" alt=""></a>
    <a class="github" href="https://github.com/hoopercode"><img src="/assets/githubfinal.svg" alt=""></a>
  </div>
</section>  
```

Could be.

```html
<section class="contact-details">
  <h2 class="contact-details__header">Details</h2>
  <a class =contact-details__email" href="mailto:hooper.rob@gmai.com">hooper.rob@gmail.com</a>
  <p class ="contact-details__phone">07796235237</p>
  <div class="contact-details__icons">
    <a class="contact-details__icon contact-details__icon--linkedin" href="https://www.linkedin.com/in/rob-hooper-74039519/">
      <img  src="/assets/linkedin-icon.svg" alt="">
    </a>
    <a class="contact-details__icon contact-details__icon--github" href="https://github.com/hoopercode">
      <img src="/assets/githubfinal.svg" alt="">
    </a>
  </div>
</section>  
```

With GIT:

- Break your jobs down and Write a list of todo's
- Treat each one as a commit, you go in do that one thing commit and then move onto the next.

Portfolio Structure:

- Put all the SCSS inside its own folder

