---
title: Entropy: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Entropy Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/entropy:Entropy

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings preset in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Entropy Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][Entropy2]

:   1. **Logo** [5%, 28%, se]
    2. **Menu** [5%, 70%, sw]
    3. **Branding** [92%, 46%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the Style indicated here relates to the template Style in this menu. More information about how Styles work can be found in our [Gantry documentation][Style].

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

| Style   | Option            | Position | Setting                                                                                                                                            |  
| :------ | :---------------- | :------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |  
| Default | CSS Style         |          | Style 1                                                                                                                                            |  
| Default | Showcase Panel    |          | Headline: `Conference Schedule`, Title Alignment: Center, Typography: Retro, Subline: `Find the sessions that interest you`                        |  
| Default | Feature Panel     |          | Headline: `Guest Speakers`, Divider: Divider 1, Title Alignment: Center, Typography: Retro, Subline: `Experts in their Field`                      |  
| Default | Main Panel        |          | Divider: Divider 1, Title Alignment: Left, Typography: Retro                                                                                       |  
| Default | Bottom Panel      |          | Headline: `How to Attend`, Pattern: Pattern 1, Divider: Divider 5, Title Alignment: Center, Typography: Retro, Subline: `Location, Prices, etc...` |  
| Default | Footer Panel      |          | Headline: `Template Features`, Divider: Divider 1, Title Alignment: Center, Subline: `Packed full of goodies and fun stuff`, Typography: Retro     |  
| Default | Read More Style   |          | Button                                                                                                                                             |  
| Default | Panel Back To Top |          | On                                                                                                                                                 |  
| Default | Fixed Header      |          | On                                                                                                                                                 |  
| Default | Font Settings     |          | Font Family: Helvetica, Font Size: Default                                                                                                         |     

### Features

| Style   | Option           | Position  | Setting                                                                                 |  
| :------ | :--------------- | :-------- | :-------------------------------------------------------------------------------------- |  
| Default | Logo             | top-a     | Show: On, Auto Size: On, Centered: On                                                   |  
| Default | Date             | utility-a | Show: Off                                                                               |  
| Default | Font-Sizer       | utility-b | Show: Off                                                                               |  
| Default | Login Panel      | utility-c | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`              |  
| Default | Popup Panel      | utility-d | Show: Off, Popup Button Text: `Popup Module`                                            |  
| Default | Branding         | copyright | Show: On                                                                                |  
| Default | Copyright        | copyright | Show: Off, Text: `Designed by RocketTheme`                                              |  
| Default | SmartLoad        |           | Show: On, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |  
| Default | More Articles    |           | Enable: Off, Text: Load More Articles, Hide Pagination: On                              |  
| Default | To-Top Scroller  | copyright | Show: Off, Text: `Back to Top`                                                          |  
| Default | System Messages  | drawer    | Show: On                                                                                |  
| Default | Reset Settings   | footer-b  | Show: Off, Text: `Reset Settings`                                                       |  
| Default | Google Analytics |           | Enable: Off                                                                             |  

### Menu

| Style   | Option             | Setting                     |  
| :------ | :----------------- | :-------------------------- |  
| Default | Menu Control       | Show: On, Type: Fusion-Menu |  
| Default | Enable ID          | Off                         |  
| Default | Select a Menu      | Main Menu                   |  
| Default | Main Menu Position | top-b                       |  
| Default | Enable JavaScript  | On                          |  
| Default | Menu Opacity       | 1                           |  
| Default | Menu Effect        | Slide and Fade              |  
| Default | Menu Delay         | 500                         |  
| Default | Menu Animation     | Circ.easeOut                |  
| Default | Menu Duration      | 300                         |  
| Default | Enable ID          | Off                         |  
| Default | Module Cache       | On                          |  

### Layouts

| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 2, 3:9     |  
| Default | Header Positions     | Positions: 2, 6:6     |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 1, 12      |  
| Default | MainTop Positions    | Positions: 2, 6:6     |  
| Default | MainBody Positions   | Positions: 2, 7:5     |  
| Default | MainBottom Positions | Positions: 1, 12      |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 4, 3:3:3:3 |  

### Mobile

| Style   | Option               | Position          | Setting                                      |  
| :------ | :------------------- | :---------------- | :------------------------------------------- |  
| Default | iPhone Custom Theme  |                   | On                                           |  
| Default | Android Custom Theme |                   | On                                           |  
| Default | Scalable Content     |                   | Off                                          |  
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |  
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Slide       |  
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25% |  
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |  
| Default | Positions Aliases    | mobile-top        | top-a                                        |  
| Default | Positions Aliases    | mobile-header     | header-b                                     |  
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |  
| Default | Positions Aliases    | mobile-showcase   | header-a                                     |  
| Default | Positions Aliases    | mobile-feature    | header-a                                     |  
| Default | Positions Aliases    | mobile-bottom     | header-a                                     |  
| Default | Positions Aliases    | mobile-footer     | footer-a                                     |  
| Default | Positions Aliases    | mobile-copyright  | copyright                                    |  

### Advanced

| Style   | Option              | Setting                                                              |  
| :------ | :------------------ | :------------------------------------------------------------------- |  
| Default | Gantry Cache        | Enabled: Off, Cache Timeout: 900                                     |  
| Default | Input Styling       | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#vmMainPage'` |  
| Default | Inline JS File      | Off                                                                  |  
| Default | Display Component   | On                                                                   |  
| Default | Display Mainbody    | On                                                                   |  
| Default | RTL Support         | On                                                                   |  
| Default | Build Titles Spans  | Off                                                                  |  
| Default | Page Suffix         | On                                                                   |  
| Default | RT Typography       | Enabled: On                                                          |  
| Default | RT Extensions       | On                                                                   |  
| Default | IE6 Redirect        | On                                                                   |  

[demo25]: assets/Entropy.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[Entropy2]: assets/entropy2.jpeg