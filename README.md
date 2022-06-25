# awesome-deep-learning-4-life-sciences
This repo lists a collection of resources for performing Deep Learning in [Python](https://www.python.org) for Life Sciences. I am observing an ever increasing volume of academic work and Open Source initiatives related to topics such as biochemistry, genetics, molecular biology, bioinformatics, etc. So, I have created this repository to provide researchers, developers and practitioners a single place to keep track of the latest developments in this space.  
# Table of contents
* [Molecules](https://github.com/virtualramblas/awesome-deep-learning-4-life-sciences/edit/main/README.md#molecules)
* [Proteins](https://github.com/virtualramblas/awesome-deep-learning-4-life-sciences/edit/main/README.md#proteins) 
* [Chemistry](https://github.com/virtualramblas/awesome-deep-learning-4-life-sciences/edit/main/README.md#chemistry)
* [Drug Discovery](https://github.com/virtualramblas/awesome-deep-learning-4-life-sciences/edit/main/README.md#drug-discovery)
* [Datasets](https://github.com/virtualramblas/awesome-deep-learning-4-life-sciences/edit/main/README.md#datasets)
* [Explainable AI](https://github.com/virtualramblas/awesome-deep-learning-4-life-sciences/edit/main/README.md#explainable-ai) 
* [Other](https://github.com/virtualramblas/awesome-deep-learning-4-life-sciences/edit/main/README.md#other) 
# Molecules
* [pysmiles](https://github.com/pckroon/pysmiles) - A lightweight Python library for reading and writing SMILES strings.
* [SmilesDrawer](https://colab.research.google.com/drive/1PmJX2XFg_1ORexGTw4FkKjr779sk1zAr?usp=sharing) - A Colab notebook to draw from SMILES strings.  
* [ChemProp](https://github.com/chemprop/chemprop) - Message Passing Neural Networks for molecule property prediction.  
* [mols2grid](https://github.com/cbouy/mols2grid) - Interactive molecule viewer for 2D structures.   
* [Image to SMILES Generator](https://github.com/syntelly/img2smiles_generator) - Code to generate datasets of pairs "image - sequence" for chemical molecules. [[Article](https://chemistry-europe.onlinelibrary.wiley.com/doi/10.1002/cmtd.202100069)]
# Proteins
* [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk) - A online database which provides open access to 992,316 protein structure predictions for the human proteome and other key proteins of interest, to accelerate scientific research.
* [AlphaFold](https://github.com/deepmind/alphafold) - Open source code for DeepMind's AlphaFold.
* [OpenFold](https://github.com/aqlaboratory/openfold) - Trainable, memory-efficient, and GPU-friendly PyTorch reproduction of AlphaFold 2.  
* [AlphaFold - single sequence input](https://colab.research.google.com/github/sokrypton/af_backprop/blob/beta/examples/AlphaFold_single.ipynb) - A Colab notebook to predict the protein structure from a single sequence (for educational purposes only). 
* [ColabFold](https://github.com/sokrypton/ColabFold) - Making Protein folding accessible to all via Google Colab. [[Article](https://www.nature.com/articles/s41592-022-01488-1)]
* [LocalColabFold](https://github.com/YoshitakaMo/localcolabfold) - Running ColabFold on your local PC.  
* [Meaningful Protein Representation](https://github.com/MachineLearningLifeScience/meaningful-protein-representations) - Learning meaningful representations of protein sequences using a VAE. [[Article](https://www.nature.com/articles/s41467-022-29443-w)] [[Paper](https://arxiv.org/pdf/2012.02679.pdf)]. 
* [Tape](https://github.com/songlab-cal/tape) - Tasks Assessing Protein Embeddings (TAPE), a set of five biologically relevant semi-supervised learning tasks spread across different domains of protein biology. [[Paper](https://arxiv.org/pdf/1906.08230.pdf)]
* [FastFold](https://github.com/hpcaitech/FastFold) - Optimizing Protein Structure Prediction Model Training and Inference on GPU Clusters.  
# Chemistry
* [DRFP](https://github.com/reymond-group/drfp) - An NLP-inspired chemical reaction fingerprint based on basic set arithmetic. [[Article](https://pubs.rsc.org/en/content/articlehtml/2022/dd/d1dd00006c)]. 
* [DeepChem](https://github.com/deepchem/deepchem) - A high quality Open Source toolchain that democratizes the use of Deep Learning in drug discovery, materials science, quantum chemistry, and biology.
* [CompAugCycleGAN](https://github.com/qai222/CompAugCycleGAN) - Augmented CycleGAN used for generating chemical compositions. [[Article](https://pubs.rsc.org/en/content/articlelanding/2022/dd/d1dd00044f)]  
# Drug Discovery
* [TorchDrug](https://github.com/DeepGraphLearning/torchdrug) - A powerful and flexible PyTorch-based Deep Learning platform for drug discovery.
# Datasets
* [DECIMER - Hand-drawn molecule images dataset](https://zenodo.org/record/6456306#.YravvC8w1QI) - A standardised, openly available benchmark dataset of 5088 hand-drawn depictions of diversely picked chemical structures. [[Article](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00620-9)]  
* [UniLanguage](https://github.com/alrojo/UniLanguage) - Homology reduced UniProt, train-/valid-/testsets for language modeling.  
* [ChEMBL](https://www.ebi.ac.uk/chembl/) - A manually curated database of bioactive molecules with drug-like properties. It brings together chemical, bioactivity and genomic data to aid the translation of genomic information into effective new drugs.  
* [Molecule OCR Real images Dataset](https://zenodo.org/record/5356500#.YrdYxi8w1QI) - Test dataset from paper "Image2SMILES: Transformer-based Molecular Optical Recognition Engine". It contains 296 structures: images and Functional Groups SMILES (FG-SMILES).  
* [FS-Mol](https://github.com/microsoft/FS-Mol) - A Few-Shot Learning Dataset of Molecules, containing molecular compounds with measurements of activity against a variety of protein targets. 
# Explainable AI
* [Interpretable and Explainable Machine Learning for Materials Science and Chemistry](https://pubs.acs.org/doi/10.1021/accountsmr.1c00244) - Interpretable and Explainable Machine Learning applied to materials science and chemistry.
* [exmol](https://github.com/ur-whitelab/exmol) - Explainer for black box models that predict molecule properties.
# Other
* [Panel-Chemistry](https://github.com/marcskovmadsen/panel-chemistry) - Easy exploratory data analysis and build powerful data and viz tools within the domain of Chemistry using Python and HoloViz Panel.
