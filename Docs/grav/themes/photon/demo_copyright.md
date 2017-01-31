---
title: Photon: Recreating the Demo - Copyright Section
description: Your Guide to Recreating Elements of the Photon Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/photon:Photon

---

## Introduction

![](assets/demo_7.jpeg)

:	1. **Logo / Image (Particle)** [5%, 1%, se]
	2. **Newsletter (Particle)** [5%, 60%, se]
	3. **Copyright (Particle)** [65%, 1%, se]
	4. **Custom HTML (Particle)** [65%, 60%, se]

The **Copyright** section includes four particles: **Logo / Image**, **Newsletter**, **Copyright**, and a **Custom HTML** particle assigned to the **copyright-a** widget position.

![](assets/home_copyright.jpeg)

Here is a breakdown of the widget(s) and particle(s) that appear in this section:

* [Logo / Image (particle)](#logo-image-(particle))
* [Newsletter (particle)](#copyright-(particle))
* [Copyright (particle)](#to-top-(particle))
* [Custom HTML (particle)](#custom-html-(particle))

## Section Settings

![](assets/demo_copyright_settings.jpeg)

| Option           | Setting                   |
| :--------------- | :----------               |
| Layout           | Fullwidth (Boxed Content) |
| CSS Classes      | `g-mobile-center-compact` |
| Tag Attributes   | Blank                     |

## Logo Image (Particle)

### Particle Settings

![Demo Copyright](demo_copyright_1.jpeg)

| Option        | Setting         |
| :-----        | :-----          |
| Particle Name | `Logo / Image`  |
| URL           | Blank           |
| Image         | Blank           |
| Text          | `Photon`        |
| CSS Classes   | `g-footer-logo` |

### Block Settings

![Demo Copyright](demo_copyright_2.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `60%`     |

## Copyright (Particle)

### Particle Settings

![Demo Copyright](demo_copyright_3.jpeg)

| Option         | Setting      |
| :-----         | :-----       |
| Particle Name  | `Newsletter` |
| CSS Classes    | Blank        |
| Width          | Full Width   |
| Layout         | Square       |
| Style          | Blank        |
| Title          | Blank        |
| Heading Text   | Blank        |
| Side Text      | `Newsletter` |
| InputBox Text  | Blank        |
| Button Icon    | `fa fa-send` |
| Button Text    | `Join`       |
| Feedburner URI | Blank        |
| Button Classes | Blank        |

### Block Settings

![Demo Copyright](demo_copyright_4.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `40%`     |

## Copyright (Particle)

### Particle Settings

![Demo Copyright](demo_copyright_5.jpeg)

| Option          | Setting           |
| :-----          | :-----            |
| Particle Name   | `Copyright`       |
| Start Year      | `2007`            |
| End Year        | `now`             |
| Copyright Owner | `RocketTheme LLC` |

### Block Settings

![Demo Copyright](demo_copyright_6.jpeg)

| Option         | Setting       |
| :-----         | :-----        |
| CSS ID         | Blank         |
| CSS Classes    | `g-copyright` |
| Variations     | Blank         |
| Tag Attributes | Blank         |
| Fixed Size     | Unchecked     |
| Block Size     | `48%`         |

## Custom HTML (Particle)

#### Particle Settings

![Demo Widget](demo_copyright_7.jpeg)

| Option             | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Twig       | Unchecked     |
| Process Shortcodes | Unchecked     |

**Custom HTML**

~~~ .html
<div class="g-grid g-sample-sitemap">
<div class="g-block">
<ul class="nomarginall g-bottom-menu align-right">
<li><a href="index.php">Home</a> </li>
<li><a href="#"><i class="fa fa-circle"></i> About</a></li>
<li><a href="#"><i class="fa fa-circle"></i> Terms</a></li>
<li><a href="#"><i class="fa fa-circle"></i> Legal</a></li>
<li><a href="#"><i class="fa fa-circle"></i> Disclaimer</a></li>
</ul>
</div>
</div>
~~~

#### Block Settings

![Demo Widget](demo_copyright_8.jpeg)

| Option         | Setting                        |
| :-----         | :-----                         |
| CSS ID         | Blank                          |
| CSS Classes    | `nomarginleft` `nopaddingleft` |
| Variations     | Blank                          |
| Tag Attributes | Blank                          |
| Fixed Size     | Unchecked                      |
| Block Size     | `52%`                          |

