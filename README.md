# Web Design - Web Visualization Dashboard (Latitude)

## Background

This project creates a web dashboard of visualizations that were created using a python script, matplotlib, and spicy.stats. In building this dashboard, individual pages were created for each plot with a bootstrap navbar for navigation between pages. These pages contain the visualizations and their corresponding explanations. The landing page includes a comparison of all of the plots, and an additional web page where the user can view the data used to build the plots.

![Images/landingResize.png](Images/landingResize.png)

### Website dashboard includes the following features:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. A sidebar containing preview images of each plot, and clicking an image takes the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so the user can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component. 
    * The data comes from exporting the `.csv` and converting it to HTML.  Pandas was used  to generate a HTML table from a pandas dataframe. 

The website includes a navigation menu at the top of every page that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). 

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page

Large screen:

![Landing page large screen](Images/landingResize.png)

Small screen:

![Landing page small screen](Images/landing-sm.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](Images/comparison-lg.png)

Small screen:

![comparison page small screen](Images/comparison-sm.png)

#### <a id="data-page"></a>Data page

Large screen:

![data page large screen](Images/data-lg.png)


Small screen:

![data page small screen](Images/data-sm.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![visualize page large screen](Images/visualize-lg.png)

Small screen:

![visualize page small screen](Images/visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:
![nav menu small screen](Images/nav-sm.png)

## Viewing the Webpage:

The webpage can be viewed through github pages at https://trvossler-max.github.io/