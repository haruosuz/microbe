Last Update: 2021-04-16

----------

# mbioinfo.2021

**Table of Contents**
- [2021-04-16](#2021-04-16)
- [resistance](#resistance) 耐性
- [plasmid](#plasmid) プラスミド
- [nucleotide_composition](#nucleotide_composition) 塩基組成、GC含量
- [ISS](#iss) International Space Station 国際宇宙ステーション
- [SSBP](#ssbp) Single-strand DNA-binding protein 一本鎖DNA結合タンパク質
- [metasub](#metasub) 都市マイクロバイオーム
- [microbiome_modeling_simulation](#microbiome_modeling_simulation) マイクロバイオーム モデリング シミュレーション
- [](#)

----------
## 2021-04-16

----------
## resistance

- https://en.wikipedia.org/wiki/Colistin
- https://ja.wikipedia.org/wiki/コリスチン
- https://ja.wikipedia.org/wiki/抗生物質
薬理
抗生物質を含む抗菌剤は、細菌が増殖するのに必要な代謝経路に作用することで細菌にのみ選択的に毒性を示す化学物質である。例えば、β-ラクタム系抗生物質は細菌特有の細胞壁の合成を阻害するが、人体の細胞に対してはほとんど毒性を示さない。アルコール、ポビドンヨードなどのように、単に化学的な作用で細菌を死滅させる殺菌剤、消毒薬とは区別される。
耐性と乱用
家畜への投与等

----------
## plasmid
プラスミド

- https://github.com/haruosuz/plasmids/blob/master/references/plasmid_resistance.md
- https://github.com/haruosuz/plasmids/blob/master/references/plasmid_metagenome.md
- https://github.com/haruosuz/plasmids/blob/master/references/plasmid_IncP1.md

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5278755/
IncP Plasmid Carrying Colistin Resistance Gene mcr-1 in Klebsiella pneumoniae from Hospital Sewage
The backbone of pMCR_1511 was highly similar (99% identity) to that of plasmid pHNFP671 (GenBank accession number KP324830), which was an IncP plasmid in E. coli isolate FP671 from Guangzhou, China but did not carry mcr-1. 

https://www.sciencedirect.com/science/article/pii/S2001037018301685
Reconsidering plasmid maintenance factors for computational plasmid design - ScienceDirect

Fig. 2. Replication module. (A) Replication module of IncP-1 plasmids. Ssb encodes a single-strand DNA binding protein.

2.3.2. G + C Content

Fig. 5. Plot of G + C contents of 209 plasmids and their host chromosomes. 
 The G + C contents of plasmids tend to be lower than (and are correlated with) those of the host chromosomes.

![](https://ars.els-cdn.com/content/image/1-s2.0-S2001037018301685-gr5.jpg)

----------
## nucleotide_composition
塩基組成、GC含量

https://github.com/haruosuz/mgsa/blob/master/references/mgsa.nucleotide_composition.md

----------
## ISS
International Space Station
国際宇宙ステーション

https://github.com/haruosuz/microbe/blob/master/references/microbe_ISS.md

----------
## SSBP
Single-strand DNA-binding protein

- https://ja.wikipedia.org/wiki/一本鎖DNA結合タンパク質
- https://en.wikipedia.org/wiki/Single-stranded_binding_protein
- https://en.wikipedia.org/wiki/SSBP1

2016
https://hrcak.srce.hr/ojs/index.php/periodicum_biologorum/article/view/4847
Variations in amino acid composition in bacterial single stranded DNA–binding proteins correlate with GC content | Periodicum Biologorum

Figure 1. ML trees constructed with 199 sequences of 16S rRNA gene (A), and corresponding SSBs (B). Branches are coloured depending on the GC content of species (blue – low GC, green – medium GC and red – high GC). Nodes with aLRT values equal or greater than 0.9 are indi- cated by asterisks.

----------
### metasub

- https://github.com/haruosuz/metasub/blob/master/README.md

MetaSUB国際コンソーシアム（都市マイクロバイオーム）の論文より。微生物の分類学的組成からサンプルの由来する都市を機械学習（ランダムフォレスト）で予測。

https://www.biorxiv.org/content/10.1101/724526v5.full
Global Genetic Cartography of Urban Metagenomes and Anti-Microbial Resistance | bioRxiv

2.2 Global Diversity Varies According to Covariates

We identified covariates which influenced the taxonomic composition of our samples: city, population density, average temperature in June, region, elevation above sea-level, surface type, surface material, elevation above or below ground and proximity to the coast. The most important factor, which could explain 19% of the variation in isolation, was the city from which a sample was taken followed by region which explained 11%. The other four factors ranged from explaining 2% to 7% of the possible variation in taxonomy in isolation (Supp. Table S2).

2.3 Microbial Signatures Reveal Urban Characteristics

We sought to determine whether a samples taxonomy reflected the environment in which it was collected. To this end we trained a Random Forest Classifier (RFC) to predict a sample’s city of origin from its taxonomic profile. 

----------
### microbiome_modeling_simulation
マイクロバイオーム モデリング シミュレーション

https://pubmed.ncbi.nlm.nih.gov/33543271/
Gigascience
. 2021 Feb 5;10(2):giab005. doi: 10.1093/gigascience/giab005.
MB-GAN: Microbiome Simulation via Generative Adversarial Network
Ruichen Rong 1, Shuang Jiang 1 2, Lin Xu 1, Guanghua Xiao 1, Yang Xie 1, Dajiang J Liu 3, Qiwei Li 4, Xiaowei Zhan 1 5

https://pubmed.ncbi.nlm.nih.gov/32127450/
mBio
. 2020 Mar 3;11(2):e02691-19. doi: 10.1128/mBio.02691-19.
Modeling of the Coral Microbiome: the Influence of Temperature and Microbial Network
Laís F O Lima 1 2, Maya Weissman 3, Micheal Reed 1, Bhavya Papudeshi 4, Amanda T Alker 1, Megan M Morris 1, Robert A Edwards 1 5, Samantha J de Putron 6, Naveen K Vaidya 3 5, Elizabeth A Dinsdale 7 5

https://pubmed.ncbi.nlm.nih.gov/32023941/
Review Microorganisms
. 2020 Jan 31;8(2):197. doi: 10.3390/microorganisms8020197.
Computational Modeling of the Human Microbiome
Shomeek Chowdhury 1, Stephen S Fong 2

https://pubmed.ncbi.nlm.nih.gov/30462168/
Bioinformatics
. 2019 Jul 1;35(13):2332-2334. doi: 10.1093/bioinformatics/bty941.
The Microbiome Modeling Toolbox: from microbial interactions to personalized microbial communities
Federico Baldini 1, Almut Heinken 1, Laurent Heirendt 1, Stefania Magnusdottir 1, Ronan M T Fleming 1 2, Ines Thiele 1

https://pubmed.ncbi.nlm.nih.gov/31337891/
Review Nat Microbiol
. 2019 Aug;4(8):1253-1267. doi: 10.1038/s41564-019-0491-9. Epub 2019 Jul 23.
Modelling approaches for studying the microbiome
Manish Kumar 1 2, Boyang Ji 1, Karsten Zengler 2 3 4, Jens Nielsen 5 6

https://pubmed.ncbi.nlm.nih.gov/30412640/
PLoS One
. 2018 Nov 9;13(11):e0207072. doi: 10.1371/journal.pone.0207072. eCollection 2018.
GutLogo: Agent-based modeling framework to investigate spatial and temporal dynamics in the gut microbiome
Charlie Lin 1, Joshua Culver 1, Bronson Weston 1, Evan Underhill 1, Jonathan Gorky 1, Prasad Dhurjati 1

----------




