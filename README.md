# Portfolio

<!-- Information -->

## < Part 1: Figma prototype >

1. [Emma Labo](https://www.figma.com/proto/7laLHF2R3oUPd59b20VAnV/Wong_ChingMan_Prototype?type=design&node-id=1-3&t=MbeEykeH3mWmT1X7-0&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=1%3A3&show-proto-sidebar=1)

2. PDF is added in PDF folder.

## < Part 2: information >

1. **CSS library**

   - credit: [Bootstrap](https://getbootstrap.com/) - used in whole portfolio website

   - credit: [Animatestyle](https://animate.style/) - used in home page

   - credit: [Bulma](https://bulma.io/documentation/form/general/) - use in contact form

2. **Used google font**

   - Cinzel and Raleway

3. **Schema**

   - Schema info is added (itemscope itemtype = VisualArtwork, Person, Contact point)

4. **Image copyright**
   - All images, including the SVG files, are owned by me.

<!-- Answer the questions -->

## < Part 3: Answer the questions >

1. **My process for this website**

   First, I built up the content of the home page by adding font styles, Bootstrap, icons, and a custom CSS link. Then, I created the body and footer. After fixing the issues and layout with the navigation bar and footer, I proceeded to work on other pages. Once all pages were completed, I added skip links and then added optimized photos. Finally, I added ARIA roles and schema markup. After adding all these elements, I used the extension WAVE to check the contrast and fix any errors.

2. **Challenges I faced during development and how I overcame those changes.**

   As I'm not yet familiar with Bootstrap, it took me some time to adjust to this new way of thinking and I was trying to remember the usage of Bootstrap classes. Consequently, home page is the page I spent the most time on. However, after building the homepage, I found that I started to adapt and understand how to utilize Bootstrap. I especially like how Bootstrap simplifies website layout across different screen sizes, making it more convenient than using media queries.

   Another challenge I encountered was working on the navigation bar. Initially, the style of my navigation bar was such that before hovering, the text appeared black with a white background. Upon hovering, the text became bold, and the background color was changed to yellow with padding and bottom shadow, resembling a button. However, after completing the styling, two problems arose when hovering.

   The first issue was that the nav-item visibly shifted to the left by approximately 0.5cm when hovering. While I think a slight movement is good for enhancing user experience, this shift was too pronounced. To address this, I added padding to the anchor element as well.

   The second issue was I noticed a transition with a rectangular yellow background upon the mouse leaving the nav-item. To resolve this, I added a bootstrap class called 'rounded-2' to the anchor element and removed the border-radius from the CSS.

3. **What have I learned by creating my web portfolio?**

   I have been learning how to use Bootstrap, especially focusing on utilizing the col class to adjust the layout for different browser sizes.

   Also, I have become accustomed to checking for accessibility as well. I use extensions to assess whether the contrast is good enough and to identify any errors. For example, one error I usually encounter is missing aria labels. By using tools like WAVE, I can discover and address these problems.

4. **The change between the design in Figma and the website.**

   During the process of creating my website, I made some adjustments to the design from Figma and below I am going to talk about the change and reason.

   i. On the work portrait page, the layout in Figma consisted of 2 rows with 3 columns. However, during the website development process, I realized that if each row contained 3 photos, the individual photos would not be big enough. Since it's a photography portrait page and I wanted to showcase my work in a larger size, I decided to change the layout to 2 columns and 3 rows for the tablet and desktop versions.

   ii. I have 3 projects on my work page, and within each project page, there are two buttons at the bottom, 'Back to Work' and 'Next'. I have added a background color blue with padding to both buttons when hovering, similar to the buttons on the home page and about me page. Since my portfolio follows a simple design, I don't want to overstyle the buttons. Therefore, I decided to align the styling of all buttons on content pages to be the same.

   iii. On the contact page, I placed an image of myself on the right side. In the Figma design, this picture was intended to remain on the mobile version as well. However, after testing it on my mobile device, I think the image is unnecessary. As the small viewport of mobile devices, the primary focus should be on the contact form. Therefore, I decided to remove the image from the smaller version (<768px) while keeping it in the bigger version (>768px). Since there is enough space on desktop screens, the image can serve as a decorative element without distracting from the main content.

   iv. I have reduced the shadow area at the bottom of the navigation bar on the website. Since I used the 'sticky-top' class to keep the nav-bar fixed at the top while scrolling down, with this setup, I think a subtle shadow effect is enough to distinguish between the navigation bar and the content area.
