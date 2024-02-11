# Lab3

For the creation of this webpage, I've implemented a range of elements including the header, nav, main, and footer. To enhance the visual appeal and typographic consistency, I've integrated custom Google fonts along with fluid typography and CSS variables throughout the codebase.

In the header element, users will find the website name and navigation bar links. The navigation bar, contained within the <nav> tag, consists of an input element, label, and an unordered list. This list features a variety of anchor tags for navigation, including home, genres, artist, albums, and events. To ensure responsiveness, I've utilized flexbox for the navigation bar. On mobile devices, a dropdown menu is activated by a hidden checkbox input element, strategically positioned within the flexbox. Utilizing the :checked selector, the dropdown menu appears when activated. Media queries have been utilized to trigger the dropdown menu's appearance when the screen size is under 742px.

Within the <main> tag, the primary content of the webpage resides. Commencing with an <h2> tag welcoming users, followed by an <h3> tag as the title for the artists' section. Artist information is displayed via a grid container, where a card like structure is used. These cards have rounded borders. These cards showcase the artist's image, name, and music genre. Using media queries, the number of columns within the grid dynamically adjusts based on screen size, providing an optimal viewing experience:
Screen sizes under 481px feature a single column layout, ensuring clarity and focus on content.
From 481px to 635px, the grid gracefully transitions to a 2-column layout.
Between 636px and 966px, the grid expands to present content across 3 columns.
With screen widths spanning 967px to 1233px, the grid accommodates 4 columns.
From 1234px to 1540px, the grid extends to 5 columns, maximizing space utilization and content visibility.
Screen sizes exceeding 1540px elegantly adopt a 6-column layout distributed across 2 rows, ensuring ample space for content presentation while maintaining visual harmony.

The subsequent section of the <main> tag presents songs released by different artists, indicated by an <h3> element for the Songs heading. Utilizing audio elements, accompanied by spans denoting the singer and song name.

Concluding the <main> tag is the section dedicated to Upcoming events. Displayed under an <h3> tag, this section features a video element showcasing forthcoming events.

Lastly, the <footer> element encapsulates the webpage, utilizing a <p> element. The content of the <p> tag is centered.
