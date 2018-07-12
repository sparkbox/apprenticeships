[← Back to Index](../index.md)

# Frontend Mini Project - Event Cards

## Week 1 - HTML

Think of a really cool event: a concert, art show, festival, play, performance, meet-up, or anything else one may wish to attend. We want to get the word out about this awesome thing, so we are going to build some "digital flyers," or event cards.

What sort of information would you want to know? How about:
- Title of event or Band name
- Picture of the band or location
- Location of the event
- When it is
- Link to the website of the band, festival, or where you can buy tickets

We want to build these cards with the following in mind:
- A "Card" is a small piece of a website, not usually the whole page. We'll probably want to put multiple cards on the final page.
- Put things in the order that makes the most sense for HTML.
- Research semantic tags for each item; it is unlikely you'll be using `<div>` very often, but you may decide that it's the best choice some places.
- Creating [accessible elements may require additional attributes](https://www.w3.org/WAI/standards-guidelines/wcag/).
- Inline comments are helpful for reminding yourself why you made a decision you made.
- Focus on semantically strong, accessible Markup. Styles will come later, and if you do them now, we'll probably completely ignore them anyway.

Next week we will spend 5 minutes or so going over the HTML choices each of you have made. Try to do this individually (not as a group). Please do take advantage of office hours or pairing with developers!

## Week 2 - CSS

This week, you've been given a single event card to style with _vanilla_ CSS. Using the HTML you've already written (and adapted where necessary), try to get as close to the design as possible by next Thursday!

I really encourage you this week to make time to pair with Frontend Designers, as well as the rest of the frontend-focused team members mentioned before. Another awesome resource is [MDN](https://developer.mozilla.org/en-US/).

Next week we will spend 5 minutes or so going over the CSS choices each of you have made. Try to do this individually and not as a group.

## Week 3 - Layout

In addition to the individual card improvements we've asked you to do, your next task is to create a grid layout with your event cards. This layout should be [responsive](https://responsivedesign.is/), developed with a [mobile first](https://vimeo.com/38187066) frame of mind, and all content should be browser tested to the specifications in our [browser testing documentation](projects/proj-browser-testing.md).

*Note*: This is a big ask. It's not fun. It won't be perfect. You don't have the full resources of a design team. Do the best you can, but don't burn out. If there is interest, we can do a 'bug bash' together, to learn about the device wall and [BrowserStack](https://www.browserstack.com/start).

If you want bonus points, find an open source svg icon library you like for later use.

*Note*: For this task, we can utilize Codepen's native features to link pens together.

To include the HTML from another pen, add the pen url, surrounded by three brackets.
```html
[[[https://<url to your event card>]]]
```

You will also need to link to your pen as an external css resource by going to *Settings -> CSS - > Add External Stylesheets/Pens* and adding the URL of your card.

## Week 4 - BEM + IMG

Your homework this week is comprised of a few smaller tasks.

#### BEM
From this point forward, you'll be expected to use BEM for any CSS and HTML you write. Fork your Grids and refactor all of your classes to use BEM. Then, pair with one of our BEM devs to review your *finished* BEM.

#### SVG or `srcset`
Spend some time playing with images or SVGs. Fork and update your event card to use either an SVG icon (Next to your address or phone number is nice, or whatever you like) OR update your images to use `srcset`.

#### Personal Websites
It's about the time in your apprenticeship when you should be looking to find a permanent web development role (if you are interested in that sort of thing). In your [career prep sessions](../phases/x-job-prep.md), you've hopefully developed skills to help you improve your marketability. Spend some time reworking or redoing your personal websites, cleaning up your git profiles, etc. We're here to help, so pair!  Remember to take advantage of pairing time not only with developers, but also with our wonderful Project Management, Content, and Design teams.

## Week 5 - Sass

Homework this week is short! Refactor your cards into Sass (SCSS).
Pair with one of our Sass devs during the next week or so to go over it. (I recommend messaging them _today_). *Note*: CSS is fully functional and semantically correct SCSS!
