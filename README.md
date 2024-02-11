# dashboard

GitHub Pages: https://kyupin64.github.io/dashboard/

Git Log:

Inspiration:
[Intellecta Dashboard](https://dribbble.com/shots/23428580-Intellecta-Dashboard) by Halo UI/UX,
[Dashboard landing concept](https://dribbble.com/shots/18538522-Dashboard-landing-concept) by Nicolas Solerieu

Image source: [papers.co](https://papers.co/desktop/nw64-space-star-blue-night-nature/)

I made this dashboard for a task/time management website. It's not actually functional, but I think it looks good. It's adaptive to screen sizes from a width of about 350px to 1540px. I replicated the layout of the page from the Intellecta dashboard design and took inspiration for the theme from the dashboard landing concept design, which has a space theme. I made the upper left logo myself in paint.net, and the rest of the icons are from [Font Awesome 6](https://fontawesome.com/). I made a navigation bar at the top of the screen on smaller screen sizes which is fixed to the left side on larger screen sizes. The activity bar was made using a grid with 8 columns and borders on either side of each column with absolutely positioned cards on top for the activities. One of my favorite features is the scrolling to-do list, which isn't difficult to do but I still think is really cool. The most challenging thing to implement was the summary graph, which required me to research how to make a graph using css and how to use the ::before pseudo-element. It includes a list for each axis and a flex container for the bars. Just for fun, I chose to use tooltips for the height of the bars (which I still don't fully understand; for example, I'm still not sure why there needs to be a double hyphen before the tooltip, or if that's even required (?)). I also used many flexboxes to make it easier to structure the page and make it adaptable to different screen sizes. Thanks for reading, and I hope you enjoy my website!