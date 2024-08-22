---
layout: page
title: GWAS information with publications dashboard
description: This dashboard organizes over 170k genes by snp, disease category, or search term.
img: assets/img/GWAS.png
importance: 1
category: work
---

<!-- Gene Information Publication Tableau Dashboard -->
<div class="row justify-content-center">
    <div class="col-12 mt-3 mt-md-0">
        <div class="tableau-container">
            <div class='tableauPlaceholder' id='viz1724292270074' style='position: relative'>
                <noscript>
                    <a href='#'>
                        <img alt='Story 1 ' src='https://public.tableau.com/static/images/78/783GW4MW4/1_rss.png' style='border: none' />
                    </a>
                </noscript>
                <object class='tableauViz' style='display:none;'>
                    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
                    <param name='embed_code_version' value='3' />
                    <param name='path' value='shared/783GW4MW4' />
                    <param name='toolbar' value='yes' />
                    <param name='static_image' value='https://public.tableau.com/static/images/78/783GW4MW4/1.png' />
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
<div class="caption text-center">
    This is a Tableau Public visualization showing gene information publication data. The genes were searched through NCBI's ClinVar database, cross-referenced through the GWAS API, and matched with publications on PubMed.
</div>

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
        var divElement = document.getElementById('viz1724292270074');
        var vizElement = divElement.getElementsByTagName('object')[0];
        vizElement.style.width = '100%';
        vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    }

    function loadTableauScript() {
        var scriptElement = document.createElement('script');
        scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
        scriptElement.onload = function() {
            resizeViz();
            window.addEventListener('resize', resizeViz);
        };
        var divElement = document.getElementById('viz1724292270074');
        divElement.parentNode.insertBefore(scriptElement, divElement);
    }

    // Load the Tableau script after the page has fully loaded
    if (document.readyState !== 'loading') {
        loadTableauScript();
    } else {
        document.addEventListener('DOMContentLoaded', loadTableauScript);
    }
</script>