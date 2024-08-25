---
layout: page
title: Property Investment BI
description: A property investment dashboard to visualize losses and gains across properties
img: assets/img/select-property-management.png
importance: 2
category: work
giscus_comments: false
---

<!-- Property Investment Tableau Public Visualization -->
<div class="row justify-content-center">
    <div class="col-12 mt-3 mt-md-0">
        <div class="tableau-container">
            <div class='tableauPlaceholder' id='viz1724290948396' style='position: relative'>
                <noscript>
                    <a href='#'><img alt='Dashboard 2 ' src='https://public.tableau.com/static/images/Pr/PropertyInvestmentBI/Dashboard2/1_rss.png' style='border: none' /></a>
                </noscript>
                <object class='tableauViz' style='display:none;'>
                    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
                    <param name='embed_code_version' value='3' />
                    <param name='site_root' value='' />
                    <param name='name' value='PropertyInvestmentBI/Dashboard2' />
                    <param name='tabs' value='no' />
                    <param name='toolbar' value='yes' />
                    <param name='static_image' value='https://public.tableau.com/static/images/Pr/PropertyInvestmentBI/Dashboard2/1.png' />
                    <param name='animate_transition' value='yes' />
                    <param name='display_static_image' value='yes' />
                    <param name='display_spinner' value='yes' />
                    <param name='display_overlay' value='yes' />
                    <param name='display_count' value='yes' />
                    <param name='language' value='en-US' />
                </object>
            </div>
        </div>
    </div>
</div>

<h2>Interactive Property Investment Dashboard</h2>

<p>This Tableau Public visualization offers a comprehensive view of property investment data across four distinct properties over a two-year period. The dashboard provides insights into various financial aspects of real estate investment, including income streams and expense categories.</p>

<h3>How to Use:</h3>

<ul>
  <li>Click on property names to filter data for individual or multiple properties</li>
  <li>Adjust the time slider to view data for specific periods</li>
  <li>Use the category dropdown to focus on particular expense or income types</li>
  <li>Hover over data points for detailed information</li>
</ul>

<h3>Key Features:</h3>

<ol>
  <li><strong>Property Filter</strong>: Focus on individual properties or compare multiple properties simultaneously by selecting specific properties of interest.</li>

  <li><strong>Time Period Selection</strong>: Selecting time periods allows for trend analysis and seasonal comparisons.</li>
   
  <li><strong>Category Breakdown</strong>: Category selection enables a granular analysis of different financial categories affecting property performance.</li>
</ol>

<p>This interactive tool is designed to provide valuable insights for property investors, managers, and analysts, offering a dynamic way to explore and understand property investment performance over time.</p>

<style>
    .tableau-container {
        width: 100%;
        max-width: 100%;
        margin: 0 auto;
        overflow: hidden;
    }
</style>

<script type='text/javascript'>
    function resizeViz() {
        var divElement = document.getElementById('viz1724290948396');
        var vizElement = divElement.getElementsByTagName('object')[0];
        var containerWidth = divElement.offsetWidth;
        var aspectRatio = 795 / 1366; // Original height / width

        vizElement.style.width = '100%';
        vizElement.style.height = (containerWidth * aspectRatio) + 'px';
        
        if (containerWidth < 500) {
            vizElement.style.height = (containerWidth * 1.5) + 'px'; // Adjusted for very small screens
        }
    }

    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    scriptElement.onload = function() {
        resizeViz();
        window.addEventListener('resize', resizeViz);
    };
    var divElement = document.getElementById('viz1724290948396');
    divElement.parentNode.insertBefore(scriptElement, divElement);
</script>
