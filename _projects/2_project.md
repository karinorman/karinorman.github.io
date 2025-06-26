---
layout: page
title: Temporal Biodiversity Change
description: Measuring change in ecological community structure through time.
img: assets/img/biodiv_change.jpg
importance: 2
category: research themes
related_publications: true
bibliography: references.bib
---

A major theme of my research is leveraging existing long term monitoring efforts to understand the impact of global change drivers on ecological communities. I approach this question using multiple dimensions of biodiversity, including tradititional species-based metrics like alpha and beta diversity, their functional diversity counterparts that incorporate data on functional traits, and recently reaching into interaction network approaches. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/norman2025_fig.jpeg" title="Norman et. al 2025" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3met_long.jpeg" title="time series models" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure depicting the scope of the time series included in Norman et. al 2025 (on the left), with (A) Map of time series locations with points colored by taxa and (B) histograms of time series duration broken down by taxa; and the general trends for different biodiversity metrics derived from those time series (on the right).
</div>

I analyzed thousands of community time series to assess change in functional structure across taxa, time, and space, which showed that across communities there is no general trend in functional metrics. However, at the level of individual communities there is profound reorginization leading to changes in functional evenness and losses and gains in functional redundancy with potentially profound implications for those communities' ability to respond to future stressors {% cite norman2025no %}.

This work built on previous explorations of the relationship between community change (i.e. turnover) and the maintenance of community stability. We found that temporal fluctuations in species abundance and turnover of functionally similar species help stabilize communities {% cite jarzyna2022community %}. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/jarzynafig.jpg" title="Jarzyna et. al 2022" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Relationships between community stability and change in community taxonomic composition as given by temporal dissimilarity (a), dissimilarity due to species replacement (b), dissimilarity due to species richness (c), relative contributions of species replacement to dissimilarity (d), and relative contributions of richness change to dissimilarity (e) for four taxonomic groups: small mammals, ground beetles, fish, and freshwater macroinvertebrates. Density plots in (d) and (e) show the frequency of relative contributions of species replacement and richness change, respectively, to dissimilarity in community taxonomic composition. From Jarzyna et al. 2022.
</div>

After spending a lot of time thinking about community structure, the potential to incorporate changes in species interactions through time felt like the natural next step. As part of a <a href="https://bios2.usherbrooke.ca/">BIOS^2^</a> funded working group, we developed an approach for moving from deterministic to probabilistic expressed interaction networks, that take into account ecological and community context when expressing the likelihood of an interaction occurring {% cite banville2024deciphering %}. This is foundational theoretical work for better incorporating interaction data into measures of community change. 
