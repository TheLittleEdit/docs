---
title: Galatea: Recreating the Demo - Contact Page
description: Your Guide to Recreating Elements of the Galatea Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/galatea:Galatea

---

## Introduction

The **Contact** example page demonstrates how you can create a beautiful page with the Galatea theme. Here is some information to help you replicate this page as it appears in the demo.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_contact.jpeg)

:   1. **Header** Info List (particle) [9%, 35%, se]
    2. **Aside** Custom HTML (particle) [23%, 70%, se]

* [Header](#header-section)
* [Aside](#aside-section)
* [Contact Form](#contact-form)

# Header Section

![](assets/page_contact_1.jpeg)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

## Section Settings

| Field          | Setting                   |
| :-----         | :-----                    |
| Layout         | Fullwidth (Boxed Content) |
| CSS Classes    | Blank                     |
| Tag Attributes | Blank                     |

## Particle Settings

| Option                   | Setting                              |
| :-----                   | :-----                               |
| Particle Name            | `Get in Touch!`                      |
| CSS Classes              | `g-layercontent` `noborder` `center` |
| Title                    | Blank                                |
| Intro                    | Blank                                |
| Grid Column              | 1 Column                             |
| Item 1 Name              | `Get in Touch!`                      |
| Item 1 Icon              | Blank                                |
| Item 1 Icon Location     | Left                                 |
| Item 1 Image             | Blank                                |
| Item 1 Image Location    | Left                                 |
| Item 1 Text Style        | Header                               |
| Item 1 Image Style       | Compact                              |
| Item 1 Description       | `Tell us about your project!`        |
| Item 1 Tag               | Blank                                |
| Item 1 Sub Tag           | Blank                                |
| Item 1 Label             | Blank                                |
| Item 1 Link              | Blank                                |
| Item 1 Button Icon       | Blank                                |
| Item 1 Read More Classes | Blank                                |
| Item 1 Target            | Self                                 |

## Block Settings

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `100%`    |

# Aside Section

![](assets/page_contact_2.jpeg)

This area of the page is a **Custom HTML** particle. You will find the settings used in our demo below.

## Section Settings

| Field          | Setting                   |
| :-----         | :-----                    |
| Layout         | Fullwidth (Boxed Content) |
| CSS Classes    | Blank                     |
| Tag Attributes | Blank                     |

## Particle Settings

| Option             | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Shortcodes | Blank         |

**Custom HTML**

~~~ .html
<p><img src="gantry-media://rocketlauncher/pages/contact/img-01.jpg" alt="image"></p>
<p><strong>Galatea</strong> is only available as part of the Club Subscription.</p>
<p>Please use the RocketLauncher to install an equivalent of the demo onto your site.</p>
<p>All demo content is for sample purposes only, to represent a live site.</p>
~~~

## Block Settings

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `100%`    |

# Contact Form

![](assets/page_contact_3.jpeg)

The contact form featured in the page is a standard page. Here are the settings we used to create it.

## Page Settings

| Option        | Setting           |
| :-----        | :-----            |
| Title         | `Contact`         |
| Folder Name   | `Contact`         |
| Parent        | `Pages`           |
| Page Template | Default           |
| Process       | Markdown and Twig |

~~~ .html
## Contact Form

{% include "forms/form.html.twig" with {form: forms( {route: '/form/contact'} )} %}
~~~

