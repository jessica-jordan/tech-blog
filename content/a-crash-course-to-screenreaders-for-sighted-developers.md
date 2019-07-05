---
title: An Intro To Screen Reader Testing for Sighted Developers
image: /images/grammo.jpg
imageMeta:
  attribution:
  attributionLink:
  alt: A black and white drawing of an old grammophone displayed six times next to one another
featured: true
authors:
  - jj
date: Fri Jul 5 2019 18:30:53 GMT+0200 (Central European Summer Time)
tags:
  - accessibility
  - screenreader
  - testing
---

Besides the design, loading time and performance, **accessibility** determines the user experience of the web apps that you're building profoundly. This quick guide will give you an introduction to the why and how of testing your website's user experience using screen readers.

## What Is a Screen Reader Exactly?

A **screen reader** is a form of **assistive technology** that is oftentimes used by blind, visually impaired website visitors as well as those who have a learning disability or who are illiterate. Screen readers can at times be essential for users to be able to navigate the web and to discover relevant content on websites which is consumed to a large part visually by sighted users.

Even though there is a range of different modi of screen readers used by your website's audience, the most popular types of device is the **text-to-speech** screen reader which this article is focussing on.

## Why You Should Know How A Screen Reader Works When You Are Sighted

With a near perfect (either corrected or not) vision, you might never feel the need to use a screen reader when browsing the internet. So obviously, there's no need for you to understand how screen readers work or how to use one, is there?

As a person who develops sites and applications on the web, it might already be second nature to you to make sure that the websites that you're building work as expected for your users. Checking that a web app runs fine for different user flows or that its design looks as expected across a range of browsers is crucial and might already be part of your daily routine at work when delivering a feature. Now imagine how difficult it would be to deliver a bug fix for a misaligned navigation bar on a site without having a single glance at your screen. The visual check turns out to be important to confirm that your fix for this styling bug addresses the issue, is functional and works fine in different browsers.

Thinking about bugs that concern accessibility, is there any valid reason why a functional check would not be needed to address issues and provide valid bug fixes? Manually testing the accessibility of the websites you're building is insightful and can be the most valuable confirmation that the patches you deliver to improve its usability actually work just as expected.

To be able to manually test websites for accessibility concerns, getting familiar with the basics of screen readers is essential to understand how users of assistive technology experience your site.

## Where to Find a Screen Reader

Today there are plenty of text-to-speech screen readers available, which differ in the way they evaluate web pages. If you want to learn more about how a screen reader works under the hood and which implications this has on different behaviours of screen reader and browser combinations, you should read [this excellent blog post](https://marcozehe.wordpress.com/2013/09/07/why-accessibility-apis-matter/) by accessibility platform engineer [Marco Zehe](https://twitter.com/MarcoInEnglish).

If you're looking for a free screen reader to get started, you can check out [**Voice Over**](https://www.apple.com/accessibility/mac/vision/) (Mac OSX), [**NVDA**](https://www.nvaccess.org/download/) (Windows) or [**Orca**](https://help.gnome.org/users/orca/stable/)(Linux).

## Getting Familiar with the Screen Reader of Your Choice

Since shortcuts between screen readers and operating systems differ, it is necessary to familiarise yourself with some of the most important shortcuts to navigate websites by reading their documentation.

What you'd like to know more about are the controls for jumping between

- interactive controls (e.g. hyperlinks or form elements)
- headings
- lists
- tables
- graphics

and how to activate form controls or links. Being comfortable with utilising this set of controls you should already be ready to navigate and explore web pages using the keyboard and a screen reader in tandem.

## Navigation Basics for Using VoiceOver

In case you're working with VoiceOver you can memorise a set of short cuts to get started with navigating web pages or alternatively, you can also use a more visual interface to switch between navigation of different kinds of elements smoothly.

### Useful VoiceOver Short Cuts for Site Navigation

The vast majority of short cuts in VoiceOver are a combination of the `Control` + `Option` key combo and another key. Navigate forwards (jump to the next element) using these key combinations:

- navigation between interactive controls: `Tab`
- navigation between headings: `Control` + `Option` + `H`
- navigation between lists: `Control` + `Option` + `X`
- navigation between tables: `Control` + `Option` + `T`
- navigation between graphics: `Control` + `Option` + `G`

When on a website, you can navigate between elements in their hierarchical order as indicated through the HTML markup using `Control` + `Option` + the left / right arrow keys.

Finally, use the `Shift` key in addition to the controls mentioned above to jump back to the previous element of the same kind.

### Quick Access to Navigation Elements Using the VoiceOver Rotor

The **VoiceOver rotor** feature provides a way to skim through different types of navigation elements quickly. Especially for sighted users the graphic user interface of this util comes into handy to have an overview of the navigation options when you do not have a cheat sheet at hand.

To use it, press `Control` + `Option` + `Command` and navigate in between the different categories using the left and right arrow keys:

![Screen recording of the clock-like VoiceOver Rotor interface and the selection arrow switching between the categories: Landmarks, Headers, Links, etc.](/images/voiceover-demo-1.gif)

Once a category has been selected, flip through all elements of that respective category using the up and down arrow keys in combination with `Control` + `Option` + `Command`:

![Screen recording of the VoiceOver Rotor interface and showing you can skip through different elements of the Landmarks category](/images/voiceover-demo-2.gif)


## Testing Websites Authentically

Testing websites using a screen reader will be a powerful method for asserting that the websites you're building are accessible to everyone. Once you feel more familiar with keyboard controls and your screen readers' short cuts, I highly recommend to test your websites as close to your site's user experience as possible: with the screen shut off.

While you're testing your website without any visual feedback, find out for yourself how easy or hard it is to find your page's main navigation. How easy is it to skim through your site's headings? Do you find it straightforward to navigate to the following page?

I hope this quick guide to using screen readers for sighted developers has been helpful for you to understand the importance of screen reader-driven user testing and how it will help you to create a better understanding for the accessibility of the applications you're building.

Questions? Suggestions? Send me an [email](mailto:me@jessicajordan.de) or ping me on [Twitter](https://twitter.com/jjordan_dev) ✨

## Sources

- [WEBAIM: Using VoiceOver to Evaluate Web Accessibility](https://webaim.org/articles/voiceover)
- [Marco Zehe: Why Accessibility APIs Matter](https://marcozehe.wordpress.com/2013/09/07/why-accessibility-apis-matter/)
