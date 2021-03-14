# Web-Design-Challenge
Checklist of requirements:
->7 pages total: index.html, cloudiness.html, data.html, humidity.html, maxtemp.html, comparison.html, windiness.html

Landing page: 
  ->An explanation of the project: used text from demonstration
  ->Links to each visualizations page in sidebar w anchored preview images: done
Four visualization pages w/:
  --> A descriptive title and heading tag.
  -->The plot/visualization itself for the selected comparison.
  -->A paragraph describing the plot and its significance.
Comparisons page:
 -->Contains all of the visualizations on the same page so we can easily visually compare them.
  -->Uses a Bootstrap grid w/ 2 across visualizations on md, lg, elg, 1across on xs and sm
Data page:
-->Displays a responsive table containing the data used in the visualizations.
-->The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
-->The data must come from exporting the `.csv` file as HTML, or converting it to HTML.

Nav:
-->name of the site on the left of the nav which allows users to return to the landing page from any page.
-->dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
-->Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.: DONE
-->Is responsive (using media queries): DONE-- use media query for color change; use Bootstrap for other changes 
-->background color change: DONE

1 persistent problem: on data.html, neither the 'Plot' dropdown nor the hamburger work. The code for the <nav> is identical between data.html and other pages. Can you point out what is messing this up?
A style question: on index.html and other pages with a sidebar, the sidebar is styled to be the same height as the main part of the page. I tried different options for shortening the sidebar, but always ran into problems. Could you point out a simple way to make the height of the sidebar short?
