---
title: Portfolio
slug: portfolio
layout: project
tags: project
categories: ['WEB']
thumbnail: /img/portfolio.webp

project_type: Web development
credits: [{'what': 'Design', 'who': 'Helena Ip'}, {'what': 'Programming', 'who': 'Jason Light'}]
tools: ['HTML', 'CSS', 'JS', '11ty']
duration: 4 Weeks

description: The portfolio you're currently browsing!
---

## Initial planning
My UI / UX designer friend Helena Ip and I decided to work together on a joint portfolio project. She would be in charge of the UI / UX design, and I would be the programmer. We started by creating a Slack team, Google Docs design document and a Figma project. We discussed our basic design requirements, and came up with the following:

* A clean, modern design that makes the projects the center of attention.
* A space to write about each project in detail
* A space to write about ourselves, such as our contact info and external links (LinkedIn, Github etc.)

## Basic design
Based on these requirements, Helena began work on a basic design in our Figma project. You can read more about how she designed this on [her portfolio](). The initial design featured three pages: 

 * **home page**: Prominently features our projects and basic info
 * **project page**: Contains the write-up for a given project
 * **about page**: contains our contact information and bio

```TODO: IMAGES```

After this basic design was put together we had a call where we discussed the strong and weak points of the design, and we went over some use cases to clarify unclear points in the design. I loved the hover effect she made for previewing projects, and the overall design was very clean and usable. After this call, Helena started work on a more refined version of the design, while I started working on basic implementations of some of the UI elements in HTML / CSS.

## HiFi Design
Taking into account our discussion, and also some of her own ideas, Helena created a much more refined "HiFi" design. This is the version of the design I based most of my development on. You can see some highlights below: 

```TODO: IMAGES```

## Development Plan
I knew I wanted to keep the cost for hosting the site down, so I knew from the start I wanted to use some kind of static site generator for rendering templates etc. as this allows us to use something like Github Pages or Netlify for hosting. I wanted to do most of the clientside development in HTML5, modern vanilla JavaScript and CSS3 without a lot of frameworks etc. as I value building things from scratch to see how everything works under the hood. Of course I recognize the value of frameworks when developing large projects, but I think using them with the knowledge of how everything works under the hood will make development with any framework easier, whereas experience with a given framework is potentially a little less transferrable to other frameworks. So I needed a static site generator that wouldn't lock me into a certain client side framework, and I also didn't want to spend a lot of time on configuration, so I ended up going with [Eleventy](https://www.11ty.dev/). 

I also decided to develop the page as a [single page app](https://developer.mozilla.org/en-US/docs/Glossary/SPA) as I wanted to see how one would implement such an app without use of the normal router tools provided by Javascript frameworks. This also allows me to use custom transitions between pages, which I feel is a good way to make the site more eye-catching and visually interesting.

