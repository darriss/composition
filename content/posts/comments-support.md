---
title: Arabic Glossary
subtitle: Add Comments to Posts With Disqus
category:
  - Third Party Integrations
author: Daniel Kelly
date: 2019-07-24T19:59:59.000Z
featureImage: /uploads/disqus-hero.jpg
---
Disqus brings the power of commenting to the Awake template. It provides features like moderation, reactions, filtering, and social sharing out of the box. Best of all, it's free and super easy to setup!

## Step 1

Go to disqus.com and click on "Get Started"

![Screenshot of Disqus homepage](/uploads/disqus-get-started.jpg)

## Step 2
| Arabic | English                                                                   |
| ------ | ------------------------------------------------------------------------- |
| مَقْبول  |                                                                           |
| تَرتيب  |                                                                           |
| رَتَّبَ    |                                                                           |
| مُناسِب/ة  مْناسِب/ة|                                                                  |
| صاحِب   |                                                                           |
|شَجَّعَ على ،يُشَجَّعو التَّشْجيع  |                                                         |
|بِنْت خال/ة |                                                                         |
|الثَّقافة |                                                                           |
|قَرار    |                                                                           |
|الطَّلاق   |                                                                           |
|التَعليم |                                                                           |
|خُطِبَت لِ  |                                                                           |
|خَطيب/ة  |                                                                           |
|أموال ، مالِيّ/ة |                                                                    |
|تَعَرَّفَ على |                                                                          |
|حُكومة   |                                                                           |
|تُراث    |                                                                           |
|زَوْج     |                                                                           |
|دعا، يَدعو|                                                                          |
|الحُبٌ، أَحَبَّ، يُحِبّ |                                                                    |
|تعارُف   |                                                                           |
|مُتَزَوَّج   |                                                                           |
|المَعْرِب  |                                                                           |
|حَماة    |                                                                           |
|حَفْلة    |                                                                           |
|فَتير    |                                                                           |
|غَنِيّ     |                                                                           |
|عُرس     |                                                                           |
|وَثِقَ "ب" أو "في"   |                                                                 |
|مَخزَن    |                                                                           |
|        |Quran                                                                      |
|        |marriage                                                                   |
|وَلِيّ‎     |guardian                                                                   |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |
|        |                                                                           |

![Disqus button "I want to install Disqus on my site"](/uploads/disqus-add-to-website.jpg)

## Step 3

Sign-up or sign in

## Step 4

Enter site name, Disqus URL and select a category. The Disqus URL name is your site’s name in your account where you can access all the required settings.

## Step 5

Select a plan. There are several premium versions available, but don't worry the free one works just great too!

## Step 6

Disqus supports a number of different platforms but also works great in static sites like Awake. Scroll to the very bottom of the list and choose: "I don't see my platform listed, install manually with"

![Disqus button "I don't see my platform listed, install manually with"](/uploads/disqus-platform-button.jpg)

## Step 7

You can ignore everything on this page, as the Awake template has already configured it for you. All you have to do is find your "Site Short Name" (it's the first part of the url) and add it to `config/_siteConfig.js`.

Take it from here:

![Site Short Name in url](/uploads/disqus-site-short-name.jpg)

and put it here:

```
// config/_siteConfig.js
export default {
...
// Disqus
  disqus: {
    on: false,
    loadingStrategy: 'button', // Options: onload, lazy, button
    siteShortName: 'testing-bjsj2bjl0i'
  },
}
```

## Step 8

That's it! You've got comments up and running on your site. Go checkout a post and see your new fancy comments section.
