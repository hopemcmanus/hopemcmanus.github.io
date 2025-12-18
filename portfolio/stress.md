---
layout: default
title: The Geometry of Typologies
tags: ["Optimality Theory", "Gephi"]
---
# The Geometry of Typologies
{{ page.date | date: "%d %B, %Y" }}


<p></p>

As part my [Ph.D. dissertation](https://roa.rutgers.edu/article/view/1583.html), I investigate formal, abstract systems within [Optimality Theory](#references) (OT) using [OTWorkplace](#OTWorkplace), an environment that calculates and displays OT objects and can export data to visualise a Typohedron, a graphic representation of a typology, in applications such as yEd or Gephi. 

<p></p>
<figure>

![Typohedron](/assets/ngo.png)

<figcaption><b>Figure:</b> A partial Typohedron for an OT system for prosodic stress with deletion, showing only the left-aligning, trochaic languages of the typology. Language names are from empirical support [<a href="https://lite.gephi.org/?file=https://raw.githubusercontent.com/hopemcmanus/hopemcmanus.github.io/main/assets/ngoLTr.gexf"   target="_blank" 
   rel="noopener noreferrer">Explore in Gephi Lite</a>] 

</figcaption>

</figure>
<p></p>

<figure>

![Typohedron](/assets/ngX.f.pf.png)

<figcaption><b>Figure:</b> A Typohedron for a stress-prosodic system calculated in OTWorkplace. Language names  refer to Properties [<a href="https://lite.gephi.org/?file=https://raw.githubusercontent.com/hopemcmanus/hopemcmanus.github.io/main/assets/ngo.json"   target="_blank" 
   rel="noopener noreferrer">Explore in Gephi Lite</a>] [<a href="https://github.com/hopemcmanus/OTWorkplace/blob/582c6da0fcf3beea71e931d75679d15a180b3c7f/OT%20Workplace%20Files/nGX.f.pf%20encyclo.xlsx"   target="_blank" 
   rel="noopener noreferrer">Download the OTWorkplace Book</a>] 

</figcaption>

</figure>
<p></p>
 

<details> 
<summary>Details</summary>

## Theory

In Optimality Theory (OT), a typology is the set of all grammars and languages. A typology emerges once an OT system is defined, specifying structures and constraints. A typology has a [space](#space), [classification](#classification) and [geometry](#geometry).   

## References

| Topic | Theory | References |
|------|-----|------|
| <h3 id="space" style="all: unset; display: inline;">**Space**</h3> | Entailed Ranking Condition (ERC) | [Prince 2002](https://roa.rutgers.edu/article/view/510.html) |
| | Most Informative Basis (MIB), Skeletal Basis (SKB), Fusional Reduction (FRed) | [Brasoveanu and Prince 2011](https://roa.rutgers.edu/article/view/804.html) |
| <h3 id="classification" style="all: unset; display: inline;">**Classification**</h3> | Property Theory |  [Alber and Prince 2015](https://roa.rutgers.edu/article/view/1265); [Alber, DelBusso and Prince 2016](https://roa.rutgers.edu/article/view/1410.html); [DelBusso 2016](https://rucore.libraries.rutgers.edu/rutgers-lib/55993/)|
| <h3 id="geometry" style="all: unset; display: inline;">**Geometry**</h3> | Mother of All Tableaux (MOAT), Permutohedra, Typohedra | [Merchant and Prince 2016](https://roa.rutgers.edu/article/view/1303); [Alber and Prince 2022](https://roa.rutgers.edu/article/view/1838.html); [DelBusso 2016](https://rucore.libraries.rutgers.edu/rutgers-lib/55993/) |
| <h3 id="OTWorkplace" style="all: unset; display: inline;">**OTWorkplace**</h3> | An interactive add-on environment for Microsoft Excel  | [Prince, Merchant and Tesar 2006-2017]((https://sites.google.com/site/otworkplace)) |
| | The Book of nGx | [Alber and Prince 2016](https://roa.rutgers.edu/article/view/1663.html)


### Technical Skills 

- **Analysis**: OT Workplace/VBA, Gephi

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