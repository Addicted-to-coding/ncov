---
title: Genomic analysis of nCoV spread. Situation update 2020-01-23.
authors: "Bedford, Neher, Hadfield, Hodcroft, et al"
authorLinks: "https://nextstrain.org"
affiliations: "Fred Hutch, Seattle, USA and Biozentrum, Basel, Switzerland"
date: "2020 Jan 23"
dataset: "https://nextstrain.org/ncov?d=map"
abstract: "This report uses publicly shared novel coronavirus (nCoV) genomic data from GISAID to estimate rates and patterns of viral epidemic spread. We plan to issue updated situation reports as new data is produced and shared."
---


# [Coronaviruses](https://nextstrain.org/ncov)

### Further Reading:

* General information on coronaviruses on [wikipedia](https://en.wikipedia.org/wiki/Coronavirus) _2020-01-23_
* Material provided by the [US CDC](https://www.cdc.gov/coronavirus/index.html) _2020-01-23_
* Organization and genome on [viralzone](https://viralzone.expasy.org/764?outline=all_by_species) _2020-01-23_

```auspiceMainDisplayMarkdown

## Different human coronaviruses

Coronaviruses (CoV) are members of a diverse species of (+)ssRNA viruses which have a history of causing respiratory infections in humans.
Some variants of coronaviruses are associated with outbreaks, others are continuously circulating and cause mostly mild respiratory infections (e.g. the common cold).

#### SARS-CoV & MERS-CoV
The most well known of these coronaviruses is [SARS-CoV](https://en.wikipedia.org/wiki/Severe_acute_respiratory_syndrome) ("severe acute respiratory syndrome"), which in a 2002-2003 outbreak spread around the world and resulted in [over 8000 cases and 774 deaths](https://www.theguardian.com/world/2017/dec/10/sars-virus-bats-china-severe-acute-respiratory-syndrome), with a fatality rate of around 9-11%.

In 2012, a novel coronavirus, [MERS-CoV](https://en.wikipedia.org/wiki/Middle_East_respiratory_syndrome) ("Middle East respiratory syndrome"), causing severe respiratory symptoms was identified. MERS has resulted in fatalities comparable to SARS, however the transmission route of MERS is very different. Whereas SARS was efficiently spread from one human to another, human MERS infections were generally a result of independent zoonoses (animal to human transmissions) from camels (see [Dudas _et al._](https://elifesciences.org/articles/31257) for more information). This has lead to a self-limiting outbreak largely restricted to the Arabian Peninsula.


#### Seasonal CoV
However it's not fair to categorize all coronaviruses as deadly as SARS-CoV and MERS-CoV.
There are four "seasonal" coronaviruses and commonly infecting humans each year.
Compared with SARS, these seasonal coronavirus strains are ["much more prevalent, much less severe, and common causes of influenza‐like illness (ILI)"](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5820427/).
In fact, [5](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2879166/) - [12](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5820427/)% of all ILI cases test positive for coronaviruses, so they are rather common, resulting in millions of infections every year with low severity.


#### Animal reservoirs
Coronaviruses infect a wide range of animals, and the human outbreaks described above are a result of one or more "jumps" from these animal reservoirs into the human population.
SARS is believed to have arrived in the human population from [horseshoe bats via a masked palm civet intermediary](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1006698).


#### Human to Human transmission
The ability for different lineages to be transmitted between humans is extremely important to understand the potential development of an outbreak.
Due to the ability of SARS to spread between humans and the high case fatality rate, SARS (or a SARS-like virus) is considered a [global public health threat](https://www.who.int/whr/2007/overview/en/index1.html) by the WHO.

```


# [Novel coronavirus (nCoV) 2019-2020](https://nextstrain.org/ncov)

### Further Reading:

* New China virus: Five questions scientists are asking  [Nature news](https://www.nature.com/articles/d41586-020-00166-6) _2020-01-22_
* China virus latest: first US case confirmed  [Nature news](https://www.nature.com/articles/d41586-020-00154-w) _2020-01-21_
* New virus surging in Asia rattles scientists  [Nature news](https://www.nature.com/articles/d41586-020-00129-x) _2020-01-20_
* New virus identified as likely cause of mystery illness in China [Nature news](https://www.nature.com/articles/d41586-020-00020-9) _2020-01-08_

```auspiceMainDisplayMarkdown

## Recent outbreak of a novel coronavirus
In December 2019, a new illness was first detected in Wuhan, China.
We now know this to be another outbreak of coronavirus in humans (the 7th), and it is being called nCoV (novel coronavirus).

As of January 23rd, 2020 over 624 cases and 17 deaths [have been reported](https://en.wikipedia.org/wiki/2019%E2%80%9320_outbreak_of_novel_coronavirus_(2019-nCoV)).
It's still too early to know the case fatality rate, but early indications are that it is less than SARS-CoV.
The case counts are dramatically rising in part due to increased surveillance and testing, with 131 new cases reported on Jan 22nd, 2020.

While the outbreak seems to be centered in Wuhan, which is now [under quarantine](https://twitter.com/PDChina/status/1220060879112282117), the virus has spread throughout China and abroad, including Hong Kong, Macau, Thailand, USA, Japan and South Korea.


The origin of the virus is still unclear, however [genomic analyis](http://virological.org/t/ncovs-relationship-to-bat-coronaviruses-recombination-signals-no-snakes/331) suggests nCoV is most closely related to viruses previously identified in bats.
It is plausible that there were other intermediate animal transmissions before the introduction into humans.

#### Nextstrain narratives

The following pages contain analysis performed using [nextstrain](https://nextstrain.org).
Scrolling through the left hand sidebar will reveal paragraphs of text with a corresponding visualization of the genomic data on the right hand side.

To have full genomes of a novel & large RNA virus this quickly is a remarkable achievement.
These analyses have been made possible by the rapid and open sharing of genomic data and interpretations by scientists all around the world (see the final slide for a visualization of sequencing authorship).


```







# [How to interpret the phylogenetic trees](https://nextstrain.org/ncov)

```auspiceMainDisplayMarkdown
## Transmission trees vs phylogenetic trees

Pathogens spread through rapid replication in one host followed by transmission to another host. An outbreak can only take off when infection results in more than one subsequent infections.

As the pathogen replicates and spreads, its genome needs to be replicated many times and random mutations -- copying mistakes -- will accumulate in the genome.
Such random mutations can help to track the spread of the pathogen and learn about its transmission routes and dynamics.

<div>
  <img alt="cartoon showing how transmission tree and phylogenetic tree relate" width="500" src="https://neherlab.org/talk_images/infection_tree_combined.png"/>
</div>

The illustration above shows a sketch of transmission tree with a subset of cases that were sampled (blue).
In practice, the transmission tree is unknown and typically only rough estimates of case counts are available.
Genome sequences allow us to infer parts of the transmission tree.
In this example, three mutations (little diamonds) are indicated on the tree.
Sequences that have the same mutations are more closely related, so these mutations allow us to group samples into clusters of closely related viruses that belong to the same transmission chains.

### Reading a Phylogenetic Tree

Below, we see an illustration with a phylogenetic tree on the left, where mutations are shown as colored circles. On the right are the corresponding sequences, also with mutations shown as colored circles.
We can see that sequences that share the same mutations group together. 
When sequences appear linked by a flat vertical line, like A and B, this means there are no differences between them - their sequences are identical.

When a sequence sits on a long line on its own, like C or E, this means it has unique mutations not found in other sequences. The longer the line, the more mutations. 
A and B also have unique mutations (the green circle) not shared by the other sequences, but they are identical to each other.

<div>
  <img alt="cartoon of phylogenetic tree and corresponding alignment, with samples labelled A-E" width="500" src="http://data.nextstrain.org/toy_alignment_tree.png"/>
</div>

At the moment, the novel Coronavirus (nCoV) phylogeny may not look much like a 'tree.' 
Many of the sequences are identical - they sit together on vertical lines like A and B (some are on the left-most part of the tree). 
Others have unique or shared mutations and so sit on lines, or 'branches,' going to the right. 
You can see how many mutations a branch has by hoving your mouse over it.

```

# [Phylogenetic analysis](https://nextstrain.org/ncov?d=tree)

Here we present a maximum likelihood phylogeny of 24 strains of nCoV that have been publicly shared.
Information on how the analysis was performed is available [in this GitHub repository](github.com/nextstrain/ncov).

<br>

The colours represent the city of isolation, with the x-axis representing nucleotide divergence.

<br>

Divergence is measured as the number of changes (mutations) per base.
Since the nCoV genome is 29,000 bases long, one mutation corresponds to a distance 1/29,000 = 0.0000335. 

Sequences that have just one mutation sit just to the left of the 0.00004 line on the x-axis.

# [Phylogenetic Interpretation](https://nextstrain.org/ncov?d=tree)

We currently see little genetic diversity across the nCoV sequences, with 8 out of 24 sequences having no unique mutations.

<br>

Low genetic diversity across these sequences suggest that the most recent common ancestor of all nCoV sequences was fairly recent.

<br>

At the moment, most mutations that can be observed are singletons -- they are unique to individual genomes. Only the sequences that form the two clusters from Guangdong share mutations -- we will explore these in later slides.

<br>

Sequencing the genome of a large novel RNA virus in an evolving outbreak situation is challenging. 
Some of the differences observed in these sequences may be sequencing errors rather than actual mutations. 
Insertions, deletions, and differences at the ends of the genome are more likely to be errors and so we masked these for the purposes of this analysis.


# [Potential within-family transmission 1](https://nextstrain.org/ncov?d=tree&f_city=Shenzhen)

Of the four isolates from Shenzhen (Southeastern China) we see three isolates which are genetically identical and share three mutations unique to those three samples (you can hover your mouse over the branches to see which mutations are present).

<br>

These three samples are [known to come from a single family](https://twitter.com/JingLu_LuJing/status/1220143773532880896), and likely represent human-to-human transmission.

<br>

The fourth sample does not seem to be related to the other three, or to any other of the available sequences.
Its genome has one mutation not seen in any other genome.

# [Potential within-family transmission 2](https://nextstrain.org/ncov?d=tree&f_city=Zhuhai)

Similarly, there are two genetically-identical isolates from Zhuhai (Southeastern China) which form a cluster, sharing one unique mutation seen in no other isolate.

<br>

These two cases are also [known to come from a single family](https://twitter.com/JingLu_LuJing/status/1220143773532880896), again indicating human-to-human transmission is likely.

# [Cases outside China](https://nextstrain.org/ncov?c=country&d=tree,map)

There are reported nCoV cases in Thailand, USA, Japan and South Korea.
These cases are all linked to Wuhan, and we are not aware of evidence for nCoV transmission in these countries.

<br>

The only currently available sequence data for cases outside of China are the two cases from Thailand, which are coloured here in red.
These samples are genetically identical to six Chinese sequences, including five isolated in Wuhan.


# [Dating the zoonosis](https://nextstrain.org/ncov?d=tree)
The high similarity of the genomes currently suggests they have a recent common ancestor (that they have descended from the same ancestral virus recently). Otherwise, we would expect a higher number of differences between the samples..

<br>

Previous research on related coronavirus suggests that these viruses accumulate between 1 and 3 changes in their genome per month (rates of 0.003 - 0.001/site and year).

<br>

On the right, we explore how different assumptions about the rate of change, and the observed genetic diversity, give us estimates for the timing of the outbreak. 

```auspiceMainDisplayMarkdown

Here, we assume a star-like phylogeny structure along with a Poisson distribution of mutations through time to estimate the time of the most recent common ancestor ('TMRCA') of sequenced viruses:

<div>
  <img alt="graph of TMRCA estimates based on different mutation rates" width="500" src="http://data.nextstrain.org/ncov_poisson-tmrca.png"/>
</div>

As the more samples are sequenced, we expect the tree to show more structure, such that the star-like phylogeny topology is no longer a good assumption.
At this point, phylodynamic estimates of the age of the epidemic will become feasible.

```

# [Estimating the growth rate](https://nextstrain.org/ncov?d=tree)

An important quantity in the spread of a pathogen is the average number of secondary cases each infection produces.

<br>

This number is known as R0 ("R-zero" or "R-nought").
One the right, we present simple estimates of R0.

```auspiceMainDisplayMarkdown

Scientists at Imperial College London have used the number of cases observed outside of China to estimate the [total number of cases](https://www.imperial.ac.uk/mrc-global-infectious-disease-analysis/news--wuhan-coronavirus/) and suggested that there have been at least several thousand cases.
Together with our previous estimates of the age of the outbreak and information on the infectious period, we can estimate plausible ranges of R0 using a branching process model.

If we assume the outbreak started at the beginning of November 2019 (12 weeks ago), we find that R0 should range between 1.5 and 2.5, depending on how large ('n') the outbreak is now.
<div>
  <img alt="graph of R0 estimates with epidemic start 12 weeks ago" width="500" src="http://data.nextstrain.org/ncov_branching-R0-early.png"/>
</div>

If we assume a more recent start, at the beginning of December 2019 (8 weeks ago), the estimates for R0 range between 1.8 and 3.5:
<div>
  <img alt="graph of R0 estimates with epidemic start 8 weeks ago" width="500" src="http://data.nextstrain.org/ncov_branching-R0-recent.png"/>
</div>

```




# [Scientific credit](https://nextstrain.org/ncov?d=map&c=author)

We would like to acknowledge the amazing and timely work done by all scientists involved in this outbreak, but particularly those working in China.
Only through the rapid sharing of genomic data and metadata are analyses such as these possible.

The nCoV genomes were generously shared by scientists at the

 * Shanghai Public Health Clinical Center & School of Public Health, Fudan University, Shanghai, China
 * National Institute for Viral Disease Control and Prevention, China CDC, Beijing, China
 * Institute of Pathogen Biology, Chinese Academy of Medical Sciences & Peking Union Medical College, Beijing, China
 * Wuhan Institute of Virology, Chinese Academy of Sciences, Wuhan, China
 * Department of Microbiology, Zhejiang Provincial Center for Disease Control and Prevention, Hangzhou, China
 * Guangdong Provincial Center for Diseases Control and Prevention
 * Department of Medical Sciences, National Institute of Health, Nonthaburi, Thailand

These data were shared via [GISAID](https://gisaid.org). We gratefully acknowledge their contributions.



# [Detailed scientific credit](https://nextstrain.org/ncov?d=map&c=author)

These data were shared via [GISAID](https://gisaid.org). We gratefully acknowledge their contributions.

<br>

To the right we give specific sequences shared by each lab.

```auspiceMainDisplayMarkdown

The nCoV genomes were generously shared by scientists at the

 * Shanghai Public Health Clinical Center & School of Public Health, Fudan University, Shanghai, China
   - Wuhan-Hu-1/2019
 * National Institute for Viral Disease Control and Prevention, China CDC, Beijing, China
   - Wuhan/IVDC-HB-01/2019
   - Wuhan/IVDC-HB-04/2020
   - Wuhan/IVDC-HB-05/2019)
 * Institute of Pathogen Biology, Chinese Academy of Medical Sciences & Peking Union Medical College, Beijing, China
   - Wuhan/IPBCAMS-WH-01/2019
   - Wuhan/IPBCAMS-WH-02/2019
   - Wuhan/IPBCAMS-WH-03/2019
   - Wuhan/IPBCAMS-WH-04/2019
 * Wuhan Institute of Virology, Chinese Academy of Sciences, Wuhan, China
   - Wuhan/WIV02/2019
   - Wuhan/WIV04/2019
   - Wuhan/WIV05/2019
   - Wuhan/WIV06/2019
   - Wuhan/WIV07/2019
 * Department of Microbiology, Zhejiang Provincial Center for Disease Control and Prevention, Hangzhou, China
   - Zhejiang/WZ-01/2020
   - Zhejiang/WZ-02/2020
 * Guangdong Provincial Center for Diseases Control and Prevention
   - Guangdong/20SF012/2020
   - Guangdong/20SF013/2020
   - Guangdong/20SF014/2020
   - Guangdong/20SF025/2020
   - Guangdong/20SF028/2020
   - Guangdong/20SF040/2020
 * Department of Medical Sciences, National Institute of Health, Nonthaburi, Thailand
   - Nonthaburi/61/2020
   - Nonthaburi/74/2020

```