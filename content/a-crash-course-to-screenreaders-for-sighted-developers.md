---
title: Getting Started with Screen Readers as a Sighted Developer
image: /images/grammo.jpg
imageMeta:
  attribution:
  attributionLink:
  alt: A black and white drawing of an old grammophone displayed six times next to one another
featured: true
authors:
  - jj
date: Mon Jun 28 2019 20:13:53 GMT+0200 (Central European Summer Time)
tags:
  - accessibility
  - screenreader
  - testing
---

some intro stuff that's interesting to keep them users reading

## What Is a Screen Reader Exactly?

A screen reader is a form of assistive technology that is oftentimes used by blind, visually impaired website visitors as well as those who have a learning disability or who are illiterate. Screen readers can at times be essential for users to be able to navigate the web and to discover relevant content on websites which is consumed to a large part visually by sighted users.

Even though there are different modi of screen readers available and used by the internet community, the most popular types of device is the text-to-speech screen reader.

## The Problem with Being Sighted and Not Knowing How a Screen Reader Works

With a near perfect (either corrected or not) vision, you might never feel the need to use a screen reader when browsing the internet. So obviously, there's no need for you to understand how screen readers work or how to use one, is there?

As a person who develops sites and applications on the web, it might already be second nature to you to make sure that the websites that you're building work as expected for your users. Checking that a web app runs fine for different user flows or that its design looks as expected is crucial and part of your daily routine at work when delivering a feature. Imagine how difficult it would be to deliver a bug fix for a misaligned navigation bar on a site without having a single glance at your screen. The visual check feels crucial to confirm that your fix for this styling issue is functional.

Is there any valid reason why a functional check would not be needed when fixing accessibility issues for the websites you're building? To be able to manually test websites for accessible concerns, getting familiar with the basics of screen readers is essential to understand how users of assisstive technology experience the site.

## Where to Find a Screen Reader

Today there are plenty of text-to-speech screen readers available, which differ in the way they evaluate web pages. If you want to learn more about how a screen reader works under the hood and which implications this has on different behaviours of screen readers, you should read [this excellent blog post](https://marcozehe.wordpress.com/2013/09/07/why-accessibility-apis-matter/) by accessibility platform engineer [Marco Zehe](https://twitter.com/MarcoInEnglish).

If you're just looking for a free screen reader to get started, you can check out [**Voice Over**](https://www.apple.com/accessibility/mac/vision/) (Mac OSX), [**NVDA**](https://www.nvaccess.org/download/) (Windows) or [**Orca**](https://help.gnome.org/users/orca/stable/)(Linux).

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

### Handy VoiceOver Short Cuts for Site Navigation

The vast majority of short cuts in VoiceOver are a combination of the `Control` + `Option` key combo and another key. Navigate forwards (jump to the next element) using these key combinations:

- navigation between interactive controls: `Tab`
- navigation between headings: `Control` + `Option` + `H`
- navigation between lists: `Control` + `Option` + `X`
- navigation between tables: `Control` + `Option` + `T`
- navigation between graphics: `Control` + `Option` + `G`

Use the `Shift` key in addition to the controls mentioned above to jump back to the previous element of the same kind.

### Quick Access to Short Cuts Using the VoiceOver Rotor

The VoiceOver rotor feature allows sighted screen reader users to...





## Testing Websites Authentically
