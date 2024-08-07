[![License: GPL](https://img.shields.io/badge/License-GPL-yellow)](https://github.com/AspirinCode/awesome-AI4ProteinConformation-MD)

## awesome-AI4MolConformation-MD
List of **protein ( molecules,  peptide, enzymes, antibody, and PPIs) conformations** and **molecular dynamics (MD)** using **generative artificial intelligence** and **deep learning**


![Protein Space and Conformations](https://github.com/AspirinCode/awesome-AI4ProteinConformation-MD/blob/main/figure/afpro.png)


**Updating ...**  


## Menu

  - [Deep Learning-protein conformations](#deep-learning-protein-conformations)

| Menu | Menu | Menu | Menu |
| ------ | :---------- | ------ | ------ |
| [Reviews](#reviews) | [Datasets and Package](#datasets-and-package) | [Molecular dynamics](#molecular-dynamics) | [AI4MD](#ai4md) |
| [AlphaFold-based](#alphaFold-based) | [GNN-based](#gnn-based)  | [LSTM-based](#lstm-based) | [Transformer-based](#transformer-based) |
| [VAE-based](#vae-based) | [GAN-based](#gan-based) | [Flow-based](#flow-based) | [Diffusion-based](#diffusion-based) |
| [Score-Based](#score-Based) | [Energy-based](#energy-based) | [Bayesian-based](#bayesian-based) | [Active Learning-based](#active-learning-based) |
| [LLM-MD](#llm-md) |  |  |  |



## Reviews




* **An overview about neural networks potentials in molecular dynamics simulation** [2024]   
 Martin‐Barrios, Raidel, Edisel Navas‐Conyedo, Xuyi Zhang, Yunwei Chen, and Jorge Gulín‐González.   
  [International Journal of Quantum Chemistry 124.11 (2024)](https://doi.org/10.1002/qua.27389)  

* **Artificial Intelligence Enhanced Molecular Simulations** [2023]   
 Zhang, Jun, Dechin Chen, Yijie Xia, Yu-Peng Huang, Xiaohan Lin, Xu Han, Ningxi Ni et al.   
  [J. Chem. Theory Comput. (2023)](https://doi.org/10.1021/acs.jctc.3c00214)  

* **Machine Learning Generation of Dynamic Protein Conformational Ensembles** [2023]   
 Zheng, Li-E., Shrishti Barethiya, Erik Nordquist, and Jianhan Chen.   
  [Molecules 28.10 (2023)](https://doi.org/10.3390/molecules28104047)  




## Datasets and Package

### Datasets

* **mdCATH: A Large-Scale MD Dataset for Data-Driven Computational Biophysics** [2024]  
Antonio Mirarchi, Toni Giorgino, G. D. Fabritiis.   
[	arXiv:2407.14794 (2024)](https://arxiv.org/abs/2407.14794) | [code](https://github.com/compsciencelab/mdCATH)




### Package


**MMolearn**  
a Python package streamlining the design of generative models of biomolecular dynamics  

https://github.com/LumosBio/MolData   





## Molecular dynamics




### Molecular Force Fields






* **Differentiable simulation to develop molecular dynamics force fields for disordered proteins** [2024]  
Greener, Joe G.   
[Chemical Science 15.13 (2024)](https://doi.org/10.1039/D3SC05230C) | [code](https://github.com/greener-group/GB99dms)




### MD Engines/Frameworks

* [Amber](http://ambermd.org/) - A suite of biomolecular simulation programs.  
* [Gromacs](http://www.gromacs.org/) - A molecular dynamics package mainly designed for simulations of proteins, lipids and nucleic acids.
* [OpenMM](http://openmm.org/) - A toolkit for molecular simulation using high performance GPU code.  
* [CHARMM](https://www.charmm.org/) - A molecular simulation program with broad application to many-particle systems.  
* [HTMD](https://github.com/Acellera/htmd) - Programming Environment for Molecular Discovery.  
* [ACEMD](https://www.acellera.com/acemd) - The next generation molecular dynamic simulation software.  
* [NAMD](https://www.ks.uiuc.edu/Research/namd/) - A parallel molecular dynamics code for large biomolecular systems..
* [StreaMD](https://github.com/ci-lab-cz/streamd) - A tool to perform high-throughput automated molecular dynamics simulations..


### AI4MD Engines/Frameworks


* [TorchMD](https://github.com/torchmd/torchmd) - End-To-End Molecular Dynamics (MD) Engine using PyTorch.
* [TorchMD-NET](https://github.com/torchmd/torchmd-net) - TorchMD-NET provides state-of-the-art neural networks potentials (NNPs) and a mechanism to train them.  
* [OpenMM-Torch](https://github.com/openmm/openmm-torch) - OpenMM plugin to define forces with neural networks.  



### MD Trajectory Processing/Analysis


* [MDAnalysis](https://www.mdanalysis.org/) - An object-oriented Python library to analyze trajectories from molecular dynamics (MD) simulations in many popular formats.  
* [MDTraj](http://mdtraj.org/) - A python library that allows users to manipulate molecular dynamics (MD) trajectories.  
* [PyTraj](https://amber-md.github.io/pytraj/) - A Python front-end package of the popular cpptraj program.  
* [CppTraj](https://github.com/Amber-MD/cpptraj) - Biomolecular simulation trajectory/data analysis.  
* [WEDAP](https://github.com/chonglab-pitt/wedap) - A Python Package for Streamlined Plotting of Molecular Simulation Data. 

### Reference

https://github.com/ipudu/awesome-molecular-dynamics  



### Visualization

* [VMD](http://www.ks.uiuc.edu/Research/vmd/) - A molecular visualization program for displaying, animating, and analyzing large biomolecular systems using 3-D graphics and built-in scripting.  
* [NGLview](https://github.com/arose/nglview) - IPython widget to interactively view molecular structures and trajectories.  
* [PyMOL](https://pymol.org/2/) - A user-sponsored molecular visualization system on an open-source foundation, maintained and distributed by Schrödinger.  
* [Avogadro](https://avogadro.cc/) - An advanced molecule editor and visualizer designed for cross-platform use in computational chemistry, molecular modeling, bioinformatics, materials science, and related areas.  



## AI4MD





* **Machine learning of force fields towards molecular dynamics simulations of proteins at DFT accuracy** [2024]  
Brunken, Christoph, Sebastien Boyer, Mustafa Omar, Bakary N'tji Diallo, Karim Beguir, Nicolas Lopez Carranza, and Oliver Bent.   
[ICLR 2024 Workshop on Generative and Experimental Perspectives for Biomolecular Design (2024)](https://openreview.net/forum?id=hrvvIOx7EM) | [code](https://github.com/ACEsuit/mace-jax)

* **Unsupervised and supervised AI on molecular dynamics simulations reveals complex characteristics of HLA-A2-peptide immunogenicity** [2024]  
Jeffrey K Weber, Joseph A Morrone, Seung-gu Kang, Leili Zhang, Lijun Lang, Diego Chowell, Chirag Krishna, Tien Huynh, Prerana Parthasarathy, Binquan Luan, Tyler J Alban, Wendy D Cornell, Timothy A Chan.   
[Briefings in Bioinformatics (2024)](https://doi.org/10.1093/bib/bbad504) | [code](https://github.com/BiomedSciAI)

* **Biomolecular dynamics with machine-learned quantum-mechanical force fields trained on diverse chemical fragments** [2024]  
Unke, Oliver T., Martin Stöhr, Stefan Ganscha, Thomas Unterthiner, Hartmut Maennel, Sergii Kashubin, Daniel Ahlin et al.   
[Science Advances 10.14 (2024)](https://www.science.org/doi/10.1126/sciadv.adn4397) | [data](https://zenodo.org/records/10720941)








## Deep Learning-protein conformations




* **GLOW: A Workflow Integrating Gaussian-Accelerated Molecular Dynamics and Deep Learning for Free Energy Profiling** [2022]  
Do, Hung N., Jinan Wang, Apurba Bhattarai, and Yinglong Miao.   
[J. Chem. Theory Comput. (2022)](https://doi.org/10.1021/acs.jctc.1c01055) | [code](https://github.com/MiaoLab20/GLOW)




### AlphaFold-based



* **A resource for comparing AF-Cluster and other AlphaFold2 sampling methods** [2024]  
Hannah K Wayment-Steele, Sergey Ovchinnikov, Lucy Colwell, Dorothee Kern.   
[bioRxiv (2024)](https://doi.org/10.1101/2024.07.29.605333) 

* **Integration of AlphaFold with Molecular Dynamics for Efficient Conformational Sampling of Transporter Protein NarK** [2024]  
Ohnuki, Jun, and Kei-ichi Okazaki.   
[The Journal of Physical Chemistry B (2024)](https://doi.org/10.1021/acs.jpcb.4c02726)  

* **AFsample2: Predicting multiple conformations and ensembles with AlphaFold2** [2024]  
Yogesh Kalakoti, Björn Wallner.   
[bioRxiv (2024)](https://doi.org/10.1101/2024.05.28.596195) | [code](https://github.com/iamysk/AFsample2/)

* **Prediction of Conformational Ensembles and Structural Effects of State-Switching Allosteric Mutants in the Protein Kinases Using Comparative Analysis of AlphaFold2 Adaptations with Sequence Masking and Shallow Subsampling** [2024]  
Nishank Raisinghani, Mohammed Alshahrani, Grace Gupta, Hao Tian, Sian Xiao, Peng Tao, Gennady Verkhivker.   
[bioRxiv (2024)](https://doi.org/10.1101/2024.05.17.594786) | [code](https://zenodo.org/records/11204773)

* **Empowering AlphaFold2 for protein conformation selective drug discovery with AlphaFold2-RAVE** [2024]  
Xinyu Gu, Akashnathan Aranganathan, Pratyush Tiwary.   
[	arXiv:2404.07102 (2024)](https://arxiv.org/abs/2404.07102)  

* **High-throughput prediction of protein conformational distributions with subsampled AlphaFold2** [2024]  
Monteiro da Silva, G., Cui, J.Y., Dalgarno, D.C. et al.   
[Nat Commun 15, 2464 (2024)](https://doi.org/10.1038/s41467-024-46715-9) | [code](https://github.com/GMdSilva/gms_natcomms_1705932980_data)

* **AlphaFold Meets Flow Matching for Generating Protein Ensembles** [2024]  
Jing, Bowen, Bonnie Berger, and Tommi Jaakkola.   
[arXiv:2402.04845 (2024)](https://arxiv.org/abs/2402.04845) | [code](https://github.com/bjing2016/alphaflow)

* **Predicting multiple conformations via sequence clustering and AlphaFold2** [2024]  
Wayment-Steele, H.K., Ojoawo, A., Otten, R. et al.   
[Nature 625, 832–839 (2024)](https://doi.org/10.1038/s41586-023-06832-9) | [code](https://github.com/HWaymentSteele/AF_Cluster)

* **AlphaFold2-RAVE: From Sequence to Boltzmann Ranking** [2023]  
Bodhi P. Vani, Akashnathan Aranganathan, Dedi Wang, and Pratyush Tiwary.   
[J. Chem. Theory Comput. (2023)](https://pubs.acs.org/doi/10.1021/acs.jctc.3c00290)) | [code](https://github.com/tiwarylab/alphafold2rave)

* **Investigating the conformational landscape of AlphaFold2-predicted protein kinase structures** [2023]  
Carmen Al-Masri, Francesco Trozzi, Shu-Hang Lin, Oanh Tran, Navriti Sahni, Marcel Patek, Anna Cichonska, Balaguru Ravikumar, Rayees Rahman.   
[Bioinformatics Advances. (2023)](https://doi.org/10.1093/bioadv/vbad129)) | [code](https://github.com/Harmonic-Discovery/AF2-kinase-conformational-landscape)

* **Exploring the Druggable Conformational Space of Protein Kinases Using AI-Generated Structures** [2023]  
Herrington, Noah B., David Stein, Yan Chak Li, Gaurav Pandey, and Avner Schlessinger.   
[bioRxiv (2023)](https://doi.org/10.1101/2023.08.31.555779) | [code](https://github.com/schlessinger-lab/af2_kinase_conformations/)

* **Sampling alternative conformational states of transporters and receptors with AlphaFold2** [2022]  
Del Alamo, Diego, Davide Sala, Hassane S. Mchaourab, and Jens Meiler.   
[Elife 11 (2022)](https://elifesciences.org/articles/75751) | [code](https://github.com/delalamo/af2_conformations)



### GNN-based





* **AbFlex: Predicting the conformational flexibility of antibody CDRs** [2024]  
Spoendlin, Fabian C., Wing Ki Wong, Guy Georges, Alexander Bujotzek, and Charlotte Deane.   
[ICML'24 Workshop ML for Life and Material Science: From Theory to Industry Applications (2024)](https://openreview.net/forum?id=or4tArwd5a) | [code](https://openreview.net/forum?id=or4tArwd5a)

* **RevGraphVAMP: A protein molecular simulation analysis model combining graph convolutional neural networks and physical constraints** [2024]  
Huang, Ying, Huiling Zhang, Zhenli Lin, Yanjie Wei, and Wenhui Xi.   
[bioRxiv (2024)](https://doi.org/10.1101/2024.03.11.584426) | [code](https://github.com/DS00HY/RevGraphVamp)








### LSTM-based







* **Learning molecular dynamics with simple language model built upon long short-term memory neural network** [2020]  
Tsai, ST., Kuo, EJ. & Tiwary, P.   
[Nat Commun 11, 5115 (2020)](https://doi.org/10.1038/s41467-020-18959-8) | [code](https://github.com/tiwarylab/LSTM-predict-MD)







### Transformer-based





* **Exploring the conformational ensembles of protein-protein complex with transformer-based generative model** [2024]  
Wang, Jianmin, Xun Wang, Yanyi Chu, Chunyan Li, Xue Li, Xiangyu Meng, Yitian Fang, Kyoung Tai No, Jiashun Mao, and Xiangxiang Zeng.   
[J. Chem. Theory Comput. (2024)](https://doi.org/10.1021/acs.jctc.4c00255) | [bioRxiv (2024)](https://doi.org/10.1101/2024.02.24.581708) | [code](https://github.com/AspirinCode/AlphaPPImd)

* **Data-Efficient Generation of Protein Conformational Ensembles with Backbone-to-Side-Chain Transformers** [2024]  
Chennakesavalu, Shriram, and Grant M. Rotskoff.   
[The Journal of Physical Chemistry B (2024)](https://pubs.acs.org/doi/full/10.1021/acs.jpcb.3c08195) | [code](https://github.com/rotskoff-group/transformer-backmapping)

* **Molecular dynamics without molecules: searching the conformational space of proteins with generative neural networks** [2022]  
Schwing, Gregory, Luigi L. Palese, Ariel Fernández, Loren Schwiebert, and Domenico L. Gatti.   
[arXiv:2206.04683 (2022)](https://arxiv.org/abs/2206.04683) | [code](https://github.com/dgattiwsu/MD_without_molecules)








### VAE-based




* **Deciphering the Coevolutionary Dynamics of L2 β-Lactamases via Deep Learning** [2024]  
  Zhu, Yu, Jing Gu, Zhuoran Zhao, AW Edith Chan, Maria F. Mojica, Andrea M. Hujer, Robert A. Bonomo, and Shozeb Haider.  
  [J. Chem. Inf. Model. (2024)](https://doi.org/10.1021/acs.jcim.4c00189) | [data](https://zenodo.org/records/10500539)

* **Protein Ensemble Generation Through Variational Autoencoder Latent Space Sampling** [2024]  
Sanaa Mansoor, Minkyung Baek, Hahnbeom Park, Gyu Rie Lee, and David Baker.   
[J. Chem. Theory Comput. (2024)](https://pubs.acs.org/doi/10.1021/acs.jctc.3c01057)

* **Phanto-IDP: compact model for precise intrinsically disordered protein backbone generation and enhanced sampling** [2024]  
  Junjie Zhu, Zhengxin Li, Haowei Tong, Zhouyu Lu, Ningjie Zhang, Ting Wei and Hai-Feng Chen.  
  [Briefings in Bioinformatics. (2024)](https://academic.oup.com/bib/article/25/1/bbad429/7453435) | [code](https://github.com/Junjie-Zhu/Phanto-IDP)

* **Enhancing Conformational Sampling for Intrinsically Disordered and Ordered Proteins by Variational Auotencoder** [2023]  
  JunJie Zhu, NingJie Zhang, Ting Wei and Hai-Feng Chen.  
  [International Journal of Molecular Sciences. (2023)](https://www.mdpi.com/1422-0067/24/8/6896) | [code](https://github.com/Junjie-Zhu/VAE)

* **Encoding the Space of Protein-protein Binding Interfaces by Artificial Intelligence** [2023]  
  Su, Zhaoqian, Kalyani Dhusia, and Yinghao Wu.  
  [bioRxiv (2023)](https://doi.org/10.1101/2023.09.08.556812)  

* **Artificial intelligence guided conformational mining of intrinsically disordered proteins** [2022]  
Gupta, A., Dey, S., Hicks, A. et al.   
[Commun Biol 5, 610 (2022)](https://doi.org/10.1038/s42003-022-03562-y) | [code](https://github.com/aaayushg/generative_IDPs)

* **LAST: Latent Space-Assisted Adaptive Sampling for Protein Trajectories** [2022]  
Tian, Hao, Xi Jiang, Sian Xiao, Hunter La Force, Eric C. Larson, and Peng Tao   
[J. Chem. Inf. Model. (2022)](https://doi.org/10.1021/acs.jcim.2c01213) | [code](https://github.com/smu-tao-group/LAST)

* **Molecular dynamics without molecules: searching the conformational space of proteins with generative neural networks** [2022]  
Schwing, Gregory, Luigi L. Palese, Ariel Fernández, Loren Schwiebert, and Domenico L. Gatti.   
[arXiv:2206.04683 (2022)](https://arxiv.org/abs/2206.04683) | [code](https://github.com/dgattiwsu/MD_without_molecules)

* **ProGAE: A Geometric Autoencoder-based Generative Model for Disentangling Protein Conformational Space** [2021]  
Tatro, Norman Joseph, Payel Das, Pin-Yu Chen, Vijil Chenthamarakshan, and Rongjie Lai.   
[ICLR (2022)](https://openreview.net/forum?id=LxhlyKH6VP)

* **Explore protein conformational space with variational autoencoder** [2021]  
  Tian, Hao, Xi Jiang, Francesco Trozzi, Sian Xiao, Eric C. Larson, and Peng Tao.   
  [Frontiers in molecular biosciences 8 (2021)](https://www.frontiersin.org/articles/10.3389/fmolb.2021.781635/full) | [code](https://github.com/smu-tao-group/protein-VAE)








### GAN-based








* **Direct generation of protein conformational ensembles via machine learning** [2023]  
Janson, G., Valdes-Garcia, G., Heo, L. et al.   
[Nat Commun 14, 774 (2023)](https://doi.org/10.1038/s41467-023-36443-x) | [code](https://github.com/feiglab/idpgan)

* **Molecular dynamics without molecules: searching the conformational space of proteins with generative neural networks** [2022]  
Schwing, Gregory, Luigi L. Palese, Ariel Fernández, Loren Schwiebert, and Domenico L. Gatti.   
[arXiv:2206.04683 (2022)](https://arxiv.org/abs/2206.04683) | [code](https://github.com/dgattiwsu/MD_without_molecules)









### Flow-based


* **Frame-to-Frame Coarse-grained Molecular Dynamics with SE (3) Guided Flow Matching** [2024]  
Li, Shaoning, Yusong Wang, Mingyu Li, Jian Zhang, Bin Shao, Nanning Zheng, and Jian Tang   
[arXiv:2405.00751 (2024)](https://arxiv.org/abs/2405.00751)  

* **AlphaFold Meets Flow Matching for Generating Protein Ensembles** [2024]  
Jing, Bowen, Bonnie Berger, and Tommi Jaakkola.   
[arXiv:2402.04845 (2024)](https://arxiv.org/abs/2402.04845) | [code](https://github.com/bjing2016/alphaflow)






### Diffusion-based


* **Direct conformational sampling from peptide energy landscapes through hypernetwork-conditioned diffusion** [2024]  
Abdin, O., Kim, P.M.   
[Nat Mach Intell 6, 775–786 (2024)](https://doi.org/10.1038/s42256-024-00860-4) | [code](https://gitlab.com/oabdin/pepflow)

* **Accurate Conformation Sampling via Protein Structural Diffusion** [2024]  
Fan, Jiahao, Ziyao Li, Eric Alcaide, Guolin Ke, Huaqing Huang, and Weinan E.   
[bioRxiv (2024)](https://doi.org/10.1101/2024.05.20.594916)  




### Score-based






* **Str2str: A score-based framework for zero-shot protein conformation sampling** [2024]  
Lu, Jiarui, Bozitao Zhong, Zuobai Zhang, and Jian Tang.   
[ICLR (2024)](https://openreview.net/forum?id=C4BikKsgmK) | [code](https://github.com/lujiarui/Str2Str)

* **Score-based enhanced sampling for protein molecular dynamics** [2023]  
Lu, Jiarui, Bozitao Zhong, and Jian Tang.   
[arXiv:2306.03117 (2023)](https://arxiv.org/abs/2306.03117) | [code](https://github.com/lujiarui/Str2Str)






### Energy-based






* **Energy-based models for atomic-resolution protein conformations** [2020]  
Du, Yilun, Joshua Meier, Jerry Ma, Rob Fergus, and Alexander Rives.   
[ICLR (2020)](https://openreview.net/forum?id=S1e_9xrFvS) | [code](https://github.com/facebookresearch/protein-ebm)











### Bayesian-based


* **Enabling Population Protein Dynamics Through Bayesian Modeling** [2024]  
Sylvain Lehmann, Jérôme Vialaret, Audrey Gabelle, Luc Bauchet, Jean-Philippe Villemin, Christophe Hirtz, Jacques Colinge.   
[Bioinformatics (2024)](https://doi.org/10.1093/bioinformatics/btae484)

* **Deep Boosted Molecular Dynamics (DBMD): Accelerating molecular simulations with Gaussian boost potentials generated using probabilistic Bayesian deep neural network** [2023]  
Do, Hung N., and Yinglong Miao.   
[bioRxiv(2023)](https://doi.org/10.1101/2023.03.25.534210) | [code](https://github.com/MiaoLab20/DBMD/)

* **Deep Generative Models of Protein Structure Uncover Distant Relationships Across a Continuous Fold Space** [2023]  
Draizen, Eli J., Stella Veretnik, Cameron Mura, and Philip E. Bourne.   
[bioRxiv(2023)](https://doi.org/10.1101/2022.07.29.501943) | [code](https://github.com/bouralab/DeepUrfold)






### Active Learning-based



* **Active Learning of the Conformational Ensemble of Proteins Using Maximum Entropy VAMPNets** [2023]  
Kleiman, Diego E., and Diwakar Shukla.   
[J. Chem. Theory Comput. (2023)](https://doi.org/10.1021/acs.jctc.3c00040) | [code](https://github.com/ShuklaGroup/MaxEntVAMPNet)



### LLM-MD


* **Molecular simulation with an LLM-agent** [2024]  
MD-Agent is a LLM-agent based toolset for Molecular Dynamics.  
[code](https://github.com/ur-whitelab/md-agent)









