---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Siderophores: Bacterial Swiss Army knives"
subtitle: ""
summary: "Bacteria can use siderophores to increase their survival, to signal with other cells, and strike against other species."
authors: []
tags: []
categories: []
date: []
lastmod: []
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Image by [PublicDomainPictures](https://pixabay.com/users/publicdomainpictures-14/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2186) from [Pixabay](https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2186)"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Siderophores are small molecules that bacteria primarily use to scavenge for iron in their environment ([which we discussed previously](https://www.asm.org/index.php/general-science-blog/item/6411-siderophores-bacterial-iron-scavengers)). But siderophores can do double duty, with functions in survival, attack, and signalling, making these molecules bacterial Swiss Army knives. 

## Survival

{{< figure src="image_1.png" title="Figure 1. Part of the periodic table highlighting some of the elements shown to be bound by siderophores. Those highlighted in green (Mn, Fe, Zn) are essential for growth and those in yellow (B, Si, Cu) are helpful for survival or signaling. [Source](https://commons.wikimedia.org/wiki/File%3APeriodic-table.jpg)." lightbox="true" >}}

[Fig]The affinity of siderophores for iron occurs along a spectrum from high to low, and where a siderophore falls on this spectrum can alter their potential to bind other elements. In the last siderophore post, we learned that siderophores can import essential nutrients other than iron like manganese or zinc. But siderophores can also bind non-essential nutrients, as occurs with the [silicon-binding enterobactin](http://www.dx.doi.org/10.1039/c3cc44437f) found in the root system of a Cameroonian medicinal plant. This silicon-binding ability doesn’t seem to benefit the producing _Streptomyces_ species, but likely acts as a cooperative molecule that provides the silicon its plant host requires. 

Some siderophores can also bind copper, not for growth, but for survival by decreasing toxic quantities to manageable ones. [Copper is toxic](http://www.dx.doi.org/10.1074/jbc.R111.316406) to bacteria, capable of killing methicillin-resistant _Staphylococcus aureus_ within 90 minutes (they can survive 72 hours on stainless steel). Copper binds to cellular proteins, altering their structure and thus their ability to function. And like iron, copper has redox potential so it can also undergo the [Fenton reaction](https://www.ncbi.nlm.nih.gov/pubmed/8597169), taking or trading electrons between Cu^1+^ and Cu^2+^ to generate hydroxyl radicals (negatively charged oxygen species like OH- or OH˙ that damage DNA).

{{< figure src="image_2.png" title="Figure 2. Enterobactin uses catechols (red) to bind iron and copper. [Source](https://en.wikipedia.org/wiki/Enterobactin#/media/File:Enterobactin.svg)." lightbox="true" >}}

Yersiniabactin is one siderophore that can [bind copper](http://www.jbc.org/content/290/31/18967.full.pdf), defending against both copper toxicity and reactive oxygen species. Enterobactin can also bind copper, but only after oxidation of the siderophore by the protein [CueO](https://jb.asm.org/content/186/17/5826.short). Enterobactin binds iron using three structural features called catechol rings (circled in Fig. 2). If these rings are left unoxidized in the non-iron-bound-siderophore they can reduce copper, which worsens toxicity. By oxidizing enterobactin, CueO both helps the siderophore bind toxic copper and prevents it from becoming more toxic. 

Both copper and reactive oxygen species are encountered by infection-causing bacteria within macrophages, which use those methods to kill invaders. Two siderophores that use catechol rings to bind iron, salmochelin and enterobactin, can [protect bacteria against the “oxidative burst”](http://www.dx.doi.org/10.1042/BJ20121771). The catch is that they must be inside the cell. The _Staphylococcus_ siderophore [staphyloferrin B](http://www.dx.doi.org/10.1007/s00284-014-0567-y) also protects against reactive oxygen species, but siderophores that lack catechols, such as yersiniabactin and aerobactin, aren’t protective. 

## Signaling

Instead, yersiniabactin appears to act as a signaling molecule with the immune response. The siderophore has been shown to help [_Klebsiella pneumoniae_ infections spread](http://www.dx.doi.org/10.1128/mBio.01397-16) and increase inflammation (which increases the production of reactive oxygen species). Other siderophores act as signals to cells of either the same or differing bacterial species. Researchers have also found [boron-bound siderophores](http://www.dx.doi.org/10.1021/ja073788v) in seawater, where boron is quite common. Since bacteria don’t require boron and the boron-siderophore structure is different from iron-bound siderophore, the authors suggest that they function as signaling molecules instead of scavengers. Perhaps their signalling function is similar to pseudomonad [pyoverdine, which helps to regulate](http://www.dx.doi.org/10.1073/pnas.092016999) its own production, as well as that of other proteins like toxins.

{{< figure src="image_3.png" title="Figure 3. When _E. coli_ and _B. subtilis_ are grown on agar together (top left), _B. subtilis_ begins sporulation indicated by the expression of fluorescent proteins (bottom left). However, culturing _B. subtilis_ with _B. circulans_ (top right), doesn't induce sporulation (bottom right). [Source, Fig. 1](http://aem.asm.org/content/83/10/e03293-16/F1.expansion.html)." lightbox="true" >}}

Some strains of bacteria belonging to the Firmicute phylum, such as _Clostridia_ and _Bacillus_, form endospores. Endospores are like survival pods that enable the bacteria to survive harsh conditions. The process of endospore formation (sporulation) occurs in response to environmental signals, such as low nutrient levels. Recently, researchers have identified another one, siderophores. When [_Bacillus subtilis_](http://www.dx.doi.org/10.1128/AEM.03293-16) imports siderophores produced by other species (e.g., enterobactin from _E. coli_), this triggers sporulation. Sporulation frees up resources for _E. coli_ but enables long-term survival for _B. subtilis_.

## Striking

The poaching of siderophores by non-producing bacterial species (such as enterobactin import by _B. subtilis_) is common in the microbial world. But siderophores are not always what they appear to be—and bear more than metallic gifts. [Sideromycins](https://pubs.rsc.org/en/content/articlelanding/2015/DT/C4DT03559C) are siderophores linked to antibiotics, their import by microbial competitors inhibits protein synthesis, making siderophores the original Trojan Horse. Additionally, the pseudomonad siderophores pyochelin and pyoverdine can create hydroxyl radicals. This helps _Pseudomonas_ spp. [degrade toxic molecules](http://www.dx.doi.org/10.2217/17460913.2.4.387) and perform other functions. [Pyochelin-produced](https://doi.org/10.1371/journal.pone.0046754) reactive oxygen, for instance, can be used a weapon in interspecies warfare with _Escherichia coli_. Of course, enterobactin can also help protect _E. coli_. 	

As we’ve seen, siderophores are not limited to iron binding but have alternate functions that can range from cell signaling, to cooperative element scavenging, to oxidative stress protectors or even producers. Microbes even use siderophores as weapons against each other, taking advantage of their competitors’ need for iron. So are there ways to target these bacterial Swiss Army knives with antibiotic treatments and turn siderophores against their makers? Stay tuned for the final installment in the siderophore series.

_This is Part 2 in a multipart post about bacterial siderophores. See [here](https://www.asm.org/index.php/general-science-blog/item/6411-siderophores-bacterial-iron-scavengers) for Part 1: an introduction to iron-binding capabilities of siderophores. Next: can humans develop treatments to exploit our knowledge of siderophores?_
