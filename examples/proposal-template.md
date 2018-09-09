# Proposal Template

## How to use this document

This outline serves as an example for your docs tear down proposal. I've included several of the headings and some example content from my own proposal, as well as sourced material from other example proposals. You are free to copy this and fill it in with your own materials.

## License

+-----------------+----------------------------------------------+
|                     License: cc-by-sa-4.0                      |
+-----------------+----------------------------------------------+
| SPDX ID         | CC-BY-SA-4.0                                 |
| SPDX Name       | Creative Commons Attribution Share Alike 4.0 |
| OSI approved    | No                                           |
| FSF approved    | No                                           |
| OD approved     | Yes                                          |
| Current license | No                                           |
+-----------------+----------------------------------------------+
| Eligible        | Yes                                          |
+-----------------+----------------------------------------------+

*************************

# Title of my proposal

Written by: Your Name
Date: September 10, 2018

## Introduction

Introductions are the place for you to spell out the fact there is a problem and why the problem exists. Prepare the reader for what to expect in the next two, five, or ten pages.

In my first draft, I addressed the fact that Joyent was long overdue for a documentation overhaul and that there were far reaching problems with consequences. Perhaps you could expect that knowing there were 9 documentation websites. 

I talked about why it was worth restructuring our documentation for the business. After all, Joyent’s company goal is to be a serious competitor in cloud, rather than a niche company for industry nerds. But just having marketing materials which say “we are the best” doesn’t make customers buy the product. And backing up our claims was even more than having a good product. Even if it was the best cloud on the market, that wouldn’t matter if customers couldn’t use it.

Think about your company goals. Maybe your company is already the industry leader, so you don’t need to spend time convincing anyone to use the product but can focus on the exciting innovations your product offers. Maybe you don’t care about being the best, but rather you care about your customers being able to say it was so easy to get from point A to point B. Your introduction prioritizes the company goal for your documentation.

## Content audit

