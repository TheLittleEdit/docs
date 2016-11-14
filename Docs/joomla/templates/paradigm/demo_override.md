---
title: Paradigm: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Paradigm Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Paradigm Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][paradigm2]

:   1. **Logo**  [6%, 17%, se]
    2. **Menu**  [6%, 84%, sw]
    3. **Social Buttons** [92%, 84%, sw]
    4. **Copyright**  [92%, 15%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

### Style
| Style   | Option        | Position | Setting                                   |  
| :------ | :------------ | :------- | :---------------------------------------- |  
| Default | Logo          | header-a | Show: On                                  |  
| Default | Font Settings |          | Font Family: Paradigm, Font Size: Default |  

### Features
| Style   | Option             | Position    | Setting                                                                                          |  
| :------ | :----------------- | :---------- | :----------------------------------------------------------------------------------------------- |  
| Default | Social Buttons     | copyright-b | Show: On                                                                                         |  
| Default | Chart              |             | Show: On                                                                                         |  
| Default | Coming Soon Page   |             | Show: Off                                                                                        |  
| Default | Email Subscription |             | Show: On                                                                                         |  
| Default | Feedburner URI     |             | Blank                                                                                            |  
| Default | Date               | utility-a   | Show: Off, Client-Side Date: Off                                                                            |  
| Default | Font-Sizer         | utility-b   | Show: Off                                                                                        |  
| Default | Login Panel        | utility-c   | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                       |  
| Default | Popup Panel        | utility-d   | Show: Off, Popup Button Text: `Popup Module`                                                     |  
| Default | Branding           | copyright-a | Show: Off                                                                                        |  
| Default | Copyright          | copyright-a | Show: On, Text: `Built by <a href="http://www.rockettheme.com/" target="_blank">RocketTheme</a>` |  
| Default | To-Top Scroller    | copyright-b | Show: Off                                                                                        |  
| Default | System Messages    | drawer      | Show: On                                                                                         |  
| Default | Reset Settings     | copyright-d | Show: Off, Text: `Reset Settings`                                                                |  
| Default | Google Analytics   |             | Enable: Off                                                                                      |  

**Social Buttons Content**

| Field       | Content                                                    |
| :---------- | :----------                                                |
| Icon 1      | `icon-facebook`                                            |
| Text 1      | `Facebook`                                                 |
| Link 1      | `http://www.facebook.com/RocketTheme`                      |
| Icon 2      | `icon-twitter`                                             |
| Text 2      | `Twitter`                                                  |
| Link 2      | `https://twitter.com/rockettheme`                          |
| Icon 3      | `icon-google-plus`                                         |
| Text 3      | `Google +`                                                 |
| Link 3      | `https://plus.google.com/114430407008695950828/posts`      |
| Icon 4      | `icon-rss`                                                 |
| Text 4      | `RSS`                                                      |
| Link 4      | `http://www.rockettheme.com/blog?format=feed&amp;type=rss` |
| Icon 5      | `icon-linkedin`                                            |
| Text 5      | `LinkedIn`                                                 |
| Link 5      | `http://www.linkedin.com/in/rockettheme`                   |

### Menu
| Style   | Option          | Setting                       |  
| :------ | :-------------- | :---------------------------- |  
| Default | Menu Control    | Show: On, Type: Dropdown-Menu |  
| Default | Select a Menu   | Main Menu                     |  
| Default | Position        | header-b                      |  
| Default | Responsive Menu | Panel                         |  
| Default | Enable ID       | Off                           |  
| Default | Module Cache    | On                            |  

### Layouts
| Style   | Option                | Setting               |  
| :------ | :-------------------- | :-------------------- |  
| Default | Header Positions      | Positions: 2, 3:9     |  
| Default | Showcase Positions    | Positions: 1, 12      |  
| Default | Top Positions         | Positions: 4, 3:3:3:3 |  
| Default | Utility Positions     | Positions: 4, 3:3:3:3 |  
| Default | Feature Positions     | Positions: 1, 12      |  
| Default | MainTop Positions     | Positions: 1, 12      |  
| Default | ExpandedTop Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions   | Positions: 1, 12      |  
| Default | Bottom Positions      | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions      | Positions: 3, 4:4:4   |  
| Default | Copyright Positions   | Positions: 2, 4:8     |  

### Advanced
| Style   | Option           | Setting                                                 |  
| :------ | :--------------- | :------------------------------------------------------ |  
| Default | Layout Mode      | Responsive                                              |  
| Default | Load Transition  | Off                                                     |  
| Default | Display Content  | On                                                      |  
| Default | Mainbody Enabled | On                                                      |  
| Default | RTL Support      | Off                                                     |  
| Default | Page Suffix      | On                                                      |  
| Default | Selectivizr      | Off                                                     |  
| Default | Less Compiler    | CSS Compression: On, Compile Wait: 2, Debug Header: Off |  
| Default | IE7 Redirect     | On                                                      |  
| Default | Demo Styling     | On                                                      |  
| Default | K2 Styling       | On                                                      |  
| Home    | Mainbody Enabled | On                                                      |  

### Assignments
| Style | Option    | Setting |  
| :---- | :-------- | :------ |  
| Home  | Main Menu | Home    |  

[demo25]: assets/Paradigm.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[paradigm2]: assets/paradigm2.jpeg
