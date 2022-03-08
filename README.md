<h1 align="center">
[The Odin Project: Intermediate HTML and CSS] - Project: Sign Up Form
</h1>

## Intro

-   The goal of this project was to practice CSS Grid. We were to create an Admin Dashboard where we layed out all the element only using CSS Grid
-   The project can be found here: . It is hosted by Netlify.
-   You can find more on the project here: [The Odin Project - Admin Dashboard](https://www.theodinproject.com/paths/full-stack-javascript/courses/intermediate-html-and-css/lessons/admin-dashboard)

## Lessons Learned

-   For this project, I challenged myself to really use CSS gid to layout the entire structure of the page and using it to layout elements inside the container where I would normally default to flex
-   For example, in the header I had two rows div. For those two divs I initially planned to use flex, but I wanted to see how it will be with grid. To accomplish this I use the `max-content` property on the `grid-template-columns`
-   `max-content` represents a box's ideal size in a given axis when given infinite available space. Basically it is saying the size a box needs to contain all of its content without being wrapped or it overflows the box
    -   Maximum width of the content to decide the size of the box
    -   I also learned about `min-content and fit-content` makes it easier to define responsive widths https://blog.logrocket.com/understanding-min-content-max-content-fit-content-css/
-   Also when making content that looks like list format it is better to use UL and LI tags. This truned out better than manually doing it with grid

## Achievements

-   I practiced my CSS selectors and no longer had to create random class names to give style to elements
-   I saw the power of CS grid and I feel more comfortable with it

## Next Steps

-   During my planning phase where I brainstorm the layout, how the HTML structure will look like, and CSS styling use I can start creating potential font sizes so that the sizes are consistent for titles, subtitles, and so on. This will make styling more consistent
-   Continue practicing CSS grid and using it to layout elements. Of course always see what will be better Flex or Grid especially where determining the behavior you want to achieve and what tool will work best

## Technologies:

-   HTML
-   HTML Semantic Elements
-   CSS
-   CSS Grid
-   CSS Selectors
-   Netlify
