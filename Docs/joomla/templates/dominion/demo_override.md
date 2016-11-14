---
title: Dominion: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Dominion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/dominion:Dominion

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings presets in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Dominion Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs.

![][template2]

:   1. **Logo** [6%, 18%, se]
    2. **Menu** [9%, 18%, ne]
    3. **Copyright** [90%, 18%, se]
    4. **To-Top Scroller** [93%, 83%, sw]


This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo.

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

![][styles]

| Style       | Option           | Setting                                    |
| :---------- | :----------      | :----------                                |
| Default     | Background Level | High                                       |
| Default     | Body Level       | High                                       |
| Default     | CSS Style        | Style 1                                    |
| Default     | Link Color       | `cc0000`                                   |
| Default     | Font Settings    | Font Family: Helvetica, Font Size: Default |

### Features

![][features]

| Style       | Option           | Position    | Setting                                                                                           |
| :---------- | :----------      | :---------- | :----------                                                                                       |
| Default     | Logo             | header-a    | Show: On                                                                                          |
| Default     | Date             | top-d       | Show: Off, Client-side Date: Off                                                                  |
| Default     | Font-Sizer       | feature-b   | Show: Off                                                                                         |
| Default     | Login Panel      | top-a       | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`                        |
| Default     | Copyright        | copyright   | Show: On, `Designed by RocketTheme, LLC`                                                          |
| Default     | SmartLoad        |             | Show: Off, Offset Y: 10, Component Ignores: `com_contact`, XPath Ignores: `ul.menutop span.image` |
| Default     | To-Top Scroller  | copyright   | Show: Off, `Scroll to Top`                                                                        |
| Default     | System Messages  | drawer      | Show: On                                                                                          |
| Default     | Reset Settings   | copyright   | Show: Off, `Reset Settings`                                                                       |
| Default     | IE6 Warning      |             | Show: On, Delay: `2000`                                                                           |
| Default     | Google Analytics |             | Enable: Off                                                                                       |

### Menu

![][menu]

| Style       | Option            | Setting                                                 |
| :---------- | :----------       | :----------                                             |
| Default     | Menu Control      | Show: On, Type: Fusion-Menu                             |
| Default     | Select a Menu     | Main Menu                                               |
| Default     | Position          | navigation                                              |
| Default     | Enable JavaScript | On                                                      |
| Default     | Menu Opacity      | 1                                                       |
| Default     | Menu Effect       | Slide + Fade                                            |
| Default     | Menu Delay        | 500                                                     |
| Default     | Menu Animation    | Quad.easeOut                                            |
| Default     | Pill              | Enable: Off, Duration: `400`, Animation: `Back.easeOut` |
| Default     | Enable ID         | Off                                                     |
| Default     | Module Cache      | On                                                      |

### Layouts

![][layouts]

| Style       | Option               | Setting               |
| :---------- | :----------          | :----------           |
| Default     | Top Positions        | Positions: 2, 5:7     |
| Default     | Header Positions     | Positions: 1, 12      |
| Default     | Showcase Positions   | Positions: 2, 8:4     |
| Default     | Feature Positions    | Positions: 1, 12      |
| Default     | MainTop Positions    | Positions: 2, 4:8     |
| Default     | MainBody Positions   | Positions: 2, 4:8     |
| Default     | MainBottom Positions | Positions: 3, 4:4:4   |
| Default     | Bottom Positions     | Positions: 3, 4:4:4   |
| Default     | Footer Positions     | Positions: 4, 3:3:3:3 |

### Mobile

![][mobile]

| Style       | Option               | Position          | Setting                                      |
| :---------- | :----------          | :----------       | :----------                                  |
| Default     | iPhone Custom Theme  |                   | On                                           |
| Default     | Scalable Content     |                   | Off                                          |
| Default     | Standard View Switch | mobile-copyright  | Enable: On, Position: mobile-copyright       |
| Default     | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Cube        |
| Default     | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 33% |
| Default     | Positions Aliases    | mobile-drawer     | drawer                                       |
| Default     | Positions Aliases    | mobile-top        | top-a                                        |
| Default     | Positions Aliases    | mobile-header     | header-b                                     |
| Default     | Positions Aliases    | mobile-navigation | mobile-navigation                            |
| Default     | Positions Aliases    | mobile-showcase   | header-a                                     |
| Default     | Positions Aliases    | mobile-footer     | footer-a                                     |
| Default     | Positions Aliases    | mobile-copyright  | copyright                                    |

### Advanced

![][advanced]

|  Style  |       Option      |                                 Setting                                 |
| :------ | :---------------- | :---------------------------------------------------------------------- |
| Default | Gantry Cache      | Enabled: On, Cache Timeout: 900                                         |
| Default | Input Styling     | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#rt-popuplogin'` |
| Default | Display Component | On                                                                      |
| Default | RTL Support       | On                                                                      |
| Default | IE7 Redirect      | On                                                                      |
| Default | Less Compiler     | CSS Compression: On, Compile Wait: `2`, Debug Header: Off               |
| Default | Page Suffix       | On                                                                      |

[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[template2]: assets/dominion2.jpeg
[styles]: assets/setstyle.jpeg
[features]: assets/setfeatures.png
[menu]: assets/setmenu.jpeg
[layouts]: assets/setlayouts.jpeg
[mobile]: assets/setmobile.jpeg
[advanced]: assets/setadvanced.jpg
