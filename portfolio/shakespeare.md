---
layout: default
title: Tidy Shakespeare
tags: ["R", "Shakespeare"]
---
# Tidy Shakespeare
{{ page.date | date: "%d %B, %Y" }}

## Relationships between Words
<figure>

![10-line Section Correlations in Hamlet](/assets/section_correlations_Hamlet.png)

<figcaption><b>Figure:</b> 10-Line Section Correlations in Hamlet  
</figcaption>

</figure>

## Sentiment

How does sentiment differ between genres? 

Comedies have positive sentiment throughout, while tragedies are progressively more negative.

<figure>

![Sentiment Patterns Across Shakespeare's Dramatic Structure](/assets/combined_genre_example_by_act.png)

<figcaption><b>Figure:</b>  Sentiment patterns across acts in Shakespeare's plays, comparing aggregate genre trends against exemplar works (Twelfth Night, Henry IV Part 1, Hamlet). Blue bars indicate positive sentiment, red bars indicate negative sentiment, with color intensity reflecting magnitude. 
</figcaption>

</figure>

<details> 

<summary>Details</summary>

## GitHub

[Shakespeare](https://github.com/hopemcmanus/shakespeare)

### Description

This repository contains data and text analysis.

### Data

This repository contains structured text data for 37 plays of William Shakespeare in CSV format, prepared for tidy text analysis.

### Analysis

Analyses include sentiment scoring, word frequency and relationships using n-grams and correlations.

### Technical Skills 

- **Data Wrangling**: dplyr; tidyr; regex text extraction (str_extract, str_remove), reshaping (pivot_wider), combining datasets (bind_rows)
- **Text Analysis**: tidytext; sentiment lexicons
- **Data Visualisation**: ggplot2; custom themes
- **Statistical Methods**: normalisation; aggregation

### Attribution and License

The texts were accessed using the [`gutenbergr`](https://github.com/ropensci/gutenbergr) R package, which provides Project Gutenberg Plain Text UTF-8 editions identified as being in the public domain. The texts reproduced here are based on those editions and therefore retain the same public-domain status.

The analyses and scripts are adapted from [*Tidy Text Mining with R*](https://github.com/juliasilge/tidy-text-mining) by Julia Silge and David Robinson (2017), used under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States License (CC BY-NC-SA 3.0 US).

The Gutenberg metadata is from the [text2map GitLab repository](https://gitlab.com/culturalcartography/text2map) (MIT License).

### Tags

<ul>
    {%- for tag in tags -%}
    <li>
        <!-- <a href="/tags/{{tag}}">{{tag}}</a> -->
        {{tag}}
    </li>
    {%- endfor -%}
</ul>

</details>