Not every content audit is the same. Moz has a useful guide for [how to start a content audit](https://moz.com/blog/content-audit).

### Website inventory

At this point, Joyent has content which lives in a multitude of places, including but not limited to:

+ docs.joyent.com: our main public and private cloud documentation
+ joyent.com: home for Node.js docs, ContainerPilot docs, technical videos, and technical blog posts
+ apidocs.joyent.com: API documentation which is single-sourced.
+ Joyent portal: online web UI for developers also contains documentation.
+ more...

## Goals

The following goals were used at Joyent for our documentation overhaul:

+ **Organize existing content.** As stated in the overview, there are at least six different websites upon which documentation can be found. We must reduce the number of locations that users must visit to get different types of content. We must also better structure the documentation so that it is easy to navigate between topics.
   + This includes reorganization of existing topics within our menu, for which an issue has been started.
   + We should look at our competitors to see their structure, as customers are used to getting documentation in a certain way. We should try to meet and exceed the expectations of the genre of cloud documentation.
   + This does not necessarily mean reducing the number of places content is created. For example, the GitHub repos are an essential part of the developer process. There are ways to automatically replicate that content in Kirby, therefore eliminating the need for our engineers to learn a new tool.
+ **Clearly segment types of documentation.** There are a number of forms in which technical documentation exists: high-level overviews, getting started materials, step-by-step tutorials, auto-generated documents, and reference materials. This documentation may be written as well as exist as screencasts.
   + We must clearly template these document styles so that the user understands what they’re looking at.
   + Grouping some of those materials by tag or within the navigation may be useful.
+ **Ensure our designs actually make a user’s experience better.** I’ve made a number of assumptions, and it’s important that we test these assumptions so that our work doesn’t amount to a vanity refresh.
   + We should talk to users before this project gets started to better understand how we have failed them and how we have succeeded. Additionally, this research process could be instrumental in deciding what initial prototypes will look like.
   + At every design stage, there should be conversations with various stakeholders, internal and external.
+ **Create a clear process for documentation requests.** The engineers, product team, documentation team, and anyone else involved in creating document materials should have a clear workflow for creating content.
   + This includes clear instructions for how to create content in whatever medium we decide should be the primary home for content, as well as templates for different types of content.
   + In some cases, it would be too disruptive to change the normal flow of content creation. We don’t want to make it any more difficult, leading to lesser contributions to docs. However, slow changes are necessary to make content creation easier in the future.
+ ** Create a Process for document deprecation.** Not all of our documentation needs to live forever, as we deprecate or stop supporting older products. A true content lifecycle includes what happens when content is no longer needed or should no longer be public.
   + Do we silently remove materials? Or do we include warnings of deprecation, and if so for how long?
   + What do redirects for removed materials look like? Should they be specialized with a message about the deprecation or just directed to newer materials?
   + There must be rules for archiving materials so that older content is still accessible internally.

This document does cover improvements to the content beyond restructuring. While that is very important, that work is actively being done. Additionally, if we don’t solve the deeper issue of structure, new docs eventually fall into the void.

## Stakeholders

Who cares about this project? Define each group and the stakes they have in this project.

**Users**: why do your users care?

**Engineers**: why do your engineers care?

**Managers / Executives**: why do they care?

**Sales team**

Anyone else?

## Audience

Your audience is not necessarily the same as the stakeholders for building your documentation. At Joyent, we use the following categories:

+ **Business owners.** Business owners are interested in our product and they want to know what our product does, understanding general concepts, and how easy it would be to start using the product with intro tutorials.
+ **Investigators.** Investigators are the engineers who may be more familiar with Joyent and our cloud but want to learn the advanced features and how to use them.
+ **Problem solvers.** These are engineers who are in a bind and need to know how to solve a problem they’re having, fast. They need a quick tutorial, no nonsense no fluff.
+ **Detectives.** These may be engineers or product managers who want to know if it’s possible to perform a specific task using our products.

If you have marketing personas, definitely refer to them in this process.

## Life cycle plan

A lifecycle plan addresses what happens when a document is first written, how to update it, and what happens when the product it is relevant to either changes dramatically, goes into end of life, or is removed from the market place.

For Joyent, that meant considering what happened from the  generation of an idea, to writing, to publishing, to updating, to archiving, to deletion. Each of those stages has a set of protocols to be followed and checks to ensure nothing is fully lost.

## Usability

Things to consider:

+ How can we integrate related materials? There may be content which doesn’t live in the same bucket of information, but could be useful (like Docker content not under the API tab).
+ Is the material overwhelming? Is it sparse?
+ How does the content index in search? Is it easy to find what users are looking for?

### UX / Wireframes

It’s important to consider how our users are interacting with our documentation. Before creating mockups and designing the docs website, we must create and test wireframes. There should be a conversation about what our documentation looks like on mobile devices and desktop and optimizing the layouts for those different situations.

### Testing

Beyond just testing wireframes, there should be testing in every single phase of this project. This includes having conversations, sharing prototypes, and interactive user testing sessions. We can learn a lot about how to execute this process by looking at the Make Us Proud testing sessions for the portal redesign.

## Project phases

This is the proposed steps necessary to complete this project. Although these steps should theoretically be completed in order, there may be some overlap and repetition as needed.

Peppered between step 4 and 8 should be user testing. We should be talking to folks from the very beginning and not waiting until something is built. This ensures we don’t have to start from scratch late in the game due to crucial missing information.

1. Project scope / definition
   1. Why are we creating this content?
   1. Personas, who is this aimed for?
   1. What are the problems to solve? And what are our goals in solving those problem.
   1. Create a detailed content audit.
   1. Write a "wants list": what do we need to create to satisfy our audience? Where are the gaps?
1. Competitor research and analysis
1. Content strategy
1. Develop documentation website information architecture design
1. Wireframes
1. Visual design
1. Site development
1. Launch

## Tools required

What tools are needed for us to be successful? I required the following:

+ [Camtasia for Mac](https://www.techsmith.com/video-editor.html): editing videos
+ [Markdown editor](https://stackedit.io/)
+ Image editor: possibly Pixelmator or Adobe Photoshop

## Cost

How much time will this project take? How much will it cost?

## Additional considerations

What else did we miss?

## Schedule

When will we deliver our deliverables.


