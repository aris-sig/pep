+++
title = 'My First Post'
date = 2024-10-21T04:50:25Z
draft = false
+++
# Welcome to My Blog!

Hello, and welcome to my very first blog post! I'm excited to share my thoughts, experiences, and projects with you. In this post, I’ll discuss my journey in learning web development and data visualization.

## What I've Learned So Far

Web development has been an incredible journey, and I’ve learned so much in a short amount of time. Here are a few key areas I've focused on:

1. **HTML & CSS**: Understanding the structure of web pages and how to style them.
2. **JavaScript**: Adding interactivity to web pages.
3. **Python**: Using Python for data analysis and visualization.
4. **Static Site Generators**: How to use Hugo to create fast and efficient blogs.

## My Favorite Tools

Here are some tools that I’ve found particularly helpful during my learning journey:

- **VSCode**: A powerful code editor with great extensions for web development.
- **GitHub**: For version control and collaboration.
- **Plotly**: An amazing library for creating interactive visualizations.

## Interactive Data Visualization

One of the most exciting parts of web development for me has been creating interactive charts. Below is an example of an interactive Plotly chart generated in Python. 

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<div>
  <div id="my-python-plot" class="plotly-graph-div" style="height: 500px; width: 100%;"></div>
  <script type="text/javascript">
    var trace1 = {
      x: [1, 2, 3, 4, 5],
      y: [10, 15, 13, 17, 22],
      mode: 'lines+markers',
      type: 'scatter',
      name: 'Data Points'
    };

    var data = [trace1];

    var layout = {
      title: 'Interactive Line Chart',
      xaxis: {
        title: 'X Axis'
      },
      yaxis: {
        title: 'Y Axis'
      }
    };

    Plotly.newPlot('my-python-plot', data, layout);
  </script>
</div>

## Conclusion

Thank you for reading my first blog post! I look forward to sharing more insights, projects, and tutorials in the future. If you have any questions or topics you’d like me to cover, feel free to reach out.

Stay tuned for more posts, and happy coding!