# Creative Jekyll Theme

This theme is based on
[Creative](http://startbootstrap.com/template-overviews/creative/) which is a one page creative theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/).

---

## How To Use
edit the config.yml file as per your requirement
```
title: Creative
author: Bhavesh
header-text: "Your Favorite Source of Free Bootstrap Themes"
header-sub-text: "Start Bootstrap can help you build better websites using the Bootstrap CSS framework! Just download your template and start going, no strings attached!"
header-btn-text: "Find Out More"
about-head: We've got what you need!
about-content: "Start Bootstrap has everything you need to get your new website up and running in no time! All of the templates and themes on Start Bootstrap are open source, free to download, and easy to use. No strings attached!"
about-btn-text: "Get Started!"
services-text: "At Your Service"
contact-header: "Let's Get In Touch!"
contact-text: "Ready to start your next project with us? That's great! Give us a call or send us an email and we will get back to you as soon as possible!"
contact-number: "123-456-6789"
contact-email: "feedback@startbootstrap.com"

markdown: kramdown
permalink: pretty

```
---
Edit, create or remove post to edit, add and remove services and portfoilio items.

For services the post should have following details.
```
---
type: services
icon: "fa-newspaper-o"
service-head: "Up to Date"
service-text: "We update dependencies to keep things fresh."
---
```

For portfoilio items the post should have following details.
```
---
type: portfolio
link: "#"
icon: "img/portfolio/3.jpg"
icon-alt: "portfolio-3"
category: "Category"
project-name: "Project Name"
---
```

*
NOTE:
If type: services or type: portfolio is not mentioned in post then the post wont be displayed on services or portfolio sections.
*

---
