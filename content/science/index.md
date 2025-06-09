+++
date = "2025-06-08"
title = "Science"
+++

**OpenBind** is generating foundational structural biology data to power the next era of AI/ML for drug discovery.

Since the advent of [AlphaFold](https://deepmind.google/science/alphafold/), rapid progress in artificial intelligence (AI) and machine learning (ML) for structure-based small molecule drug discovery has resulted in an incredible variety of tools able to predict protein-ligand interactions, including including [AlphaFold3](https://blog.google/technology/ai/google-deepmind-isomorphic-alphafold-3-ai-model/), [RoseTTAFold All-Atom](https://github.com/baker-laboratory/RoseTTAFold-All-Atom), [OpenFold](http://openfold.io), [Chai-1](https://www.chaidiscovery.com/blog/introducing-chai-1), [Boltz-2](https://boltz.bio/), [NeuralPLexer3](https://www.iambic.ai/post/np3-preview), among others.

While these AI/ML tools [hold tremenous promise in accelerating early-stage drug discovery](https://www.google.com/url?q=https://www.nature.com/articles/d41586-024-01383-z&sa=D&source=docs&ust=1749405936970166&usg=AOvVaw2MQGntU06d0t4I2a8Ra54k), these methods universally [require abundant, high-quality structural and affinity data to generalize to new drug targets and chemistries](https://doi.org/10.1101/2025.02.03.636309). OpenBind aims to furnish the experimental data needed for this revolution to fluorish.

OpenBind aims to:
* **Double the number of protein-ligand structures in the [Protein Data Bank](http://rcsb.org) in under two years** by leveraging protein (re)design, automated chemistry, and ultra-high-throughput X-ray crystallography---ultimately aiming to produce more than 500,000 structures over 5 years.
* **Pair structures with high-quality binding affinities** through mesoscale, microliter-scale, and nanoliter-scale chemistry to map out affities and structure-activity relationships.
* **Produce high-quality open source / open weights models** for protein-ligand structure and affinity prediction, in partnership with [OpenFold](http://openfold.io).
* **Drive data collection** through iterative active learning cycles in order to collect the most informative data for building highly predictive models.
* **Field quarterly blind predictive modeling challenges** to assess progress against open souce baselines and focus the field on overcoming obstacles to rapid development of useful AI/ML models to accelerate drug discovery.
* **Unlock new targets** through protein (re)design efforts that preserve the active site while redesigning the periphery of the protein to permit robust crystallization.
* **Promote data use** by streamlining the availability of ready-to-use data under [FAIR principles](https://www.go-fair.org/fair-principles/) through trusted public repositories such as the [PDB](http://rcsb.org) and [ChEMBL](https://www.ebi.ac.uk/chembl/), alongside ML-ready formats in hubs like [PolarisHub](https://polarishub.io/) and the [Therapeutic Data Commons](https://tdcommons.ai/).

OpenBind's senior consortium Principal Investigators are: 
* [Professor Frank von Delft]() ([Diamond Light Source](https://www.diamond.ac.uk/Home.html) [XChem](https://www.diamond.ac.uk/Instruments/Mx/Fragment-Screening.html) and [University of Oxford](https://www.ox.ac.uk/) [Centre for Medicines Discovery](https://www.cmd.ox.ac.uk/)) 
* [Professor Charlotte Deane](https://www.stats.ox.ac.uk/people/charlotte-deane) ([University of Oxford](https://www.ox.ac.uk/) [Protein Informatics Group](https://opig.stats.ox.ac.uk/)) 
* [Dr John Chodera](http://choderalab.org) ([Memorial Sloan Kettering Cancer Center](http://mskcc.org) [Computational and Systems Biology Program](https://www.mskcc.org/research/ski/programs/computational-biology)) 
* [Dr Mark Murcko](https://relaytx.com/our-team/mark-murcko/) ([Relay Therapeutics](https://relaytx.com/)) 
* [Professor Mohammed AlQuraishi](https://systemsbiology.columbia.edu/faculty/mohammed-alquraishi) ([Columbia University](https://www.columbia.edu/) [Systems Biology](https://systemsbiology.columbia.edu/) and [OpenFold](http://openfold.io))  
* [Professor David Baker](https://www.ipd.uw.edu/david-baker/) ([University of Washington](https://www.washington.edu/) [Institute for Protein Design](https://www.ipd.uw.edu/)) 
* [Dr Ed Griffen](https://www.medchemica.com/team/griffen-ed-j/) ([MedChemica](https://www.medchemica.com/)) 
* [Professor Paul Brennan](https://www.ndm.ox.ac.uk/team/paul-brennan) ([University of Oxford](https://www.ox.ac.uk/) [Centre for Medicines Discovery](https://www.cmd.ox.ac.uk/))


<!--
---

**OpenBind:** Powering AI for drug discovery through data.

The consortium goal is to transform small molecule drug discovery by making AI reliably predictive in computational compound design. Specifically, OpenBind aims to produce a fit-for-purpose open dataset of critical mass for effective machine learning (>10x existing data; >200k structure/affinity pairs) and, in tandem, will convene a network of ML practitioners to actively guide and validate the data generation.   

The OpenBind concept was developed within the XChem group at [Diamond Light Source](https://www.diamond.ac.uk/Home.html) and its collaborator network. 
It crystallized around [XChem](https://www.diamond.ac.uk/Instruments/Mx/Fragment-Screening.html)’s leading role in successive antiviral discovery efforts ([COVID Moonshot](https://dndi.org/research-development/portfolio/covid-moonshot/), [ASAP](http://asapdiscovery.org), [READDI-AC](http://readdi-ac.org/)) and in long-running methodology work accelerated by the antiviral and other grant-funded partnerships ([iNEXT-Discovery](https://inext-discovery.eu/), [Fragment-Screen](https://instruct-eric.org/news/fragment-screen-a-new-european-project-coordinated-by-instruct-eric/), [EUbOpen](https://www.eubopen.org/), [SABS-R3](https://gtr.ukri.org/projects?ref=studentship-2736609), [ALC](https://adalovelacecentre.ac.uk/)).   

The overall long-term ambition is for OpenBind to be a large 5-7 year project. The first phase (~£16m, 2yr) aims to *double* the <25K protein:small-molecule structures currently in the public domain ([PDB](http://rcsb.org), pairing these structures with high-quality affinity measurements. This would allow the critical *scaling laws* to be better understood (how much data is required to solve the problem) and hence allow improved projections of overall cost and consortium requirements. Once established the OpenBind Consortium can immediately coordinate proof-of-concept studies between consortium partners, ensuring funded work aligns with the partners’ existing scientific goals. Long-term, OpenBind aims to broaden into an international coalition of self-funding data generators, that collectively addresses long-term sustainability including data hosting.  The ultimate goal is that the consortium will evolve its methodologies into standard practice for target-based discovery and establish a sustainable data hosting model (as exists for structural biology via the global PDB, EMDB and EMPIAR public databases).  

The driver for OpenBind is Diamond’s world-leading capacity for MX data collection, and the output achieved by XChem in its NIH AViDD-funded partnerships (6% of all new structures in the global PDB in 2023-2024).  This capability is augmented upstream by sample production methodologies at the University of Oxford Centre for Medicines Discovery (CMD) and frontier protein redesign at University of Washington; and downstream at Diamond XChem’s evolving Fast-Forward Fragments (FFF) process of algorithmic compound design (Fragalysis) and rapid automated mesoscale chemistry (CAR).  This will be complemented at CMD-Oxford by HT biophysical measurement and new pan-dataset analysis; and nanoscale chemistry for in-depth SAR sampling.  Data pipelining and open models and competitions will be established by the Open Molecular Software Foundation (OMSF) in synergy with its other problem-adjacent consortia. 

-->