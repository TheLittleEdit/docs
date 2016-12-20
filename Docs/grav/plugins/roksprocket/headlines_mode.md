---
title: RokSprocket: Headlines Layout Mode
description: Your Guide to the Headlines RokSprocket Layout Mode for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/!roksprocket:RokSprocket

---

Headlines
-----

![][headlines]

Headlines is a content ticket layout mode. It can displays lines of text in succession.

![][headlines1]

:   1. **Title** This is the title you wish to give the RokSprocket instance. This is only used as a label on the backend, as the widget title will be what appears on the frontend of the site. [27%, 15%, se]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the posts title, description, image, and link. [55%, 52%, nw]
    3. **Content Filter Rules** Sets the content filter rules for the widget. [54%, 83%, sw]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more theme integrated look. The **Position** field right below it gives you the ability to set the position within the theme's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:
    * **Image** - This allows you to circumvent the assigned image from the post and replace it with one specifically for the headline. 
    * **Link** - If set, the link will show a *Read More** button as well as link the title. On specific themes, it will link the image in the headline, as well.
    * **Description** - Allows you to set a description for the headline. If this is left at *Default* the introtext from the post is used. 

3. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the headlines. For example, you can have the widget pull posts that are within a specific category, contain a particular name or keyword in the title, or choose specific posts. You can also modify how this content is sorted in the widget.

![][headlines_2]

:   1. **Theme** This sets the theme for displaying headlines in the widget. [14%, 49%, sw]
    2. **Display Limit** The amount of posts to show when rendering. [17%, 74%, sw]
    3. **Label Text** This is where you input the text you wish to appear as the label preceding the headlines text. [23%, 70%, sw]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the widget's post display. [29%, 73%, sw]
    5. **Arrow Navigation** This option configures the arrow naviagtion behavior in the widget. [35%, 52%, sw]
    6. **Animation**  This dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next. [40%, 62%, sw]
    7. **Autoplay** Sets whether you want the widget to start rolling through headlines automatically when the page loads, or to await a command from the visitor. [45%, 54%, sw]
    8. **Autoplay Delay** Sets the amount of time between cycled headlines in the widget. The longer this delay (in seconds), the longer a single post will be featured in the widget. [51%, 69%, sw]
    9. **Image Resize** This option is best utilized on a non-responsive theme. It renders a copy of the selected image with a maximum width or height determined in these fields. [57%, 87%, sw]
    10. **Default Article Text** This field allows you to set default post text for all headlines in the widget. If this is not changed from its default, then the post's introductory text is used. [73%, 66%, sw]
    11. **Default Article Image** Determines which image field the widget will default to when locating an image for the feature. [78%, 68%, sw]
    12. **Default Link** Determines which link field the widget will default to when locating a link for the feature. [83%, 66%, sw]

1. The **Theme** option sets the theme for displaying headlines in the widget. These themes determine how the headlines look within the widget. You can choose the one that best fits your theme and/or personal taste.

2. The **Display Limit** field sets the amount of posts shown when the page is rendered.  Setting this limit to zero or infinity will allow it to cycle through all applicable items.

3. **Label Text** is where you input the text you wish to appear as the label preceding the headlines text.

4. **Preview Length** sets the amount of words you wish to limit the preview to within the widget's post display. 

5. **Arrow Navigation** configures the arrow navigation behavior in the widget.

6. The **Animation** dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next.

7. **Autoplay** sets whether you want the widget to start rolling through headlines automatically when the page loads, or to await a command from the visitor.

8. **Autoplay Delay** sets the amount of time between cycled headlines in the widget. The longer this delay (in seconds), the longer a single post will be featured in the widget.

9. **Image Resize** is best utilized on a non-responsive theme. It renders a copy of the selected image with a maximum width or height determined in these fields.

10. The **Default Article Text** field allows you to set default post text for all features in the widget. If this is not changed from its default, then the post's introductory text is used. You can choose to use post content, an assigned post excerpt, the default article text, or to have nothing appear at all.

11. **Default Article Image** determines which image field the widget will default to when locating an image for the feature. 

12. **Default Link** gives you the ability to set a default link field from posts in the widget. This can be either the default article link, a custom link that applies as the default for all items, or nothing at all.

[headlines]: assets/headlines.png
[headlines_link]: headlines_mode.md
[headlines_2]: assets/headlines_2.png
[headlines1]: assets/headlines_1.jpg