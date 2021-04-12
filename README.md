# Interactive Biodiversity Dashboard

## Project Overview
The purpose of this project is to build an interactive dashboard using event handlers in JavaScript and Plotly.js to create graphs, such as bubble graphs and bar graphs. The finished product is deployed to GitHub Pages.

## Software

The only software that I used to create this dashboard is [VS Code](https://code.visualstudio.com/). However, any code editor that supports the following can be used:
  - HTML
  - JavaScript
  - D3.js
  - Plotly.js
  - CSS
  - Bootstrap

## Project Completion

To view the completed dashboard, please [click here](https://mishkanian.github.io/plotly_deploy.io/).

### GitHub Pages Deployment Issue  
After successfully testing the dashboard locally, the header image was not displaying correctly after deployment to GitHub Pages. The issue is caused by [style.css](https://github.com/Mishkanian/plotly_deploy.io/blob/master/static/css/style.css) on line 2. The file path "../images/lab.jpg" was not recognized by GitHub Pages.
```css
/* This is a workaround to have the image display on GitHub Pages.
background-image: url("https://raw.githubusercontent.com/Mishkanian/plotly_deploy.io/master/static/images/lab.jpg");
```


**Author: Michael Mishkanian**  
For all questions and inquiries, please contact me on [LinkedIn](https://www.linkedin.com/in/michaelmishkanian/).
