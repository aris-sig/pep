---
title: Required
description: 
url: ""
---
    # Sales Over Time
    
    Below is a Plotly chart showing sales over time.

<div id="lineChart" style="width: 100%; max-width: 600px; height: 400px;"></div>
    
    <script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
    <script>
    var trace1 = {
        x: ['2024-01-01', '2024-02-01', '2024-03-01', '2024-04-01'],
        y: [10, 12, 8, 15],
        mode: 'lines+markers',
        type: 'scatter'
    };

var layout = {
    title: 'Monthly Sales',
    xaxis: { title: 'Month' },
    yaxis: { title: 'Sales' }
};

Plotly.newPlot('lineChart', [trace1], layout);
</script>
    
Page content here
