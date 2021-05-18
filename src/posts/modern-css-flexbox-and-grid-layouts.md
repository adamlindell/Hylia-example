---
tags:
- css
- " training"
title: 'Modern CSS: Flexbox and Grid layouts'
date: 2020-02-05T21:31:00Z
ogImage: ''

---
The promise of CSS is awesome - seperate all of your styling code from the content of your document. That way, you can format your content in a way that makes semantic sense, and not worry about where it actually lands on the page. This is especially important when designing for the web, since your styling can change based on client capability (screen size, browser version, javascript enabled or not), while your content remains the same. However, for many years this dream was very difficult to achieve. The way most designers are used to working is by laying things out on a grid, and CSS didn't provide very handy tools for doing such a thing. CSS by default uses a flow layout, where content flow to fill the space that is available in the container. This works well for simple, flexible layouts, but doesn't match the process of say designing for a magazine. What was even more frustrating is that it was actually easier to abuse the HTML `table`​ tags to create flexible, grid-based layouts!​

## Enter Flexbox and Grid

​Finally, CSS got wise and added two great layout options. Here is a fun and easy way to learn about them!

**Flexbox**, as its name implies, gives you access of how child elements flex inside of the boundary of the object. You can easily control the order, spacing, and orientation of components. Since you don't specify specific positioning of these elements the parent object can remain _flexible_, shifting content around without resorting to media queries.​

### Check out [Flexbox Froggy](https://flexboxfroggy.com/) to learn more about Flexbox.

**​CSS Grid** is also aptly named. It allows you to do flexible, grid-based layouts without resorting to putting presentational markup or using JavaScript libraries like [Bootstrap](https://getbootstrap.com/).  
​

### Check out [CSS Grid Garden](http://cssgridgarden.com/) to learn more about CSS Grid.