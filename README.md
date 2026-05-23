# Awesome Sequence-to-Function Papers

Hand-picked research papers on sequence-to-function modeling and applications.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Research Papers](https://img.shields.io/badge/Research%20Papers-690%2B-red)
![Last Update](https://img.shields.io/badge/Last%20update-May%202026-yellowgreen)
![S2F](https://img.shields.io/badge/S2F-Sequence--to--Function-brightgreen)
![Plant S2F](https://img.shields.io/badge/Plant%20S2F-123-blue)

Sequence-to-function models have become a major research focus in AI4Bio in recent years. This repository organizes papers related to S2F models into categories such as reviews, methods, and applications, with plant-focused studies listed separately. The plant-focused section is based on the review paper **“Exploring the Oasis of Plant Genomes: From Genetic Variations to Function and Beyond”** ([DOI](https://doi.org/10.1016/j.molp.2026.05.014)).

## Table of Contents

Coverage note: papers in `S2F-For-Plant` are recorded through online publication dates up to 2026-03-18; papers in the other sections are recorded through online publication dates up to 2025-08-25.

| Section | Description |
| --- | --- |
| [S2F-For-Plant (123)](#s2f-for-plant-123) | Plant S2F models and/or applications of general S2F models in plant studies. |
| [S2F-Review (54)](#s2f-review-54) | Review articles on sequence-to-function topics. |
| [S2F-OneHot-Model (106)](#s2f-onehot-model-106) | Method papers using one-hot encoded input sequences. |
| [S2F-Other-Model (154)](#s2f-other-model-154) | Method papers using other sequence encoding strategies. |
| [S2F-Model-Interpretation (61)](#s2f-model-interpretation-61) | Interpretability methods for S2F models. |
| [S2F-Application (192)](#s2f-application-192) | Biological applications of S2F models, typically studies using existing models to answer biological questions. |

## TODO

Add upcoming sections:

- [ ] Evaluation and Benchmarking
- [ ] Regulatory sequences and their design
- [ ] Guidance and Toolkit
- [ ] S+X 2F Models

Maintenance tasks:

- [ ] Catch up with recent publications (target: <=2 months from online date)
- [ ] Add citation counts and GitHub repository information for papers

## S2F-For-Plant (123)

<details>
<summary>Show S2F-For-Plant papers (123)</summary>


| Year | Paper | Venue | Note |
| --- | --- | --- | --- |
| 2026 | [Cross-species prediction of histone modifications in plants via deep learning](https://link.springer.com/10.1186/s13059-025-03929-4) | Genome Biology |  |
| 2026 | [DL-GapFilling: a novel deep learning framework for improved plant genome gap filling](https://academic.oup.com/bib/article/doi/10.1093/bib/bbag007/8441032) | Briefings in Bioinformatics | Genome assembly has been a cornerstone of bioinformatics for decades, with faster and more accurate assembly of unknown genomes remaining a critical challenge. |
| 2026 | [Dbert2_LR: A deep learning-based model for predicting cis-regulatory elements in crops](https://linkinghub.elsevier.com/retrieve/pii/S0888754326000091) | Genomics |  |
| 2026 | [Deep learning-based semantic matching of cis-regulatory DNA sequences facilitates the prediction of gene function](https://www.nature.com/articles/s41477-026-02231-w) | Nature Plants |  |
| 2026 | [Enhancing Genomic Selection for Soybean Drought Tolerance via Integration of Epistasis and AlphaFold2 Prediction](https://onlinelibrary.wiley.com/doi/10.1111/pce.70408) | Plant, Cell & Environment | Soybean is a globally important economic and food crop, whose production is often constrained by drought stress, posing a serious threat to yield and quality. |
| 2026 | [From Natural Discovery to AI-Guided Design: A Curated Collection of Compact Enhancers for Crop Engineering](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202516600) | Advanced Science | Precise transgene-free gene upregulation remains a challenge in crop biotechnology, as conventional enhancers often exceed CRISPR-mediated knock-in size constraints and face regulatory hurdles. |
| 2026 | [FungiGuard: identification of plant antifungal peptides with artificial intelligence](https://link.springer.com/10.1186/s13059-026-03983-6) | Genome Biology |  |
| 2026 | [GS-Impute: a neural network framework for accurate imputation of low-density markers in across-population genomic selection](https://linkinghub.elsevier.com/retrieve/pii/S259034622600129X) | Plant Communications |  |
| 2026 | [Investigating cis-regulatory elements and gene expression in multiple tomato varieties using interpretable deep learning](https://link.springer.com/10.1007/s00122-025-05109-1) | Theoretical and Applied Genetics |  |
| 2026 | [MegaPlantTF: a machine learning framework for comprehensive identification and classification of plant transcription factors](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btaf678/8405040) | Bioinformatics | Motivation Understanding the role of transcription factors (TFs) in plants is essential for the study of gene regulation and various biological processes. |
| 2026 | [PlantCTCIP : Chromatin Interaction Prediction Using Convolutional Neural Network and Transformer in Plants](https://onlinelibrary.wiley.com/doi/10.1111/pbi.70586) | Plant Biotechnology Journal | Chromatin interactions establish spatial proximity between distant regulatory elements and their target genes, significantly influencing gene expression, and phenotypic traits. |
| 2026 | [S2 - PepAnalyst : A Web Tool for Predicting Plant Small Signalling Peptides](https://onlinelibrary.wiley.com/doi/10.1111/pbi.70536) | Plant Biotechnology Journal | Small signalling peptides (SSPs) serve as crucial mediators of cell-to-cell communication in plants, orchestrating diverse physiological processes from development to stress responses. |
| 2025 | [AlphaFold-Guided Bespoke Gene Editing Enhances Field-Grown Soybean Oil Contents](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202500290) | Advanced Science | The study demonstrates that the combination of AlphaFold-guided protein design and gene editing has the potential to generate novel beneficial alleles, which can optimize protein function in the context of crop breeding. |
| 2025 | [AtSubP-2.0: An integrated web server for the annotation of Arabidopsis proteome subcellular localization using deep learning](https://acsess.onlinelibrary.wiley.com/doi/10.1002/tpg2.20536) | The Plant Genome | AtSubP2 will help researchers to better understand organelle-specific functions, cellular processes, and regulatory mechanisms important for plant growth, development, and response to environmental stimuli. |
| 2025 | [CRISPR meets AlphaFold: guiding SWEET10-enhanced oil production](https://linkinghub.elsevier.com/retrieve/pii/S1360138525002274) | Trends in Plant Science | A recent study by Wang and colleagues reported that AlphaFold-guided CRISPR genome editing of SWEET10 boosts oil contents, highlighting a breakthrough in precision crop engineering. |
| 2025 | [Computationally Guided Design of a Soluble, Abundant and Functional AnfH Variant for the Expression of Fe-Only Nitrogenase in Plant Mitochondria](https://onlinelibrary.wiley.com/doi/10.1111/pbi.70263) | Plant Biotechnology Journal | The results show that the computational design strategy used here is a powerful approach for engineering nitrogenase into plants and more broadly to plant synthetic biology and recombinant protein production. |
| 2025 | [Cross-species modeling of plant genomes at single-nucleotide resolution using a pretrained DNA language model](https://pnas.org/doi/10.1073/pnas.2421738122) | Proceedings of the National Academy of Sciences | PlantCaduceus is a versatile DNA LM that can accelerate plant genomics and crop breeding applications and outperformed the best existing DNA language model in variant effect prediction and showed performance comparative to state-of-the-art protein LMs. |
| 2025 | [DMRU: Generative Deep-Learning to unravel condition specific cytosine methylation in plants](http://biorxiv.org/lookup/doi/10.1101/2025.02.06.635186) | bioRxiv | A first of its kind an explainable Deep Encoders-Decoders generative system, DMRU, which learns the relationship between transcritpome status and DNA methylation states at any given time, giving a strong alternative to costly bisulfite sequencing experiment... |
| 2025 | [Deciphering the sequence basis and application of transcriptional initiation regulation in plant genomes through deep learning](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03782-5) | Genome Biology | GenoRetriever is an interpretable deep learning model that deciphers the sequence basis of transcriptional initiation regulation across plant genomes and reveals that 31.85% of natural variation between wild and domesticated soybean drives shifts in promote... |
| 2025 | [Decoding tissue-specific enhancers in plants using massively parallel assays and deep learning](https://academic.oup.com/plcell/article/doi/10.1093/plcell/koaf236/8269526) | The Plant Cell | This study designed synthetic enhancers and experimentally validated their ability to specifically target tomato fruit, facilitating the de novo design of synthetic enhancers for tissue-specific gene expression in plants. |
| 2025 | [Deep Learning Enhances Precision of Citrullination Identification in Human and Plant Tissue Proteomes](https://linkinghub.elsevier.com/retrieve/pii/S1535947625000222) | Molecular & Cellular Proteomics | A novel data analysis pipeline that incorporates the deep learning model Prosit-Cit into the MS database search workflow to improve both the sensitivity and precision of citrullination site identification and reduces false positives is presented. |
| 2025 | [Deep learning applications advance plant genomics research](https://linkinghub.elsevier.com/retrieve/pii/S2468014125001839) | Horticultural Plant Journal | With the rapid development of high-throughput sequencing technologies and the accumulation of large-scale multi-omics data, deep learning (DL) has emerged as a powerful tool to solve complex biological problems, with particular promise in plant genomics. |
| 2025 | [DeepWheat: predicting the effects of genomic variants on gene expression and regulatory activities across tissues and varieties in wheat using deep learning](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03809-x) | Genome Biology | DeepWheat is presented, a broadly applicable deep learning framework comprising DeepEXP and DeepEPI, for accurate, tissue-specific gene expression prediction, enabling targeted cis-regulatory elements editing and offering a powerful tool for crop functional... |
| 2025 | [Effective Gene Expression Prediction and Optimization from Protein Sequences](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202407664) | Advanced Science | A novel connection between protein expression and sequence is uncovered, leading to the development of SRAB (Strength of Relative Amino Acid Bias) based on AEI (Amino Acid Expression Index), which highlights the efficacy of the developed model in predicting... |
| 2025 | [Engineering crop flower morphology facilitates robotization of cross-pollination and speed breeding](https://linkinghub.elsevier.com/retrieve/pii/S0092867425008402) | Cell | Artificial intelligence (AI) and robots offer vast opportunities in shifting toward precision agriculture to enhance crop yields, reduce costs, and promote sustainable practices. |
| 2025 | [Exploring plant protein functions through structure-based clustering](https://linkinghub.elsevier.com/retrieve/pii/S1360138525000913) | Trends in Plant Science | Structural-based protein clustering enables the identification of distant evolutionary relationships and novel protein families, and offers an effective strategy for exploring plant protein functions, bridging the gap between sequence data and function anno... |
| 2025 | [Feedback regulation of m6A modification creates local auxin maxima essential for rice microsporogenesis](https://linkinghub.elsevier.com/retrieve/pii/S1534580724007731) | Developmental Cell | It is suggested that OsZAF-dependent feedback regulation of m6A modification is integral to local auxin biosynthesis and signaling in anthers, which facilitates the timely generation of auxin maxima required for male meiosis in rice. |
| 2025 | [Fishing for a reelGene : evaluating gene models with evolution and machine learning](https://onlinelibrary.wiley.com/doi/10.1111/tpj.70483) | The Plant Journal | Assembled genomes and their associated annotations have transformed our study of gene function. |
| 2025 | [Gene regulatory network prediction using machine learning, deep learning, and hybrid approaches](https://www.maxapress.com/article/doi/10.48130/forres-0025-0014) | Forestry Research | This study developed and evaluated machine learning, deep learning, and hybrid approaches for constructing GRNs by integrating prior knowledge and large-scale transcriptomic data from Arabidopsis thaliana, poplar, and maize, demonstrating the effectiveness... |
| 2025 | [Genome-wide profiling of polymorphic short tandem repeats and their influence on gene expression and trait variation in diverse rice populations](https://linkinghub.elsevier.com/retrieve/pii/S1673852725000785) | Journal of Genetics and Genomics | This study constructs a map of 137,629 polymorphic STRs in the rice genome using a population-scale resequencing dataset, and identifies 44,672 expression STRs (eSTRs) by modeling gene expression in response to the length variation of STRs. |
| 2025 | [Harnessing DNA Foundation Models for Cross-Species Transcription Factor Binding Site Prediction in Plant Genomes](http://biorxiv.org/lookup/doi/10.1101/2025.07.14.664780) | bioRxiv | This study evaluates the performance of three large-scale pretrained DNA foundation models-DNABERT-2, AgroNT, and HyenaDNA-in predicting TFBSs in plants and demonstrates that foundation models, particularly HyenaDNA, offer superior predictive accuracy and c... |
| 2025 | [Harnessing the Foundation Model for Exploration of Single-cell Expression Atlases in Plants](https://academic.oup.com/gpb/advance-article/doi/10.1093/gpbjnl/qzaf024/8081791) | Genomics, Proteomics & Bioinformatics | Compared to traditional methods, scPlantLLM outperforms in key metrics such as adjusted rand index (ARI), normalized mutual information (NMI), and silhouette score (SIL), highlighting its superior clustering accuracy and biological relevance. |
| 2025 | [Heat stress responses mediated by N6-methyladenine DNA methylation in maize](https://linkinghub.elsevier.com/retrieve/pii/S2211124725008290) | Cell Reports | It is shown that 6mA dynamics in two maize inbred lines, B73 and Mo17, correlate with their responses to HS, and the role of 6mA in transcriptional regulation of crop stress adaptation is uncovered. |
| 2025 | [Kinetic parameter prediction using neural networks identifies limitations to C4 photosynthesis](http://biorxiv.org/lookup/doi/10.1101/2025.07.16.665120) | bioRxiv | The use of C4TUNE presents a fast and precise approach for parameter prediction based on minimal datasets, which can efficiently predict parameters of a large-scale photosynthesis model from photosynthesis response curves. |
| 2025 | [Large DNA and protein language models enhance discovery of deleterious mutations in maize](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03890-2) | Genome Biology |  |
| 2025 | [Machine learning-based identification of general transcriptional predictors for plant disease](https://nph.onlinelibrary.wiley.com/doi/10.1111/nph.20264) | New Phytologist | This study investigated the generalizability of Arabidopsis thaliana immune responses across diverse pathogens, including Botrytis cinerea, Sclerotinia sclerotiorum, and Pseudomonas syringae, using a data-driven, machine learning approach. |
| 2025 | [Machine-learning models based on biological ligand theory and quantitative ion character-activity relationship for predicting metal plant toxicity](https://linkinghub.elsevier.com/retrieve/pii/S0304389425025385) | Journal of Hazardous Materials | The proposed machine-learning (ML) model enables three-dimensional analysis of toxicity-influencing factors, outperforming traditional BLM and QICAR approaches, providing a transformative tool for rapid metal risk assessment and precision soil management in... |
| 2025 | [PDLLMs: A group of tailored DNA large language models for analyzing plant genomes](https://linkinghub.elsevier.com/retrieve/pii/S1674205224003903) | Molecular Plant |  |
| 2025 | [PLM-OMG: Protein Language Model-Based Ortholog Detection for Cross-Species Cell Type Mapping](http://biorxiv.org/lookup/doi/10.1101/2025.05.30.657127) | bioRxiv | The results show that PLM-OMG enables scalable and reusable orthogroup detection without recomputing existing groups, significantly reducing computational overhead and highlighting its potential to transform cross-species transcriptomic analysis in plant ge... |
| 2025 | [PTF-Vāc: An explainable and generative deep co-learning encoder-decoder system for ab initio discovery of plant transcription factor binding sites](https://linkinghub.elsevier.com/retrieve/pii/S2590346225003050) | Plant Communications |  |
| 2025 | [PlantCAD2: A Long-Context DNA Language Model for Cross-Species Functional Annotation in Angiosperms](http://biorxiv.org/lookup/doi/10.1101/2025.08.27.672609) | bioRxiv | Comprehensive zero-shot testing shows that PlantCAD2 efficiently captures evolutionary conservation, surpassing the 7-billion-parameter Evo2 model in 10 of 12 tasks and with parameter-efficient fine-tuning, PlantCAD2 also outperforms the 1-billion-parameter... |
| 2025 | [PlantDeBERTa: An Open Source Language Model for Plant Science](http://arxiv.org/abs/2506.08897) | arXiv | arXiv:2506.08897 \[cs\] TLDR: By providing a scalable and reproducible framework for high-resolution entity recognition, PlantDeBERTa bridges a critical gap in agricultural NLP and paves the way for intelligent, data-driven systems in plant genomics, phenomic... |
| 2025 | [PmiProPred: A novel method towards plant miRNA promoter prediction based on CNN-Transformer network and convolutional block attention mechanism](https://linkinghub.elsevier.com/retrieve/pii/S0141813025011791) | International Journal of Biological Macromolecules | PmiProPred is an advanced tool designed for predicting plant miRNA promoters from a wide spectrum of genomes and is a robust and effective tool for discovering plant miRNA promoters. |
| 2025 | [Polymer-derived distance penalties improve chromatin interaction predictions from single-cell data across crop genomes](http://biorxiv.org/lookup/doi/10.1101/2025.08.20.671329) | bioRxiv | A penalty function grounded in polymer physics is derived by fitting a multi-component power-law model to experimental Hi-C data from maize, rice, and soybean, which substantially improves concordance with Hi-C, reduces false-positive rates of long-range in... |
| 2025 | [Precise engineering of gene expression by editing plasticity](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03516-7) | Genome Biology | Background: Identifying transcriptional cis-regulatory elements (CREs) and understanding their role in gene expression are essential for the precise manipulation of gene expression and associated phenotypes. |
| 2025 | [Predicted protein 3D structures provide essential insights into the genetic architecture underlying phenotypic diversity in maize](http://genome.cshlp.org/lookup/doi/10.1101/gr.280514.125) | Genome Research | Variation in protein 3D structures reflects genetic variation and contributes to phenotypic diversity, yet its underlying genetic mechanisms remain unclear. |
| 2025 | [Predicting Gene Expression Responses to Cold in Arabidopsis thaliana Using Natural Variation in DNA Sequence](https://www.mdpi.com/2073-4425/16/9/1108) | Genes | Convolutional neural networks, which learn de novo cis-regulatory motifs in DNA sequences to predict expression response to cold, found that CNNs predicted differential expression with moderate accuracy, with evidence that predictions were hindered by the b... |
| 2025 | [Predictive genetic circuit design for phenotype reprogramming in plants](https://www.nature.com/articles/s41467-025-56042-2) | Nature Communications | A predictive framework for designing synthetic genetic circuits in Arabidopsis and Nicotiana benthamiana in reprograming gene expression and hypersensitive response is established, offering valuable tools for the rapid engineering of plant traits in biotech... |
| 2025 | [Synthetic biology and artificial intelligence in crop improvement](https://linkinghub.elsevier.com/retrieve/pii/S2590346224006412) | Plant Communications | This review explores the fundamental engineering principles used in crop synthetic biology and their applications for crop improvement, and proposes the development of SMART (self-monitoring, adapted, and responsive technology) crops through AI-empowered sy... |
| 2025 | [Systematically Revealing Quantitative Multi-Target Integrative Effects of Plants With Artificial Intelligence Method](https://onlinelibrary.wiley.com/doi/10.1111/pbi.70321) | Plant Biotechnology Journal | A deep auto-encoding neural network model was used to encode the expression levels of multiple common targets between hawthorn and atherosclerosis in each cell of the single-cell transcriptome of atherosclerotic perivascular adipose tissue as an integrated... |
| 2025 | [TransGeneSelector: using a transformer approach to mine key genes from small transcriptomic datasets in plant responses to various environments](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-025-11434-y) | BMC Genomics | This study introduces TransGeneSelector, the first deep learning framework specifically designed for mining key genes from small transcriptomic datasets, and provides a framework that leverages deep learning for key gene identification in small transcriptom... |
| 2025 | [UniSplicer: A deep-learning framework for accurate splice-site prediction and splice-altering mutation detection across diverse taxa](https://linkinghub.elsevier.com/retrieve/pii/S2590346225004481) | Plant Communications |  |
| 2025 | [mamp-ml: A deep learning approach to epitope immunogenicity in plants](http://biorxiv.org/lookup/doi/10.1101/2025.07.11.664399) | bioRxiv | Eukaryotes detect biomolecules through surface-localized receptors, key signaling components. |
| 2024 | [A foundational large language model for edible plant genomes](https://www.nature.com/articles/s42003-024-06465-2) | Communications Biology | Significant progress has been made in the field of plant genomics, as demonstrated by the increased use of high-throughput methodologies that enable the characterization of multiple genome-wide molecular phenotypes. |
| 2024 | [A scalable method for modulating plant gene expression using a multispecies genomic model and protoplast-based massively parallel reporter assay](http://biorxiv.org/lookup/doi/10.1101/2024.12.05.626999) | bioRxiv | The CRE.AI.TIVE platform is presented, enabling upregulation of plant gene activity without a priori knowledge of individual cis-regulatory elements or their specific location, and is demonstrated by mutagenesis of a proximal promoter of the tomato gene Slb... |
| 2024 | [Advancing Plant Metabolic Research By Using Large Language Models To Expand Databases And Extract Labelled Data](http://biorxiv.org/lookup/doi/10.1101/2024.11.05.622126) | bioRxiv | The use of large language models and various prompt engineering techniques to expand and subset existing databases in task-specific ways are explored and evaluated, illustrating the potential for high-accuracy additions and restructurings of existing databa... |
| 2024 | [Advancing plant biology through deep learning-powered natural language processing](https://link.springer.com/10.1007/s00299-024-03294-9) | Plant Cell Reports | The strategic application of deep learning methodologies, particularly leveraging the potential of LLMs, will undoubtedly play a pivotal role in advancing plant sciences, plant production, plant uses and propelling the trajectory toward sustainable agroecol... |
| 2024 | [An interpretable RNA foundation model for exploring functional RNA motifs in plants](https://www.nature.com/articles/s42256-024-00946-z) | Nature Machine Intelligence | This study introduced PlantRNA-FM, a high-performance and interpretable RNA FM specifically designed for plants, which achieves superior performance in plant RNA biology tasks and enables the discovery of functional RNA sequence and structure motifs across... |
| 2024 | [Arabidopsis and maize terminator strength is determined by GC content, polyadenylation motifs and cleavage probability](https://www.nature.com/articles/s41467-024-50174-7) | Nature Communications | Using Plant STARR-seq, Gorjifard et al analyzed over 50,000 plant terminators and found that plant terminator activity is species-specific, highly dependent on GC content and polyadenylation motifs, and they developed a computational model to predict termin... |
| 2024 | [Artificial intelligence in plant breeding](https://linkinghub.elsevier.com/retrieve/pii/S0168952524001677) | Trends in Genetics | This work explores the wider potential of AI tools in various facets of breeding, including data collection, unlocking genetic diversity within genebanks, and bridging the genotype-phenotype gap to facilitate crop breeding. |
| 2024 | [Big data and artificial intelligence-aided crop breeding: Progress and prospects](https://onlinelibrary.wiley.com/doi/10.1111/jipb.13791) | Journal of Integrative Plant Biology | This work summarizes current breeding methods and discusses the need for new ways to support breeding efforts, and proposes the concept of intelligent precision design breeding (IPDB), which will enhance the predictability, efficiency, and cost of crop bree... |
| 2024 | [Comprehensive analysis of computational approaches in plant transcription factors binding regions discovery](https://linkinghub.elsevier.com/retrieve/pii/S2405844024151717) | Heliyon | This study expects this study to serve as a guide for better understanding of software tools' approaches for plant specific TFBRs discovery and the care to be taken while applying them, especially during cross-species applications. |
| 2024 | [Deep learning can predict subgenome dominance in ancient but not in neo/synthetic polyploidized genomes](https://onlinelibrary.wiley.com/doi/10.1111/tpj.16979) | The Plant Journal | Results show that subgenome dominance is associated with long-term sequence differentiation between the promoters of homoeologs, suggesting that subgenome expression dominance precedes and is the driving force or even the determining factor for sequence div... |
| 2024 | [Deep learning chromatin profiles reveal the cis-regulatory sequence code of the rice genome](https://linkinghub.elsevier.com/retrieve/pii/S1673852724003564) | Journal of Genetics and Genomics |  |
| 2024 | [Deep learning the cis-regulatory code for gene expression in selected model plants](https://www.nature.com/articles/s41467-024-47744-0) | Nature Communications | The training of interpretable deep learning models predicting gene expression profiles from gene flanking regions of the plant species Arabidopsis thaliana, Solanum lycopersicum, Sorghum bicolor, and Zea mays shows utility in functional genomics and phenoty... |
| 2024 | [DeepCBA: A deep learning framework for gene expression prediction in maize based on DNA sequences and chromatin interactions](https://linkinghub.elsevier.com/retrieve/pii/S2590346224002931) | Plant Communications | This study developed a highly accurate deep learning-based gene expression prediction model (DeepCBA) based on maize chromatin interaction data that exhibits higher accuracy in expression classification and expression value prediction and demonstrates the f... |
| 2024 | [Explainable AI-guided identification of a novel protein-RNA interactive frame for selective siRNA accumulation in plants](http://biorxiv.org/lookup/doi/10.1101/2024.12.02.626406) | bioRxiv | A progressive deep learning framework integrating Transformer and convolutional neural networks is developed and identified RNA-binding proteins that directly recognize the key signal sequences to act for selective siRNA accumulation. |
| 2024 | [Exploring salt tolerance mechanisms using machine learning for transcriptomic insights: case study in Spartina alterniflora](https://academic.oup.com/hr/article/doi/10.1093/hr/uhae082/7636586) | Horticulture Research | This innovative approach, combining transcriptomic analysis with machine learning-based annotation, avoids the reliance on homology information and facilitates the discovery of unknown gene functions, and is applicable across all sequenced species. |
| 2024 | [GenomicLinks: deep learning predictions of 3D chromatin interactions in the maize genome](https://academic.oup.com/nargab/article/doi/10.1093/nargab/lqae123/7770960) | NAR Genomics and Bioinformatics | Gene regulation in eukaryotes is partly shaped by the 3D organization of chromatin within the cell nucleus. |
| 2024 | [Identification of lineage-specific cis - trans regulatory networks related to kiwifruit ripening initiation](https://onlinelibrary.wiley.com/doi/10.1111/tpj.17093) | The Plant Journal | Previous research on the ripening process of many fruit crop varieties typically involved analyses of the conserved genetic factors among species. |
| 2024 | [Identification of plant transcriptional activation domains](https://www.nature.com/articles/s41586-024-07707-3) | Nature | A yeast library approach is used to experimentally identify Arabidopsis ADs on a proteome-wide scale, and a deep learning approach applied to this dataset can predict AD activity on the basis of sequence features. |
| 2024 | [Inference and prioritization of tissue-specific regulons in Arabidopsis and Oryza](https://link.springer.com/10.1007/s42994-024-00176-2) | aBIOTECH | InferReg was used to successfully identify important regulons in various tissues of Arabidopsis and Oryza, which has improved the understanding of tissue-specific regulations and the roles of regulons in tissue differentiation and development. |
| 2024 | [LOGOWheat: deep learning-based prediction of regulatory effects for noncoding variants in wheats](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae705/7950730) | Briefings in Bioinformatics | The concept of extracting potential functional variations from the wheat population by integrating evolutionary conservation information is proposed, using LOGOWheat, a deep learning-based tool designed to predict the regulatory effects of noncoding variant... |
| 2024 | [Machine learning assists prediction of genes responsible for plant specialized metabolite biosynthesis by integrating multi-omics data](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-024-10258-6) | BMC Genomics | This work integrated state-of-the-art automated machine learning (ML) frame AutoGluon-Tabular and multi-omics data from Arabidopsis to predict genes encoding enzymes involved in biosynthesis of plant specialized metabolite (PSM), focusing on the three main... |
| 2024 | [Modeling 0.6 million genes for the rational design of functional cis -regulatory variants and de novo design of cis- regulatory sequences](https://pnas.org/doi/10.1073/pnas.2319811121) | Proceedings of the National Academy of Sciences | PhytoExpr is a deep learning framework that reads regulatory DNA sequences to predict their messenger ribonucleic acid (mRNA) abundance and also the plant species they are from and is fit into two algorithms for the rational design of functional cis-regulat... |
| 2024 | [Modeling alternative translation initiation sites in plants reveals evolutionarily conserved cis -regulatory codes in eukaryotes](http://genome.cshlp.org/lookup/doi/10.1101/gr.278100.123) | Genome Research | The TIS prediction model provides global estimates of TISs to discover neglected protein-coding genes across plant genomes and elucidate the mechanistic and evolutionary basis of T IS recognition, whereby cis-regulatory RNA signatures affect start site sele... |
| 2024 | [Multi-kernel feature extraction with dynamic fusion and downsampled residual feature embedding for predicting rice RNA N 6-methyladenine sites](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae647/7923979) | Briefings in Bioinformatics | A new end-to-end deep learning framework is developed, MFDm, to address issues faced on rice, including sparse information and invalid padding, reducing feature extraction accuracy. |
| 2024 | [Organ-delimited gene regulatory networks provide high accuracy in candidate transcription factor selection across diverse processes](https://pnas.org/doi/10.1073/pnas.2322751121) | Proceedings of the National Academy of Sciences | A machine-learning framework for building unbiased gene expression datasets for each organ, and to infer organ-delimited gene regulatory networks is developed, which is broadly applicable across any organism (plant or animal) that has a large body of public... |
| 2024 | [PEA-m6A: an ensemble learning framework for accurately predicting N 6-methyladenosine modifications in plants](https://academic.oup.com/plphys/article/195/2/1200/7617589) | Plant Physiology | The PEA-m6A framework builds ensemble learning-based m6A prediction models with statistic-based and deep learning-driven features, achieving superior performance with an improvement of 6.7% in the area under precision-recall curve (PRC). |
| 2024 | [PTFSpot: deep co-learning on transcription factors and their binding regions attains impeccable universality in plants](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae324/7714599) | Briefings in Bioinformatics | A revolutionary transformers based deep-learning approach, PTFSpot, which learns from TF structures and their binding regions co-variability to bring a universal TF-DNA interaction model to detect TFBR with complete freedom from TF and species specific mode... |
| 2024 | [Plant enhancers exhibit both cooperative and additive interactions among their functional elements](https://academic.oup.com/plcell/article/36/7/2570/7633284) | The Plant Cell | This work demonstrates that plant enhancers show evidence for both cooperative and additive interactions among their functional elements, which can be harnessed to design strong, condition-specific synthetic enhancers. |
| 2024 | [Population-wide DNA methylation polymorphisms at single-nucleotide resolution in 207 cotton accessions reveal epigenomic contributions to complex traits](https://www.nature.com/articles/s41422-024-01027-x) | Cell Research | The findings prove that DNA methylation data can serve as an additional resource for breeding purposes and can offer opportunities to enhance and expedite the crop improvement process. |
| 2024 | [Predicting gene expression responses to environment in Arabidopsis thaliana using natural variation in DNA sequence](http://biorxiv.org/lookup/doi/10.1101/2024.04.25.591174) | bioRxiv | Convolutional neural networks, which learn de novo cis-regulatory motifs in DNA sequences to predict expression response to environment, found that CNNs predicted differential expression with moderate accuracy, with evidence that predictions were hindered b... |
| 2024 | [Predicting protein synergistic effect in Arabidopsis using epigenome profiling](https://www.nature.com/articles/s41467-024-53565-y) | Nature Communications | QHistone is a machine learning tool for Arabidopsis that predicts histone modifications and synergistic interactions that helps researchers understand gene cooperation, identify new protein partners, and gain insights into plant epigenetic regulation. |
| 2024 | [Predmoter-cross-species prediction of plant promoter and enhancer regions](https://academic.oup.com/bioinformaticsadvances/article/doi/10.1093/bioadv/vbae074/7681899) | Bioinformatics Advances | Predmoter is presented, a deep neural network able to predict base-wise ATAC-seq and histone Chromatin immunoprecipitation DNA-sequencing (ChIP-seq) read coverage for plant genomes and will help identifying CREs and so gaining further insight into gene regu... |
| 2024 | [RNAirport: a deep neural network-based database characterizing representative gene models in plants](https://linkinghub.elsevier.com/retrieve/pii/S1673852724000572) | Journal of Genetics and Genomics | A ranking algorithm and a deep-learning model are developed to annotate representative 5'-leaders for five plant species and will pave the way to Ribo-Seq ORF annotation, identical to the project recently initiated by human GENCODE. |
| 2024 | [RiceSNP-BST: a deep learning framework for predicting biotic stress-associated SNPs in rice](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae599/7904843) | Briefings in Bioinformatics | RiceSNP-BST, an automatic architecture search framework designed to predict SNPs associated with rice biotic stress traits (BST-associated SNPs) by integrating multidimensional features, successfully innovates the datasets and offers more precision than sta... |
| 2024 | [The CropGPT project: Call for a global, coordinated effort in precision design breeding driven by AI using biological big data](https://linkinghub.elsevier.com/retrieve/pii/S1674205223004094) | Molecular Plant |  |
| 2023 | [AlphaFold-Multimer predicts cross-kingdom interactions at the plant-pathogen interface](https://www.nature.com/articles/s41467-023-41721-9) | Nature Communications | Alphafold-Multimer is used to screen 1,879 SSPs of seven tomato pathogens for interacting with six defence-related hydrolases of tomato that accumulate to high levels in the apoplast during infection to demonstrate the power of artificial intelligence to ac... |
| 2023 | [Cross-species predictive modeling reveals conserved drought responses between maize and sorghum](https://pnas.org/doi/10.1073/pnas.2216894120) | Proceedings of the National Academy of Sciences | A predictive model to classify drought stress responses in sorghum and identify important features that are responsive to water deficit is developed, which suggests there are deeply conserved drought responses across C4 grasses that are unrelated to tolerance. |
| 2023 | [DNA language models are powerful predictors of genome-wide variant effects](https://pnas.org/doi/10.1073/pnas.2311219120) | Proceedings of the National Academy of Sciences | The expanding catalog of genome-wide association studies (GWAS) provides biological insights across a variety of species, but identifying the causal variants behind these associations remains a significant challenge. |
| 2023 | [DNABERT-based explainable lncRNA identification in plant genome assemblies](https://linkinghub.elsevier.com/retrieve/pii/S2001037023004397) | Computational and Structural Biotechnology Journal | This study presents a study using Natural Language Processing (NLP) models to identify plant lncRNAs from genomic sequences rather than transcriptomic data, and demonstrates for the first time the identification of lncRNA as well as genomic sequences, inste... |
| 2023 | [Deep learning-assisted prediction of protein-protein interactions in Arabidopsis thaliana](https://onlinelibrary.wiley.com/doi/10.1111/tpj.16188) | The Plant Journal | An integrative deep learning framework, DeepAraPPI, allowing us to predict protein-protein interactions (PPIs) of Arabidopsis utilizing sequence, domain and Gene Ontology (GO) information, shows superior performance and provides better cross-species predict... |
| 2023 | [Deep learning-enabled discovery and characterization of HKT genes in Spartina alterniflora](https://onlinelibrary.wiley.com/doi/10.1111/tpj.16397) | The Plant Journal | Deep learning-based methods are used to automatically extract sequence and protein characteristics from the newly assemble S. |
| 2023 | [Designing artificial synthetic promoters for accurate, smart, and versatile gene expression in plants](https://linkinghub.elsevier.com/retrieve/pii/S2590346223000561) | Plant Communications | The importance of synthetic promoters is illustrated, promoter architecture is introduced, and advances in synthetic promoter construction are summarized, which thoroughly summarizes advances in Synthetic promoter construction. |
| 2023 | [ExamPle: explainable deep learning framework for the prediction of plant small secreted peptides](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btad108/7075544) | Bioinformatics | ExamPle, a novel deep learning model using Siamese network and multi-view representation for the explainable prediction of the plant SSPs, can discover sequential characteristics and identify the contribution of each amino acid for the predictions by utiliz... |
| 2023 | [Functional annotation of proteins for signaling network inference in non-model species](https://www.nature.com/articles/s41467-023-40365-z) | Nature Communications | A multi-layer neural network that determines protein functionality directly from the protein sequence is developed that shows generalization and scalability and extends to Oryza sativa, Zea mays, Sorghum bicolor, and Triticum aestivum. |
| 2023 | [Plant Promoters and Terminators for High-Precision Bioengineering](https://linkinghub.elsevier.com/retrieve/pii/S2693125724000177) | BioDesign Research | The function and features of plant core promoters, proximal and distal promoters, and terminators are reviewed, and their effects on and benchmarking strategies for regulating gene expression are reviewed. |
| 2023 | [TSPTFBS 2.0: trans-species prediction of transcription factor binding sites and identification of their core motifs in plants](https://www.frontiersin.org/articles/10.3389/fpls.2023.1175837/full) | Frontiers in Plant Science | DenseNet not only has achieved greater predictability than baseline methods such as LS-GKM and MEME for above 389 TFs from Arabidopsis, maize and rice, but also has greater performance on trans-species prediction of a total of 15TFs from other six plant spe... |
| 2023 | [iCREPCP: A deep learning-based web server for identifying base-resolution cis-regulatory elements within plant core promoters](https://linkinghub.elsevier.com/retrieve/pii/S2590346222002929) | Plant Communications | The identification of plant CRMs or critical CREs will not only help to understand transcriptional regulatory mechanisms in plants but also serve as an essential prerequisite for plant breeding 4.0-breeding by genome editing. |
| 2022 | [Comprehensive transcriptional variability analysis reveals gene networks regulating seed oil content of Brassica napus](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02801-z) | Genome Biology | The XGBoost model is constructed and the mechanisms affecting the seed oil content regulated by hotspot87-88 are predicted and experimentally validate that the transcription factors, NAC13 and SCL31, positively regulate the seedOil content. |
| 2022 | [Cross-species enhancer prediction using machine learning](https://linkinghub.elsevier.com/retrieve/pii/S0888754322001999) | Genomics | This work investigates the ability of ML methods to identify enhancers in three non-model mammalian species (cattle, pig and dog) using human and mouse enhancer data from VISTA and publicly available ChIP-seq and proposes that the ML methods have predictive... |
| 2022 | [Deciphering the regulatory code of histone modifications in plants](https://linkinghub.elsevier.com/retrieve/pii/S1673852722001837) | Journal of Genetics and Genomics |  |
| 2022 | [DeepBSA: A deep-learning algorithm improves bulked segregant analysis for dissecting complex traits](https://linkinghub.elsevier.com/retrieve/pii/S1674205222002672) | Molecular Plant | A BSA method driven by deep learning -DeepBSA for QTL mapping and functional gene cloning is developed, integrating five widely used BSA algorithms and two newly developed algorithms, which are easy to operate and can quickly map QTLs and functional genes. |
| 2022 | [Genome-wide cis-decoding for expression design in tomato using cistrome data and explainable deep learning](https://academic.oup.com/plcell/article/34/6/2174/6542321) | The Plant Cell | This study used cistrome datasets and explainable convolutional neural network (CNN) frameworks to predict genome-wide expression patterns in tomato fruits from the DNA sequences in gene regulatory regions and developed a prediction model of a key expressio... |
| 2022 | [Identifying transcription factor-DNA interactions using machine learning](https://academic.oup.com/insilicoplants/article/doi/10.1093/insilicoplants/diac014/6652810) | in silico Plants | Machine learning approaches have been applied to identify transcription factor (TF)-DNA interaction important for gene regulation and expression. |
| 2022 | [Machine learning models reveal the importance of time-point specific cis-regulatory elements in Arabidopsis thaliana wounding response](https://academic.oup.com/plcell/article/34/2/716/6454953) | The Plant Cell | Machine learning approaches incorporating information from curated cis-elements, in silico predicted cis-Elements, DNase hypersensitivity sites (DHSs), and in vitro DNA affinity purification sequencing (DAP-seq) data are utilized to characterize wound-induc... |
| 2022 | [Modeling chromatin state from sequence across angiosperms using recurrent convolutional neural networks](https://acsess.onlinelibrary.wiley.com/doi/10.1002/tpg2.20249) | The Plant Genome | With the cross-species "a2z" model it is now feasible to predict the chromatin accessibility and methylation landscape of any angiosperm genome, suggesting strong conservation of chromatin mechanisms across angiosperms. |
| 2022 | [PlantBind: an attention-based multi-label neural network for predicting plant transcription factor binding sites](https://academic.oup.com/bib/article/doi/10.1093/bib/bbac425/6713513) | Briefings in Bioinformatics | PlantBind is presented, a method for integrated prediction and interpretation of transcription factor binding sites based on DNA sequences and DNA shape profiles that provides an effective solution for identifying plant TFBSs, which will promote greater und... |
| 2022 | [Predicting protein phosphorylation sites in soybean using interpretable deep tabular learning network](https://academic.oup.com/bib/article/doi/10.1093/bib/bbac015/6526722) | Briefings in Bioinformatics | A hybrid feature set of sequential-based features, physicochemical properties and position-specific scoring matrices is used to predict serine (Ser/S), threonine (Thr/T) and tyrosine (Tyr/Y) p-sites in soybean for the first time. |
| 2022 | [Prediction of conserved and variable heat and cold stress response in maize using cis-regulatory information](https://academic.oup.com/plcell/article/34/1/514/6420714) | The Plant Cell | Transcriptome profiling of maize inbred and hybrid seedlings subjected to heat or cold stress was used to identify key cis-regulatory elements and develop models to predict gene expression responses. |
| 2022 | [Prediction of evolutionary constraint by genomic annotations improves functional prioritization of genomic variants in maize](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02747-2) | Genome Biology | The results suggest that predicting nucleotide conservation across angiosperms may effectively prioritize sites most likely to impact fitness-related traits in crops, without being limited by shifting selection, missing data, and low depth of multiple-seque... |
| 2022 | [SMOC: a smart model for open chromatin region prediction in rice genomes](https://linkinghub.elsevier.com/retrieve/pii/S1673852722000522) | Journal of Genetics and Genomics |  |
| 2022 | [iProm-Zea: A two-layer model to identify plant promoters and their types using convolutional neural network](https://linkinghub.elsevier.com/retrieve/pii/S088875432200129X) | Genomics | A two-layer predictor called "iProm-Zea" using the convolutional neural network (CNN) for identify TATA and TATA less promoters and demonstrated that the constructed predictor showed great potential for identifying promoters and classifying them as Tata and... |
| 2021 | [A deep learning approach to automate whole-genome prediction of diverse epigenomic modifications in plants](https://nph.onlinelibrary.wiley.com/doi/10.1111/nph.17630) | New Phytologist | The deep-learning-enabled SMEP can reliably mine epigenomic datasets from diverse plants to yield actionable insights about epigenomic sites and opens new avenues for the application of predictive tools to facilitate functional research, and will almost cer... |
| 2021 | [An inferred functional impact map of genetic variants in rice](https://linkinghub.elsevier.com/retrieve/pii/S1674205221002604) | Molecular Plant | It is demonstrated how the functional impact map could be used to prioritize the causal variants in mapping populations and found that large-effect GVs in coding and regulatory regions might be subject to selection in different directions. |
| 2021 | [CharPlant: A De Novo Open Chromatin Region Prediction Tool for Plant Genomes](https://academic.oup.com/gpb/article/19/5/860/7230429) | Genomics, Proteomics & Bioinformatics | Chromatin accessibility is a highly informative structural feature for understanding gene transcription regulation, because it indicates the degree to which nuclear macromolecules such as proteins and RNAs can access chromosomal DNA. |
| 2021 | [Evolutionarily informed machine learning enhances the power of predictive gene-to-phenotype relationships](https://www.nature.com/articles/s41467-021-25893-w) | Nature Communications | An evolutionarily informed machine learning approach within and across species is used to predict genes affecting nitrogen utilization in crops, and their approach is also useful in mammalian systems. |
| 2021 | [Interpreting machine learning models to investigate circadian regulation and facilitate exploration of clock function](https://pnas.org/doi/full/10.1073/pnas.2103070118) | Proceedings of the National Academy of Sciences | The circadian clock is an internal molecular 24-h timer that is critical to life on Earth. |
| 2021 | [PlantDeepSEA, a deep learning-based web service to predict the regulatory effects of genomic variants in plants](https://academic.oup.com/nar/article/49/W1/W523/6284177) | Nucleic Acids Research | PlantDeepSEA is presented as a deep learning-based web service to predict regulatory effects of genomic variants in multiple tissues of six plant species (including four crops). |
| 2021 | [Synthetic promoter designs enabled by a comprehensive analysis of plant core promoters](https://www.nature.com/articles/s41477-021-00932-y) | Nature Plants | It is demonstrated that core promoter elements-notably the TATA box-as well as promoter GC content and promoter-proximal transcription factor binding sites influence promoter strength, and a promising experimental approach is established to optimize native... |
| 2021 | [TSPTFBS: a Docker image for trans-species prediction of transcription factor binding sites in plants](https://academic.oup.com/bioinformatics/article/37/2/260/6069568) | Bioinformatics | The deep convolutional neural network (DeepCNN) is employed to build 265 Arabidopsis TFBS prediction models based on available DAP-seq (DNA affinity purification sequencing) datasets, and then transferred into homologous TFs in other plants to demonstrate t... |
| 2019 | [Cis-Regulatory Code for Predicting Plant Cell-Type Transcriptional Response to High Salinity](https://academic.oup.com/plphys/article/181/4/1739-1751/6000542) | Plant Physiology | These findings not only advance the understanding of the regulatory mechanisms of the plant spatial transcriptional response through cis-regulatory codes but also suggest broad applicability of the approach to any species, particularly those with little or... |

</details>

## S2F-Review (54)

<details>
<summary>Show S2F-Review papers (54)</summary>

| Year | Paper | Venue | Note |
| --- | --- | --- | --- |
| 2025 | [A Comparative Review of RNA Language Models](https://doi.org/10.48550/arXiv.2505.09087) | arXiv | Results shows that the models doing well on secondary structure prediction often perform worse in function classification or vice versa, suggesting that more balanced unsupervised training is needed. |
| 2025 | [A Comprehensive Review of Transformer-based language models for Protein Sequence Analysis and Design](http://arxiv.org/abs/2507.13646) | arXiv | arXiv:2507.13646 \[cs\] |
| 2025 | [AI-driven protein design](https://www.nature.com/articles/s44222-025-00349-8) | Nature Reviews Bioengineering |  |
| 2025 | [AI-empowered human microbiome research](https://gut.bmj.com/lookup/doi/10.1136/gutjnl-2025-335946) | Gut | This review systematically explore AI-driven methodologies in microbiome research, including clustering algorithms, dimensionality reduction techniques, convolutional and recurrent neural networks, and emerging large language models to chart a path forward... |
| 2025 | [AI4Protein: transforming the future of protein design](https://link.springer.com/10.1007/s11427-024-2906-3) | Science China Life Sciences | This review aims to introduce the recent progress of AI in protein research by introducing how AI models represent protein sequences, structures, and other properties and the applications of generative models in protein design. |
| 2025 | [Advancing bioinformatics with large language models: components, applications and perspectives](https://doi.org/10.48550/arXiv.2401.04155) | arXiv | This review will present a summary of the prominent large language models used in natural language processing, such as BERT and GPT, and focus on exploring the applications of large language models at different omics levels in bioinformatics, mainly includi... |
| 2025 | [Artificial intelligence for comprehensive DNA methylation analysis: overview, challenges, and future directions](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf468/8254330) | Briefings in Bioinformatics | A comprehensive review of the synergy between artificial intelligence and DNA methylation analysis, encompassing machine learning, deep learning, natural language processing, and explainable artificial intelligence is offered. |
| 2025 | [Artificial intelligence in bioinformatics: a survey](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf576/8315885) | Briefings in Bioinformatics | This review systematically summarizes recent research progress and representative applications of AI techniques in bioinformatics, specifically discussing suitable scenarios and advantages of traditional machine learning algorithms, deep learning models, an... |
| 2025 | [Artificial intelligence in molecular biology](https://linkinghub.elsevier.com/retrieve/pii/S1097276524010086) | Molecular Cell | In this focus issue, researchers spoke with researchers about using these tools to address various biological questions and explore both current implications and future possibilities. |
| 2025 | [Bridging artificial intelligence and biological sciences: a comprehensive review of large language models in bioinformatics](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf357/8212018) | Briefings in Bioinformatics | The current research status of LLMs in bioinformatics is summarized, their advantages and limitations are evaluated, and insights and recommendations for future research directions are provided, thereby positioning LLMs as essential tools in bioinformatics... |
| 2025 | [Computational Protein Science in the Era of Large Language Models (LLMs)](http://arxiv.org/abs/2501.10282) | arXiv | arXiv:2501.10282 \[cs\] TLDR: A systematic overview of computational protein science empowered by LLM techniques is presented, highlighting their remarkable achievements in promoting protein structure prediction, protein function prediction, and protein desig... |
| 2025 | [DNA sequence analysis landscape: a comprehensive review of DNA sequence analysis task types, databases, datasets, word embedding methods, and language models](https://www.frontiersin.org/articles/10.3389/fmed.2025.1503229/full) | Frontiers in Medicine | This paper equips AI researchers with essential biological knowledge of 44 distinct DNA sequence analysis tasks and aligns these tasks with 3 distinct AI-paradigms, namely, classification, regression, and clustering. |
| 2025 | [Foundation models in bioinformatics](https://academic.oup.com/nsr/article/doi/10.1093/nsr/nwaf028/7979309) | National Science Review | The aim is to assist scientists in selecting appropriate FMs in bioinformatics, according to four model types: language FMs, vision FMs, graph FMs and multimodal FMs, to establish the theoretical and practical foundation for continued innovation in molecula... |
| 2025 | [From Code to Life: The AI-Driven Revolution in Genome Editing](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202417029) | Advanced Science | This review explores the intersection of AI and genome editing, highlighting key innovations, challenges, and future prospects at the intersection of artificial intelligence and genome editing. |
| 2025 | [Genomic language models: opportunities and challenges](https://linkinghub.elsevier.com/retrieve/pii/S0168952524002956) | Trends in Genetics | This work discusses major considerations for developing and evaluating genomic language models (gLMs), and highlights key applications of gLMs, including functional constraint prediction, sequence design, and transfer learning. |
| 2025 | [Harnessing artificial intelligence to advance CRISPR-based genome editing technologies](https://www.nature.com/articles/s41576-025-00907-1) | Nature Reviews Genetics | This Review summarizes key AI methodologies underlying genome editing advances and discusses their recent noteworthy applications, and discusses emerging opportunities, such as AI-powered virtual cell models, which can guide genome editing through target se... |
| 2025 | [Identification, characterization, and design of plant genome sequences using deep learning](https://onlinelibrary.wiley.com/doi/10.1111/tpj.17190) | The Plant Journal | Prospects for the future development of deep learning in plants with regard to multiple omics data, algorithm optimization, large language models, sequence design, and intelligent breeding are provided. |
| 2025 | [Illuminating the universe of enzyme catalysis in the era of artificial intelligence](https://linkinghub.elsevier.com/retrieve/pii/S2405471225002054) | Cell Systems | Scientific research has revealed only a minuscule fraction of the enzymes that evolution has generated to power life's essential chemical reactions-and an even tinier fraction of the vast universe of possible enzymes. |
| 2025 | [In silico genome transplants and the cis-regulatory basis of biodiversity](https://linkinghub.elsevier.com/retrieve/pii/S0168952525002665) | Trends in Genetics |  |
| 2025 | [In silico prediction of variant effects: promises and limitations for precision plant breeding](https://link.springer.com/10.1007/s00122-025-04973-1) | Theoretical and Applied Genetics | It is argued that modern sequence models extend traditional methods by generalizing across genomic contexts, fitting a unified model across loci rather than a separate model for each locus, addressing inherent limitations of traditional quantitative and evo... |
| 2025 | [Large Language Models in Bioinformatics: A Survey](http://arxiv.org/abs/2503.04490) | arXiv | arXiv:2503.04490 \[cs\] TLDR: A systematic review of recent advancements, focusing on genomic sequence modeling, RNA structure prediction, protein function inference, and single-cell transcriptomics, underscores the transformative potential of LLMs in driving... |
| 2025 | [Large language model applications in nucleic acid research](https://www.maxapress.com/article/doi/10.48130/gcomm-0025-0003) | Genomics Communications | Recent advances have demonstrated the capabilities of large language models (LLMs) in harnessing nucleotide information to address biological questions. |
| 2025 | [Leveraging Natural Language Processing to Unravel the Mystery of Life: A Review of NLPApproaches in Genomics, Transcriptomics, and Proteomics.](https://doi.org/10.48550/arXiv.2506.02212) | arXiv | This review explores the application of NLP methods to biological sequence data, focusing on genomics, transcriptomics, and proteomics and highlights the potential of these methods for extracting meaningful insights from large-scale genomic data. |
| 2025 | [Modelling and design of transcriptional enhancers](https://www.nature.com/articles/s44222-025-00280-y) | Nature Reviews Bioengineering |  |
| 2025 | [Perspective on recent developments and challenges in regulatory and systems genomics](https://doi.org/10.1093/bioadv/vbaf106) | Bioinformatics Advances | How cis-regulatory elements are mapped with various genomics assays and how studies of the 3D chromatin organization could help identifying long-range regulatory effects and current methods for mapping gene regulatory networks to describe biological process... |
| 2025 | [Predicting gene expression from DNA sequence using deep learning models](https://www.nature.com/articles/s41576-025-00841-2) | Nature Reviews Genetics | The principles of these approaches, the types of training data sets that are available and the strengths and limitations of different approaches are discussed. |
| 2025 | [Protein Large Language Models: A Comprehensive Survey](http://arxiv.org/abs/2502.17504) | arXiv | arXiv:2502.17504 \[q-bio\] TLDR: This work provides the first comprehensive overview of Protein LLMs, covering their architectures, training datasets, evaluation metrics, and diverse applications, and proposes a structured taxonomy of state-of-the-art Protein... |
| 2025 | [Towards multimodal foundation models in molecular cell biology](https://www.nature.com/articles/s41586-025-08710-y) | Nature | Developing multimodal foundation models, pretrained on diverse omics datasets, are expected to exhibit unprecedented potential for characterizing the molecular states of cells across a broad continuum, thereby facilitating the creation of holistic maps of c... |
| 2025 | [Transformers and genome language models](https://www.nature.com/articles/s42256-025-01007-9) | Nature Machine Intelligence |  |
| 2025 | [Tutorial: guidelines for the use of machine learning methods to mine genomes and proteomes for antibiotic discovery](https://www.nature.com/articles/s41596-025-01144-w) | Nature Protocols | Computational approaches, including machine learning and artificial intelligence tools, which have been used to date to identify antimicrobial compounds, with a special emphasis on peptides are discussed, and potential avenues for future exploration are pro... |
| 2024 | [A review of deep learning models for the prediction of chromatin interactions with DNA and epigenomic profiles](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae651/7930069) | Briefings in Bioinformatics | This review systematically summarizes recent advances in chromatin interaction matrix prediction models, focusing on how one-dimensional information transforms into the 3D structure chromatin interactions, and how the integration of different deep learning... |
| 2024 | [Deep Learning Sequence Models for Transcriptional Regulation](https://www.annualreviews.org/content/journals/10.1146/annurev-genom-021623-024727) | Annual Review of Genomics and Human Genetics | The development and application of interpretability approaches have led to the identification of key sequence patterns contributing to the predicted tasks, providing insights into the underlying biological mechanisms learned and revealing opportunities for... |
| 2024 | [Deep learning approaches for non-coding genetic variant effect prediction: current progress and future prospects](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae446/7756794) | Briefings in Bioinformatics | This review delineates the popular sequencing technologies for epigenetic profiling and deep learning approaches for discerning the effects of non-coding variants and summarizes the limitations of current approaches in variant effect prediction research and... |
| 2024 | [Fundamentals for predicting transcriptional regulations from DNA sequence patterns](https://www.nature.com/articles/s10038-024-01256-3) | Journal of Human Genetics | This review introduces machine learning methods to learn sequence-dependent transcriptional regulation mechanisms from DNA sequences for predicting such allelic effects (not associations) and provides a concise history of machine-learning-based approaches,... |
| 2024 | [Large language models and their applications in bioinformatics](https://linkinghub.elsevier.com/retrieve/pii/S2001037024003209) | Computational and Structural Biotechnology Journal | The current trends in LLMs research are discussed and their potential to revolutionize the field of bioinformatics and accelerate novel discoveries in the life sciences is discussed. |
| 2024 | [Leveraging genomic deep learning models for non-coding variant effect prediction](http://arxiv.org/abs/2411.11158) | arXiv | arXiv:2411.11158 \[q-bio\] |
| 2024 | [Machine learning for functional protein design](https://www.nature.com/articles/s41587-024-02127-0) | Nature Biotechnology |  |
| 2024 | [Progress and opportunities of foundation models in bioinformatics](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae548/7842778) | Briefings in Bioinformatics | A general investigation and summary of FMs in bioinformatics, tracing their evolutionary trajectory, current research landscape, and methodological frameworks, and outline prospective pathways and methodologies for the future development of FMs in biologica... |
| 2024 | [Scientific Large Language Models: A Survey on Biological & Chemical Domains](http://arxiv.org/abs/2401.14656) | arXiv | arXiv:2401.14656 \[cs\] |
| 2024 | [Unlocking gene regulation with sequence-to-function models](https://www.nature.com/articles/s41592-024-02331-5) | Nature Methods |  |
| 2023 | [A survey on algorithms to characterize transcription factor binding sites](https://academic.oup.com/bib/article/doi/10.1093/bib/bbad156/7142798) | Briefings in Bioinformatics | Transcription factors (TFs) are key regulatory proteins that control the transcriptional rate of cells by binding short DNA sequences called transcription factor binding sites (TFBS) or motifs. |
| 2023 | [Applications of deep learning in understanding gene regulation](https://linkinghub.elsevier.com/retrieve/pii/S2667237522002892) | Cell Reports Methods | The design principles and datasets used by each method for gene regulation are discussed, creating a reference for researchers who wish to replicate or improve existing methods and prospectively introduce the emerging deep-learning paradigms that will poten... |
| 2023 | [Deep learning in regulatory genomics: from identification to design](https://linkinghub.elsevier.com/retrieve/pii/S095816692200221X) | Current Opinion in Biotechnology | Two emerging trends in regulatory genomics are reviewed: the modeling of very long input sequence (up to 200 kb), which requires self-matched modularization of model architecture; and the balance of model predictability and model interpretability because th... |
| 2023 | [Obtaining genetics insights from deep learning via explainable artificial intelligence](https://www.nature.com/articles/s41576-022-00532-2) | Nature Reviews Genetics | Advances in deep learning approaches in genomics are described, whereby researchers are moving beyond the typical 'black box' nature of models to obtain biological insights through explainable artificial intelligence (xAI). |
| 2023 | [Off the deep end: What can deep learning do for the gene expression field?](https://linkinghub.elsevier.com/retrieve/pii/S0021925822012030) | Journal of Biological Chemistry |  |
| 2022 | [A review of deep learning applications in human genomics using next-generation sequencing data](https://humgenomics.biomedcentral.com/articles/10.1186/s40246-022-00396-x) | Human Genomics | This review addresses development and application of deep learning methods/models in different subarea of human genomics, and assesses over- and under-charted area of genomics by deep learning techniques. |
| 2022 | [Computational Approaches for Understanding Sequence Variation Effects on the 3D Genome Architecture](https://www.annualreviews.org/doi/10.1146/annurev-biodatasci-102521-012018) | Annual Review of Biomedical Data Science | This review focuses on computational approaches for both the detection and modeling of sequence variation effects on the 3D genome, and discusses the opportunities presented by these approaches. |
| 2022 | [Navigating the pitfalls of applying machine learning in genomics](https://www.nature.com/articles/s41576-021-00434-9) | Nature Reviews Genetics | How responsible application of machine learning requires an understanding of several common pitfalls that users should be aware of (and mitigate) to avoid unreliable results is described. |
| 2022 | [Toward learning the principles of plant gene regulation](https://linkinghub.elsevier.com/retrieve/pii/S1360138522002163) | Trends in Plant Science | Advanced machine learning algorithms produce highly accurate models of gene expression, uncovering novel regulatory features in nucleotide sequences involving multiple cis-regulatory regions across whole genes and structural properties. |
| 2021 | [Decoding disease: from genomes to networks to phenotypes](https://www.nature.com/articles/s41576-021-00389-x) | Nature Reviews Genetics | This Review highlights existing methods and key challenges and opportunities in identifying specific disease-causing genetic variants and linking them to molecular pathways and, ultimately, to disease phenotypes, and focuses on methods leveraging machine le... |
| 2020 | [Application of deep learning in genomics](https://doi.org/10.1007/s11427-020-1804-5) | Sci China Life Sci | The basic concepts in machine learning and artificial neural network are described, followed by elaboration on the workflow of using convolutional neural network in genomics and synthetic biology at the levels of DNA, RNA and protein are provided. |
| 2020 | [Deep learning for plant genomics and crop improvement](https://linkinghub.elsevier.com/retrieve/pii/S1369526619301256) | Current Opinion in Plant Biology | A central role of deep learning is proposed in future plant genomics research and crop genetic improvement and the possibility of unleashing the power ofdeep learning in synthetic biology to create novel genomic elements with desirable functions is discussed. |
| 2019 | [A primer on deep learning in genomics](https://www.nature.com/articles/s41588-018-0295-5) | Nature Genetics | A perspective and primer on deep learning applications for genome analysis and successful applications in the fields of regulatory genomics, variant calling and pathogenicity scores are provided. |
| 2019 | [Deep learning: new computational modelling techniques for genomics](https://www.nature.com/articles/s41576-019-0122-6) | Nature Reviews Genetics | Different deep learning techniques and how they can be applied to extract biologically relevant information from large, complex genomic data sets are described. |

</details>

## S2F-OneHot-Model (106)

<details>
<summary>Show S2F-OneHot-Model papers (106)</summary>

- **[A deep learning framework for building INDEL mutation rate maps](http://biorxiv.org/lookup/doi/10.1101/2025.11.18.689146)** - 2025, bioRxiv
  - This work presents MuRaL-indel, a deep learning framework that predicts germline INDEL mutation rates by leveraging long-range sequence context through a U-Net architecture and establishes a generalizable and scalable framework for building high-resolution...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (one-hot encoded) → INDEL mutation probabilities (length-stratified)

  To develop a deep learning framework named MuRaL-indel for predicting germline short insertion or deletion (INDEL) mutation rates to build high-resolution, length-stratified mutation rate maps, uncover mutational mechanisms, and enable downstream biomedical applications.

  </details>

- **[A scalable approach to investigating sequence-to-expression prediction from personal genomes](https://doi.org/10.1101/2025.02.21.639494)** - 2025, bioRxiv
  - SAGE-net is introduced, a scalable framework and software package for training and evaluating S2F models using personal genomes that improves predictions for held-out individuals and highlights the need for further exploration to unlock the full potential o...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop SAGE-net, a scalable sequence-to-expression (S2E) prediction framework leveraging personal genomes to train deep learning models that better predict inter-individual gene expression variation.

  </details>

- **[A sparse and wide neural network model for DNA sequences](https://linkinghub.elsevier.com/retrieve/pii/S0893608024009699)** - 2025, Neural Networks
  - SwanDNA is a new neural network model called SwanDNA that enables inferences over very long DNA sequences by using a sparse and wide network architecture and incorporating the neural network into a self-supervised learning framework.
  <details>
  <summary>Series description</summary>

  **Series:** DNA MLM

  To introduce SwanDNA, a sparse and wide neural network enabling inference over very long DNA sequences via self-supervised learning, addressing the limitations of existing models in capturing long-range interactions and scaling to large inputs.

  </details>

- **[AlphaGenome: advancing regulatory variant effect prediction with a unified DNA sequence model](https://doi.org/10.1101/2025.06.25.661532)** - 2025, bioRxiv
  - AlphaGenome is presented, which takes as input 1 megabase of DNA sequence and predicts thousands of functional genomic tracks up to single base pair resolution across diverse modalities - including gene expression, transcription initiation, chromatin access...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a deep learning model that integrates 1 megabase of DNA sequence to predict high-resolution, multimodal genomic tracks across species and accurately infer the regulatory effects of noncoding variants.

  </details>

- **[Analysis of RNA translation with a deep learning architecture provides new insight into translation control](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf277/8112693)** - 2025, Nucleic Acids Research
  - A deep neural network to directly predict and analyze translation initiation and termination sites from RNA sequences is developed, which revealed a new role of codon usage in regulating translation termination, which was experimentally validated.
  <details>
  <summary>Series description</summary>

  **Series:** RNA

  To develop TranslationAI, a deep learning model predicting translation initiation and termination sites from full-length mRNA sequences and uncovering novel regulatory features of translation control.

  </details>

- **[Base-resolution binding profile prediction of proteins on RNAs with deep learning](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf748/8223173)** - 2025, Nucleic Acids Research
  - Comprehensive evaluation on the newly developed benchmark datasets demonstrates that iDeepB outperforms existing methods in predicting protein binding profile on RNAs.
  <details>
  <summary>Series description</summary>

  **Series:** RNA

  Develop a deep learning model (iDeepB) to predict protein binding profiles on RNAs at base resolution by integrating cell-line-specific gene expression profiles and eCLIP-seq data.

  </details>

- **[CacPred: a cascaded convolutional neural network for TF-DNA binding prediction](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-025-11399-y)** - 2025, BMC Genomics
  - It is demonstrated that CacPred is an effective and feasible model for predicting TF-DNA binding and that pooling processing of the existing models leads to losing some sequence information.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To introduce CacPred, a cascaded convolutional neural network relying solely on convolution operations for accurate TF-DNA binding prediction from ChIP-seq and ChIP-nexus data, while identifying significant binding motifs.

  </details>

- **[Deep genomic models of allele-specific measurements](https://doi.org/10.1101/2025.04.09.648060)** - 2025, bioRxiv
  - DeepAllele is proposed, a novel deep learning sequence-to-function model using paired allele-specific input, designed to learn sequence features that predict subtle changes in gene regulation between alleles, enhancing causal discovery in genomics.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop DeepAllele, a deep learning sequence-to-function model using paired allele sequences as input to directly model allele-specific regulatory effects and enhance causal inference of gene regulation mechanisms.

  </details>

- **[Deep learning predicts DNA methylation regulatory variants in specific brain cell types and enhances fine mapping for brain disorders](https://doi.org/10.1126/sciadv.adn1870)** - 2025, SCIENCE ADVANCES
  - It is demonstrated that incorporating predicted variant effects and DNAm levels of CpG sites enhances the fine mapping for three brain disorders-schizophrenia, depression, and Alzheimer's disease-and facilitates mapping causal genes to particular cell types.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop INTERACT, a deep learning model integrating CNN and transformer attention to predict DNA methylation regulatory variants in specific brain cell types and enhance fine mapping of risk loci for schizophrenia, depression, and Alzheimer's disease.

  </details>

- **[DeepMVP: deep learning models trained on high-quality data accurately predict PTM sites and variant-induced alterations](https://www.nature.com/articles/s41592-025-02797-x)** - 2025, Nature Methods
  - PTMAtlas and DeepMVP provide a robust platform for PTM research and a scalable framework for assessing the functional consequences of coding variants through the lens of PTMs, and DeepMVP substantially outperforms existing tools across all six PTM types.
  <details>
  <summary>Series description</summary>

  **Series:** Protein

  To develop a deep learning framework (DeepMVP) trained on a large-scale, high-quality curated PTM dataset (PTMAtlas) for accurately predicting sites of six major post-translational modifications (PTMs) and variant-induced functional alterations, thereby linking genetic variants to disease phenotypes through the lens of PTMs.

  </details>

- **[Detecting interspecific positive selection using convolutional neural networks](https://doi.org/10.1093/molbev/msaf154)** - 2025, Molecular Biology and Evolution
  - This work trained and tested convolutional neural network (CNN) models on simulated data and achieved higher accuracy in detecting selection across a specific range of phylogenetic scenarios and evolutionary modes, making it a scalable alternative to tradit...
  <details>
  <summary>Series description</summary>

  **Series:** DNA MSA

  To introduce OmegaAI, a convolutional neural network (CNN) model that detects positive selection signals in protein-coding genes directly from interspecies multiple sequence alignments, achieving higher inference accuracy, especially in datasets with high alignment errors and sequence divergence.

  </details>

- **[Dissecting sequence determinants of DNA methylation and in silico perturbation](http://biorxiv.org/lookup/doi/10.1101/2025.11.20.689274)** - 2025, bioRxiv
  - DNA methylation shapes cellular identity and genome function, yet the sequence logic that governs its establishment remains largely unresolved.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a cross-species pretrained deep learning framework (MethylAI) that predicts single-CpG methylation states directly from genomic sequence and dissects its underlying sequence determinants.

  </details>

- **[ETNet: an interpretable transformer framework for enhancer-enhancer interaction prediction with cross-context transferability](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf634/8361797)** - 2025, Briefings in Bioinformatics
  - ETNet (Enhancer-enhancer Interaction Explainable Transformer Network), a deep learning architecture integrating convolutional neural networks with Transformer modules to predict EEIs from DNA sequences, advances computational approaches for studying enhance...
  <details>
  <summary>Series description</summary>

  **Series:** NA sequence (2000 bp, one-hot encoded) → enhancer-enhancer interaction probability (binary classification)

  To predict enhancer-enhancer interactions (EEIs) from DNA sequences using the end-to-end deep learning framework ETNet, thereby improving understanding of gene regulatory networks and providing interpretable functional insights.

  </details>

- **[Enhancing mRNA translation efficiency with discriminative and generative artificial intelligence by optimizing 5′ UTR sequences](https://linkinghub.elsevier.com/retrieve/pii/S258900422501805X)** - 2025, iScience
  <details>
  <summary>Series description</summary>

  **Series:** UTR

  To develop a computational framework called UTailoR that significantly improves mRNA translation efficiency by optimizing 5' UTR sequences based on a two-step artificial intelligence strategy (discriminative model for prediction + generative model for optimization).

  </details>

- **[Genome-wide rules of transcription factor cooperativity revealed through in silico binding site ablation](https://doi.org/10.1101/2025.06.19.660093)** - 2025, bioRxiv
  - DeepCompARE is introduced, a lightweight model paired with an in silico ablation (ISA) framework for genome-wide analysis of regulatory sequences that enables precise interpretation of the motif syntax governing chromatin accessibility, enhancer activity, a...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop DeepCompARE, a deep convolutional model with in silico ablation (ISA) for systematic analysis of transcription factor cooperativity rules in regulatory DNA, quantifying the roles of redundancy and synergy in gene regulation.

  </details>

- **[Genos: A Human-Centric Genomic Foundation Model](https://academic.oup.com/gigascience/advance-article/doi/10.1093/gigascience/giaf132/8296738)** - 2025, GigaScience
  - Genos (Genos-1.2B/Genos-10B), a human-centric genomic foundation model engineered for million-base-pair sequence modeling, is introduced and provides a reliable technical blueprint and performance benchmark for the next generation of high-efficiency genomic...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (one-hot encoded) → probability distribution for next token (vocabulary size 128 or 256)

  To develop a human-centric genomic foundation model for modeling sequences up to a million base pairs, capturing population diversity and enabling efficient clinical inference.

  </details>

- **[Interpreting the CTCF-mediated sequence grammar of genome folding with AkitaV2](https://dx.plos.org/10.1371/journal.pcbi.1012824)** - 2025, PLOS Computational Biology
  - A framework for using neural network models to probe the sequences instructing genome folding is presented and a number of predictions to guide future experimental inquiries are provided to guide future experimental inquiries.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To leverage the updated AkitaV2 deep neural network to predict and interpret the impact of CTCF binding sites and their flanking sequences on 3D genome folding, revealing the sequence grammar underlying regulatory function.

  </details>

- **[Lyra: An Efficient and Expressive Subquadratic Architecture for Modeling Biological Sequences](https://doi.org/10.48550/arXiv.2503.16351)** - 2025, arXiv
  - Lyra is introduced, a subquadratic architecture for sequence modeling, grounded in the biological framework of epistasis for understanding sequence-to-function relationships, and it is demonstrated that state space models efficiently capture global epistati...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose Lyra, a unified deep learning model that predicts transcriptional and epigenetic features-including RNA-seq, CAGE, ATAC, and ChIP-seq-across diverse human cell types from DNA sequence, enhancing variant interpretation and understanding of gene regulation.

  </details>

- **[Massive experimental quantification allows interpretable deep learning of protein aggregation](https://doi.org/10.1126/sciadv.adt5111)** - 2025, SCIENCE ADVANCES
  - This work experimentally quantifies the aggregation of >100,000 protein sequences to provide an interpretable and robust neural network model to predict aggregation and adapt genomic neural network interpretability analyses to reveal CANYA's decision-making...
  <details>
  <summary>Series description</summary>

  **Series:** Protein

  To experimentally quantify aggregation across &gt;100,000 random peptides and train the interpretable deep learning model CANYA for predicting and understanding protein aggregation propensity.

  </details>

- **[Melody: Decoding the Sequence Determinants of Locus-Specific DNA Methylation Across Human Tissues](http://biorxiv.org/lookup/doi/10.1101/2025.11.23.689975)** - 2025
  - Melody, a deep learning framework designed to elucidate the sequence determinants underlying human DNA methylation landscapes across multiple tissues, is introduced and demonstrates strong generalization in meQTLs variant effect prediction, and Melody revea...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (one-hot encoding) → locus-specific DNA methylation probability (base-pair resolution)

  To develop a deep learning framework, Melody, for predicting locus-specific DNA methylation across human tissues from DNA sequence and elucidating its sequence determinants.

  </details>

- **[Precise, predictable genome integrations by deep-learning-assisted design of microhomology-based templates](https://www.nature.com/articles/s41587-025-02771-0)** - 2025, Nature Biotechnology
  - This work devised a strategy of base-pair tandem repeat repair arms matching microhomologies at double-strand breaks that promote frame-retentive cassette integration and reduce deletions both at the target site and within the transgene.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Extended transfer learning based on pre-trained inDelphi model to develop the Pythia prediction framework; designed μH repair arms optimized by sequence context features to achieve microhomology mediated end joining (MMEJ)-based genome integration/editing.

  </details>

- **[Predicting RNA-seq coverage from DNA sequence as a unifying model of gene regulation](https://www.nature.com/articles/s41588-024-02053-6)** - 2025, Nature Genetics
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop Borzoi, a deep learning model predicting RNA-seq coverage from DNA sequence to jointly model transcription, splicing, and polyadenylation, improving variant functional interpretation.

  </details>

- **[Predicting cell type-specific coverage profiles from DNA sequence](https://doi.org/10.1101/2025.06.10.658961)** - 2025, bioRxiv
  - The recently developed Borzoi model is extended by training on single-cell 3'-seq expression profiles from the Tabula Sapiens, Tabula Muris, and the Adult Brain Atlas, aggregated by cell type to enable accurate variant interpretation across diverse cells, s...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop Borzoi Prime, a deep learning model predicting single-cell 3'-seq coverage and cell type-specific expression profiles from DNA sequence, improving multi-layer regulatory modeling and variant effect interpretation.

  </details>

- **[Predicting dynamic expression patterns in budding yeast with a fungal DNA language model](http://biorxiv.org/lookup/doi/10.1101/2025.09.19.677475)** - 2025, bioRxiv
  - Predicting gene expression from DNA sequence remains challenging due to complex regulatory codes.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (one-hot encoded) → masked nucleotide prediction Fine-tune: DNA (one-hot encoded) → gene expression coverage (RNA-seq, ChIP-exo/MNase signals at 16 bp resolution)

  To develop a DNA language model named Shorkie, pretrained self-supervisedly on an evolutionary-scale dataset of 165 fungal genomes and fine-tuned on high-resolution RNA-seq data (including transcriptional regulator induction time courses) from budding yeast (Saccharomyces cerevisiae), substantially improving gene expression prediction accuracy and enabling the dissection of regulatory dynamics and prediction of noncoding variant effects.

  </details>

- **[Predicting expression-altering promoter mutations with deep learning](https://www.science.org/doi/10.1126/science.ads7373)** - 2025, Science
  - PromoterAI, a deep neural network that accurately identifies non-coding promoter variants which dysregulate gene expression is described, showing that promoter variants with predicted expression-altering consequences produce outlier expression at both RNA a...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop PromoterAI, a deep neural network predicting quantitative effects of promoter variants on gene expression directly from long-range DNA sequence, and to validate its functional and clinical relevance across large-scale human genomic datasets.

  </details>

- **[Predicting functional constraints across evolutionary timescales with phylogeny-informed genomic language models](http://biorxiv.org/lookup/doi/10.1101/2025.09.21.677619)** - 2025, bioRxiv
  - Genomic language models (gLMs) have emerged as a powerful approach for learning genome-wide functional constraints directly from DNA sequences.
  <details>
  <summary>Series description</summary>

  **Series:** Multispecies DNA sequence alignment (One-hot) + Phylogenetic tree → Nucleotide position probability distribution

  To develop a phylogeny-aware genomic language model (GPN-Star) leveraging multispecies phylogenies and whole-genome alignments for predicting functional impacts and constraints of genomic variants across evolutionary timescales.

  </details>

- **[Predicting gene expression using millions of yeast promoters reveals cis -regulatory logic](https://doi.org/10.1093/bioadv/vbaf130)** - 2025, Bioinformatics Advances
  - This work investigates the complex association between gene promoters and expression in S.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop Camformer, a convolutional neural network trained on millions of random yeast promoters to predict gene expression and, using explainable AI, reveal cis-regulatory logic and transcription factor cooperativity.

  </details>

- **[Predicting sequence-specific amplification efficiency in multi-template PCR with deep learning](https://www.nature.com/articles/s41467-025-64221-4)** - 2025, Nature Communications
  - A one-dimensional convolutional neural networks model predicting amplification efficiency directly from the DNA sequence is developed and adapter-mediated self-priming is discovered as a key cause of uneven amplification during PCR.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a deep learning approach using one-dimensional convolutional neural networks (1D-CNN) with positional encoding and the CluMo interpretation framework to predict amplification efficiency of DNA sequences in multi-template PCR, identifying key sequence features (e.g. adapter-mediated self-priming) causing amplification bias for improved homogeneous amplification and efficiency in applications like DNA data storage.

  </details>

- **[QTFPred: robust high-performance quantum machine learning modeling that predicts main and cooperative transcription factor bindings with base resolution](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf604/8343189)** - 2025, Briefings in Bioinformatics
  - QTFPred (Quantum-based TF Predictor), a quantum-classical hybrid framework that integrates quantum convolutional layers within neural networks to predict TF binding at base resolution, achieves robust performance even in data-sparse scenarios, highlighting...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (One-hot encoding) → Base-resolution transcription factor binding probability or binding signal intensity

  To develop a quantum-classical hybrid machine learning framework, QTFPred, for predicting transcription factor binding sites and binding signals at base resolution, achieving robust high performance especially with limited training data.

  </details>

- **[REVISITING CONVOLUTION ARCHITECTURE IN THE REALM OF DNA FOUNDATION MODELS](https://doi.org/10.48550/arXiv.2502.18538)** - 2025, ICLR
  - It is demonstrated that ConvNova significantly outperforms recent methods on more than half of the tasks across several foundation model benchmarks, indicating that CNNs are still a strong competitor compared to Transformers and SSMs.
  <details>
  <summary>Series description</summary>

  **Series:** DNA; one-hot; MLM

  To reassess the effectiveness of convolutional neural networks (CNNs) in DNA foundation models, propose ConvNova with three key designs (dilated convolution, gated convolution, dual-branch structure), and demonstrate superior accuracy, efficiency, and parameter efficiency compared to Transformer and SSM-based approaches across multiple benchmarks.

  </details>

- **[REnformer, a single-cell ATAC-seq predicting model to investigate open chromatin sites](https://doi.org/10.1101/2025.06.04.657786)** - 2025, bioRxiv
  - It is concluded that REnformer is and can be a state-of-the-art tool to predict cell type specific regulatory elements, and interrogate the effect of genome variation in health and disease.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop REnformer, leveraging transfer learning on the Enformer architecture with high-quality scATAC-seq data, to build a model accurately predicting genome-wide human chromatin accessibility and enabling variant effect analysis and regulatory element interpretation.

  </details>

- **[Refining the cis-regulatory grammar learned by sequence-to-activity models by increasing model resolution](http://biorxiv.org/lookup/doi/10.1101/2025.01.24.634804)** - 2025, bioRxiv
  - Chromatin accessibility can be measured genome-wide with ATAC-seq, enabling the discovery of regulatory regions that control gene expression and determine cell type.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop bpAI-TAC, a multi-task convolutional model predicting ATAC-seq Tn5 insertion profiles at base-pair resolution to improve understanding of chromatin accessibility and cis-regulatory grammar.

  </details>

- **[Sequence based prediction of cell type specific microRNA binding and mRNA degradation for therapeutic discovery](https://doi.org/10.1101/2025.05.15.654105)** - 2025, bioRxiv
  - A deep learning model that predicts cell-type-specific microRNA binding and mRNA degradation directly from RNA sequence, which reveals biology that other state-of-the-art methods did not and provides insights into novel biology and the design of RNA therape...
  <details>
  <summary>Series description</summary>

  **Series:** RNA

  To develop REPRESS, a large-scale deep learning model predicting cell-type-specific miRNA binding and mRNA degradation from RNA sequence, enabling discovery of regulatory mechanisms and design of RNA therapeutics.

  </details>

- **[SpliceSelectNet: A Hierarchical Transformer-Based Deep Learning Model for Splice Site Prediction](http://biorxiv.org/lookup/doi/10.1101/2025.02.17.638749)** - 2025, bioRxiv
  - This work presents SpliceSelectNet (SSNet), a novel deep-learning model that predicts splice sites directly from DNA sequences using a hierarchical Transformer-based architecture with both local and global attention mechanisms and offers interpretability at...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop SpliceSelectNet (SSNet), a hierarchical Transformer-based deep learning model that predicts splice sites and aberrant splicing events directly from DNA sequences, with improved accuracy and interpretability.

  </details>

- **[UniMethylNet: A Universal DNA Methylation Site Prediction Network Integrating a Neural Network and an Attention Mechanism](https://pubs.acs.org/doi/10.1021/acs.jcim.5c02000)** - 2025, Journal of Chemical Information and Modeling
  - UniMethylNet provides a powerful tool for DNA methylation site prediction, offering a quantitative approach for in-depth exploration of the conservation and specificity of epigenetic regulation by capturing the underlying conserved sequence motifs across di...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a unified framework (UniMethylNet) that integrates a Position Linear Layer, Bidirectional Long Short-Term Memory, and Channel-Spatial Dual Attention mechanism to enhance accuracy and generalization for predicting DNA methylation sites across species and types (4mC, 5hmC, 6 mA).

  </details>

- **[scooby: modeling multimodal genomic profiles from DNA sequence at single-cell resolution](https://www.nature.com/articles/s41592-025-02854-5)** - 2025, Nature Methods
  - Scooby is introduced, a framework to model genomic profiles of single-cell RNA-sequencing coverage and single-cell assay for transposase-accessible chromatin using sequencing insertions from sequence at single-cell resolution to aid unraveling the complexit...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To predict chromatin accessibility (scATAC-seq) and gene expression profiles (scRNA-seq) at single-cell resolution directly from DNA sequence, enabling the dissection of cell-type-specific gene regulatory mechanisms.

  </details>

- **[ChromBPNet: bias factorized, base-resolution deep learning models of chromatin accessibility reveal cis-regulatory sequence syntax, transcription factor footprints and regulatory variants](http://biorxiv.org/lookup/doi/10.1101/2024.12.25.630221)** - 2024, bioRxiv
  - ChromBPNet is introduced, a deep learning DNA sequence model of base-resolution accessibility profiles that detects, learns and deconvolves assay-specific enzyme biases from regulatory sequence determinants of accessibility, enabling robust discovery of com...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop ChromBPNet, a deep learning model that predicts base-resolution chromatin accessibility while deconvolving enzyme sequence biases, enabling discovery of cis-regulatory sequence syntax, transcription factor footprints, and functional impacts of genetic variants.

  </details>

- **[Cross-Species Prediction of Transcription Factor Binding by Adversarial Training of a Novel Nucleotide-Level Deep Neural Network](https://onlinelibrary.wiley.com/doi/10.1002/advs.202405685)** - 2024, Advanced Science
  - This study proposes a novel Nucleotide-Level Deep Neural Network (NLDNN) to predict TF binding within or across species, and designs a dual-path framework for adversarial training of NLDNN to improve the cross-species prediction performance by pulling the d...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose NLDNN, a nucleotide-level regression model for TF binding prediction, and use adversarial training to improve cross-species prediction accuracy, while providing a unified framework for comparing classification and regression models.

  </details>

- **[Deciphering the 3D genome organization across species from Hi-C data](http://biorxiv.org/lookup/doi/10.1101/2024.11.14.623548)** - 2024, bioRxiv
  - Chimaera enables the exploration and validation of complex hypotheses regarding the principles of 3D-genome folding, including sequence-specific folding patterns at protein binding sites and genes, and performs a targeted search for DNA sequence elements as...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To predict 3D genome architecture (Hi-C maps) from DNA sequences and investigate evolutionary rules and sequence determinants of chromatin folding across species.

  </details>

- **[Deep learning models to predict the editing efficiencies and outcomes of diverse base editors](https://www.nature.com/articles/s41587-023-01792-x)** - 2024, Nature Biotechnology
  - A computational model is developed that predicts editing efficiencies and outcomes of 63 BEs that were generated by incorporating nine Cas9 variants as nickase domains into the seven BE variants, and the best base editor for specific applications is predict...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop deep learning models that systematically predict the target-site-specific editing efficiencies and outcomes of diverse Cas9 variants and base editors, enabling rational sgRNA and BE selection.

  </details>

- **[Deep-learning prediction of gene expression from personal genomes](http://biorxiv.org/lookup/doi/10.1101/2024.07.27.605449)** - 2024, bioRxiv
  - Performer is developed, a model with accuracy approaching the cis-heritability of most genes that prioritizes genetic variants across the allele frequency spectrum that disrupt motifs, fall in annotated regulatory elements, and have functional evidence for...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To improve Enformer's ability to predict inter-individual gene expression variation by fine-tuning on paired personal genome and transcriptome data.

  </details>

- **[Dissecting the cis-regulatory syntax of transcription initiation with deep learning](http://biorxiv.org/lookup/doi/10.1101/2024.05.28.596138)** - 2024, bioRxiv
  - A neural network called ProCapNet is trained and interpreted that accurately models base-resolution initiation profiles from PRO-cap experiments using local DNA sequence, revealing a shared cis-regulatory logic across promoters and enhancers and a highly ep...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop ProCapNet, a deep learning model that accurately predicts the location and activity of transcription initiation from local DNA sequence and uncovers the cis-regulatory code and motif interactions at promoters and enhancers.

  </details>

- **[Fine-tuning sequence-to-expression models on personal genome and transcriptome data](http://biorxiv.org/lookup/doi/10.1101/2024.09.23.614632)** - 2024, bioRxiv
  - The results show that fine-tuning improves cross-individual prediction performance over the baseline Enformer model for held-out individuals on genes seen during fine-tuning, with comparable performance to variant-based linear models commonly used in transc...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To explore whether fine-tuning the deep learning model Enformer on personal genome and transcriptome data improves the prediction of inter-individual gene expression variation.

  </details>

- **[Flashzoi: An enhanced Borzoi model for accelerated genomic analysis](http://biorxiv.org/lookup/doi/10.1101/2024.12.18.629121)** - 2024, bioRxiv
  - An enhanced Borzoi model that leverages rotary positional encodings and FlashAttention-2 achieves over 3-fold faster training and inference and up to 2.4-fold reduced memory usage, while maintaining or improving accuracy in modeling various genomic assays i...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To improve the computational efficiency of the Borzoi model for large-scale genomic analyses, such as variant effect prediction and enhancer-promoter linking, by enhancing the Transformer positional encoding and attention mechanism while maintaining or improving predictive accuracy.

  </details>

- **[Interpretable prediction of mRNA abundance from promoter sequence using contextual regression models](https://academic.oup.com/nargab/article/doi/10.1093/nargab/lqae055/7683404)** - 2024, NAR Genomics and Bioinformatics
  - While machine learning models have been successfully applied to predicting gene expression from promoter sequences, it remains a great challenge to derive intuitive interpretation of the model and reveal DNA motif grammar such as motif cooperation and dista...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To predict mRNA expression levels from promoter DNA sequences using contextual regression deep learning models, and interpretively reveal key activating or repressing sequences, motifs, and their combinatorial grammar governing gene expression regulation.

  </details>

- **[Prediction and functional interpretation of inter-chromosomal genome architecture from DNA sequence with TwinC](http://biorxiv.org/lookup/doi/10.1101/2024.09.16.613355)** - 2024, bioRxiv
  - TwinC models and interprets trans genome architecture and sheds light on this poorly understood aspect of gene regulation, shedding light on this poorly understood aspect of gene regulation.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop TwinC, a model that predicts human inter-chromosomal (trans) 3D contacts from DNA sequence and interprets which sequence features (e.g., TF binding, chromatin accessibility, G4 structures) drive such interactions.

  </details>

- **[Predictive Modeling of Gene Expression and Localization of DNA Binding Site Using Deep Convolutional Neural Networks](http://biorxiv.org/lookup/doi/10.1101/2024.12.17.629042)** - 2024, bioRxiv
  - Deep learning Adaptable Regulatory Sequence Identifier (DARSI) generates experimentally actionable predictions that can feed iterations of the theory-experiment cycle aimed at reaching a predictive understanding of transcriptional control by automating and...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop DARSI, a deep convolutional neural network that predicts gene expression levels directly from raw regulatory DNA sequences and identifies potential transcription factor binding sites.

  </details>

- **[Self-supervised Learning for DNA sequences with circular dilated convolutional networks](https://linkinghub.elsevier.com/retrieve/pii/S0893608023006962)** - 2024, Neural Networks
  - DNA molecules commonly exhibit wide interactions between the nucleobases. Modeling the interactions is important for obtaining accurate sequence-based inference. Although many deep learning methods have recently been developed for modeling 
  <details>
  <summary>Series description</summary>

  **Series:** DNA; one-hot; MLM

  To propose a novel CDIL deep learning architecture that uses self-supervised pretraining and circular dilated convolutions to capture long-range nucleotide dependencies on long DNA sequences, reducing reliance on labeled data and improving performance in variant effect and open chromatin region prediction.

  </details>

- **[Sequence basis of transcription initiation in the human genome](https://www.science.org/doi/10.1126/science.adj0116)** - 2024, Science
  - A unified model for transcription initiation in most human promoters is presented and shed new light on fundamental questions related to promoter sequence and function.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop the Puffin model that predicts base-pair resolution human transcription initiation signals from DNA sequence and explains directional and bidirectional motif contributions in promoters and enhancers.

  </details>

- **[SpliceTransformer predicts tissue-specific splicing linked to human diseases](https://www.nature.com/articles/s41467-024-53088-6)** - 2024, Nature Communications
  - Analysis of whole exon sequencing data from blood samples of patients with diabetic nephropathy predicts kidney-specific RNA splicing alterations with 83% accuracy, demonstrating the potential to infer disease-causing tissue-specific splicing events.
  <details>
  <summary>Series description</summary>

  **Series:** RNA

  To develop a Transformer-based deep learning framework that accurately predicts splicing events across 15 human tissues from genomic sequences and applies this to interpret disease-associated variants.

  </details>

- **[Training deep learning models on personalized genomic sequences improves variant effect prediction](https://doi.org/10.1101/2024.10.15.618510)** - 2024, Research Square
  - It is shown that training models on functional genomic data with matched personal genomes improves their performance at variant effect prediction, and variant effect representations are retained even when fine tuning models to unseen cellular contexts and e...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To demonstrate that training deep learning models directly on matched personal whole-genome sequences significantly improves variant effect prediction accuracy and supports transfer learning across cell types and experimental readouts.

  </details>

- **[Transfer learning for cross-context prediction of protein expression from 5'UTR sequence](https://academic.oup.com/nar/article/52/13/e58/7691520)** - 2024, Nucleic Acids Research
  - This study demonstrates how a simple transfer learning procedure can effectively tune a pre-trained deep learning model to predict protein translation rate from 5' untranslated region sequence (5'UTR) for diverse contexts in Escherichia coli using a small n...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a transfer learning approach that enables deep learning models trained on large-scale 5'UTR translation efficiency data to be fine-tuned for new genetic and experimental contexts, achieving accurate generalization of protein expression prediction.

  </details>

- **[Transformers significantly improve splice site prediction](https://www.nature.com/articles/s42003-024-07298-9)** - 2024, Communications Biology
  - This work presents a method using transformers, a type of machine learning model, to detect splicing from raw 45,000-nucleotide sequences, and surpasses the leading tool, SpliceAI, in detecting splice sites in GENCODE and ENSEMBL annotations.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop Spliceformer, a Transformer-based model that uses 45kb raw DNA sequence to predict splice sites with significantly improved accuracy, outperforming existing methods (e.g., SpliceAI), particularly for unannotated and pathogenic splice variants.

  </details>

- **[An RNA foundation model enables discovery of disease mechanisms and candidate therapeutics](https://doi.org/10.1101/2023.09.20.558508)** - 2023, bioRxiv
  - A foundation model for RNA biology, "BigRNA" is described, which was trained on thousands of genome-matched datasets to predict tissue-specific RNA expression, splicing, microRNA sites, and RNA binding protein specificity from DNA sequence.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a large-scale RNA foundation model (BigRNA) capable of predicting tissue-specific RNA expression, splicing, microRNA and RNA-binding protein interactions from DNA sequence, enabling interpretation of pathogenic variants and supporting personalized RNA therapeutic design.

  </details>

- **[An intrinsically interpretable neural network architecture for sequence-to-function learning](https://academic.oup.com/bioinformatics/article/39/Supplement_1/i413/7210441)** - 2023, Bioinformatics
  - Sequence-based deep learning approaches have been shown to predict a multitude of functional genomic readouts, including regions of open chromatin and RNA expression of genes.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To introduce a novel, fully interpretable deep learning model (tiSFM) that can predict functional genomic readouts such as open chromatin from DNA sequence, while enabling direct biological interpretation of model parameters.

  </details>

- **[Assessing base-resolution DNA mechanics on the genome scale](https://academic.oup.com/nar/article/51/18/9552/7269185)** - 2023, Nucleic Acids Research
  - BendNet is introduced - a neural network to accurately predict the intrinsic DNA bending at base-resolution by only given DNA sequences and provides a tool to assess DNA bendability for large-scale DNA sequences and expands the understanding on DNA mechanic...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop BendNet, a deep learning model trained on Loop-seq measurements of short DNA fragments, enabling base-resolution prediction of DNA bendability across genomes and uncovering its roles in epigenetic regulation, TF binding, replication origins, and disease-associated regions.

  </details>

- **[Atlas of primary cell-type-specific sequence models of gene expression and variant effects](https://linkinghub.elsevier.com/retrieve/pii/S2667237523002242)** - 2023, Cell Reports Methods
  - ExPectoSC, an atlas of modular deep-learning-based models for predicting cell-type-specific gene expression directly from sequence, is introduced, demonstrating the accuracy of the approach through systematic evaluations and applying the models to prioritiz...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop ExPectoSC, a deep learning framework constructing 105 primary human cell-type sequence models to predict gene expression from DNA sequence and assess variant impacts on cell-type-specific gene expression.

  </details>

- **[CRMnet: A deep learning model for predicting gene expression from large regulatory sequence datasets](https://www.frontiersin.org/articles/10.3389/fdata.2023.1113402/full)** - 2023, Frontiers in Big Data
  - To understand the regulatory code that delineates gene expression, a novel deep-learning model (CRMnet) is designed to predict gene expression in Saccharomyces cerevisiae and outperforms the current benchmark models and achieves a Pearson correlation coeffi...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose CRMnet, a deep learning model combining convolutional neural networks, Transformer encoders, and a U-Net architecture to predict gene expression directly from large-scale synthetic yeast promoter sequences and to uncover the importance of regulatory elements via model interpretation.

  </details>

- **[Deep learning of human polyadenylation sites at nucleotide resolution reveals molecular determinants of site usage and relevance in disease](https://www.nature.com/articles/s41467-023-43266-3)** - 2023, Nature Communications
  - Deep/machine learning models are developed to identify genome-wide putative polyA sites at unprecedented nucleotide-level resolution and calculate their strength and usage in the genomic context and reveal thousands of disease- and trait-associated genetic...
  <details>
  <summary>Series description</summary>

  **Series:** RNA

  To develop deep learning models enabling genome-wide, nucleotide-resolution identification of polyadenylation (polyA) sites, quantifying sequence determinants, splicing competition, and functional impacts of genetic variants.

  </details>

- **[DeepFormer: a hybrid network based on convolutional neural network and flow-attention mechanism for identifying the function of DNA sequences](https://academic.oup.com/bib/article/doi/10.1093/bib/bbad095/7077271)** - 2023, Briefings in Bioinformatics
  - A hybrid deep neural network model, called DeepFormer, based on convolutional neural network and flow-attention mechanism for DNA sequence function prediction is proposed, and the effectiveness of DeepFormer in capturing functional variation using Alzheimer...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose a hybrid deep neural network model called DeepFormer for more accurately predicting DNA sequence functions in terms of chromatin features (e.g., transcription factor binding, DNase I sensitivity, histone marks), addressing issues of high computational complexity and inadequate consideration of distant feature interactions in existing methods.

  </details>

- **[Discovery of regulatory motifs in 5′ untranslated regions using interpretable multi-task learning models](https://linkinghub.elsevier.com/retrieve/pii/S2405471223003034)** - 2023, Cell Systems
  - This work proposes MTtrans, a multi-task translation rate predictor capable of learning common sequence patterns from datasets across various experimental techniques, and introduces "GRU-rewiring," a technique to interpret the hidden states of the recurrent...
  <details>
  <summary>Series description</summary>

  **Series:** RNA

  To develop MTtrans, a multi-task deep learning model integrating diverse experimental datasets to identify conserved regulatory motifs in 5′UTRs controlling translation efficiency, with interpretable localization and variant impact assessment.

  </details>

- **[ExplaiNN: interpretable and transparent neural networks for genomics](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-02985-y)** - 2023, Genome Biology
  - ExplaiNN is introduced, which combines the expressiveness of CNNs with the interpretability of linear models, and can predict TF binding, chromatin accessibility, and de novo motifs, achieving performance comparable to state of theart methods.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To present ExplaiNN, a neural network framework combining deep learning expressiveness with linear model interpretability for genomic sequence analysis, achieving both predictive accuracy and transparency.

  </details>

- **[Single-cell gene expression prediction from DNA sequence at large contexts](http://biorxiv.org/lookup/doi/10.1101/2023.07.26.550634)** - 2023, bioRxiv
  - This work uses a transfer learning framework, seq2cells, leveraging a pre-trained epigenome model for gene expression prediction from large sequence contexts at single-cell resolution, and shows thatseq2cells captures cell-specific gene expression beyond th...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop seq2cells, a framework combining large DNA sequence contexts and pretrained epigenomic models to predict gene expression at single-cell resolution and characterize cell-specific effects of genetic variants across cell states.

  </details>

- **[Towards in silico CLIP-seq: predicting protein-RNA interaction via sequence-to-signal learning](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03015-7)** - 2023, Genome Biology
  - RBPNet improves imputation of protein-RNA interactions, as well as mechanistic interpretation of predictions, and achieves high generalization on eCLIP, iCLIP and miCLIP assays, outperforming state-of-the-art classifiers.
  <details>
  <summary>Series description</summary>

  **Series:** RNA

  To develop RBPNet, a deep convolutional neural network model that predicts CLIP-seq crosslink count distributions directly from RNA sequence, enabling single-nucleotide resolution modeling, interpretation, and variant impact assessment of protein-RNA interactions.

  </details>

- **[Transfer learning identifies sequence determinants of cell-type specific regulatory element accessibility](https://academic.oup.com/nargab/article/doi/10.1093/nargab/lqad026/7092956)** - 2023, NAR Genomics and Bioinformatics
  - ChromTransfer is developed, a transfer learning method that uses a pre-trained, cell-type agnostic model of open chromatin regions as a basis for fine-tuning on regulatory sequences to demonstrate ChromTransfer as a promising tool for learning the regulator...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop ChromTransfer, a transfer learning approach that pre-trains on large-scale, cell-type agnostic open chromatin sequences and fine-tunes on small, cell-type specific datasets, enabling high-accuracy prediction of chromatin accessibility and its sequence determinants.

  </details>

- **[A sequence-based global map of regulatory activity for deciphering human genetics](https://www.nature.com/articles/s41588-022-01102-2)** - 2022, Nature Genetics
  - Sei is a new framework for integrating human genetics data with a sequence-based mapping of predicted regulatory activities to elucidate mechanisms contributing to complex traits and diseases.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a deep learning framework (Sei) that predicts 21,907 chromatin profiles to globally classify and quantify the regulatory activities of any DNA sequence or variant, thereby elucidating regulatory mechanisms underlying complex traits and diseases.

  </details>

- **[Base-resolution prediction of transcription factor binding signals by a deep learning framework](https://dx.plos.org/10.1371/journal.pcbi.1009941)** - 2022, PLOS Computational Biology
  - An integrated framework, which utilizes the FCN architecture to predict TF-DNA binding signals at the base-resolution level, to simultaneously study multiple TFBSs-associated tasks and demonstrated the potential ability of the framework in discovering causa...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose FCNsignal, an FCN-based framework that predicts base-resolution transcription factor binding signals directly from DNA sequence, enabling modeling of binding regions, sequence classification, binding site localization, and motif prediction.

  </details>

- **[Domain-adaptive neural networks improve cross-species prediction of transcription factor binding](http://genome.cshlp.org/lookup/doi/10.1101/gr.275394.121)** - 2022, Genome Research
  - The intrinsic DNA sequence preferences and cell type-specific cooperative partners of transcription factors (TFs) are typically highly conserved.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To study the generalization performance of deep learning models for cross-species TF binding prediction and propose a domain-adaptive neural network that suppresses species-specific sequence feature learning to improve prediction accuracy.

  </details>

- **[Exploiting deep transfer learning for the prediction of functional non-coding variants using genomic sequence](https://academic.oup.com/bioinformatics/article/38/12/3164/6564688)** - 2022, Bioinformatics
  - Though genome-wide association studies have identiﬁed tens of thousands of variants associated with complex traits and most of them fall within the non-coding regions, they may not be the causal ones.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose TLVar, a deep transfer learning framework that pretrains convolutional neural networks on large-scale generic functional variants and fine-tunes them on small-scale context-specific validated variants to improve prediction of functional non-coding variants.

  </details>

- **[MAResNet: predicting transcription factor binding sites by combining multi-scale bottom-up and top-down attention and residual network](https://academic.oup.com/bib/article/doi/10.1093/bib/bbab445/6399874)** - 2022, Briefings in Bioinformatics
  - This study provides a new and useful framework for the prediction of transcription factor binding sites by combining the funnel attention modules with the residual network.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose MAResNet, a deep learning method that integrates multi-scale bottom-up and top-down attention mechanisms with residual networks to efficiently predict transcription factor binding sites (TFBS) from DNA sequences.

  </details>

- **[Sequence-based modeling of three-dimensional genome architecture from kilobase to chromosome scale](https://www.nature.com/articles/s41588-022-01065-4)** - 2022, Nature Genetics
  - Orca is a sequence-based deep-learning algorithm that predicts 3D genome architecture from kilobase to whole-chromosome scale, including the impact of structural variants, and in silico modeling identifies a putative sequence basis for chromatin compartment...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose Orca, a multiscale deep learning framework predicting 3D genome architecture directly from sequence across scales from kilobase to whole chromosome, including TADs, compartments, and diverse interactions.

  </details>

- **[scBasset: sequence-based modeling of single-cell ATAC-seq using convolutional neural networks](https://www.nature.com/articles/s41592-022-01562-8)** - 2022, Nature Methods
  - It is shown that by leveraging the DNA sequence information underlying accessibility peaks and the expressiveness of a neural network model, scBasset achieves state-of-the-art performance across a variety of tasks on scATAC and single-cell multiome datasets...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose scBasset, a CNN-based model to predict single-cell ATAC-seq chromatin accessibility directly from DNA sequence, enabling efficient cell embedding, denoising, cross-batch integration, and TF activity inference.

  </details>

- **[Base-resolution models of transcription-factor binding reveal soft motif syntax](https://www.nature.com/articles/s41588-021-00782-6)** - 2021, Nature Genetics
  - A deep learning model, BPNet, is introduced that uses DNA sequence to predict base-resolution chromatin immunoprecipitation-nexus binding profiles of pluripotency TFs and develops interpretation tools to learn predictive motif representations and identify s...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To predict base-resolution transcription factor binding profiles from DNA sequence using BPNet, and to uncover soft motif syntax rules and TF cooperativity.

  </details>

- **[Biologically relevant transfer learning improves transcription factor binding prediction](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02499-5)** - 2021, Genome Biology
  - It is corroborated that transfer learning improves model performance, especially if in the pre-training step the multi-task model is trained with biologically relevant TFs, and the effectiveness of transfer learning for TFs with ~ 500 ChIP-seq peak regions...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a transfer learning framework combining multi-task pre-training and biologically relevant information (e.g., shared binding mode and cofactors) to improve transcription factor binding site prediction accuracy, especially for TFs with limited ChIP-seq data.

  </details>

- **[Chromatin interaction neural network (ChINN): a machine learning-based method for predicting chromatin interactions from DNA sequences](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02453-5)** - 2021, Genome Biology
  - A computational method, chromatin interaction neural network (ChINN), is developed, to predict chromatin interactions between open chromatin regions using only DNA sequences, which shows good across-sample performances and captures various sequence features...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop ChINN, a deep learning framework that predicts chromatin interactions-including CTCF-, RNA Pol II-associated and Hi-C interactions-from DNA sequence alone, and to explore its application in patient samples to understand 3D genome organization.

  </details>

- **[Deep neural networks identify sequence context features predictive of transcription factor binding](https://www.nature.com/articles/s42256-020-00282-y)** - 2021, Nature Machine Intelligence
  - A machine-learning framework leveraging existing convolutional neural network architectures and model interpretation techniques to identify and interpret sequence context features most important for predicting whether a particular motif instance will be bou...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose AgentBind, a framework that uses deep neural networks to predict whether instances of TF motifs are bound, and applies Grad-CAM to identify the most predictive context nucleotides.

  </details>

- **[DeepTFactor: A deep learning-based tool for the prediction of transcription factors](https://pnas.org/doi/full/10.1073/pnas.2021171118)** - 2021, Proceedings of the National Academy of Sciences
  - A deep learning-based tool that predicts transcription factors using protein sequences as inputs, DeepTFactor uses a convolutional neural network to extract features of a protein, and showed high performance in predicting TFs of both eukaryotic and prokaryo...
  <details>
  <summary>Series description</summary>

  **Series:** Protein

  To develop DeepTFactor, a deep learning tool that automatically predicts transcription factors from protein sequences, overcoming the limitations of homology-based and manually engineered feature approaches.

  </details>

- **[Disease variant prediction with deep generative models of evolutionary data](https://www.nature.com/articles/s41586-021-04043-8)** - 2021, Nature
  - The model EVE (evolutionary model of variant effect) not only outperforms computational approaches that rely on labelled data but also performs on par with, if not better than, predictions from high-throughput experiments, which are increasingly used as evi...
  <details>
  <summary>Series description</summary>

  **Series:** Protein MSA

  To train deep generative models on the evolutionary distribution of protein sequences and predict the pathogenicity of human genetic variants without relying on clinical labels.

  </details>

- **[Effective gene expression prediction from sequence by integrating long-range interactions](https://www.nature.com/articles/s41592-021-01252-x)** - 2021, Nature Methods
  - How noncoding DNA determines gene expression in different cell types is a major unsolved problem, and critical downstream applications in human genetics depend on improved solutions.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a Transformer-based deep learning model that integrates distal regulatory information up to 100 kb away from the transcription start site to accurately predict gene expression and chromatin state from DNA sequence.

  </details>

- **[High-resolution transcription factor binding sites prediction improved performance and interpretability by deep learning method](https://academic.oup.com/bib/article/doi/10.1093/bib/bbab273/6322761)** - 2021, Briefings in Bioinformatics
  - Ability of D-AEDNet to learn TFs-DNA binding motifs outperform the state-of-the-art methods and availability of TF-MoDSW to discover biological sequence motifs inTFs- DNA interaction by conducting experiment on ChIP-seq datasets.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To propose D-AEDNet, a deep attentive encoder-decoder neural network that predicts transcription factor binding sites at base-pair resolution with improved performance and interpretability, along with TF-MoDSW for discovering binding motifs.

  </details>

- **[Interpretation of allele-specific chromatin accessibility using cell state-aware deep learning](http://genome.cshlp.org/lookup/doi/10.1101/gr.260851.120)** - 2021, Genome Research
  - A new integrative genomics approach and a deep learning model are presented to identify and interpret functional enhancer mutations with allelic imbalance of chromatin accessibility and gene expression in melanoma cell states.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To predict allele-specific chromatin accessibility in melanoma cells from DNA sequence using the DeepMEL2 deep learning model, and to elucidate how enhancer mutations affect gene regulation.

  </details>

- **[Locating transcription factor binding sites by fully convolutional neural network](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaa435/6120268)** - 2021, Briefings in Bioinformatics
  - A fully convolutional network coupled with global average pooling (FCNA) is developed, which by contrast is equivalent to a nucleotide-level binary classification task, to roughly locate TFBSs and accurately identify motifs and Experimental results on human...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a novel fully convolutional neural network (FCNA) method performing nucleotide-level binary classification to accurately locate transcription factor binding sites (TFBSs) and extract binding motifs from DNA sequences.

  </details>

- **[MTSplice predicts effects of genetic variants on tissue-specific splicing](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02273-7)** - 2021, Genome Biology
  - MTSplice outperforms MMSplice on predicting tissue-specific variations associated with genetic variants in most tissues of the GTEx dataset, and predicts that autism-associated de novo mutations are enriched for variants affecting splicing specifically in t...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop MTSplice by combining MMSplice with a new neural network TSplice to predict the tissue-specific effects of genetic variants on splicing across 56 human tissues.

  </details>

- **[Modeling transcriptional regulation of model species with deep learning](http://genome.cshlp.org/lookup/doi/10.1101/gr.266171.120)** - 2021, Genome Research
  - DeepArk, a set of deep learning models of the cis-regulatory activities for four widely studied model species, can predict the regulatory impact of any genomic variant and enables the regulatory annotation of understudied model species.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop DeepArk, a deep learning model predicting over 6,500 regulatory features-including TF binding, chromatin accessibility, and histone marks-in four model organisms (C. elegans, D. rerio, D. melanogaster, M. musculus) using only DNA sequence.

  </details>

- **[ReFeaFi: Genome-wide prediction of regulatory elements driving transcription initiation](https://dx.plos.org/10.1371/journal.pcbi.1009376)** - 2021, PLOS Computational Biology
  - A dynamic negative set updating scheme with a two-model approach, using one model for scanning the genome and the other one for testing candidate positions that achieves good genome-level performance and maintains robust performance when applied to other sp...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a deep learning method that accurately predicts promoters and enhancers genome-wide using only DNA sequence, with strong generalization to other species.

  </details>

- **[Cross-species analysis of enhancer logic using deep learning](http://genome.cshlp.org/lookup/doi/10.1101/gr.260844.120)** - 2020, Genome Research
  - The combination of deep learning and cross-species chromatin accessibility profiling to build explainable enhancer models is explored, and the accuracy of DeepMEL predictions on the CAGI5 challenge is shown, where it significantly outperforms existing model...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Develop a deep learning model to predict melanoma enhancer activity in different cell states (MEL and MES) directly from DNA sequence, elucidate their regulatory logic, and identify conserved enhancers and critical transcription factor combinations across species.

  </details>

- **[Cross-species regulatory sequence activity prediction](https://dx.plos.org/10.1371/journal.pcbi.1008050)** - 2020, PLOS Computational Biology
  - A novel and powerful transfer learning approach to use mouse regulatory models to analyze human genetic variants associated with molecular phenotypes and disease and unleash thousands of non-human epigenetic and transcriptional profiles toward more effectiv...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Directly predict cross-species (human and mouse) regulatory sequence activity-including chromatin accessibility, transcription factor binding, and gene expression-from DNA sequence, and use these predictions to assess the functional impact of human noncoding variants.

  </details>

- **[Deep learning of immune cell differentiation](https://pnas.org/doi/full/10.1073/pnas.2011795117)** - 2020, Proceedings of the National Academy of Sciences
  - Applying artificial intelligence tools to a highly complex question of immunology, it is shown that a deep neural network can learn to predict the patterns of chromatin opening across 81 stem and differentiated cells across the immune system, solely from th...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Predict chromatin accessibility profiles of 81 mouse immune cell types solely from regulatory DNA sequence, reconstruct the regulatory logic underlying immune cell differentiation, and identify critical transcription factor combinations and their functional importance.

  </details>

- **[DeepC: predicting 3D genome folding using megabase-scale transfer learning](https://www.nature.com/articles/s41592-020-0960-3)** - 2020, Nature Methods
  - DeepC, a transfer learning-based deep neural network that accurately predicts genome folding from megabase-scale DNA sequence, predicts domain boundaries at high resolution, learns the sequence determinants of genome folding and predicts the impact of both...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Develop a deep learning model to predict high-resolution 3D genome folding (Hi-C contact maps) from 1 Mb DNA sequence, enabling dissection of the sequence determinants of chromatin architecture and assessment of the effects of sequence variants ranging from single nucleotides to large structural rearrangements.

  </details>

- **[DeepGOPlus: improved protein function prediction from sequence](https://academic.oup.com/bioinformatics/article/36/2/422/5539866)** - 2020, Bioinformatics
  - A novel method for predicting protein functions from sequence alone which combines deep convolutional neural network (CNN) model with sequence similarity based predictions which can annotate around 40 protein sequences per second, thereby making fast and ac...
  <details>
  <summary>Series description</summary>

  **Series:** Protein

  To predict protein functions accurately and efficiently from amino acid sequences by combining deep convolutional neural networks with sequence similarity information.

  </details>

- **[Enhancing the interpretability of transcription factor binding site prediction using attention mechanism](https://www.nature.com/articles/s41598-020-70218-4)** - 2020, Scientific Reports
  - TBiNet is an attention based interpretable deep neural network for predicting transcription factor binding sites, which outperforms the current state-of-the-art methods quantitatively in the TF-DNA binding prediction task and is more effective than the prev...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Propose an attention-based deep neural network model to predict transcription factor (TF) binding sites from DNA sequences and improve interpretability of predictions.

  </details>

- **[MusiteDeep: a deep-learning based webserver for protein post-translational modification site prediction and visualization](https://academic.oup.com/nar/article/48/W1/W140/5824154)** - 2020, Nucleic Acids Research
  - The MusiteDeep framework is updated by utilizing more advanced ensemble techniques, and providing prediction and visualization for multiple PTMs simultaneously for users to analyze potential PTM cross-talks directly and interactively review the predicted PT...
  <details>
  <summary>Series description</summary>

  **Series:** Protein

  Develop a general deep-learning framework to predict multiple types of protein post-translational modification (PTM) sites directly from protein sequences, with visualization and interactive analysis capabilities.

  </details>

- **[Predicting 3D genome folding from DNA sequence with Akita](https://www.nature.com/articles/s41592-020-0958-x)** - 2020, Nature Methods
  - A convolutional neural network, Akita, is presented that accurately predicts genome folding from DNA sequence alone and can be used to perform in silico saturation mutagenesis, interpret eQTLs, make predictions for structural variants and probe species-spec...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Predict locus-specific 3D genome folding patterns (chromosome contact frequency maps) directly from DNA sequence and assess the functional impact of single nucleotide mutations or structural variants.

  </details>

- **[DeepPhos: prediction of protein phosphorylation sites with deep learning](https://academic.oup.com/bioinformatics/article/35/16/2766/5270665)** - 2019, Bioinformatics
  - DeepPhos, a novel deep learning architecture for prediction of protein phosphorylation, consists of densely connected convolutional neuron network blocks which can capture multiple representations of sequences to make final phosphorylated prediction by intr...
  <details>
  <summary>Series description</summary>

  **Series:** Protein

  English: To develop a deep learning architecture, DeepPhos, based on densely connected convolutional neural network (DC-CNN) blocks, for accurate prediction of general phosphorylation sites and kinase-specific phosphorylation sites at group/family/subfamily/individual kinase levels.

  </details>

- **[Functional interpretation of genetic variants using deep learning predicts impact on chromatin accessibility and histone modification](https://academic.oup.com/nar/article/47/20/10597/5572574)** - 2019, Nucleic Acids Research
  - A deep learning model is developed to accurately predict locus-specific signals from four epigenetic assays using only DNA sequence as input, and generates a score of the predicted epigenetic consequences for 438 million variants observed in previous sequen...
  <details>
  <summary>Series description</summary>

  **Series:** DNA(with personal SNPs)

  Predict quantitative variation in chromatin accessibility and histone modifications from DNA sequence and evaluate the functional impact of genetic variants on the epigenome.

  </details>

- **[Predicting Splicing from Primary Sequence with Deep Learning](https://linkinghub.elsevier.com/retrieve/pii/S0092867418316295)** - 2019, Cell
  - A deep neural network is described that accurately predicts splice junctions from an arbitrary pre-mRNA transcript sequence, enabling precise prediction of noncoding genetic variants that cause cryptic splicing.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Predict mRNA splicing from primary genomic sequence and evaluate the impact of noncoding variants on splicing, enabling functional interpretation in genetic disease.

  </details>

- **[DeFine: deep convolutional neural networks accurately quantify intensities of transcription factor-DNA binding and facilitate evaluation of functional non-coding variants](https://academic.oup.com/nar/article/46/11/e69/4958204)** - 2018, Nucleic Acids Research
  - The complex system of gene expression is regulated by the cell type-speciﬁc binding of transcription factors (TFs) to regulatory elements.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To accurately predict transcription factor (TF)-DNA binding intensities from DNA sequence and quantify the functional impact of noncoding variants (SNPs/indels) on TF binding, enabling systematic prioritization and annotation of disease-associated variants.

  </details>

- **[Deep learning sequence-based ab initio prediction of variant effects on expression and disease risk](https://www.nature.com/articles/s41588-018-0160-6)** - 2018, Nature Genetics
  - ExPecto is a deep learning-based framework that can predict the tissue-specific transcriptional effects of mutations on the basis of DNA sequence alone and can prioritize causal variants from GWAS loci and be used to predict the disease risk of a variant.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  Predict tissue-specific gene expression from DNA sequence alone and assess variant effects on expression and disease risk.

  </details>

- **[Predictable and precise template-free CRISPR editing of pathogenic variants](https://www.nature.com/articles/s41586-018-0686-x)** - 2018, Nature
  - This study establishes an approach for precise, template-free genome editing by using a machine-learning algorithm to predict the spectrum of CRISPR-Cas9-nuclease-mediated DNA repair outcomes at human genomic target sites.
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (one-hot) → indel genotype frequencies

  Develop a machine learning model to predict template-free CRISPR-Cas9 editing outcomes for precise correction of pathogenic variants.

  </details>

- **[Sequential regulatory activity prediction across chromosomes with convolutional neural networks](http://genome.cshlp.org/lookup/doi/10.1101/gr.227819.117)** - 2018, Genome Research
  - Models for predicting phenotypic outcomes from genotypes have important applications to understanding genomic function and improving human health.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To develop a deep neural network model that predicts cell-type-specific epigenetic and transcriptional profiles (e.g., chromatin accessibility, histone marks, gene expression) directly from DNA sequence and quantifies the impact of noncoding variants on gene regulation genome-wide.

  </details>

- **[MusiteDeep: a deep-learning framework for general and kinase-specific phosphorylation site prediction](https://academic.oup.com/bioinformatics/article/33/24/3909/4061279)** - 2017, Bioinformatics
  - MusiteDeep takes raw sequence data as input and uses convolutional neural networks with a novel two-dimensional attention mechanism and achieves over a 50% relative improvement in the area under the precision-recall curve in general phosphorylation site pre...
  <details>
  <summary>Series description</summary>

  **Series:** Protein

  To develop a deep learning framework that predicts general and kinase-specific phosphorylation sites directly from protein sequences, overcoming limitations of feature engineering and improving prediction accuracy.

  </details>

- **[Basset: learning the regulatory code of the accessible genome with deep convolutional neural networks](http://genome.cshlp.org/lookup/doi/10.1101/gr.200535.115)** - 2016, Genome Research
  - An open source package Basset is introduced to apply CNNs to learn the functional activity of DNA sequences from genomics data and offers a powerful computational approach to annotate and interpret the noncoding genome.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To use deep convolutional neural networks (CNNs) to predict chromatin accessibility (DNase I hypersensitivity) from DNA sequence and to assess the functional impact of noncoding variants (SNPs/indels) at single-nucleotide resolution, thereby decoding the regulatory genome.

  </details>

- **[DanQ: a hybrid convolutional and recurrent deep neural network for quantifying the function of DNA sequences](https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkw226)** - 2016, Nucleic Acids Research
  - The DanQ model, a novel hybrid convolutional and bi-directional long short-term memory recurrent neural network framework for predicting noncoding function de novo from sequence, improves considerably upon other models across several metrics.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To directly predict the function of noncoding DNA (e.g., transcription factor binding, chromatin accessibility, histone marks) from raw sequence and to quantify the functional effects of noncoding variants (SNPs/indels), thereby revealing the regulatory "grammar" of the genome.

  </details>

- **[DeeperBind: Enhancing Prediction of Sequence Speciﬁcities of DNA Binding Proteins](https://doi.org/10.1109/bibm.2016.7822515)** - 2016, BIBM
  - Transcription factors (TFs) are macromolecules that bind to cis-regulatory speciﬁc sub-regions of DNA promoters and initiate transcription.
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To accurately predict transcription factor (TF) binding specificities and affinities from DNA sequences using deep learning, improving binding site localization and affinity estimation from high-throughput assays (e.g., PBM).

  </details>

- **[Predicting effects of noncoding variants with deep learning-based sequence model](https://www.nature.com/articles/nmeth.3547)** - 2015, Nature Methods
  - A deep learning-based algorithmic framework, DeepSEA, is developed that directly learns a regulatory sequence code from large-scale chromatin-profiling data, enabling prediction of chromatin effects of sequence alterations with single-nucleotide sensitivity...
  <details>
  <summary>Series description</summary>

  **Series:** DNA

  To directly predict transcription factor binding, chromatin accessibility (DNase I hypersensitivity), and histone modifications from genomic sequence, and to estimate the functional effects of noncoding variants (SNPs/indels) at single-nucleotide resolution.

  </details>

- **[Predicting the sequence specificities of DNA- and RNA-binding proteins by deep learning](https://www.nature.com/articles/nbt.3300)** - 2015, Nature Biotechnology
  - This work shows that sequence specificities can be ascertained from experimental data with 'deep learning' techniques, which offer a scalable, flexible and unified computational approach for pattern discovery.
  <details>
  <summary>Series description</summary>

  **Series:** DNA, RNA

  To predict the sequence specificities of DNA- and RNA-binding proteins and assess the impact of genetic variants on binding and gene regulation.

  </details>

</details>

## S2F-Other-Model (154)

<details>
<summary>Show S2F-Other-Model papers (154)</summary>

- **[A DNA language model based on multispecies alignment predicts the effects of genome-wide variants](https://www.nature.com/articles/s41587-024-02511-w)** - 2025, Nature Biotechnology
  - GPN-MSA (genomic pretrained network with multiple-sequence alignment), a framework that leverages whole-genome alignments across multiple species while taking only a few hours to train, achieves outstanding performance on deleteriousness prediction for both...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA (MSA one-hot) → masked nucleotide prediction; Fine-tune (VEP): DNA (MSA one-hot) → log-likelihood ALT/REF

  To develop a DNA language model leveraging multispecies alignment (MSA) to predict genome-wide variant effects.

  </details>

- **[A contextualised protein language model reveals the functional syntax of bacterial evolution](https://doi.org/10.1101/2025.07.20.665723)** - 2025, bioRxiv
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein sequences (ESM-2 embedding + positional) → Masked protein family prediction; Fine-tune: Contextual protein embeddings → PPI probability / Phenotype probability / Protein family sequence

  Develop a transformer-based contextualised protein language model (Bacformer) pretrained to learn genome-wide evolutionary patterns for predicting protein-protein interactions, operon structure, and other functional genomic tasks.

  </details>

- **[A disease-specific language model for variant pathogenicity in cardiac and regulatory genomics](https://www.nature.com/articles/s42256-025-01016-8)** - 2025, Nature Machine Intelligence
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein sequence → masked amino acid prediction; Fine-tune: Protein (LM embedding) → PLLR → pathogenicity label Pre-train: DNA sequence → masked k-mer prediction; Fine-tune: DNA (LM embedding) → Euclidean distance/logit → splicing/pathogenicity label

  To improve variant effect prediction (VEP) in disease contexts by fine-tuning genomic foundation models using DYNA, a disease-specific Siamese network framework applied to both protein and DNA sequence models.

  </details>

- **[A foundation language model to decipher diverse regulation of RNAs](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03752-x)** - 2025, Genome Biology
  <details>
  <summary>Series description</summary>

  **Series:** RNA(character embedding) → masked nucleotide prediction

  To develop a Transformer-based foundation language model, LAMAR, which learns intrinsic features of RNAs through unsupervised pretraining on large-scale RNA sequences and is fine-tuned for diverse regulatory tasks including predicting splice sites, translation efficiency, degradation rates, and internal ribosome entry site (IRES) activity.

  </details>

- **[A generative artificial intelligence approach for the discovery of antimicrobial peptides against multidrug-resistant bacteria](https://www.nature.com/articles/s41564-025-02114-4)** - 2025, Nature Microbiology
  - This study presents a generative artificial intelligence approach for the discovery of novel antimicrobials against multidrug-resistant bacteria, enabling efficient and extensive exploration of AMP space.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein sequences (Tokenization) → Masked token prediction AMP mining: Sliding-window peptides (8-30 AA) → AMP probability (AMPSorter) AMP generation: Temperature + prefix AA → Novel peptide sequences (AMPGenix) Toxicity screening: Peptide sequence → Cytotoxicity probability (BioToxiPept)

  To achieve high-throughput mining and generation of antimicrobial peptides (AMPs) using a pre-trained protein large language model (ProteoGPT) and its transfer learning submodels, targeting clinical superbugs such as carbapenem-resistant Acinetobacter baumannii (CRAB) and methicillin-resistant Staphylococcus aureus (MRSA).

  </details>

- **[Annotating the genome at single-nucleotide resolution with DNA foundation models](https://www.nature.com/articles/s41592-025-02881-2)** - 2025, Nature Methods
  - This work frames the genome annotation problem as instance segmentation and introduces a novel methodology for fine-tuning pre-trained DNA foundation models to segment 14 different genic and regulatory elements at single-nucleotide resolution, leading to a...
  <details>
  <summary>Series description</summary>

  **Series:** Fine-tuning stage: DNA sequence (tokenized via 6-mer + NT embedding) → per-nucleotide probabilities for 14 genomic elements; Multimodal framework: DNA sequence (Enformer embedding) / DNA sequence (Borzoi embedding) → probabilities for regulatory elements (e.g., enhancers/promoters).

  To annotate 14 different types of genetic and regulatory elements in the genome at single-nucleotide resolution by fine-tuning pretrained DNA foundation models and adopting multilabel semantic segmentation.

  </details>

- **[AttenRNA: multi-scale deep attentive model with RNA feature variability analysis](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf336/8195923)** - 2025, Briefings in Bioinformatics
  - AttenRNA, a multi-class classification model that integrates multi-scale k-mer embeddings and attention mechanisms to simultaneously differentiate between various RNA classes is developed, suggesting that AttenRNA offers a reliable and scalable solution for...
  <details>
  <summary>Series description</summary>

  **Series:** RNA（3-mer/4-mer/5-mer embedding）→ circRNA/lncRNA/mRNA label

  To construct a multi-scale attention model for simultaneously classifying circRNAs, lncRNAs, and mRNAs to enable systematic RNA functional analysis.

  </details>

- **[AutoFE-Pointer: Auto-weighted feature extractor based on pointer network for DNA methylation prediction](https://linkinghub.elsevier.com/retrieve/pii/S0141813025042205)** - 2025, International Journal of Biological Macromolecules
  - AutoFE-Pointer is designed to simultaneously process 17 different benchmark datasets spanning multiple species, achieving superior performance compared to models that are trained individually on single-species data and significantly reduces computational de...
  <details>
  <summary>Series description</summary>

  **Series:** AutoFE-S: DNA (1-mer embedding + species + position) → methylation (4mC/5hmC/6mA/5mC) prediction; AutoFE (multi-task): DNA (1-mer embedding + species + position) → multi-species methylation prediction

  Develop a lightweight pointer network-based model, AutoFE-Pointer, to accurately predict DNA methylation sites across multiple species with robust cross-species generalization.

  </details>

- **[B-EPIC: A Transformer-Based Language Model for Decoding B Cell Immunodominance Patterns](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202508896)** - 2025, Advanced Science
  - B-Epic utilizes self-attention, high-dimensional feature projection, and convolutional neural networks to autonomously extract complicated BCE features, enabling accurate BCE prediction and thereby facilitating efforts to prevent infectious diseases and can...
  <details>
  <summary>Series description</summary>

  **Series:** Amino acid sequence (ProtTrans embedding) → B-cell epitope probability

  To develop B-EPIC, a Transformer-based model for B-cell epitope (BCE) prediction, enabling high-accuracy identification of immunoreactive peptides in pathogen antigens to accelerate vaccine and immunodiagnostic design.

  </details>

- **[BBANsh: a deep learning architecture based on BERT and bilinear attention networks to identify potent shRNA](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf443/8242584)** - 2025, Briefings in Bioinformatics
  - BBANsh, a new shRNA prediction model based on bidirectional encoder representation from transformers and bilinear attention network, is proposed and comprehensively evaluated against traditional feature-based models, various feature fusion methods, and exis...
  <details>
  <summary>Series description</summary>

  **Series:** shRNA sequence (DNABERT/GENA-LM encoding) → potent shRNA probability

  To develop a deep learning model (BBANsh) based on BERT and bilinear attention networks (BAN) for efficient and accurate prediction of short hairpin RNA (shRNA) potency.

  </details>

- **[BBATProt: a framework predicting biological function with enhanced feature extraction via interpretable deep learning](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf593/8319949)** - 2025, Briefings in Bioinformatics
  - A BERT-BiLSTM-Attention-TCN Protein Function Prediction Framework (BBATProt), a versatile framework for predicting protein and peptide functions that consistently outperforms state-of-the-art models in tasks such as hydrolytic catalysis, peptide bioactivity...
  <details>
  <summary>Series description</summary>

  **Series:** Amino acid sequence (BERT embedding) → Functional prediction probability (Sigmoid)

  To develop an interpretable deep learning framework (BBATProt) based on BERT-BiLSTM-Attention-TCN for predicting biological functions of proteins and peptides from amino acid sequences, such as enzymatic activity, antimicrobial activity, and post-translational modification sites.

  </details>

- **[BMFM-DNA: A SNP-aware DNA foundation model to capture variant effects](http://arxiv.org/abs/2507.05265)** - 2025, arXiv
  - arXiv:2507.05265 \[q-bio\]
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（BPE-ref/variant）→ masked token prediction；Fine-tune: DNA（BPE）→ promoter / TFBS / splice / MPRA / SNP-disease

  To develop SNP-aware DNA language models that capture the biological effects of sequence variations more effectively.

  </details>

- **[BiRNA-BERT allows efficient RNA language modeling with adaptive tokenization](https://www.nature.com/articles/s42003-025-08982-0)** - 2025, Communications Biology
  - BiRNA-BERT can dynamically adjust its tokenization strategy based on sequence lengths, utilizing NUC for shorter sequences and switching to BPE for longer ones, thereby offering, for the first time, the capability to efficiently handle arbitrarily long DNA/...
  <details>
  <summary>Series description</summary>

  **Series:** quence tasks: RNA sequences (NUC tokenization, one-hot) → classification probability/structural matrices; Long-sequence tasks: RNA sequences (BPE tokenization, vocab indices) → interaction/classification probability; Nucleotide-level tasks: RNA sequences (NUC tokenization, one-hot) → secondary structure/distance map/torsion angles

  To develop BiRNA-BERT, a Transformer model with adaptive dual-tokenization (nucleotide-level and BPE), addressing limitations of sequence truncation in long RNA contexts and enabling fine-grained tasks.

  </details>

- **[Bio-xLSTM: Generative modeling, representation and in-context learning of biological and chemical sequences](http://arxiv.org/abs/2411.04165)** - 2025, ICLR
  - arXiv:2411.04165 \[q-bio\] TLDR: Assessment of xLSTM's ability to model biological and chemical sequences and a suite of architectural variants called Bio-xLSTM, which can serve as proficient generative models for DNA, protein, and chemical sequences, and lea...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (one-hot) → masked/base prediction; Fine-tune: DNA (one-hot) → epigenetic/splice/promoter classification Pre-Train: Protein (one-hot) → next amino acid / fill-in prediction Pre-Train: SMILES (one-hot) → next character prediction / ICL-based SMILES generation

  To develop efficient generative models for DNA, protein, and chemical sequences using xLSTM, enabling long-range modeling, representation learning, and in-context learning.

  </details>

- **[BioToken and BioFM - Biologically-Informed Tokenization Enables Accurate and Efficient Genomic Foundation Models](https://doi.org/10.1101/2025.03.27.645711)** - 2025, bioRxiv
  - BioToken is introduced, a modular and extendable tokenization framework designed to encode genomic variants and biologically relevant structural annotations directly into genomic representations directly into genomic representations, providing a robust and...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（BioToken-Annotation-Variant）→ next token prediction; Fine-tune: DNA（BioToken-Annotation-Variant）→ expression/splicing/pathogenicity/ancestry/commonness

  To enhance accuracy and generalizability of genomic variant modeling by introducing a biologically-informed tokenization scheme (BioToken) and an efficient genomic foundation model (BioFM).

  </details>

- **[Boosting the predictive power of protein representations with a corpus of text annotations](https://www.nature.com/articles/s42256-025-01088-6)** - 2025, Nature Machine Intelligence
  <details>
  <summary>Series description</summary>

  **Series:** Protein sequence (PLM embedding) → Text annotation (14 types) ; Protein representation (PAIR) → EC/GO/Domain prediction

  To enhance the generalization capability of protein representations for function prediction tasks by fine-tuning protein language models (PLMs) on diverse text annotations from UniProt.

  </details>

- **[CREATE: a novel attention-based framework for efficient classification of transposable elements](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf608/8324532)** - 2025, Briefings in Bioinformatics
  - A novel framework called CREATE is proposed, which simultaneously integrates the global pattern distribution and the local sequence profile of TEs using Convolutional neural networks and Recurrent neural nEtworks with an Attention mechanism for efficient TE...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (k-mer frequency encoding) + both-end sequences (one-hot encoding) → transposable element type probabilities

  To develop an attention-based CNN-RNN hybrid framework for efficient classification of transposable elements to enhance genome annotation accuracy.

  </details>

- **[CaLMPhosKAN: Prediction of General Phosphorylation Sites in Proteins via Fusion of Codon Aware Embeddings with Amino Acid Aware Embeddings and Wavelet-based Kolmogorov-Arnold Network](https://doi.org/10.1093/bioinformatics/btaf124)** - 2025, Bioinformatics
  - This work introduces a novel approach for prediction of phosphorylation sites by incorporating codon-level information through embeddings from a recently developed codon language model trained exclusively on protein-coding DNA sequences, and emerges as a ro...
  <details>
  <summary>Series description</summary>

  **Series:** Protein (ProtT5 embedding, 1024) + Coding DNA (CaLM embedding, 768) → phosphorylation site probability

  A novel bimodal neural framework is proposed that integrates embeddings from coding DNA and protein sequences for general phosphorylation site prediction in proteins.

  </details>

- **[CodonMoE: DNA Language Models for mRNA Analyses](http://arxiv.org/abs/2508.04739)** - 2025, arXiv
  - arXiv:2508.04739 \[q-bio\]
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA sequence (nucleotide token) → nucleotide embeddings; Fine-Tune: RNA sequence (codon-averaged embedding) → stability/expression/regulation score

  Develop a lightweight adapter module CodonMoE to transform pretrained DNA language models into effective mRNA analyzers without RNA-specific pretraining.

  </details>

- **[CodonTransformer: a multispecies codon optimizer using context-aware neural networks](https://www.nature.com/articles/s41467-025-58588-7)** - 2025, Nature Communications
  - CodonTransformer, a multispecies deep learning model trained on over 1 million DNA-protein pairs from 164 organisms spanning all domains of life, is introduced and the strategy of Shared Token Representation and Encoding with Aligned Multi-masking (STREAM)...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein + DNA（amino acid-codon token, STREAM）→ masked codon prediction; Fine-tune: Protein + DNA → optimized codon sequence

  Leverage a Transformer-based deep learning model to generate species-specific optimized DNA sequences from protein sequences across multiple organisms.

  </details>

- **[DRBP-EDP: classification of DNA-binding proteins and RNA-binding proteins using ESM-2 and dual-path neural network](https://academic.oup.com/nargab/article/doi/10.1093/nargab/lqaf058/8136478)** - 2025, NAR Genomics and Bioinformatics
  - A phased classification method integrating ESM-2 with a dual-path neural network is proposed, called DRBP-EDP, which achieved strong performance and a refined approach to dataset construction is designed, resulting in the creation of high-quality protein cl...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein (tokenized input_ids) → last_hidden_state; Fine-tune: Protein (ESM-2 embedding) → NABP/non-NABP / DBP/RBP

  This study proposes a phased method integrating ESM-2 and a dual-path neural network for classifying DNA-binding proteins (DBPs) and RNA-binding proteins (RBPs).

  </details>

- **[Deciphering enzymatic potential in metagenomic reads through DNA language models](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf836/8246932)** - 2025, Nucleic Acids Research
  - Microbial communities drive essential global processes, yet much of their functional potential remains unexplored.
  <details>
  <summary>Series description</summary>

  **Series:** DNA read (trinucleotide tokens) → First-level enzymatic activity class probability (EC1-7 or non-enzyme)

  To develop DNA language model-based tools (REMME and REBEAN) for predicting the enzymatic activity (first-level EC classes) encoded by genes giving rise to metagenomic sequencing reads, without requiring sequence assembly or homology-based alignment

  </details>

- **[DeepCOI: a large language model-driven framework for fast and accurate taxonomic assignment in animal metabarcoding](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03861-7)** - 2025, Genome Biology
  - DeepCOI enables fast and accurate taxonomic assignment across eight major phyla, achieving an AU-ROC of 0.958 and AU-PR of 0.897-outperforming existing methods while significantly reducing inference time.
  <details>
  <summary>Series description</summary>

  **Series:** COI DNA sequences (4-mer tokenized) → probability labels for phylum/class/order/family/genus/species

  To develop a large language model (LLM)-based classifier for fast and accurate taxonomic assignment of animal cytochrome c oxidase I (COI) gene sequences from phylum to species level, enhancing the efficiency and precision of metabarcoding analysis.

  </details>

- **[DeepPhosPPI: a deep learning framework with attention-CNN and transformer for predicting phosphorylation effects on protein-protein interactions](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf462/8248860)** - 2025, Briefings in Bioinformatics
  - DeepPhosPPI is proposed, the first sequence-based deep learning framework for phosphorylation effects on PPIs prediction, which employs the pre-trained protein language model for feature embedding, with ProtBERT and ESM-2 as alternative backbone encoders.
  <details>
  <summary>Series description</summary>

  **Series:** Task 1: Protein sequence (ProtBERT/ESM-2 embedding) → Functional phosphorylation site probability (binary) Task 2: Protein A (local features: phosphorylation site window) + Protein A (global) + Protein B (global) → PPI regulatory effect probability (enhancement/inhibition)

  To develop a protein sequence-based deep learning framework (DeepPhosPPI) that integrates an attention-based convolutional neural network (CNN) and a Transformer model to predict the regulatory effects (enhancement or inhibition) of phosphorylation on protein-protein interactions (PPIs).

  </details>

- **[Discovering the complete enhancer map of human herpesviruses using a natural language processing model](https://www.nature.com/articles/s41467-025-66861-y)** - 2025, Nature Communications
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (character tokenization) → Enhancer activity (continuous value)

  To develop a natural language processing (NLP) tool named ENHAvir, trained on enhancer data from Kaposi's sarcoma-associated herpesvirus (KSHV), for predicting enhancer sequences in human herpesviruses and other viral genomes.

  </details>

- **[EDS-Kcr: deep supervision based on large language model for identifying protein lysine crotonylation sites across multiple species](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf249/8154762)** - 2025, Briefings in Bioinformatics
  - The EDS-Kcr model, a novel bioinformatics tool that integrates the state-of-the-art protein language model ESM2 with deep supervision to improve the efficiency and accuracy of Kcr site prediction, demonstrated outstanding performance across various species...
  <details>
  <summary>Series description</summary>

  **Series:** Protein（ESM2 embedding + 1-mer/2-mer）→ Kcr probability

  Propose a deep supervision-based tool integrating a protein language model for efficient identification of protein lysine crotonylation (Kcr) sites across multiple species.

  </details>

- **[ERNIE-RNA: an RNA language model with structure-enhanced representations](https://www.nature.com/articles/s41467-025-64972-0)** - 2025, Nature Communications
  - It is found that the attention maps from ERNIE-RNA with no fine-tuning are able to capture RNA structure in the zero-shot experiment more precisely than conventional methods such as fine-tuned RNAfold and RNAstructure, suggesting that the ERNIE-RNA can prov...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: RNA sequence (raw nucleotide tokens + MLM masking) → masked token prediction; Fine-tune (Structure prediction): RNA sequence (one-hot or raw token input) → Attention map (ERNIE-RNA specific feature); RNA sequence → token embedding vector (common feature); Attention map / Embedding vector → RNA secondary structure contact map / distance probability map ; Fine-tune (Function prediction): RNA sequence (CLS token feature) → ncRNA family classification; RNA sequence (CLS token feature) → 5'UTR mean ribosomal loading (MRL); RNA Sequence (CLS token feature) → RNA-protein binding probability

  To develop a pre-trained RNA language model (named ERNIE-RNA) based on a modified BERT architecture that integrates RNA base-pairing structural information to enhance feature representation and improve performance on downstream tasks such as RNA structure and function prediction.

  </details>

- **[Effective Gene Expression Prediction and Optimization from Protein Sequences](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202407664)** - 2025, Advanced Science
  - A novel connection between protein expression and sequence is uncovered, leading to the development of SRAB (Strength of Relative Amino Acid Bias) based on AEI (Amino Acid Expression Index), which highlights the efficacy of the developed model in predicting...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein（Token Embedding）→ masked token prediction; Fine-tune: Protein（Token Embedding）→ high/low expression label / mutant sequences

  To develop deep learning models that predict and optimize heterologous soluble expression levels from protein sequences.

  </details>

- **[EnTao-GPM: DNA Foundation Model for Predicting the Germline Pathogenic Mutations](https://arxiv.org/abs/2507.21706)** - 2025, arXiv
  - Version Number: 1 TLDR: EnTao-GPM revolutionizes genetic testing by enabling faster, more accurate, and accessible interpretation for clinical diagnostics and research, advancing personalized medicine.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Mammalian DNA sequence → contextual embeddings; &gt; Fine-Tune (GPMFast): Human reference DNA → SNV pathogenicity probability; &gt; Fine-Tune (GPMPro): Human reference DNA + mutant DNA → SNV/non-SNV pathogenicity probability

  Develop a DNA sequence-based AI model (EnTao-GPM) to accurately distinguish germline pathogenic mutations from benign polymorphisms via cross-species pre-training and fine-tuning on clinical mutation data.

  </details>

- **[Enhancing nucleotide sequence representations in genomic analysis with contrastive optimization](https://www.nature.com/articles/s42003-025-07902-6)** - 2025, Communications Biology
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（6-mer / BigBird）→ embedding vector; Fine-tune: DNA embedding → gene/taxa/promotion/AMR label + confidence

  To optimize DNA sequence embeddings via contrastive learning, enhancing generalization in classification tasks for unseen genes and taxa.

  </details>

- **[Euktect: Enhanced eukaryotic sequence detection and classification in metagenomes via the DNA language model](https://www.researchsquare.com/article/rs-7056517/v1)** - 2025, Research Square
  - The current taxonomy classification of DNA sequences in metagenomics primarily relies on alignment against reference databases.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (single-nucleotide token) → masked nucleotide prediction; Fine-tune: DNA (single-nucleotide token) → eukaryote/bacterium/archaeon/virus probability; Application: Metagenomic contigs (single-nucleotide token) → eukaryote sequence probability

  Develop a deep learning model (Eukect) based on the HyenaDNA architecture for high-accuracy detection and classification of eukaryotic sequences in metagenomes.

  </details>

- **[FGeneBERT: function-driven pre-trained gene language model for metagenomics](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf592/8317925)** - 2025, Briefings in Bioinformatics
  - FGeneBERT is introduced, a novel metagenomic pre-trained model that employs a protein-based gene representation as a context-aware and structure-relevant tokenizer that incorporates masked gene modeling and triplet enhanced metagenomic contrastive learning...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (translated to protein ESM representation) → Knowledge representation

  To propose FGeneBERT, a pre-trained model using protein-based gene representations, for addressing one-to-many (OTM) and many-to-one (MTO) relationships in metagenomic data and improving function-driven representation learning.

  </details>

- **[Fast and Low-Cost Genomic Foundation Models via Outlier Removal](https://doi.org/10.48550/arXiv.2505.00598)** - 2025, arXiv
  - To address the challenge of scarce computational resources in genomic modeling, we introduce GERM, a genomic foundation model with strong compression performance and fast adaptability.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（BPE）→ masked token classification; Fine-tune: DNA（BPE）→ task-specific class/score

  Build an efficient genomic foundation model (GERM) that removes outliers in the transformer attention mechanism to enhance robustness and performance of low-rank adaptation and quantization in resource-constrained settings.

  </details>

- **[Fine-Tuning Protein Language Models Enhances the Identification and Interpretation of the Transcription Factors](http://biorxiv.org/lookup/doi/10.1101/2025.11.27.691010)** - 2025, bioRxiv
  - Transcription factors (TFs) are pivotal regulators of gene expression and play essential roles in diverse cellular activities.
  <details>
  <summary>Series description</summary>

  **Series:** Protein sequences (PSSM encoding or ESM2 embeddings) → transcription factor classification probability; transcription factor sequences → methylated DNA binding preference probability.

  To develop a two-layer predictive framework using protein language models for identifying transcription factors and predicting their binding preference for methylated DNA.

  </details>

- **[G4mer: An RNA language model for transcriptome-wide identification of G-quadruplexes and disease variants from population-scale genetic data](https://www.nature.com/articles/s41467-025-65020-7)** - 2025, Nature Communications
  - G4mer is introduced, an RNA language model that predicts rG4 formation and evaluates the effects of genetic variants across the transcriptome, and significantly improves accuracy over existing methods, highlighting sequence length and flanking motifs as imp...
  <details>
  <summary>Series description</summary>

  **Series:** RNA sequence (6-mer token encoding) → rG4 formation probability (continuous) / rG4 subtype probabilities (8-dimensional vector).

  To develop a transformer-based RNA language model, G4mer, for transcriptome-wide prediction of RNA G-quadruplex formation and subtype classification, assess the impact of genetic variants on rG4 structures, and identify disease-associated variants.

  </details>

- **[GENA-LM: a family of open-source foundational DNA language models for long sequences](https://academic.oup.com/nar/article/doi/10.1093/nar/gkae1310/7954523)** - 2025, Nucleic Acids Research
  - Recent advancements in genomics, propelled by artificial intelligence, have unlocked unprecedented capabilities in interpreting genomic sequences, mitigating the need for exhaustive experimental analysis of complex, intertwined molecular processes inherent...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA (BPE) → masked token prediction; Fine-tune: DNA (BPE) → promoter / splice site / chromatin profile / enhancer activity / polyA signal / species label

  To develop and release GENA-LM, a family of open-source transformer-based language models for long DNA sequences, enabling efficient fine-tuning and representation learning across multiple genomic tasks and species.

  </details>

- **[GENERator: A Long-Context Generative Genomic Foundation Model](http://arxiv.org/abs/2502.07272)** - 2025, arXiv
  - arXiv:2502.07272 \[cs\] TLDR: The GENERator is presented, a generative genomic foundation model featuring a context length of 98k base pairs (bp) and 1.2B parameters that shows significant promise in sequence optimization, particularly through the prompt-resp...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (6-mer) → next 6-mer prediction; Fine-tune: DNA (6-mer) → protein-coding DNA / promoter (activity-labeled) / gene type / taxonomy label

  To develop a long-context DNA generative foundation model capable of producing functional sequences and generalizing across diverse genomic tasks.

  </details>

- **[GQ-DNABERT reveals GQ proximal enhancer-promoter interactions associated with tissue-specific transcription](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf1007/8285783)** - 2025, Nucleic Acids Research
  - The usefulness of GQ-DNABERT for investigating transcriptional regulation in single-cell experiments is demonstrated and it is demonstrated that the model is a valuable tool for extending and harmonizing data collected ex vivo.
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (6-mer embedding) → GQ probability (binary classification) ; Predicted GQ + open chromatin regions (ATAC-seq) → tissue-specific GQ proximal enhancer-promoter (pEP) pairs

  To develop the GQ-DNABERT model for predicting functional G-quadruplex (GQ) locations in the genome and analyzing their roles in tissue-specific transcriptional regulation.

  </details>

- **[Generalized biological foundation model with unified nucleic acid and protein language](https://www.nature.com/articles/s42256-025-01044-4)** - 2025, Nature Machine Intelligence
  - The language of biology, encoded in DNA, RNA and proteins, forms the foundation of life but remains challenging to decode owing to its complexity.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA/RNA/Protein（token embedding）→ masked token / region / taxonomy / structure prediction; Fine-tune: DNA (embedding) + Protein (embedding) → DNA-protein pair classification / Genus / ncRNA family / stability / subcellular location / antigenicity / PPI / ncRPI

  Build a unified foundation model, LucaOne, for nucleic acid and protein sequences to understand the central dogma and improve generalization in biological sequence tasks.

  </details>

- **[Generanno: A Genomic Foundation Model for Metagenomic Annotation](https://doi.org/10.1101/2025.06.04.656517)** - 2025, bioRxiv
  - This study introduces Generanno, a compact yet powerful genomic foundation model (GFM) specifically optimized for metagenomic annotation that achieves superior accuracy compared to traditional HMM-based methods and recent LLM-based approaches, while demonst...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA (single-nucleotide token) → masked base prediction; Fine-tune: DNA (single-nucleotide token) → CDS labeling/antibiotic resistance/gene class/taxonomy classification

  To build and optimize a single-nucleotide-resolution genomic foundation model for high-accuracy prokaryotic metagenomic annotation.

  </details>

- **[Genome modeling and design across all domains of life with Evo 2](http://biorxiv.org/lookup/doi/10.1101/2025.02.18.638918)** - 2025, bioRxiv
  - Evo 2, a biological foundation model trained on 9.3 trillion DNA base pairs from a highly curated genomic atlas spanning all domains of life, is introduced and it is revealed that Evo 2 autonomously learns a breadth of biological features, including exon-in...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (single-nucleotide tokens) → next nucleotide prediction; Fine-tune: DNA (embedding) → BRCA1 variant classification / exon labeling / chromatin accessibility

  To build a generalist biological foundation model capable of genome-scale prediction and generation across all domains of life, based solely on DNA sequence.

  </details>

- **[GenomeOcean: An Efficient Genome Foundation Model Trained on Large-Scale Metagenomic Assemblies](http://biorxiv.org/lookup/doi/10.1101/2025.01.30.635558)** - 2025, bioRxiv
  - A byte-pair encoding (BPE) tokenization strategy for genome sequence generation, alongside architectural optimizations, achieving up to 150× faster sequence generation while maintaining high biological fidelity sets a new benchmark for metagenomic research,...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (BPE tokenization) → Sequence embeddings / New DNA sequences (enabling full-length protein-coding genes and biosynthetic gene cluster generation)

  To develop a genome foundation model trained on large-scale metagenomic assemblies for efficient generation and understanding of microbial genomic sequences, with enhanced representation of rare biosphere species.

  </details>

- **[Genomic Language Models (gLMs) decode bacterial genomes for improved gene prediction and translation initiation site identification](https://doi.org/10.1093/bib/bbaf311)** - 2025, Briefings in Bioinformatics
  - GeneLM demonstrates the power of gLMs in decoding genetic information, achieving state-of-the-art performance in bacterial genome analysis and highlights the potential of language models to revolutionize genome annotation, outperforming conventional tools a...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA k-mer → masked k-mer prediction; Fine-tune: DNA (k-mer) → CDS/TIS classification

  To develop a BERT-based genomic language model to improve the prediction of bacterial coding sequences (CDS) and translation initiation sites (TIS).

  </details>

- **[HAD: Hybrid Architecture Distillation Outperforms Teacher in Genomic Sequence Modeling](http://arxiv.org/abs/2505.20836)** - 2025, arXiv
  - arXiv:2505.20836 \[cs\] TLDR: This work proposes a Hybrid Architecture Distillation (HAD) approach, leveraging both distillation and reconstruction tasks for more efficient and effective pre-training, and employs the NTv2-500M as the teacher model and devise...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (character-level tokenization) → visible nucleotide feature alignment; DNA (character-level tokenization) → masked nucleotide reconstruction; Fine-tune: DNA (character-level tokenization) → histone mark/enhancer/promoter/splice site prediction

  Enhance the performance of compact models in genomic sequence modeling via Hybrid Architecture Distillation (HAD) to surpass larger teacher models

  </details>

- **[HybProm: An attention-assisted hybrid CNN-BiLSTM model for the interpretable prediction of DNA promoter](https://linkinghub.elsevier.com/retrieve/pii/S1046202325000349)** - 2025, Methods
  - The HybProm model is proposed, which uses DNA2Vec to transform DNA sequences into low-dimensional vectors, followed by a CNN-BiLSTM-Attention architecture to extract features and predict promoters across species, including E.
  <details>
  <summary>Series description</summary>

  **Series:** DNA（DNA2Vec embedding）→ promoter label

  To predict DNA promoters across species using an attention-assisted hybrid CNN-BiLSTM model with improved accuracy and interpretability.

  </details>

- **[HybridKla: a hybrid deep learning framework for lactylation site prediction](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf375/8219060)** - 2025, Briefings in Bioinformatics
  - This work collected 23 984 Kla sites in 7297 proteins from the literature to construct the benchmark dataset and tailored a multi-feature hybrid system, which integrated eight complementary feature-encoding strategies derived from two automated encoders and...
  <details>
  <summary>Series description</summary>

  **Series:** Protein KSP(25,25) (ESM2 embedding + LSTM hidden state + ACF/AAINDEX/CKSAAP/GPS/OBC/PseAAC) → Kla site probability

  Develop a multi-feature hybrid system-based deep learning predictor (HybridKla) for precise identification of lysine lactylation (Kla) sites

  </details>

- **[HydraRNA: a hybrid architecture based full-length RNA language model](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03853-7)** - 2025, Genome Biology
  - HydraRNA is presented, which is based on a hybrid architecture of bidirectional state space model and multi-head attention mechanism, and is pre-trained on a large amount of both protein-coding and non-coding RNAs, and can accurately predict the effect of m...
  <details>
  <summary>Series description</summary>

  **Series:** RNA sequence (nucleotide token encoding) → masked nucleotide prediction

  To develop HydraRNA, a hybrid architecture-based full-length RNA language model, for handling full-length RNA sequences and enhancing performance across various RNA-related tasks.

  </details>

- **[Integrating Protein and DNA Embeddings for Improving Genome-Wide Transcription Factor Binding Site Prediction](http://biorxiv.org/lookup/doi/10.1101/2025.09.15.676319)** - 2025, bioRxiv
  - Transcription factors (TFs) regulate gene expression by binding to specific DNA sites on genome, making accurate TF binding site prediction critical for understanding gene regulation and downstream phenotypes.
  <details>
  <summary>Series description</summary>

  **Series:** DNA (one-hot) + TF protein embedding → Binding probability for a single transcription factor

  To achieve high-accuracy transcription factor binding site prediction and zero-shot prediction for unseen transcription factors by integrating protein embeddings (TF sequence and structural information) and DNA sequence embeddings via a cross-attention mechanism.

  </details>

- **[Interpretation of RNA Universe and Coding Potential Using IntRNA](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202509518)** - 2025, Advanced Science
  - The interpretation of RNA universe and coding potential are long-standing issues in modern RNA studies, and three crucial questions remain unanswered: a) how to detect and interpret the coding potential of RNA, b) how to annotate the sophisticated taxonomy...
  <details>
  <summary>Series description</summary>

  **Series:** RNA sequence (1477-dimensional G/D features) → mRNA/ncRNA probability / sncRNA category probability / circular-linear lncRNA probability

  Develop a multi-channel deep learning framework, IntRNA, to simultaneously address three key challenges in RNA universe annotation: detecting RNA coding potential, annotating the sophisticated taxonomy of sncRNAs, and distinguishing circular from linear lncRNAs.

  </details>

- **[Introducing a foundational sequence transformer for range adaptive nucleotide decoding (STRAND)](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf618/8341161)** - 2025, Briefings in Bioinformatics
  - The advent of high-throughput sequencing has led to an exponential increase in genomic data, highlighting the need for efficient and accurate models to analyze and interpret this information.
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (tokenized encoding) → nucleotide prediction / variant pathogenicity probability / rheumatoid arthritis status

  To develop an exomic foundational model based on a short-range transformer architecture, leveraging the human reference genome and multispecies data to improve variant detection and interpretation.

  </details>

- **[JanusDNA: A Powerful Bi-directional Hybrid DNA Foundation Model](https://arxiv.org/abs/2505.17257)** - 2025, arXiv
  - Version Number: 4 TLDR: JanusDNA is the first bidirectional DNA foundation model built upon a novel pretraining paradigm that combines the optimization efficiency of autoregressive modeling with the bidirectional comprehension of masked modeling, and adopts...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA single-nucleotide sequence → Bidirectional context reconstruction loss (Janus modeling objective) ;Fine-tune: DNA single-nucleotide sequence → Regulatory element/histone marker/splice site/eQTL probability

  To develop a bidirectional efficient DNA foundation model (JanusDNA) that addresses long-range dependency modeling by integrating the optimization efficiency of autoregressive modeling with the bidirectional comprehension capability of masked modeling.

  </details>

- **[LOL-EVE: Predicting Promoter Variant Effects from Evolutionary Sequences](http://biorxiv.org/lookup/doi/10.1101/2024.11.11.623015)** - 2025, ICLR
  - LOL-EVE (Language of Life across EVolutionary Effects), a conditional autoregressive transformer model trained on 14.6 million diverse mammalian promoter sequences, is presented, demonstrating the potential of region-specific large genomic language models a...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（token） → masked base prediction; Fine-tune: DNA（token） → SNV effect (log-likelihood delta)

  This study develops the LOL-EVE model to predict the regulatory effects of human promoter variants from cross-species evolutionary promoter sequences.

  </details>

- **[LassoESM a tailored language model for enhanced lasso peptide property prediction](https://www.nature.com/articles/s41467-025-63412-3)** - 2025, Nature Communications
  - LassoESM embeddings enable accurate prediction of substrate compatibility, facilitate identification of novel non-cognate cyclase-substrate pairs, and enhance prediction of RNA polymerase inhibitory activity, a biological activity of several known lasso pep...
  <details>
  <summary>Series description</summary>

  **Series:** Lasso peptide core sequence (LassoESM embedding) → Substrate/non-substrate probability;Lasso peptide variant sequence (LassoESM embedding) → RNAP inhibitory enrichment value;Cyclase sequence (VanillaESM embedding) + Lasso peptide sequence (LassoESM embedding) → Compatible/incompatible probability

  To develop a lasso peptide-specific language model (LassoESM) via domain-adaptive pretraining, enhancing prediction accuracy for substrate compatibility, cyclase-substrate pairing, and RNA polymerase inhibitory activity.

  </details>

- **[MCAMEF-BERT: an efficient deep learning method for RNA N7-methylguanosine site prediction via multi-branch feature integration](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf447/8245190)** - 2025, Briefings in Bioinformatics
  - This model adopts a parallel architecture that integrates both a DNABERT-2-2-based pretrained model branch and multiple traditional feature encoding branches, enabling comprehensive multi-perspective sequence feature extraction and validate the interpretabi...
  <details>
  <summary>Series description</summary>

  **Series:** RNA sequence (201 bp, One-hot/ENAC/EIIP/NCP encoded) → m7G modification site probability

  To develop a deep learning method named MCAMEF-BERT that integrates the pretrained model DNABERT-2 with multiple traditional feature encoding strategies and a multi-channel attention mechanism for accurate prediction of RNA N7-methylguanosine (m7G) modification sites.

  </details>

- **[METAGENE-1: Metagenomic Foundation Model for Pandemic Monitoring](http://arxiv.org/abs/2501.02045)** - 2025, arXiv
  - arXiv:2501.02045 \[q-bio\] TLDR: The performance of METAGENE-1 is demonstrated, which achieves state-of-the-art results on a set of genomic benchmarks and new evaluations focused on human-pathogen detection and genomic sequence embedding, showcasing its poten...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA/RNA（BPE）→ next BPE token; Fine-tune: DNA（BPE）→ pathogen class / embedding / epigenetic label / anomaly score

  To train a large-scale foundation model on diverse wastewater metagenomic sequences for supporting pathogen monitoring and surveillance tasks.

  </details>

- **[MergeDNA: Context-aware Genome Modeling with Dynamic Tokenization through Token Merging](http://arxiv.org/abs/2511.14806)** - 2025, arXiv
  - arXiv:2511.14806 \[q-bio\]
  <details>
  <summary>Series description</summary>

  **Series:** DNA nucleotide sequence → Reconstructed DNA nucleotide sequence (via dynamic tokenization and hierarchical context modeling)

  This paper aims to address the core challenges of uneven genomic information density and the lack of well-defined vocabulary units by introducing a hierarchical architecture that jointly optimizes a dynamic genomic tokenizer and latent Transformers with context-aware pre-training tasks.

  </details>

- **[Methyl-GP: accurate generic DNA methylation prediction based on a language model and representation learning](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf223/8099202)** - 2025, Nucleic Acids Research
  - It is found that the conservation of sequence patterns among different species contributes to enhancing the generalizability of the model, and fine-tuning a language model on a dataset comprising multiple species with similar sequence patterns shows satisfa...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (k-mer) → masked k-mer prediction; Fine-tune: DNA (k-mer) → 4mC/5hmC/6mA label

  To develop a general model that accurately predicts three types of DNA methylation (4mC, 5hmC, and 6mA) from DNA sequences.

  </details>

- **[MotifAE Reveals Functional Motifs from Protein Language Model: Unsupervised Discovery and Interpretability Analysis](http://biorxiv.org/lookup/doi/10.1101/2025.11.04.686576)** - 2025, bioRxiv
  - MotifAE provides an unsupervised framework for discovering functional motifs from the protein language model ESM2, which captures evolutionary-scale sequence regularities and has the potential to advance protein function analysis, mutation effect interpreta...
  <details>
  <summary>Series description</summary>

  **Series:** ESM2 protein embeddings → Reconstructed embeddings + Sparse latent features

  To develop an unsupervised framework, MotifAE, for extracting interpretable functional motifs from protein language models (ESM2), systematically analyze their biological significance, and apply them to protein engineering.

  </details>

- **[Multi-megabase scale genome interpretation with genetic language models](http://arxiv.org/abs/2501.07737)** - 2025, arXiv
  - arXiv:2501.07737 \[q-bio\] TLDR: Phenformer is presented, a multi-scale genetic language model that learns to generate mechanistic hypotheses as to how differences in genome sequence lead to disease-relevant changes in expression across cell types and tissues...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (one-hot) → expression/chromatin tracks (Enformer); Fine-tune: DNA (Enformer embedding) → disease risk

  Predict individual disease risk directly from DNA sequence and generate multi-scale mechanistic hypotheses.

  </details>

- **[MutBERT: Probabilistic Genome Representation Improves Genomics Foundation Models](http://biorxiv.org/lookup/doi/10.1101/2025.01.23.634452)** - 2025, bioRxiv
  - MutBERT is presented, a probabilistic genome-based masked language model that efficiently utilizes SNP information from population-scale genomic data and enables better utilization of biobank-scale genomic data in building pretrained genomic foundation models.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (probabilistic matrix) → masked base probability; Fine-tune: DNA (probabilistic matrix) → TFBS / epigenetic / splice / eQTL label

  To enhance genomic foundation models' ability to capture human variation by introducing a probabilistic genome representation based on allele frequencies from population-scale data.

  </details>

- **[NucEL: Single-Nucleotide ELECTRA-Style Genomic Pre-training for Efficient and Interpretable Representations](http://biorxiv.org/lookup/doi/10.1101/2025.08.17.670700)** - 2025, bioRxiv
  - Pre-training large language models on genomic sequences has become a powerful approach for learning biologically meaningful representations.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (single-nucleotide token) → token replacement detection; Fine-tune: DNA (single-nucleotide) → TF binding / promoter / enhancer / epigenetic mark / open chromatin prediction

  Develop the first ELECTRA-style genomic pre-training framework (NucEL) using single-nucleotide tokenization and Replaced Token Detection (RTD) to achieve efficient and interpretable sequence representations.

  </details>

- **[Omni-DNA: A Unified Genomic Foundation Model for Cross-Modal and Multi-Task Learning](https://arxiv.org/abs/2502.03499)** - 2025, arXiv
  - Version Number: 1 TLDR: Omni-DNA, a family of cross-modal multi-task models ranging from 20 million to 1 billion parameters, is introduced and two complex genomic tasks, DNA2Function and Needle-in-DNA, are designed, indicating Omni-DNA's cross-modal capabil...
  <details>
  <summary>Series description</summary>

  **Series:** Pretraining: DNA sequence (BPE token) → next token prediction; Finetuning (Conventional): DNA sequence (BPE token) + task instruction → histone/promoter/enhancer label; Finetuning (DNA2Func): DNA sequence (BPE token) + "What is the function?" → natural language functional description; Finetuning (DNA2Image): DNA sequence (BPE token) + "map to image" → handwritten digit image (VQ-VAE token)

  To develop a unified cross-modal multi-task genomic foundation model (GFM) that simultaneously addresses conventional genomic classification tasks and novel cross-modal tasks (e.g., DNA to functional descriptions/images) through a single finetuning step, overcoming the limitation of existing GFMs requiring separate finetuning for each downstream task.

  </details>

- **[Omnireg-gpt: a high-efficiency foundation model for comprehensive genomic sequence understanding](https://www.nature.com/articles/s41467-025-65066-7)** - 2025, Nature Communications
  - OmniReg-GPT, a generative foundation model designed for the low-resource pretraining of long genomic sequences by optimized attention mechanism, is introduced with a hybrid local-global attention architecture, enabling efficient analysis of multi-scale regu...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Human DNA sequence (20kb, BPE tokenization) → Next-token prediction (model optimization objective); Fine-tune: Human DNA sequence (variable length, BPE tokenization / OmniReg-GPT embedding) → cis-regulatory element probability / gene expression level / single-cell chromatin accessibility state / Hi-C contact frequency matrix / enhancer activity score.

  To develop a high-efficiency generative foundation model named OmniReg-GPT for low-resource pretraining of long genomic sequences, enabling multi-scale understanding and predictive capabilities for genomic regulatory sequences.

  </details>

- **[PLM-interact: extending protein language models to predict protein-protein interactions](https://www.nature.com/articles/s41467-025-64512-w)** - 2025, Nature Communications
  - A sequence-based model that jointly encodes protein pairs, achieving state-of-the-art cross-species and virus-host PPI prediction and mutation effects analysis and demonstrates that large language models can be extended to learn the intricate relationships...
  <details>
  <summary>Series description</summary>

  **Series:** Predict Protein-Protein Interaction (Main task): ProteinA amino acid sequence (ESM-2 encoding) + ProteinB amino acid sequence (ESM-2 encoding) (Format: [CLS, Protein1 sequence, EOS, Protein2 sequence, EOS]) → ProteinA &amp; ProteinB interaction probability (0-1)

  To extend a pre-trained protein language model (ESM-2) by jointly encoding protein pairs and employing a next-sentence prediction task analogous to natural language processing, enabling it to predict protein-protein interactions (PPIs), mutation effects on interactions, and virus-host protein interactions directly from amino acid sequences.

  </details>

- **[PTM-Mamba: a PTM-aware protein language model with bidirectional gated Mamba blocks](https://doi.org/10.1038/s41592-025-02656-9)** - 2025, Nature Methods
  - PTM-Mamba is developed, a PTM-aware protein LM that integrates PTM tokens using bidirectional Mamba blocks fused with ESM-2 protein LM embeddings via a newly developed gating mechanism, establishing PTM-Mamba as a foundational tool for PTM-aware protein mod...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein (wild-type + PTM tokens) → masked token prediction; Fine-tune: Protein (PTM tokenized) → disease/druggability/PPI label

  Develop a protein language model capable of modeling both wild-type and PTM-modified protein sequences to support downstream PTM-related tasks.

  </details>

- **[PhosF3C: a feature fusion architecture with fine-tuned protein language model and conformer for prediction of general phosphorylation site](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf242/8151288)** - 2025, Briefings in Bioinformatics
  - Low-Rank Adaptation (LoRA) fine-tuning is applied to ESM2, a powerful protein large language model to efficiently extract features with minimal computational resources, optimizing task-specific text alignment and improving prediction accuracy.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein (ESM2 embedding) → task-aligned feature representation; Fine-tune: Protein (LoRA-tuned ESM2) → phosphorylation site label (+1/−1)

  To accurately and efficiently predict general protein phosphorylation sites by integrating a LoRA-fine-tuned protein language model and a conformer architecture.

  </details>

- **[Pre-training Genomic Language Model with Variants for Better Modeling Functional Genomics](https://doi.org/10.1101/2025.02.26.640468)** - 2025, bioRxiv
  - It is demonstrated that UKBioBERT generates informative embeddings capable of identifying gene functions, and improving gene expression prediction in cell lines, thereby enhancing the understanding of gene expression predictability and underscore the value...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（k-mer）→ masked k-mer prediction; Fine-tune: DNA（one-hot）+ UKBioBERT embedding → gene expression

  To develop and pre-train a DNA language model, UKBioBERT, incorporating UK BioBank variants, for enhancing functional genomics modeling and individualized gene expression prediction.

  </details>

- **[Predicting differentially methylated cytosines in TET and DNMT3 knockout mutants via a large language model](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf092/8074756)** - 2025, Briefings in Bioinformatics
  - L-MAP, a transformer-based large language model that is trained on DNMT3-knockout and TET-knockout data in human and mouse embryonic stem cells, enables the identification of sequence motifs associated with the enzymatic activity of DNMT3 and TET, which inc...
  <details>
  <summary>Series description</summary>

  **Series:** DNA (DNABERT embedding) → DMC label

  To predict differentially methylated cytosines (DMCs) in TET or DNMT3 knockout mutants using the surrounding DNA sequence.

  </details>

- **[Predicting functional constraints across evolutionary timescales with phylogeny-informed genomic language models](http://biorxiv.org/lookup/doi/10.1101/2025.09.21.677619)** - 2025, bioRxiv
  - GPN-Star is introduced, a biologically grounded gLM featuring a phylogeny-aware architecture that leverages whole-genome alignments and species trees to model evolutionary relationships explicitly and is positioned as a scalable, powerful, and flexible new...
  <details>
  <summary>Series description</summary>

  **Series:** Multispecies whole-genome alignment (integer encoding) and species tree → Per-nucleotide variant constraint probabilities or effect scores

  To introduce GPN-Star, a phylogeny-aware genomic language model leveraging species trees and multispecies whole-genome alignments, for predicting the effects of genetic variants in coding and non-coding regions of the human genome.

  </details>

- **[Predicting protein-protein interactions in the human proteome](https://www.science.org/doi/10.1126/science.adt1630)** - 2025, Science
  - This work systematically screened 200 million human protein pairs and predicted 17,849 interactions with an expected precision of 90%, of which 3,631 interactions were not identified in previous experimental screens.
  <details>
  <summary>Series description</summary>

  **Series:** Protein sequence pairs (omicMSA encoding) → Interaction probability (RFIntProb/AFIntProb)

  To systematically identify the human protein-protein interactome by enhancing coevolutionary signals (omicMSA) and developing a novel deep learning network (RF2-PPI), providing high-precision 3D structural models.

  </details>

- **[Predicting the Evolutionary and Functional Landscapes of Viruses with a Unified Nucleotide-Protein Language Model: LucaVirus](https://doi.org/10.1101/2025.06.14.659722)** - 2025, bioRxiv
  - The power of a unified foundation model to comprehensively decode the viral world is demonstrated, with LucaVirus, a unified, multi-modal foundation model specifically designed for viruses, offering an efficient and versatile platform for board applications...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA/protein (token) → masked token prediction + taxonomy/domain/function label; Fine-tune: DNA/protein (token) → RdRP/Capsid / EC number / fitness score / binding label

  To develop a unified nucleotide-protein language model, LucaVirus, for predicting viral evolutionary and functional properties.

  </details>

- **[PromoterAtlas: decoding regulatory sequences across Gammaproteobacteria using a transformer model](https://doi.org/10.1101/2025.07.11.664312)** - 2025, bioRxiv
  - Recent advances in deep learning, particularly transformer architectures, have improved computational approaches for biological sequence analysis.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA（one-hot） → masked nucleotide prediction；Fine-tune: DNA（PromoterAtlas embedding） → promoter segmentation / expression level (transcription &amp; translation)

  To build a transformer model, PromoterAtlas, that identifies and annotates promoters and regulatory elements from Gammaproteobacterial genomes and predicts gene expression levels.

  </details>

- **[ProtRNA: A protein-derived RNA language model by cross-modality transfer learning](https://linkinghub.elsevier.com/retrieve/pii/S2405471225002042)** - 2025, Cell Systems
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: RNA sequences (single-nucleotide token) → masked nucleotide prediction; Fine-tune: RNA sequences (single-nucleotide token) → secondary structure contact map / RBP-binding probability / mean ribosome loading

  To adapt the protein language model ESM-2 for RNA sequence modeling via cross-modality transfer learning, addressing RNA data scarcity and achieving efficient performance in multiple downstream tasks.

  </details>

- **[Protein Set Transformer: a protein-based genome language model to power high-diversity viromics](https://www.nature.com/articles/s41467-025-66049-4)** - 2025, Nature Communications
  - Exponential increases in microbial and viral genomic data demand transformational advances in scalable, generalizable frameworks for their interpretation.
  <details>
  <summary>Series description</summary>

  **Series:** Protein sequences (ESM2 embeddings) → Genome embeddings + Contextualized protein embeddings

  To develop a protein-based genome language model (Protein Set Transformer, PST) that learns representations of viral genomes via self-supervised learning to power various viromics tasks such as virus identification, taxonomy, and host prediction

  </details>

- **[ProteomeLM: A proteome-scale language model allowing fast prediction of protein-protein interactions and gene essentiality across taxa](https://doi.org/10.1101/2025.08.01.668221)** - 2025, bioRxiv
  - Language models starting from biological sequence data are advancing many inference problems, both at the scale of single proteins, and at the scale of genomic neighborhoods.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein sequences (ESM-C embedding + OrthoDB functional encoding) → masked protein embedding reconstruction; PPI Prediction: ProteomeLM embeddings + attention coefficients → PPI probability; Essentiality: ProteomeLM embeddings → essentiality probability

  Develop a transformer-based proteome-scale language model (ProteomeLM) that learns protein dependencies through whole-proteome context for fast cross-taxa protein-protein interaction and gene essentiality prediction.

  </details>

- **[RESM: Capturing sequence and structure encoding of RNAs by 2 mapped transfer learning from ESM (evolutionary scale modeling) 3 protein language model](https://doi.org/10.1101/2025.08.09.669469)** - 2025, bioRxiv
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: RNA (AUCG→KDNY mapping) → masked pseudo-protein prediction; Zero-shot: RNA (mapped) → attention maps → base-pair probability; Supervised: RNA (one-hot) + attention maps → secondary structure / siRNA efficacy / ribosome loading

  To adapt protein language models (ESM-2) to RNA via mapped transfer learning, building RESM for unified prediction of RNA secondary structures, functional classes, and regulatory functions.

  </details>

- **[RNA-xLSTM: Evaluating xLSTM as an Alternative Foundation to Transformers in RNA Modeling](https://doi.org/10.1101/2025.07.14.664653)** - 2025, bioRxiv
  - Transformer-based architectures currently achieve state-of-the-art performance across a wide range of domains, including biological sequence modeling.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: RNA (token embedding) → masked token prediction; Fine-tune-1: RNA (token embedding) → base-pair probability matrix; Fine-tune-2: RNA (token embedding) → splice site classification

  To evaluate the performance of the xLSTM architecture in RNA modeling and compare it against existing transformer-based models RNA-FM and RiNALMo.

  </details>

- **[RNALens: Study on 5' UTR Modeling and Cell-Specificity](https://doi.org/10.1101/2025.07.20.665722)** - 2025, bioRxiv
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Genomic sequences (BPE) → masked nucleotides prediction; 5' UTR sequences (BPE) → masked nucleotides + secondary structure + min free energy; Fine-tune: 5' UTR (fixed length 100 nt, BPE) → EL / TE prediction

  Predict mRNA 5' UTR sequence expression level and translation efficiency in specific cell types.

  </details>

- **[RiNALMo: general-purpose RNA language models can generalize well on structure prediction tasks](https://doi.org/10.1038/s41467-025-60872-5)** - 2025, Nature Communications
  - RiNALMo is the largest RNA language model to date, with 650M parameters pre-trained on 36M non-coding RNA sequences from several databases, and shows that its generalization capabilities overcome the inability of other deep learning methods for secondary st...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: RNA (single-nucleotide token) → masked base prediction Fine-tune: RNA (single-nucleotide token) → secondary structure / splice site / ncRNA family / MRL / TE / EL

  To pre-train a large-scale general-purpose RNA language model that extracts structural information from non-coding RNA sequences and generalizes well across various downstream tasks.

  </details>

- **[Scaling Unlocks Broader Generation and Deeper Functional Understanding of Proteins](http://biorxiv.org/lookup/doi/10.1101/2025.04.15.649055)** - 2025, bioRxiv
  - The ProGen3 family of sparse generative PLMs are introduced, compute-optimal scaling laws to scale up to a 46B-parameter model pre-trained on 1.5T amino acid tokens are developed, and it is found both computationally and experimentally that larger models ar...
  <details>
  <summary>Series description</summary>

  **Series:** Unconditional Generation: Amino acid sequence (natural distribution) → Protein sequence (diverse generation) Infilling: Protein sequence (partially masked) → Masked region sequence (infilled) Prediction after Alignment: Amino acid sequence → Protein fitness score (e.g., stability ΔG)

  To establish compute-optimal scaling laws, train large-scale sparse protein language models (ProGen3), investigate the impact of model scale on the diversity, in vitro expression, and functional prediction capabilities of generated proteins, and validate the effectiveness of model alignment strategies.

  </details>

- **[SetBERT: the deep learning platform for contextualized embeddings and explainable predictions from high-throughput sequencing](https://doi.org/10.1093/bioinformatics/btaf370)** - 2025, Bioinformatics
  - SetBERT is presented, a robust pre-training methodology for creating generalized deep learning models for processing HTS data to produce contextualized embeddings and be fine-tuned for downstream tasks with explainable predictions.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA (DNABERT embedding) → masked taxa abundance; Fine-tune: DNA (DNABERT embedding) → sample label / taxonomy probability

  Develop a deep learning platform (SetBERT) that captures sequence interactions in high-throughput sequencing data to produce contextual embeddings and support explainable predictions.

  </details>

- **[Simulating 500 million years of evolution with a language model](https://www.science.org/doi/10.1126/science.ads0018)** - 2025, Science
  - It is shown that language models trained at scale on evolutionary data can generate functional proteins that are far away from known proteins, and ESM3, a frontier multimodal generative language model that reasons over the sequence, structure, and function...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein (sequence tokens + structure tokens + function tokens) → masked token prediction; Fine-tune: Protein backbone (coordinates + amino acids) → optimized protein sequence

  Develop a multimodal language model (ESM3) capable of modeling protein evolution across sequence, structure, and function, and generating novel functional proteins distant from natural ones via prompting.

  </details>

- **[Spliformer-v2 predicts multi-tissue RNA splicing and reveals functional genomic links with neurodegenerative diseases](https://doi.org/10.1101/2025.06.28.662167)** - 2025, bioRxiv
  - Deep learning model Spliformer-v2 is introduced, a deep learning model based on SegmentNT architecture to predict multi-tissue RNA splicing across the most comprehensive set of human brain and spinal cord tissues to date, thereby advancing the discovery of...
  <details>
  <summary>Series description</summary>

  **Series:** DNA (SegmentNT embedding) × 2 alleles → donor/acceptor site usage (continuous)

  Predict RNA splicing usage across multiple human tissues from genomic sequences using a deep learning model and identify disease-associated splicing variants.

  </details>

- **[Systems and Algorithms for Convolutional Multi-Hybrid Language Models at Scale](http://arxiv.org/abs/2503.01868)** - 2025, arXiv
  - arXiv:2503.01868 \[cs\]
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (byte-tokenized) → masked token prediction; Fine-tune/Extension: DNA (PI/ABF) → token probability distribution

  Propose a multi-hybrid convolutional architecture, StripedHyena 2, which combines diverse input-dependent convolution operators to significantly improve training efficiency of large-scale language models without compromising accuracy.

  </details>

- **[TRAFICA: An Open Chromatin Language Model to Improve Transcription Factor Binding Affinity Prediction](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaf469/8240329)** - 2025, Bioinformatics
  - Motivation In silico transcription factor and DNA (TF-DNA) binding affinity prediction plays a vital role in examining TF binding preferences and understanding gene regulation.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Open chromatin DNA (k-mer/BPE) → Masked token prediction; Fine-tune: DNA sequence (k-mer/one-hot) → TF-DNA binding affinity (continuous)

  Develop a language model integrating sequence features from open chromatin regions (via ATAC-seq) and in vitro TF-DNA binding profiles (from PBM/HT-SELEX) to improve transcription factor-DNA binding affinity prediction.

  </details>

- **[Toward high-efficiency, low-resource, and explainable neuropeptide prediction with MSKDNP](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf466/8250822)** - 2025, Briefings in Bioinformatics
  - MSKDNP, a neuropeptide prediction model based on a multi-stage knowledge distillation framework, attains performance comparable to a fully fine-tuned protein language model while achieving state-of-the-art results in neuropeptide recognition.
  <details>
  <summary>Series description</summary>

  **Series:** Amino acid sequence (ESM-tokenized) → Neuropeptide probability/classification

  To develop a high-efficiency, low-resource, and explainable neuropeptide prediction model (MSKDNP) based on a multi-stage knowledge distillation framework to overcome the high computational cost, slow processing speed, and deployment difficulties of existing methods.

  </details>

- **[TransBind allows precise detection of DNA-binding proteins and residues using language models and deep learning](https://www.nature.com/articles/s42003-025-07534-w)** - 2025, Communications Biology
  - This work introduces TransBind, an alignment-free deep learning framework that predicts DNA-binding proteins and residues directly from a single primary sequence, eliminating the need for MSAs.
  <details>
  <summary>Series description</summary>

  **Series:** Protein（ProtT5 embedding）→ DNA-binding residue label / DNA-binding protein label

  Propose TransBind to predict DNA-binding proteins and binding residues directly from primary amino acid sequences without relying on MSA or structural information.

  </details>

- **[TrinityDNA: A Bio-Inspired Foundational Model for Efficient Long-Sequence DNA Modeling](http://arxiv.org/abs/2507.19229)** - 2025, arXiv
  - arXiv:2507.19229 \[cs\]
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (char-level token) → masked nucleotide prediction; Fine-tune: DNA (char-level token) → promoter/TFBS/splice site/CDS annotation probability

  To design a bio-inspired DNA foundational model (TrinityDNA) that efficiently captures local and global dependencies in long DNA sequences by integrating structural feature modeling (Groove Fusion), reverse-complement symmetry handling (GRC), and multi-scale attention mechanisms (SMWA).

  </details>

- **[UNICORN: Towards universal cellular expression prediction with a multi-task learning framework](https://www.nature.com/articles/s41467-025-64506-8)** - 2025, Nature Communications
  - It is demonstrated that UNICORN outperforms the existing methods in both gene expression prediction and multiomic phenotype prediction at the cellular level and the cell-type level, and it can also generate uncertainty scores of the predictions.
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (Enformer/HyenaDNA embedding) → Single-cell/Cell-type gene expression level; DNA sequence (Enformer embedding) + Amino acid sequence (ESM2 embedding) → Cell-type protein expression level; DNA sequence (Enformer embedding) → ATAC peak intensity Gene embeddings (Pre-trained models) → LossPred uncertainty score

  To develop a multi-task learning framework (UNICORN) that leverages embeddings from pre-trained models to predict multi-omic expression levels at single-cell or cell-type resolution and quantify predictive uncertainty for enhanced interpretability.

  </details>

- **[VariantFormer: A hierarchical transformer integrating DNA sequences with genetic variations and regulatory landscapes for personalized gene expression prediction](http://biorxiv.org/lookup/doi/10.1101/2025.10.31.685862)** - 2025, bioRxiv
  - VariantFormer is presented, a 1.2-billion-parameter transformer that predicts gene-level RNA abundance directly from personalized diploid genomes and established as a scalable, diploid-aware framework for variant interpretation and personalized gene express...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (with IUPAC ambiguity codes embedding variants) + tissue context → Personalized gene expression prediction (tissue-specific RNA abundance)

  To predict gene-level RNA abundance directly from personalized diploid genomes for interpreting genetic variation expression regulation across tissues, individuals, and ancestries.

  </details>

- **[YModPred: an interpretable prediction method for multi-type RNA modification sites in S. cerevisiae based on deep learning](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-025-02372-y)** - 2025, BMC Biology
  - A novel deep learning model, YModPred, is proposed, which accurately predicts multiple types of RNA modification sites in S.
  <details>
  <summary>Series description</summary>

  **Series:** RNA sequence (length 601nt, embedding encoding) → Central site modification probability

  To develop an interpretable deep learning model (YModPred) for accurately predicting ten types of RNA post-transcriptional modification sites in Saccharomyces cerevisiae (S. cerevisiae).

  </details>

- **[eccDNAMamba: A Pre-Trained Model for Ultra-Long eccDNA Sequence Analysis](http://arxiv.org/abs/2506.18940)** - 2025, arXiv
  - arXiv:2506.18940 \[q-bio\]
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA（BPE）→ masked span prediction; Fine-tune: DNA（BPE）→ cancer/healthy / real/pseudo classification

  To develop a pre-trained model, eccDNAMamba, for efficient structural and functional modeling of ultra-long circular DNA (eccDNA) sequences.

  </details>

- **[iPro-MP: a BERT-based model to predict multiple prokaryotic promoters](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03819-9)** - 2025, Genome Biology
  - iPro-MP, a transformer-based prokaryotic promoter prediction framework that uses a multi-head attention mechanism to capture textual information in DNA sequences and effectively learns the hidden patterns, provides the superiority to other existing tools, e...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (6-mer tokenization) → promoter/non-promoter probability

  To develop a DNABERT-based model iPro-MP for accurately predicting promoters across multiple prokaryotic species, with enhanced performance for non-model organisms.

  </details>

- **[mRNA-LM: full-length integrated SLM for mRNA analysis](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf044/7997216)** - 2025, Nucleic Acids Research
  - The success of SARS-CoV-2 (severe acute respiratory syndrome coronavirus 2) messenger RNA (mRNA) vaccine has led to increased interest in the design and use of mRNA for vaccines and therapeutics.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: 5′ UTR（nucleotide）/CDS（codon）/3′ UTR（nucleotide）→ masked token prediction; Fine-tune: mRNA（5′ UTR+CDS+3′ UTR embeddings）→ stability/translation rate/transcript or protein expression

  To build an integrated small language model that jointly models 5′ UTR, CDS, and 3′ UTR regions of full-length mRNA to improve prediction of sequence-related properties such as stability and translation efficiency.

  </details>

- **[resLens: genomic language models to enhance antibiotic resistance gene detection](https://doi.org/10.1101/2025.07.08.663767)** - 2025, bioRxiv
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（masked token embedding）→ masked base prediction; Fine-tune: DNA（gLM embedding）→ ARG binary label / ARG class label

  Fine-tune genomic language models (gLMs) to improve antibiotic resistance gene (ARG) detection, particularly in scenarios with low sequence homology or novel resistance mechanisms.

  </details>

- **[seqLens: optimizing language models for genomic predictions](http://biorxiv.org/lookup/doi/10.1101/2025.03.12.642848)** - 2025, bioRxiv
  - Key innovations in DNA sequence modeling are investigated, treating DNA as a language and applying language models to genomic data, and seqLens, a family of models based on disentangled attention with relative positional encoding, outperforms state-of-the-a...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (BPE) → masked token prediction; Fine-tune: DNA (BPE) → genomic class/feature label

  To construct and optimize the general-purpose DNA language model seqLens for enhanced performance and generalization across diverse genomic prediction tasks.

  </details>

- **[xTrimoPGLM: unified 100-billion-parameter pretrained transformer for deciphering the language of proteins](https://doi.org/10.1038/s41592-025-02636-z)** - 2025, Nature Methods
  - This work proposes a unified protein language model, xTrimoPGLM, to address protein understanding and generation tasks simultaneously through an innovative pretraining framework, leading to an advanced three-dimensional structural prediction model that surp...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein sequence (token embedding + [MASK]/[gMASK]/[sMASK]) → masked token prediction / next token generation; Fine-tune: Protein sequence (embedding) → structure/function/developability property

  To build a unified, large-scale protein language model capable of both protein understanding and generation tasks simultaneously.

  </details>

- **[A 5′ UTR language model for decoding untranslated regions of mRNA and function predictions](https://www.nature.com/articles/s42256-024-00823-9)** - 2024, Nature Machine Intelligence
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: RNA embedding → masked nucleotide/SS/MFE prediction; Fine-tune: RNA embedding → MRL/TE/EL/IRES

  This study developed a 5′ UTR language model (UTR-LM) to decode mRNA 5′ untranslated regions and predict their regulatory functions.

  </details>

- **[A Suite of Foundation Models Captures the Contextual Interplay Between Codons](https://doi.org/10.1101/2024.10.10.617568)** - 2024, bioRxiv
  <details>
  <summary>Series description</summary>

  **Series:** DNA (codon tokenizer) → codon probability distribution

  To develop EnCodon and DeCodon models that learn the contextual interplay of synonymous codons, capturing their influence on protein function and expression within coding sequences.

  </details>

- **[A foundation language model to decipher diverse regulation of RNAs](http://biorxiv.org/lookup/doi/10.1101/2024.10.12.617732)** - 2024, bioRxiv
  - LAMAR, a transformer-based foundation language model for RNA regulation, is developed, indicating that a single foundation language model is applicable in the comprehensive analysis of different aspects of RNA regulation, providing new insight into the desi...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: RNA (tokenized) → masked token prediction; Fine-tune: RNA (tokenized) → splice site / translation efficiency / half-life / IRES activity

  To construct and pretrain a foundational RNA language model for unified analysis of multi-layer RNA regulatory mechanisms including splicing, translation, stability, and IRES-mediated translation.

  </details>

- **[Accurate and General DNA Representations Emerge from Genome Foundation Models at Scale](http://biorxiv.org/lookup/doi/10.1101/2024.12.01.625444)** - 2024, NIPS
  - AIDO.DNA, a pretrained module for DNA representation in an AI-driven Digital Organism, shows substantial improvements across a breadth of supervised, generative, and zero-shot tasks relevant to functional genomics, synthetic biology, and drug development.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (character embedding) → masked nucleotide prediction; Fine-tune: DNA (character embedding) → classification/regression/sequence generation

  To develop AIDO.DNA, a seven-billion-parameter DNA language model pretrained on genomes from 796 species for diverse genomic tasks.

  </details>

- **[Caduceus: Bi-Directional Equivariant Long-Range DNA Sequence Modeling](https://doi.org/10.48550/arXiv.2403.03234)** - 2024, ICML
  - Large-scale sequence modeling has sparked rapid advances that now extend into biology and genomics.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（one-hot） → masked base prediction; Fine-tune: DNA（one-hot） → variant effect probability

  Develop the first long-range DNA language model architecture that jointly incorporates bidirectionality and reverse complement (RC) equivariance to improve genomic modeling tasks.

  </details>

- **[CodonBERT large language model for mRNA vaccines](http://genome.cshlp.org/lookup/doi/10.1101/gr.278870.123)** - 2024, Genome Research
  - CodonBERT, a large language model (LLM) for mRNAs, which outperforms previous mRNA prediction methods, including on a new flu vaccine data set and can be extended to perform prediction tasks for various mRNA properties.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: RNA (codon embedding) → masked codon prediction + sequence taxonomy; Fine-tune: RNA (codon embedding) → expression/stability/classification

  To develop CodonBERT, a model leveraging codon-based representation learning to improve mRNA sequence prediction of expression, stability, and vaccine design properties.

  </details>

- **[CodonBERT: a BERT-based architecture tailored for codon optimization using the cross-attention mechanism](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btae330/7681883)** - 2024, Bioinformatics
  - The result showed that CodonBERT can effectively capture the long-term dependencies between codons and amino acids, suggesting that it can be used as a customized training framework for specific optimization targets.
  <details>
  <summary>Series description</summary>

  **Series:** Train: Protein (tokenized) + Codon (tokenized) → Codon prediction; Inference: Protein (tokenized) → Codon (optimized)

  CodonBERT aims to perform customized codon optimization by translating protein sequences into optimized mRNA codon sequences to improve expression and stability.

  </details>

- **[Convolutions are competitive with transformers for protein sequence pretraining](https://linkinghub.elsevier.com/retrieve/pii/S2405471224000292)** - 2024, Cell Systems
  - Pretrained protein sequence language models have been shown to improve the performance of many prediction tasks and are now routinely integrated into bioinformatics tools.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein (embedding) → masked amino acid prediction; Fine-tune: Protein (embedding) → structure/function/fitness prediction

  To evaluate whether convolutional neural networks (CNNs) can match the performance of transformer architectures in pretraining and downstream tasks for protein language modeling.

  </details>

- **[DNA language model GROVER learns sequence context in the human genome](https://www.nature.com/articles/s42256-024-00872-0)** - 2024, Nature Machine Intelligence
  - On fine-tuning tasks addressing genome biology with questions of genome element identification and protein-DNA binding, GROVER exceeds other models' performance and can be used to compose a grammar book for the code of life.
  <details>
  <summary>Series description</summary>

  **Series:** DNA (BPE token) → masked token prediction; Fine-tune: DNA (BPE token) → promoter/protein-DNA binding

  Develop and validate GROVER as a pretrained DNA language model to learn genomic sequence context and token relationships, improving genome functional annotation and protein-DNA binding prediction.

  </details>

- **[DNABERT-2: Efficient Foundation Model and Benchmark For Multi-Species Genome](http://arxiv.org/abs/2306.15006)** - 2024, ICLR
  - arXiv:2306.15006 \[q-bio\] TLDR: This work proposes DNABERT-2, a refined genome foundation model that adapts an efficient tokenizer and employs multiple strategies to overcome input length constraints, reduce time and memory expenditure, and enhance model cap...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（BPE）→ masked token prediction; Fine-tune: DNA（BPE）→ promoter/TF/splice/variant class

  DNABERT-2 is proposed as an efficient cross-species genome foundation model by replacing k-mer with BPE tokenization and introducing multiple computational optimizations.

  </details>

- **[DNABERT-S: Pioneering Species Differentiation with Species-Aware DNA Embeddings](http://arxiv.org/abs/2402.08777)** - 2024, arXiv
  - arXiv:2402.08777 \[q-bio\] TLDR: DNABERT-S, a tailored genome model that develops species-aware embeddings to naturally cluster and segregate DNA sequences of different species in the embedding space is introduced, and Manifold Instance Mixup (MI-Mix), a cont...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (DNABERT-2 embedding) → species-aware embedding vector

  Develop a species-aware DNA embedding model to naturally cluster and segregate DNA sequences of different species in the embedding space.

  </details>

- **[Deciphering 3'UTR Mediated Gene Regulation Using Interpretable Deep Representation Learning](https://onlinelibrary.wiley.com/doi/10.1002/advs.202407013)** - 2024, Advanced Science
  - 3UTRBERT is described, which implements an attention-based language model, i.e., Bidirectional Encoder Representations from Transformers (BERT), which outperformed other contemporary methods in each of these tasks and showed that the self-attention mechanis...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: RNA (3-mer) → masked token prediction; Fine-tune: RNA (3-mer) → RBP binding/m6A site/subcellular location

  Apply Transformer-based language modeling to human mRNA 3′UTR sequences for identifying regulatory elements and enhancing downstream task predictions such as RBP binding, m6A modification, and subcellular localization.

  </details>

- **[DeepGene: An Efficient Foundation Model for Genomics based on Pan-genome Graph Transformer](http://biorxiv.org/lookup/doi/10.1101/2024.04.24.590879)** - 2024, bioRxiv
  - DeepGene is introduced, a model leveraging Pan-genome and Minigraph representations to encompass the broad diversity of genetic language and employs the rotary position embedding to improve the length extrapolation in various genetic analysis tasks.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（BPE） → masked token prediction; Fine-tune: DNA（BPE） → promoter/TF/epigenetic label

  Develop an efficient genomic foundation model that supports multi-task DNA sequence understanding and enhances modeling of genetic variation and long sequences.

  </details>

- **[Enhancing personalized gene expression prediction from DNA sequences using genomic foundation models](https://linkinghub.elsevier.com/retrieve/pii/S2666247724000873)** - 2024, Human Genetics and Genomics Advances
  - A transformer model is trained using the pre-trained embeddings from the Nucleotide Transformer and significantly outperforms Enformer in terms of correlation across individuals, and narrows the performance gap with an elastic net regression approach that u...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA（6-mer）→ masked 6-mer prediction; Fine-tune: DNA（NT embedding）→ gene expression（continuous）

  Improve the accuracy of predicting personalized gene expression from DNA sequences by leveraging embeddings from a pre-trained Nucleotide Transformer model.

  </details>

- **[Genomics-FM: Universal Foundation Model for Versatile and Data-Efficient Functional Genomic Analysis](https://doi.org/10.1101/2024.07.16.603653)** - 2024, bioRxiv
  - Genomics-FM is developed, a genomic vocabulary driven foundation model that enables versatile and label-efficient functional genomic analysis and demonstrates the capability to outperform existing models across a comprehensive suite of tasks including genom...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA（ensemble vocab） → masked token prediction；Fine-tune: DNA（task-specific vocab）/DNA + TF expression → promoter/splice/gene expression/variant effect

  To develop a versatile and label-efficient foundation model, Genomics-FM, to improve performance in functional genomic analysis.

  </details>

- **[LC-PLM: Long-context Protein Language Modeling Using Bidirectional Mamba with Shared Projection Layers](http://biorxiv.org/lookup/doi/10.1101/2024.10.29.620988)** - 2024, bioRxiv
  - This work proposes LC-PLM based on an alternative protein LM architecture, BiMamba-S, built upon selective structured state-space models, to learn high-quality universal protein representations at the amino acid token level using masked language modeling.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein (token embedding) → masked AA token prediction; Fine-tune: Multi-protein sequence (token embedding + graph token) → masked AA token prediction

  To develop LC-PLM and its graph-contextual variant LC-PLM-G for long-context protein language modeling and improved structure/function prediction.

  </details>

- **[Limitations and Enhancements in Genomic Language Models: Dynamic Selection Approach](http://biorxiv.org/lookup/doi/10.1101/2024.11.25.624002)** - 2024, bioRxiv
  - A multi-model fusion approach with a dynamic model selector that effectively integrates three models with distinct architectures enhances predictive performance in downstream tasks, outperforming any individual model and achieving complementary advantages.
  <details>
  <summary>Series description</summary>

  **Series:** Fine-tune: DNA（BPE / k-mer / char）→ enhancer/expression label (binary classification); Selector-train: [DNA + confidence vector] → soft routing label (1-hot or soft label over models)

  To propose a dynamic selection approach that integrates three structurally distinct genomic language models to improve prediction performance on both short and long genomic sequence tasks.

  </details>

- **[Multi-modal Transfer Learning between Biological Foundation Models](https://doi.org/10.48550/arXiv.2406.14150)** - 2024, NIPS
  - A multi-modal model that connects DNA, RNA, and proteins by leveraging information from different pre-trained modality-specific encoders is proposed, able to accurately predict differential transcript expression, outperforming existing methods and leveragin...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA/RNA/Protein embedding → masked k-mer prediction; Fine-tune: DNA/RNA/Protein embedding → transcript expression levels

  To develop IsoFormer, a multi-modal model integrating DNA, RNA, and protein sequence information to predict transcript isoform expression levels across human tissues.

  </details>

- **[Multi-purpose RNA language modelling with motif-aware pretraining and type-guided fine-tuning](https://www.nature.com/articles/s42256-024-00836-4)** - 2024, Nature Machine Intelligence
  - RNAErnie is introduced, an RNA-focused pretrained model built upon the transformer architecture, employing two simple yet effective strategies that enhance pretraining and demonstrate its robustness and adaptability with a unified pretrained foundation.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: RNA (token) + RNA type → masked token prediction (base/subseq/motif level); Fine-tune: RNA (token) → RNA class / interaction (0/1) / secondary structure matrix

  To develop a general-purpose RNA language model, RNAErnie, by integrating motif-aware pretraining and type-guided fine-tuning to improve performance across diverse downstream RNA analysis tasks.

  </details>

- **[Multiple sequence alignment-based RNA language model and its application to structural inference](https://academic.oup.com/nar/article/52/1/e3/7369930)** - 2024, Nucleic Acids Research
  - An unsupervised Multiple sequence-alignment-based RNA language model (RNA-MSM) is developed by utilizing homologous sequences from an automatic pipeline, RNAcmap, which can be directly mapped with high accuracy to 2D base pairing probabilities and 1D solven...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: RNA MSA (Discrete Tokens + Mask Encoding) → MSA Embeddings (N x L x 768) + Attention Maps (L x L x 120)

  To develop a multiple sequence alignment (MSA)-based RNA language model (RNA-MSM) that captures evolutionary information by utilizing large numbers of homologous sequences generated by the automated pipeline RNAcmap3, leading to significantly improved accuracy in predicting RNA secondary structure and solvent accessibility.

  </details>

- **[Nucleotide GPT: Sequence-Based Deep Learning Prediction of Nuclear Subcompartment-Associated Genome Architecture](http://biorxiv.org/lookup/doi/10.1101/2024.11.27.625761)** - 2024, bioRxiv
  - The results demonstrate the utility of transformer architectures for studying three-dimensional (3D) genome organization and substantiate a role for DNA sequence in determining nuclear subcompartment associations.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (single-nucleotide embedding) → next nucleotide prediction; Fine-tune: DNA (single-nucleotide embedding) → LAD/SPAD classification

  To develop Nucleotide GPT, a model predicting genome associations with nuclear subcompartments such as the lamina and speckles from DNA sequence alone to explore the sequence basis of 3D genome architecture.

  </details>

- **[Nucleotide Transformer: building and evaluating robust foundation models for human genomics](https://www.nature.com/articles/s41592-024-02523-z)** - 2024, Nature Methods
  - An extensive study of foundation models pre-trained on DNA sequences, ranging from 50 million up to 2.5 billion parameters and integrating information from 3,202 human genomes and 850 genomes from diverse species, that yield context-specific representations...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA（6-mer token）→ masked token prediction；Fine-tune: DNA（6-mer token embedding）→ splice site / enhancer / promoter / TFBS / variant effect classification

  To build and systematically evaluate large pre-trained transformer models on DNA sequences for cross-task molecular phenotype prediction.

  </details>

- **[Post-translational modification prediction via prompt-based fine-tuning of a GPT-2 model](https://www.nature.com/articles/s41467-024-51071-9)** - 2024, Nature Communications
  - This work introduces PTMGPT2, an interpretable protein language model that utilizes prompt-based fine-tuning to improve its accuracy in precisely predicting PTMs, and adopts unsupervised learning to identify PTMs.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein sequence (BPE) → next token prediction; Fine-tune: Protein subsequence (BPE) + prompt → PTM label (POSITIVE/NEGATIVE)

  Predict post-translational modification (PTM) sites from protein sequences via prompt-based fine-tuning of a GPT-2 model.

  </details>

- **[RNA-ModX: a multilabel prediction and interpretation framework for RNA modifications](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae688/7934572)** - 2024, Briefings in Bioinformatics
  - The RNA-ModX presents a highly precise predictive model designed to forecast post-transcriptional RNA modifications, complemented by a user-friendly web application tailored for seamless utilization by future researchers, a significant step forward in facil...
  <details>
  <summary>Series description</summary>

  **Series:** Step 1: RNA（3-mer one-hot）→ modified / unmodified;Step 2: RNA（3-mer one-hot）→ base type (A/C/G/U);Step 3: RNA（3-mer one-hot）→ modification class probability (within A/C/G/U group)

  To develop a multilabel framework for predicting and interpreting 12 prevalent RNA modification types from RNA sequences.

  </details>

- **[RNAGenesis: A Generalist Foundation Model for Functional RNA Therapeutics](https://doi.org/10.1101/2024.12.30.630826)** - 2024, bioRxiv
  - RNAGenesis is introduced, a Generalist RNA foundation model that integrates sequence representation, structural prediction, and de novo functional design within a single generative framework and demonstrates strong predictive performance across ASOs, siRNAs...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: RNA (1-mer/N-gram) → masked token prediction; Fine-tune: RNA (one-hot/embedding) → 3D structure / aptamer / sgRNA / ASO efficacy / UTR effect

  To develop a unified RNA foundation model that integrates sequence understanding, structural prediction, and functional design for broad-spectrum RNA therapeutics.

  </details>

- **[Self-supervised learning on millions of primary RNA sequences from 72 vertebrates improves sequence-based RNA splicing prediction](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae163/7644137)** - 2024, Briefings in Bioinformatics
  - This study developed SpliceBERT, a language model pretrained on primary ribonucleic acids sequences from 72 vertebrates by masked language modeling, and applied it to sequence-based modeling of RNA splicing and suggested that SSL is a promising approach to...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: RNA (single-base token) → masked nucleotide prediction; Fine-tuning Branchpoint: RNA (single-base token) → branchpoint probability; Fine-tuning Splice site: RNA (single-base token) → splice site probability; Zero-shot variant effect: RNA (single-base token) → nucleotide probability distributions (KL divergence)

  This study aimed to develop SpliceBERT, a model pretrained by self-supervised learning on primary RNA sequences from 72 vertebrates, to improve sequence-based RNA splicing prediction.

  </details>

- **[Semi-supervised learning with pseudo-labeling compares favorably with large language models for regulatory sequence prediction](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae560/7863775)** - 2024, Briefings in Bioinformatics
  - A novel semi-supervised learning (SSL) based on pseudo-labeling is proposed, which allows to exploit unlabeled DNA sequences from numerous genomes during model pre-training and shows in most cases strong predictive performance improvements compared to stand...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (one-hot) → regulatory label prediction; Fine-tune: DNA (one-hot) → regulatory label probability

  Propose a semi-supervised learning approach using cross-species pseudo-labeling to pretrain on unlabeled DNA and improve regulatory sequence prediction compared to the large language model DNABERT2.

  </details>

- **[Sequence modeling and design from molecular to genome scale with Evo](https://www.science.org/doi/10.1126/science.ado9336)** - 2024, Science
  - Evo is presented, a long-context genomic foundation model with a frontier architecture trained on millions of prokaryotic and phage genomes, enabling zero-shot function prediction competitive with domain-specific language models and the generation of functi...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (byte-level) → masked nucleotide prediction; Fine-tune: DNA (byte-level) → functional sequence generation / mutation effect prediction / gene essentiality prediction

  Build a unified deep learning model, Evo, to predict and generate functional DNA, RNA, and protein sequences from single-nucleotide to whole-genome scale.

  </details>

- **[Sitetack: a deep learning model that improves PTM prediction by using known PTMs](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btae602/7817805)** - 2024, Bioinformatics
  - This work evaluated the use of known PTM sites in prediction via sequence-based deep learning algorithms and highlighted the importance of PTMs for the installation of additional PTMs.
  <details>
  <summary>Series description</summary>

  **Series:** Protein (numeric embedding) → PTM probability

  To improve deep learning prediction accuracy of diverse PTMs by encoding known PTM locations within protein sequences.

  </details>

- **[Species-aware DNA language models capture regulatory elements and their evolution](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03221-x)** - 2024, Genome Biology
  - Background: The rise of large-scale multi-species genome sequencing projects promises to shed new light on how genomes encode gene regulatory instructions.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA k-mer → masked nucleotide prediction; Fine-tune: DNA k-mer → expression/half-life regression

  To develop a species-aware DNA language model trained on genomes of over 800 fungal species to capture conserved regulatory elements and their evolution without requiring alignments.

  </details>

- **[VQDNA: Unleashing the Power of Vector Quantization for Multi-Species Genomic Sequence Modeling](https://doi.org/10.48550/arXiv.2405.10812)** - 2024, arXiv
  - VQDNA is introduced, a general-purpose framework that renovates genome tokenization from the perspective of genome vocabulary learning and proposes Hierarchical Residual Quantization (HRQ), where varying scales of codebooks are designed in a hierarchy to en...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (VQ/HRQ embedding) → masked nucleotide prediction; Fine-tune: DNA (VQ/HRQ embedding) → classification/regression

  To introduce VQDNA, a framework that leverages learnable vector quantization codebooks for pattern-aware genome tokenization, enhancing multi-species genomic sequence modeling.

  </details>

- **[Accurate proteome-wide missense variant effect prediction with AlphaMissense](https://www.science.org/doi/10.1126/science.adg7492)** - 2023, Science
  - AlphaMissense, an adaptation of AlphaFold fine-tuned on human and primate variant population frequency databases to predict missense variant pathogenicity, achieves state-of-the-art results across a wide range of genetic and experimental benchmarks, all wit...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: Protein sequence + MSA → masked amino acid prediction; Fine-tuning: Protein sequence + MSA + variant amino acid → pathogenicity probability

  To introduce AlphaMissense, a model based on AlphaFold and protein language modeling to predict the pathogenicity of all human proteome missense variants, supporting rare disease diagnostics and functional studies.

  </details>

- **[Deciphering "the language of nature": A transformer-based language model for deleterious mutations in proteins](https://linkinghub.elsevier.com/retrieve/pii/S2666675823001157)** - 2023, The Innovation
  - This study introduces MutFormer, a transformer-based model for the prediction of deleterious missense mutations, which uses reference and mutated protein sequences from the human genome as the primary features and shows similar or improved performance over...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein sequence (token embeddings + convolution) → masked residue prediction; Fine-tune: Mutant+reference protein sequence → deleteriousness probability

  To introduce MutFormer, a transformer-based model for predicting the deleteriousness of protein missense mutations by learning from reference sequences and common variant sequences.

  </details>

- **[Evolutionary-scale prediction of atomic-level protein structure with a language model](https://doi.org/10.1126/science.ade2574)** - 2023, Science
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: Protein sequence → masked residue prediction; Fine-tune: Protein sequence → atomic coordinates + confidence

  To predict atomic-level protein structures directly from primary sequences using large-scale protein language models (ESM-2), enabling faster inference than existing methods and large-scale characterization of natural diversity.

  </details>

- **[GenSLMs: Genome-scale language models reveal SARS-CoV-2 evolutionary dynamics](https://journals.sagepub.com/doi/10.1177/10943420231201154)** - 2023, The International Journal of High Performance Computing Applications
  - We seek to transform how new and emergent variants of pandemic-causing viruses, specifically SARS-CoV-2, are identified and classified.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: DNA (codon tokens) → next codon prediction; Generation: codon sequence → complete genome

  To develop GenSLMs, a genome-scale large language model for modeling SARS-CoV-2 full-genome sequences to reveal viral evolutionary dynamics and support variant detection and prediction.

  </details>

- **[HyenaDNA: Long-Range Genomic Sequence Modeling at Single Nucleotide Resolution](https://doi.org/10.48550/arXiv.2306.15794)** - 2023, NIPS
  - This work presents HyenaDNA, a genomic foundation model pretrained on the human reference genome with context lengths of up to 1 million tokens at the single nucleotide-level, an up to 500x increase over previous dense attention-based models.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-train: DNA (single nucleotide embedding) → next nucleotide prediction; Fine-tuning: DNA sequence (+ optional soft prompt) → classification probability

  To introduce HyenaDNA, a foundation model leveraging long convolutions to model million-token DNA sequences at single nucleotide resolution, overcoming Transformer length constraints and enabling diverse downstream genomics tasks.

  </details>

- **[ProteinNPT: Improving Protein Property Prediction and Design with Non-Parametric Transformers](http://biorxiv.org/lookup/doi/10.1101/2023.12.06.570473)** - 2023, NIPS
  - This work introduces ProteinNPT, a non-parametric trans-former variant tailored to protein sequences and particularly suited to label-scarce and multi-task learning settings, and reimplement prior top-performing baselines, introduce several extensions of th...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-Train: Protein (MSA Transformer embedding) → masked amino acid + property prediction; Fine-tuning: Protein embedding + auxiliary labels → property prediction &amp; conditional sampling

  To introduce ProteinNPT, a semi-supervised conditional pseudo-generative model based on non-parametric transformers, aimed at improving protein property prediction and iterative design in label-scarce and multi-task settings.

  </details>

- **[The landscape of tolerated genetic variation in humans and primates](https://www.science.org/doi/10.1126/science.abn8197)** - 2023, Science
  - This resource is used to classify 6% of all possible human protein-altering variants as likely benign and impute the pathogenicity of the remaining 94% of variants with deep learning, achieving state-of-the-art accuracy for diagnosing pathogenic variants in...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: Protein sequence + MSA + 3D voxel → masked residue prediction; Fine-tuning: Protein sequence + MSA + variant amino acid → pathogenicity probability

  To leverage large-scale primate genome sequencing and deep learning (PrimateAI-3D) to predict the pathogenicity of human protein missense variants and improve clinical interpretation.

  </details>

- **[Detection of transcription factors binding to methylated DNA by deep recurrent neural network](https://academic.oup.com/bib/article/doi/10.1093/bib/bbab533/6484512)** - 2022, Briefings in Bioinformatics
  - A robust predictor to detect methylated DNA-bound transcription factors and a free web server was established based on the proposed model, which can be available at https://bioinfor.nefu.edu.cn/TFPM/.
  <details>
  <summary>Series description</summary>

  **Series:** Step 1: Protein sequence (tripeptide embedding, 100-dim) → TF probability; Step 2: Protein sequence (tripeptide embedding, 200-dim) → methylation binding probability

  To propose a two-step prediction model based on deep recurrent neural networks for identifying transcription factors and determining whether they bind to methylated DNA.

  </details>

- **[Integrating convolution and self-attention improves language model of human genome for interpreting non-coding regions at base-resolution](https://academic.oup.com/nar/article/50/14/e81/6583232)** - 2022, Nucleic Acids Research
  - LOGO is an accurate, fast, scalable, and robust framework to interpret non-coding regions for global sequence labeling as well as for variant prioritization at base-resolution and locality introduced by one dimensional convolution shows improved sensitivity...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: DNA sequence (k-mer encoding) → masked k-mer prediction; Fine-tuning: DNA sequence (k-mer encoding + Ref/Alt/Type) → chromatin feature/variant effect probability

  To propose LOGO, a lightweight genome language model integrating convolution and self-attention to enable high-resolution interpretation of human non-coding regions and functional prioritization of variants.

  </details>

- **[Interpretable RNA Foundation Model from Unannotated Data for Highly Accurate RNA Structure and Function Predictions](http://arxiv.org/abs/2204.00300)** - 2022, arXiv
  - arXiv:2204.00300 \[q-bio\]
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: RNA sequence (token embedding) → masked token reconstruction embedding; Fine-tuning: RNA sequence → secondary structure/3D closeness/RBP binding/expression prediction

  To propose RNA-FM, a foundation model leveraging 23 million unlabeled ncRNA sequences through self-supervised learning for highly accurate RNA structure and function prediction.

  </details>

- **[MoDNA: motif-oriented pre-training for DNA language model](https://dl.acm.org/doi/10.1145/3535508.3545512)** - 2022, Proceedings of the 13th ACM International Conference on Bioinformatics, Computational Biology and Health Informatics
  - A novel Motif-oriented DNA (MoDNA) pre-training framework is proposed, which is designed self-supervised and can be fine-tuned for different downstream tasks, and is more computationally efficient than previous methods.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: DNA（6-mer tokens） → masked k-mer prediction + motif distribution + motif occurrence; Fine-tuning: DNA（6-mer tokens） → promoter/TFBS probability

  This study aims to propose MoDNA, a motif-oriented self-supervised pre-training framework to learn semantic representations of DNA sequences and improve performance on promoter and transcription factor binding site prediction tasks.

  </details>

- **[iDNA-ABF: multi-scale deep biological language learning model for the interpretable prediction of DNA methylations](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02780-1)** - 2022, Genome Biology
  - iDNA-ABF is proposed, a multi-scale deep biological language learning model that enables the interpretable prediction of DNA methylations based on genomic sequences only and shows the power of deep language learning in capturing both sequential and function...
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: DNA sequence (3-mer + 6-mer tokens) → masked token prediction embeddings; Fine-tuning: DNA sequence → methylation probability

  To propose iDNA-ABF, a multi-scale deep biological language learning model enabling interpretable prediction of DNA methylations solely based on genomic sequences.

  </details>

- **[iEnhancer-BERT: A Novel Transfer Learning Architecture Based on DNA-Language Model for Identifying Enhancers and Their Strength](https://link.springer.com/10.1007/978-3-031-13829-4_13)** - 2022, Lecture Notes in Computer Science
  - DOI: 10.1007/978-3-031-13829-4_13
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: DNA sequence (k-mer embedding) → masked token prediction; Fine-tuning: DNA sequence (k-mer embedding) → enhancer/strength probability

  To propose iEnhancer-BERT, a transfer learning model based on DNABERT for identifying enhancers and their strength, aiming to improve DNA sequence feature extraction and classification performance.

  </details>

- **[iPro-WAEL: a comprehensive and robust framework for identifying promoters in multiple species](https://academic.oup.com/nar/article/50/18/10278/6717829)** - 2022, Nucleic Acids Research
  - A novel weighted average ensemble learning model, termed iPro-WAEL, for identifying promoters in multiple species, and identifies the most important transcription factor binding site (TFBS) motif in promoter regions to facilitate the study of identifying im...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence (Word2vec) → promoter probability

  To propose iPro-WAEL, a weighted ensemble learning framework integrating random forest and convolutional neural networks for accurate multi-species promoter prediction and interpretation of key transcription factor binding sites.

  </details>

- **[A transformer architecture based on BERT and 2D convolutional neural network to identify DNA enhancers from sequence information](https://academic.oup.com/bib/article/doi/10.1093/bib/bbab005/6128847)** - 2021, Briefings in Bioinformatics
  - This study presents a novel technique by incorporating BERT-based multilingual model in bioinformatics to represent the information of DNA sequences and suggests that BERT and 2D CNNs could open a new avenue in biological modeling using sequence information.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: DNA unigram sequence → masked token prediction; Fine-tuning: DNA embedding matrix → enhancer probability

  This study aims to develop a novel method combining BERT pre-trained models and two-dimensional convolutional neural networks (2D CNN) to identify DNA enhancers from sequence information.

  </details>

- **[BERT-m7G: A Transformer Architecture Based on BERT and Stacking Ensemble to Identify RNA N7-Methylguanosine Sites from Sequence Information](https://www.hindawi.com/journals/cmmm/2021/7764764/)** - 2021, Computational and Mathematical Methods in Medicine
  - This study proposes a novel method via incorporating BERT-based multilingual model in bioinformatics to represent the information of RNA sequences that significantly outperforms state-of-the-art prediction methods in the identification of m7G modifications.
  <details>
  <summary>Series description</summary>

  **Series:** RNA 41nt sequence → m7G modification probability

  This study aims to develop BERT-m7G, a method that combines the BERT language model and a stacking ensemble classifier to efficiently identify N7-methylguanosine (m7G) modification sites from RNA sequence information.

  </details>

- **[Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences](https://pnas.org/doi/full/10.1073/pnas.2016239118)** - 2021, Proceedings of the National Academy of Sciences
  - Learning biological properties from sequence data is a logical step toward generative and predictive artificial intelligence for biology.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: protein sequence → masked amino acid prediction; Fine-tuning: protein sequence → secondary structure/contacts/mutational effects

  This study aims to train deep Transformer language models (ESM-1b) on 250 million protein sequences via unsupervised learning to uncover information about protein structure and function and improve performance on downstream tasks such as structure prediction and mutational effect estimation.

  </details>

- **[DNABERT: pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome](https://academic.oup.com/bioinformatics/article/37/15/2112/6128680)** - 2021, Bioinformatics
  - Deciphering the language of non-coding DNA is one of the fundamental problems in genome research.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: DNA k-mer sequence → masked k-mer prediction; Fine-tuning: DNA sequence → promoter/TFBS/splice site probability

  This study aims to develop DNABERT, a Transformer-based pre-trained model to capture global representations of genomic DNA language from upstream and downstream nucleotide contexts, achieving high performance across various sequence tasks including promoter, TF binding site, and splice site prediction.

  </details>

- **[Deep4mC: systematic assessment and computational prediction for DNA N4-methylcytosine sites by deep learning](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaa099/5856341)** - 2021, Briefings in Bioinformatics
  - A novel deep learning-based 4mC site predictor, namely Deep4mC, which applies convolutional neural networks with four representative features and could obtain high accuracy and robust performance with the average area under curve (AUC) values greater than 0...
  <details>
  <summary>Series description</summary>

  **Series:** DNA 41bp sequence (binary + ENAC + EIIP + NCP) → 4mC site probability

  This study aims to systematically assess existing DNA N4-methylcytosine (4mC) site prediction tools and to develop Deep4mC, a novel deep convolutional neural network-based predictor for identifying 4mC sites across multiple species.

  </details>

- **[Language models enable zero-shot prediction of the effects of mutations on protein function](http://biorxiv.org/lookup/doi/10.1101/2021.07.09.450648)** - 2021, NIPS
  - It is shown that using only zero-shot inference, without any supervision from experimental data or additional training, protein language models capture the functional effects of sequence variation, performing at state-of-the-art levels.
  <details>
  <summary>Series description</summary>

  **Series:** Pre-training: protein sequence → masked amino acid prediction; Zero-shot inference: protein sequence → mutation effect scores

  This study aims to develop ESM-1v, a large-scale protein language model that predicts the effects of amino acid mutations on protein function in a zero-shot setting without additional supervision or task-specific training.

  </details>

- **[iDHS-Deep: an integrated tool for predicting DNase I hypersensitive sites by deep neural network](https://academic.oup.com/bib/article/doi/10.1093/bib/bbab047/6158360)** - 2021, Briefings in Bioinformatics
  - A deep learning-based algorithm is developed to identify whether an unknown sequence region would be potential DHS, and shows high prediction performance on both training datasets and independent datasets in different cell types and developmental stages, de...
  <details>
  <summary>Series description</summary>

  **Series:** DNA sequence → DHS probability

  This study aims to develop iDHS-Deep, a deep learning tool using convolutional and long short-term memory networks to identify potential DNase I hypersensitive sites across different tissues and developmental stages in the mouse genome.

  </details>

- **[iDNA-ABT: advanced deep learning model for detecting DNA methylation with adaptive features and transductive information maximization](https://academic.oup.com/bioinformatics/article/37/24/4603/6380543)** - 2021, Bioinformatics
  - DNA methylation plays an important role in epigenetic modiﬁcation, the occurrence, and the development of diseases.
  <details>
  <summary>Series description</summary>

  **Series:** DNA 41nt sequence → methylation probability

  This study aims to develop iDNA-ABT, an advanced deep learning model combining BERT-based adaptive embedding and Transductive Information Maximization (TIM) loss to predict multiple types of DNA methylation sites across species.

  </details>

- **[Unified rational protein engineering with sequence-based deep representation learning](https://www.nature.com/articles/s41592-019-0598-1)** - 2019, Nature Methods
  - Deep learning is applied to unlabeled amino-acid sequences to distill the fundamental features of a protein into a statistical representation that is semantically rich and structurally, evolutionarily and biophysically grounded and broadly applicable to uns...
  <details>
  <summary>Series description</summary>

  **Series:** Protein amino acid sequence → learned vector representation → stability/function prediction

  This study aims to apply deep learning to raw protein sequences to learn statistical representations (UniRep) capturing fundamental structural, functional, and evolutionary features, enabling diverse protein engineering prediction tasks.

  </details>

- **[Chromatin accessibility prediction via a hybrid deep convolutional neural network](https://academic.oup.com/bioinformatics/article/34/5/732/4562336)** - 2018, Bioinformatics
  - The proposed Deopen, a hybrid framework mainly based on a deep convolutional neural network, to automatically learn the regulatory code of DNA sequences and predict chromatin accessibility, shows superior performance in not only the classification of access...
  <details>
  <summary>Series description</summary>

  **Series:** DNA (one-hot + k-mer) → Chromatin accessibility probability or continuous openness score

  This study aims to propose Deopen, a hybrid deep convolutional neural network model to automatically learn regulatory features of DNA sequences and predict genome-wide chromatin accessibility.

  </details>

- **[Chromatin accessibility prediction via convolutional long short-term memory networks with k -mer embedding](https://academic.oup.com/bioinformatics/article/33/14/i92/3953949)** - 2017, Bioinformatics
  - This work addresses the problem of chromatin accessibility prediction with a convolutional Long Short-Term Memory (LSTM) network with k-mer embedding and proves the efficacy of both the convolution and the BLSTM layers by comparing two variations of the net...
  <details>
  <summary>Series description</summary>

  **Series:** DNA k-mer embedding → chromatin accessibility probability

  This study proposes a deep learning framework combining k-mer embedding and convolutional bidirectional long short-term memory networks (BLSTM) to predict chromatin accessibility from DNA sequences.

  </details>

- **[Learning the Language of Codon Translation with CodonFM](https://research.nvidia.com/labs/dbr/assets/data/manuscripts/nv-codonfm-preprint.pdf)** - N/A
  <details>
  <summary>Series description</summary>

  **Series:** Pretraining Core Task: Codon sequence (codon tokenization) → Predicted probabilities for masked codons; Zero-shot Pathogenicity Scoring: Reference DNA sequence codon position (codon tokenization) + Synonymous mutation position → Pathogenicity Δlog-likelihood; Translation Efficiency / Expression Prediction: Codon sequence (codon tokenization → sequence embedding) → Translation efficiency / Protein expression prediction (using downstream regressor).

  To learn the contextual grammar of codon usage directly from &gt;130 million coding sequences spanning &gt;22,000 species using the CodonFM family of foundation models, and apply it to assess missense/synonymous variant pathogenicity and predict mRNA translation/expression efficiency.

  </details>

</details>

## S2F-Model-Interpretation (61)

<details>
<summary>Show S2F-Model-Interpretation papers (61)</summary>

| Year | Paper | Venue | Note |
| --- | --- | --- | --- |
| 2025 | [A comprehensive benchmark and guide for sequence-function interpretable deep learning models in genomics](http://biorxiv.org/lookup/doi/10.1101/2025.01.06.631405) | bioRxiv | This benchmark study highlights that different model architectures and interpretability methods are better suited to specific scenarios, and demonstrates that interpretable sequence-function models can complement traditional sequence alignment methods in st... |
| 2025 | [Coding schemes in neural networks learning classification tasks](https://www.nature.com/articles/s41467-025-58276-6) | Nature Communications |  |
| 2025 | [DECODING THE MECHANISTIC IMPACT OF GENETIC VARIATION ON REGULATORY SEQUENCES WITH DEEP LEARNING](https://doi.org/10.1101/2025.10.07.681052) | NIPS | Non-coding DNA encodes complex cis-regulatory mechanisms that govern gene expression by orchestrating transcription factor binding within specific sequence contexts. |
| 2025 | [Decode-gLM: Tools to Interpret, Audit, and Steer Genomic Language Models](http://biorxiv.org/lookup/doi/10.1101/2025.10.31.685860) | bioRxiv | It is shown that sparse autoencoders trained on Nucleotide Transformer activations decompose hidden representations into interpretable biological features without supervision, establishing SAEs as a method for both discovery and auditing, providing a toolki... |
| 2025 | [Error-controlled non-additive interaction discovery in machine learning models](https://www.nature.com/articles/s42256-025-01086-8) | Nature Machine Intelligence |  |
| 2025 | [Explainable AI in Genomics: Transcription Factor Binding Site Prediction with Mixture of Experts](http://arxiv.org/abs/2507.09754) | arXiv | arXiv:2507.09754 \[cs\] TLDR: A novel Mixture of Experts (MoE) approach for TFBS prediction is introduced, integrating multiple pre-trained Convolutional Neural Network models, each specializing in different TFBS patterns to present an efficient, generalizabl... |
| 2025 | [From Mechanistic Interpretability to Mechanistic Biology: Training, Evaluating, and Interpreting Sparse Autoencoders on Protein Language Models](http://biorxiv.org/lookup/doi/10.1101/2025.02.06.636901) | bioRxiv | A better understanding of the limitations of pLMs is given, and it is demonstrated how SAE features can be used to help generate hypotheses for biological mechanisms. |
| 2025 | [Gauge fixing for sequence-function relationships](https://dx.plos.org/10.1371/journal.pcbi.1012818) | PLOS Computational Biology | An analytically tractable family of gauges is derived for a large class of sequence-function relationships derived in the context of models with all-order interactions, but an important subset of these gauges can be applied to diverse types of models, inclu... |
| 2025 | [Inferring fungal cis-regulatory networks from genome sequences](http://biorxiv.org/lookup/doi/10.1101/2025.02.27.640643) | bioRxiv | The results indicate that specific hypotheses about transcriptional regulation in fungi can be obtained for many genes from genome sequence analysis alone, thus scaling comparative genomics beyond evolutionary comparisons where these regions can be aligned. |
| 2025 | [InfluenceNet: Encoding Motif Influence for Interpretable Modeling of Cis-Regulatory Syntax](http://biorxiv.org/lookup/doi/10.1101/2025.11.20.689553) | bioRxiv | Cis-regulatory elements shape gene expression by recruiting transcription factors (TFs) to DNA motifs, yet how motifs cooperate or compete across distances remains poorly understood. |
| 2025 | [InterPLM: discovering interpretable features in protein language models via sparse autoencoders](https://www.nature.com/articles/s41592-025-02836-7) | Nature Methods |  |
| 2025 | [Interpretable Distillation Reveals that Deep-learning-based Splicing Models Suffer from Pervasive Confounders and Blind Spots](http://biorxiv.org/lookup/doi/10.1101/2025.11.28.691252) | bioRxiv | Despite their growing popularity, genomic deep-learning-based models function largely as black boxes, raising concerns about their trustworthiness. |
| 2025 | [Interpreting Attention Mechanisms in Genomic Transformer Models: A Framework for Biological Insights](https://doi.org/10.1101/2025.06.26.661544) | bioRxiv | Transformer models have shown strong performance on biological sequence prediction tasks, but the interpretability of their internal mechanisms remains underexplored. |
| 2025 | [LLMGEN: Evolving Interpretable Surrogate Programs for Genomics with LLMs](https://openreview.net/pdf?id=HIlgNdObra) | NIPS | Deep learning models have achieved state-of-the-art performance in predicting complex regulatory tasks. |
| 2025 | [Life as a Function: Why Transformer Architectures Struggle to Gain Genome-Level Foundational Capabilities](http://biorxiv.org/lookup/doi/10.1101/2025.01.13.632745) | bioRxiv | This study explores DNA as a complex functional representation of evolutionary processes and assess the ability of transformer-based models to capture this complexity, demonstrating that current transformer architectures, particularly auto-regressive models... |
| 2025 | [Mechanistic understanding and validation of large AI models with SemanticLens](https://doi.org/10.1038/s42256-025-01084-w) | Nature Machine Intelligence |  |
| 2025 | [Nucleotide dependency analysis of genomic language models detects functional elements](https://www.nature.com/articles/s41588-025-02347-3) | Nature Genetics | Deciphering how nucleotides in genomes encode regulatory instructions and molecular machines is a long-standing goal. |
| 2025 | [PISA: a versatile interpretation tool for visualizing cis-regulatory rules in genomic data](https://doi.org/10.1101/2025.04.07.647613) | bioRxiv | Sequence-to-function neural networks learn cis-regulatory rules of many types of genomic data from DNA sequence. |
| 2025 | [PLM-eXplain: Divide and Conquer the Protein Embedding Space](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaf631/8339745) | Bioinformatics | Motivation Protein language models (PLMs) have revolutionised computational biology through their ability to generate powerful sequence representations for diverse prediction tasks. |
| 2025 | [Sparse autoencoders uncover biologically interpretable features in protein language model representations](https://pnas.org/doi/10.1073/pnas.2506316122) | Proceedings of the National Academy of Sciences | It is shown that sparse features are more interpretable than ESM2 neurons across all trained SAEs and transcoders, demonstrating that SAEs offer a promising unsupervised approach for disentangling biologically relevant information present in PLM representat... |
| 2025 | [Tomtom-lite: accelerating Tomtom enables large-scale and real-time motif similarity scoring](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btaf577/8297099) | Bioinformatics | Summary Pairwise sequence similarity is a core operation in genomic analysis, yet most attention has been given to sequences made up of discrete characters. |
| 2025 | [Under which circumstances do genomic neural networks learn motifs and their interactions?](http://biorxiv.org/lookup/doi/10.1101/2025.07.25.666754) | bioRxiv | The use of neural networks to model genomic data in sequence-to-function scenarios has soared over the last decade. |
| 2025 | [Understanding Language Model Scaling on Protein Fitness Prediction](http://biorxiv.org/lookup/doi/10.1101/2025.04.25.650688) | bioRxiv | It is found that the performance of ESM2 peaks when the predicted perplexity for a given protein falls within the range of 3-6, highlighting the importance of perplexity in mutation effect prediction and suggesting a direction for developing pLMs optimized... |
| 2025 | [tangermeme: A toolkit for understanding cis-regulatory logic using deep learning models](http://biorxiv.org/lookup/doi/10.1101/2025.08.08.669296) | bioRxiv | Deep learning models have achieved state-of-the-art performance at predicting diverse genomic modalities, yet their promise for biological discovery lies in how they are used \textit{after} demonstrating their predictive performance. |
| 2024 | [A Comprehensive Evaluation of Self Attention for Detecting Regulatory Feature Interactions](https://doi.org/10.1101/2024.08.23.609428) | bioRxiv | The benefit of the entropy-enhanced attention models are demonstrated and additional insights are provided that would enable practitioners to make effective use of this valuable tool for biological discovery. |
| 2024 | [Enformation Theory: A Blueprint for Evaluating Deep Learning Models in Genomics](http://biorxiv.org/lookup/doi/10.1101/2024.09.03.611127) | bioRxiv | A statistically grounded framework for performance evaluation, visualization, and interpretation using the prominent sequence-based deep learning models Enformer and Borzoi as case studies is presented and a new protocol, Enformation Theory, is illustrated... |
| 2024 | [Interpreting cis-regulatory interactions from large-scale deep neural networks](https://www.nature.com/articles/s41588-024-01923-3) | Nature Genetics |  |
| 2024 | [Interpreting cis-regulatory mechanisms from genomic deep neural networks using surrogate models](https://www.nature.com/articles/s42256-024-00851-5) | Nature Machine Intelligence |  |
| 2024 | [Motif Interactions Affect Post-Hoc Interpretability of Genomic Convolutional Neural Networks](http://biorxiv.org/lookup/doi/10.1101/2024.02.15.580353) | bioRxiv | It is shown that post-hoc interpretability methods can miss motifs if interactions are present depending on how negative data is defined, and differences in interpretability between additive and non-additive effects as well as between post-hoc interpretabil... |
| 2024 | [Quick and effective approximation of in silico saturation mutagenesis experiments with first-order taylor expansion](https://linkinghub.elsevier.com/retrieve/pii/S2589004224020327) | iScience | To understand the decision process of genomic sequence-to-function models, explainable AI algorithms determine the importance of each nucleotide in a given input sequence to the model's predictions and enable discovery of cis-regulatory motifs for gene regu... |
| 2024 | [SuPreMo: a computational tool for streamlining in silico perturbation using sequence-based predictive models](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btae340/7682378) | Bioinformatics | This work presents Sequence Mutator for Predictive Models (SuPreMo), a scalable and comprehensive tool for performing and supporting in silico mutagenesis experiments and demonstrates how pairs of reference and perturbed sequences can be used with machine l... |
| 2024 | [Symmetry, gauge freedoms, and the interpretability of sequence-function Relationships](https://doi.org/10.1103/PhysRevResearch.7.023005) | Physical Review Research | This work finds that in many (and possibly all) nontrivial models, the ability to interpret individual model parameters as quantifying intrinsic allelic effects requires that gauge freedoms be present, and establishes an incompatibility between two distinct... |
| 2024 | [Training data composition determines machine learning generalization and biological rule discovery](http://biorxiv.org/lookup/doi/10.1101/2024.06.17.599333) | bioRxiv | The role of dataset composition, including negative data selection, in creating robust, generalizable, and biology-aware sequence-based ML models is highlighted, including negative data selection based on the negative data used. |
| 2024 | [Uncertainty-aware genomic deep learning with knowledge distillation](http://biorxiv.org/lookup/doi/10.1101/2024.11.13.623485) | bioRxiv | DGU (Distilling Ensembles for Genomic Uncertainty-aware models), a method that integrates ensemble learning and knowledge distillation to improve the robustness and explainability of DNN predictions, paves the way for robust and trustworthy applications of... |
| 2023 | [Accelerating Systematic Prediction of Variant Effects and Sequence Interpretation with Multiplexer Models](https://icml-compbio.github.io/2023/papers/WCBICML2023_paper139.pdf) | ICML | Deep learning models have found wide applications in capturing sequence dependencies of biological functions. |
| 2023 | [Algorithms to estimate Shapley value feature attributions](https://www.nature.com/articles/s42256-023-00657-x) | Nature Machine Intelligence | The authors provide a comprehensive survey of Shapley value feature attribution algorithms by disentangling and clarifying the fundamental challenges underlying their computation. |
| 2023 | [Correcting gradient-based interpretations of deep neural networks for genomics](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-02956-3) | Genome Biology | This work identifies a previously overlooked attribution noise source that arises from how DNNs handle one-hot encoded DNA and introduces a statistical correction that effectively reduces it, leading to more reliable attribution maps. |
| 2023 | [Investigation of the BERT model on nucleotide sequences with non-standard pre-training and evaluation of different k-mer embeddings](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btad617/7303863) | Bioinformatics | In recent years, pre-training with the transformer architecture has gained signiﬁcant attention. |
| 2023 | [NeuronMotif: Deciphering cis-regulatory codes by layer-wise demixing of deep neural networks](https://pnas.org/doi/10.1073/pnas.2216698120) | Proceedings of the National Academy of Sciences | This work proposes an algorithm capable of revealing the individual facets of deep neurons, which enables better understanding of the cis-regulatory codes embedded in the state-of-the-art CNNs. |
| 2023 | [Prediction-powered inference](https://www.science.org/doi/10.1126/science.adi6000) | Science | Prediction-powered inference is a standardized protocol for constructing valid confidence intervals and P values that enables the power and scale of ML systems to be used as predictors while ensuring responsible and reliable scientific inferences. |
| 2023 | [Reliable interpretability of biology-inspired deep neural networks](https://www.nature.com/articles/s41540-023-00310-8) | npj Systems Biology and Applications | Deep neural networks display impressive performance but suffer from limited interpretability. |
| 2023 | [Topological structure of complex predictions](https://www.nature.com/articles/s42256-023-00749-8) | Nature Machine Intelligence | Current complex prediction models are the result of fitting deep neural networks, graph convolutional networks or transducers to a set of training data. |
| 2022 | [Accelerating in silico saturation mutagenesis using compressed sensing](https://academic.oup.com/bioinformatics/article/38/14/3557/6604724) | Bioinformatics | In silico saturation mutagenesis (ISM) is a popular approach in computational genomics for calculating feature attributions on biological sequences that proceeds by systematically perturbing each position in a sequence and recording the difference in model... |
| 2022 | [Explaining a series of models by propagating Shapley values](https://www.nature.com/articles/s41467-022-31384-3) | Nature Communications | G-DeepSHAP is presented, a tractable method to compute local feature attributions for a series of machine learning models inspired by connections to the Shapley value and its use in an important distributed series of models setting is demonstrated. |
| 2022 | [FastSHAP: Real-Time Shapley Value Estimation](http://arxiv.org/abs/2107.07436) | ICLR | arXiv:2107.07436 \[stat\] |
| 2022 | [Interpreting neural networks for biological sequences by learning stochastic masks](https://www.nature.com/articles/s42256-021-00428-6) | Nature Machine Intelligence | An approach based on deep learning-scrambler networks-wherein the most important sequence positions are identified with learned input masks, enabling efficient attribution across large datasets and result in high-quality explanations, often outperforming st... |
| 2022 | [Selecting deep neural networks that yield consistent attribution-based interpretations for genomics](https://pmc.ncbi.nlm.nih.gov/articles/PMC10194041/) | Proc Mach Learn Res | Deep neural networks (DNNs) have advanced our ability to take DNA primary sequence as input and predict a myriad of molecular activities measured via highthroughput functional genomic assays. |
| 2022 | [Towards more realistic simulated datasets for benchmarking deep learning models in regulatory genomics](https://proceedings.mlr.press/v165/prakash22a.html) | Proceedings of the 16th machine learning in computational biology meeting | Deep neural networks and support vector machines have been shown to accurately predict genome-wide signals of regulatory activity from raw DNA sequences. |
| 2022 | [fastISM: performant in silico saturation mutagenesis for convolutional neural networks](https://academic.oup.com/bioinformatics/article/38/9/2397/6541633) | Bioinformatics | Deep-learning models, such as convolutional neural networks, are able to accurately map biological sequences to associated functional readouts and properties by learning predictive de novo representations. |
| 2021 | [A self-attention model for inferring cooperativity between regulatory features](https://academic.oup.com/nar/article/49/13/e77/6266414) | Nucleic Acids Research | Deep learning has demonstrated its predictive power in modeling complex biological phenomena such as gene expression. |
| 2021 | [Discovering differential genome sequence activity with interpretable and efficient deep learning](https://dx.plos.org/10.1371/journal.pcbi.1009282) | PLOS Computational Biology | Discovering sequence features that differentially direct cells to alternate fates is key to understanding both cellular development and the consequences of disease related mutations. |
| 2021 | [Global importance analysis: An interpretability method to quantify importance of genomic features in deep neural networks](https://dx.plos.org/10.1371/journal.pcbi.1008925) | PLOS Computational Biology | Deep neural networks have demonstrated improved performance at predicting the sequence specificities of DNA- and RNA-binding proteins compared to previous methods that rely on k-mers and position weight matrices. |
| 2021 | [Improving representations of genomic sequence motifs in convolutional networks with exponential activations](https://www.nature.com/articles/s42256-020-00291-x) | Nature Machine Intelligence |  |
| 2020 | [Biophysical ambiguities prevent accurate genetic prediction](https://www.nature.com/articles/s41467-020-18694-0) | Nature Communications | A goal of biology is to predict how mutations combine to alter phenotypes, fitness and disease. |
| 2020 | [Efﬁcient inference of nonlinear feature attributions with Scrambling Neural Networks](https://mlcb.github.io/mlcb2020_proceedings/papers/33_Linder_etal_2020.pdf) | MLCB |  |
| 2020 | [Learning and interpreting the gene regulatory grammar in a deep learning framework](https://dx.plos.org/10.1371/journal.pcbi.1008334) | PLOS Computational Biology | Deep neural networks (DNNs) have achieved state-of-the-art performance in identifying gene regulatory sequences, but they have provided limited insight into the biology of regulatory elements due to the difficulty of interpreting the complex features they l... |
| 2020 | [Technical Note on Transcription Factor Motif Discovery from Importance Scores (TF-MoDISco) version 0.5.6.5](http://arxiv.org/abs/1811.00416) | arXiv | arXiv:1811.00416 \[cs\] |
| 2019 | [Learning Important Features Through Propagating Activation Differences](http://arxiv.org/abs/1704.02685) | arXiv | arXiv:1704.02685 \[cs\] |
| 2019 | [Representation learning of genomic sequence motifs with convolutional neural networks](https://dx.plos.org/10.1371/journal.pcbi.1007560) | PLOS Computational Biology | Although convolutional neural networks (CNNs) have been applied to a variety of computational genomics problems, there remains a large gap in our understanding of how they build representations of regulatory genomic sequences. |
| 2017 | [A Unified Approach to Interpreting Model Predictions](https://doi.org/10.48550/arXiv.1705.07874) | NIPS | Understanding why a model makes a certain prediction can be as crucial as the prediction's accuracy in many applications. |
| 2016 | [Grad-CAM: Visual Explanations From Deep Networks via Gradient-Based Localization](https://doi.org/10.48550/arXiv.1610.02391) | ICCV | We propose a technique for producing 'visual explanations' for decisions from a large class of Convolutional Neural Network (CNN)-based models, making them more transparent. |

</details>

## S2F-Application (192)

<details>
<summary>Show S2F-Application papers (192)</summary>

| Year | Paper | Venue | Note |
| --- | --- | --- | --- |
| 2025 | [3D Epigenome Evolution Underlies Divergent Gene Regulatory Programs in Primate Neural Development](http://biorxiv.org/lookup/doi/10.1101/2025.03.11.642620) | bioRxiv | A comprehensively mapped 3D genome organization, chromatin accessibility and gene expression in induced pluripotent stem cells and derived neural stem cells from human, chimpanzee, gorilla and macaque to provide new insights into the epigenetic basis of pri... |
| 2025 | [A novel deep learning-based framework reveals a continuum of chromatin sensitivities across transcription factors](http://biorxiv.org/lookup/doi/10.1101/2025.08.11.669605) | bioRxiv | The genome-wide binding of many transcription factors (TFs) depends not only on the presence of their recognition motifs, but also on the surrounding chromatin context. |
| 2025 | [A systematic delineation of 3′UTR regulatory elements and their contextual associations](https://doi.org/10.1101/2025.06.09.658412) | bioRxiv | The 3′ region of genes plays a crucial role in transcriptional and post-transcriptional regulation, yet the functional elements within it remain largely unknown. |
| 2025 | [AIPred: comprehensive prediction and analysis of non-histone acetylation via protein language model and interpretable machine learning](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-025-02418-1) | BMC Biology | Background Non-histone lysine acetylation is a widespread protein post-translational modification that regulates almost all key cellular processes, and its dysregulation is closely associated with various human diseases. |
| 2025 | [Active learning of enhancers and silencers in the developing neural retina](https://linkinghub.elsevier.com/retrieve/pii/S2405471224003685) | Cell Systems | The ability of the resulting models to discriminate between CRX sites with identical sequence but opposite functions establishes active learning as an effective strategy to train models of regulatory DNA. |
| 2025 | [Adaptive Selection of Cis-regulatory Elements in the Han Chinese](https://doi.org/10.1093/molbev/msae034) | Molecular Biology and Evolution | Cis-regulatory elements have an important role in human adaptation to the living environment. |
| 2025 | [Advancing Human Population Genomics with DNA Foundation Models](https://www.researchsquare.com/article/rs-7889315/v1) | Research Square | DNA foundation models offer a new approach to interpret genetic variation, but their potential in population-scale genomics remains untapped. |
| 2025 | [An automated ATAC-seq method reveals sequence determinants of transcription factor dose response in the open chromatin](http://biorxiv.org/lookup/doi/10.1101/2025.07.24.666684) | bioRxiv | Rob RoboATAC, a scalable, automated ATAC-seq platform for high-throughput accessibility profiling, was developed and contributions of motif orientation, spacing, and flanking bases to accessibility were revealed, both recapitulating known motifs and nominat... |
| 2025 | [An integrated multi-tissue atlas of epigenomic landscapes and regulatory elements in the bovine genome](http://biorxiv.org/lookup/doi/10.1101/2025.08.21.671512) | bioRxiv | Deciphering the regulatory grammar of the genome is essential to understand the genetic and molecular architecture of complex traits, as most trait-associated variants lie in non-coding regions. |
| 2025 | [BRAIN-MAGNET: A functional genomics atlas for interpretation of non-coding variants](https://linkinghub.elsevier.com/retrieve/pii/S0092867425012346) | Cell | Genome-wide assessment of genetic variation is becoming routine in genetics, yet functional interpretation of non-coding single nucleotide variants in both common and rare diseases remains a major challenge. |
| 2025 | [Borzoi-informed fine mapping improves causal variant prioritization in complex trait GWAS](https://doi.org/10.1101/2025.07.09.663936) | bioRxiv |  |
| 2025 | [Building a neural network model to define DNA sequence specificity in V(D)J recombination](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf551/8171874) | Nucleic Acids Research | In developing lymphocytes, V(D)J recombination assembles functional antigen receptor (AgR) genes through rearrangement of the AgR loci to adjoin component gene segments. |
| 2025 | [Chromatin and gene-regulatory dynamics of human pulmogenesis by single cell multiomic sequencing](http://biorxiv.org/lookup/doi/10.1101/2025.09.24.678382) | bioRxiv | Human lung development is governed by complex gene regulatory networks that orchestrate cellular differentiation and organogenesis. |
| 2025 | [Combining Machine Learning and Multiplexed, In Situ Profiling to Engineer Cell Type and Behavioral Specificity](https://doi.org/10.1101/2025.06.20.660790) | bioRxiv | A promising strategy for the precise control of neural circuits is to use cis-regulatory enhancers to drive transgene expression in specific cells. |
| 2025 | [Comprehensive molecular impact mapping of common and rare variants at GWAS loci](https://doi.org/10.1101/2025.06.05.658079) | bioRxiv | DNACipher DVIM prioritises common and rare variants at GWAS loci by predicting molecular effects across a broad range of contexts, which allows for better detection of variant effects at expression quantitative trait loci (eQTLs). |
| 2025 | [Conservation of Regulatory Elements with Highly Diverged Sequences Across Large Evolutionary Distances](https://doi.org/10.1038/s41588-025-02202-5) | Nature Genetics | Highlights the regulatory genome in the embryonic hearts of chicken and mouse at equivalent developmental stages and reveals functional conservation of CREs across large evolutionary distances is more widespread than previously recognized. |
| 2025 | [Context-dependent regulatory variants in Alzheimer's disease](https://doi.org/10.1101/2025.07.11.659973) | bioRxiv | In vitro and in vivo massively parallel reporter assays with interpretable machine-learning models combined to systematically characterize common and rare variants across myeloid and neural contexts underscore the context-dependent nature of noncoding varia... |
| 2025 | [Custom CRISPR-Cas9 PAM variants via scalable engineering and machine learning](https://www.nature.com/articles/s41586-025-09021-y) | Nature | PAMmla integrates ML and protein engineering to curate a catalog of SpCas9 enzymes with distinct PAM requirements, and motivates the use of efficient and safe bespoke Cas9 enzymes instead of generalist enzymes for various applications. |
| 2025 | [Custom CRISPR-Cas9 PAM variants via scalable engineering and machine learning](https://www.nature.com/articles/s41586-025-09021-y) | Nature |  |
| 2025 | [Data-driven protease engineering by DNA-recording and epistasis-aware machine learning](https://www.nature.com/articles/s41467-025-60622-7) | Nature Communications | Protein engineering has recently seen tremendous transformation due to machine learning (ML) tools that predict structure from sequence at unprecedented precision. |
| 2025 | [Deciphering the biosynthetic potential of microbial genomes using a BGC language processing neural network model](https://academic.oup.com/nar/article/doi/10.1093/nar/gkaf305/8113170) | Nucleic Acids Research | Biosynthetic gene clusters (BGCs), key in synthesizing microbial secondary metabolites, are mostly hidden in microbial genomes and metagenomes. |
| 2025 | [Decoding cnidarian cell type gene regulation](https://doi.org/10.1101/2025.07.01.662323) | bioRxiv | Animal cell types are defined by differential access to genomic information, a process orchestrated by the combinatorial activity of transcription factors that bind to cis-regulatory elements (CREs) to control gene expression. |
| 2025 | [Deep Learning Combined with Quantitative Structure-Activity Relationship Accelerates De Novo Design of Antifungal Peptides](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202412488) | Advanced Science | Novel antifungal drugs that evade resistance are urgently needed for Candida infections. |
| 2025 | [Deep Learning for Biomarker Discovery in Cancer Genomes](http://biorxiv.org/lookup/doi/10.1101/2025.01.06.631471) | bioRxiv | It is demonstrated that deep learning can identify patterns in unfiltered somatic mutations without the need for manual feature extraction and paves the way for developing NGS-based biomarkers using minimally processed data. |
| 2025 | [Deep indel mutagenesis reveals the regulatory and modulatory architecture of alternative exon splicing](https://www.nature.com/articles/s41467-025-62957-7) | Nature Communications |  |
| 2025 | [Deep learning imputes DNA methylation states in single cells and enhances the detection of epigenetic alterations in schizophrenia](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25000308) | Cell Genomics | Comprehensive evaluations across five single-nucleus DNAm datasets from human and mouse demonstrate scMeFormer's superior performance over alternative models, achieving high-fidelity imputation even with coverage reduced to 10% of original CpG sites. |
| 2025 | [Deep learning the dynamic regulatory sequence code of cardiac organoid differentiation](http://biorxiv.org/lookup/doi/10.1101/2025.10.15.680997) | bioRxiv | A time-resolved, single-cell multi-omic atlas of human iPSC-derived cardiac organoids is combined with deep learning models that predict chromatin accessibility from DNA sequence, enabling the discovery of the regulatory syntax underlying early heart develo... |
| 2025 | [DeepAnnotation: A novel interpretable deep learning-based genomic selection model that integrates comprehensive functional annotations](https://academic.oup.com/gigascience/article/doi/10.1093/gigascience/giaf083/8242612) | GigaScience | DeepAnnotation is an open-source, interpretable deep learning approach for phenotype prediction, leveraging comprehensive multiomics functional annotations, and provides a valuable tool for researchers and practitioners in genomic selection. |
| 2025 | [DeepCAST-GWAS: Improving the Discovery of Genetic Associations Using Deep Learning-Based Regulatory SNP Prioritization](http://biorxiv.org/lookup/doi/10.1101/2025.11.27.690924) | bioRxiv | Genome-wide association studies (GWAS) have uncovered numerous variants linked to complex traits, yet power remains limited by the large multiple testing burden and the inclusion of many variants with minimal regulatory impact. |
| 2025 | [Design of highly functional genome editors by modelling CRISPR-Cas sequences](https://www.nature.com/articles/s41586-025-09298-z) | Nature |  |
| 2025 | [Design of highly functional genome editors by modelling CRISPR-Cas sequences](https://www.nature.com/articles/s41586-025-09298-z) | Nature |  |
| 2025 | [Design principles of cell-state-specific enhancers in hematopoiesis](https://linkinghub.elsevier.com/retrieve/pii/S0092867425004490) | Cell | It is found that identical sites displayed both repressive and activating function as a consequence of cell state, site combinatorics, or simply predicted occupancy of a TF on an enhancer as a consequence of cell state, site combinatorics, or simply predict... |
| 2025 | [Discovering the nuclear localization signal universe through a deep learning model with interpretable attention units](https://linkinghub.elsevier.com/retrieve/pii/S2666389925001102) | Patterns | This study applies NLSExplorer to the nucleus-localized proteins in the Swiss-Prot database to extract valuable segments and revealed a potential NLS landscape and uncovered features of nuclear transport segments across 416 species. |
| 2025 | [Discovery and protein language model-guided design of hyperactive transposases](https://www.nature.com/articles/s41587-025-02816-4) | Nature Biotechnology | Using a eukaryotic transposon mining pipeline, fine-tuning a protein language model to further expand PiggyBac sequence space discovers transposases with improved activity and that are compatible with T cell engineering and Cas9-directed transposase-assiste... |
| 2025 | [Discovery of CRISPR-Cas12a clades using a large language model](https://www.nature.com/articles/s41467-025-63160-4) | Nature Communications |  |
| 2025 | [Dissecting regulatory syntax in human development with scalable multiomics and deep learning](https://doi.org/10.1101/2025.04.30.651381) | bioRxiv | The HDMA is presented, a single-cell atlas of chromatin accessibility and gene expression from 817,740 fetal cells across 12 organs, spanning 203 cell types and over 1 million candidate cis-regulatory elements, many of which exhibit organ-specific in vivo e... |
| 2025 | [ERV3-MLT1 provides cis-regulatory elements for human placental functioning and are commonly dysregulated in human-specific preeclampsia](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03821-1) | Genome Biology | Background: Owing to their transcription factor binding sites, endogenous retroviruses (ERVs) can act as cis-regulatory-elements (CREs). |
| 2025 | [ESM-Effect: An Effective and Efficient Fine-Tuning Framework towards accurate prediction of Mutation's Functional Effect](http://biorxiv.org/lookup/doi/10.1101/2025.02.03.635741) | bioRxiv | ESM-Effect, an optimized PLM-based functional effect prediction framework through extensive ablation studies, is developed and a novel metric for prediction accuracy termed relative Bin-Mean Error (rBME): rBME emphasizes prediction accuracy in challenging,... |
| 2025 | [ESM-Ezy: a deep learning strategy for the mining of novel multicopper oxidases with superior properties](https://www.nature.com/articles/s41467-025-58521-y) | Nature Communications |  |
| 2025 | [EUP: Enhanced cross-species prediction of ubiquitination sites via a conditional variational autoencoder network based on ESM2](https://doi.org/10.1371/journal.pcbi.1013268) | PLoS Comput Biol | Ubiquitination is critical in biomedical research. Predicting ubiquitination sites based on deep learning model have advanced the study of ubiquitination. However, traditional supervised model limits in the scenarios where labels are scarci |
| 2025 | [Empathi: Embedding-based Phage Protein Annotation Tool by Hierarchical Assignment](http://biorxiv.org/lookup/doi/10.1101/2024.12.31.630607) | bioRxiv | Bacteriophages, viruses infecting bacteria, are estimated to outnumber their cellular hosts by 10-fold, acting as key players in all microbial ecosystems. |
| 2025 | [Enhancer-driven cell type comparison reveals similarities between the mammalian and bird pallium](https://www.science.org/doi/10.1126/science.adp3957) | Science | This study used deep learning to characterize these enhancer codes and devised three metrics to compare cell types in the telencephalon across amniotes, and generated single-cell multiome and spatially resolved transcriptomics data of the chicken telencepha... |
| 2025 | [Enzyme specificity prediction using cross attention graph neural networks](https://www.nature.com/articles/s41586-025-09697-2) | Nature |  |
| 2025 | [Evaluating methods for the prediction of cell-type-specific enhancers in the mammalian cortex](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25001351) | Cell Genomics | Identifying cell-type-specific enhancers is critical for developing genetic tools to study the mammalian brain. |
| 2025 | [Evo2HiC: a multimodal foundation model for integrative analysis of genome sequence and architecture](http://biorxiv.org/lookup/doi/10.1101/2025.11.18.689171) | bioRxiv | Evo2HiC is a foundation model that integrates genome sequences and 3D chromatin structure information, substantially reduces computational cost while maintaining state-of-the-art accuracy on predicting various epigenomic signals and genome architecture, ena... |
| 2025 | [Expanding the DNA Motif Lexicon of the Transcriptional Regulatory Code](https://doi.org/10.1101/2025.07.09.662874) | bioRxiv | Comparative analysis with a neural network model trained on chromatin accessibility demonstrates striking convergence and distinctions within the expanded regulatory lexicon, enabling joint predictions of motif contributions and the impact of variants on ch... |
| 2025 | [FANTASIA leverages language models to decode the functional dark proteome across the animal tree of life](https://www.nature.com/articles/s42003-025-08651-2) | Communications Biology | FANTASIA (Functional ANnoTAtion based on embedding space SImilArity) integrates protein language models for large-scale functional annotation, offering advantages over homology-based tools in sensitivity and generalizability. |
| 2025 | [GLM-Prior: a nucleotide transformer model reveals prior knowledge as the driver of GRN inference performance](https://doi.org/10.1101/2025.06.29.662198) | bioRxiv | Gene regulatory network inference depends on high-quality prior-knowledge, yet curated priors are often incomplete or unavailable across species and cell types. |
| 2025 | [Genomic Language Model for Predicting Enhancers and Their Allele-Specific Activity in the Human Genome](http://biorxiv.org/lookup/doi/10.1101/2025.03.18.644040) | bioRxiv | The genome-wide enhancer annotations and candidate loss-of-function genetic variants predicted by DNABERT-Enhancer provide valuable resources for genome interpretation in functional and clinical genomics studies. |
| 2025 | [Global cis-regulatory landscape of double-stranded DNA viruses](http://biorxiv.org/lookup/doi/10.1101/2025.07.20.665756) | bioRxiv | A comprehensive functional CRE map of human-infecting dsDNA viruses that serves as a blueprint for further studies in viral regulation, reactivation, evolution, and viral vector design is presented. |
| 2025 | [High-resolution dissection of human cell type-specific enhancers in cis and trans activities](https://linkinghub.elsevier.com/retrieve/pii/S0888754325000011) | Genomics | The spatiotemporal-specific gene expression is regulated by cell type-specific regulatory elements. |
| 2025 | [HyDrop v2: Scalable atlas construction for training sequence-to-function models](https://doi.org/10.1101/2025.04.02.646792) | bioRxiv | A new version of the open-source microfluidic system HyDrop is developed with increased sensitivity and scale to facilitate the cost-effective generation of large scATAC-seq atlases for model training and can contribute to unraveling cell-type specific regu... |
| 2025 | [Identification of gut microbial bile acid metabolic enzymes via an AI-assisted pipeline](https://linkinghub.elsevier.com/retrieve/pii/S0092867425008062) | Cell | The modifications of bile acids (BAs) are fundamental to their role in host physiology and pathology. |
| 2025 | [Identifying non-coding variant effects at scale via machine learning models of cis-regulatory reporter assays](https://doi.org/10.1101/2025.04.16.648420) | bioRxiv | The value of non-coding functional predictions is established and MPAC is presented, an ensemble of machine-learning models trained on MPRA data that provides accurate and scalable prediction of the cis-regulatory impact of non-coding variants. |
| 2025 | [Identifying the DNA methylation preference of transcription factors using ProtBERT and SVM](https://dx.plos.org/10.1371/journal.pcbi.1012513) | PLOS Computational Biology | A novel two-step computational approach to classify TFs and TFPMs and found that most of the top 20 proteins belong to the Krueppel C2H2-type Zinc-finger family, thereby showing the robustness of the proposed approach. |
| 2025 | [Improved CRISPR/Cas9 Off-target Prediction with DNABERT and Epigenetic Features](https://doi.org/10.1101/2025.04.16.649101) | bioRxiv | CRISPR/Cas9 genome editing is a powerful tool in genetic engineering and gene therapy; however, off-target effects pose significant challenges for clinical applications. |
| 2025 | [Improving polygenic prediction from whole-genome sequencing data by leveraging predicted epigenomic features](https://pnas.org/doi/10.1073/pnas.2419202122) | Proceedings of the National Academy of Sciences | Polygenic risk scores (PRS) are essential tools for estimating individual susceptibility to complex diseases by aggregating the effects of many genetic variants. |
| 2025 | [In vivo mapping of mutagenesis sensitivity of human enhancers](https://www.nature.com/articles/s41586-025-09182-w) | Nature |  |
| 2025 | [Integrating Single-Molecule Sequencing and Deep Learning to Predict Haplotype-Specific 3D Chromatin Organization in a Mendelian Condition](http://biorxiv.org/lookup/doi/10.1101/2025.02.26.640261) | bioRxiv | Fold is presented, a deep learning model that combines convolutional neural networks and transformer architectures to accurately predict cell-type-specific and haplotype-specific 3D genome organization using multi-omic data from a single, long-read sequenci... |
| 2025 | [Integrating genetic variation with deep learning provides context for variants impacting transcription factor binding during embryogenesis](http://genome.cshlp.org/lookup/doi/10.1101/gr.279652.124) | Genome Research | Understanding how genetic variation impacts transcription factor (TF) binding remains a major challenge, limiting our ability to model disease-associated variants. |
| 2025 | [Interpreting regulatory mechanisms of Hippo signaling through a deep learning sequence model](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25000771) | Cell Genomics | Signaling pathway components are well studied, but how they mediate cell-type-speciﬁc transcription responses is an unresolved problem. |
| 2025 | [Iterative deep learning-design of human enhancers exploits condensed sequence grammar to achieve cell type-specificity](https://doi.org/10.1016/j.cels.2025.101302) | Cell Systems | This work applies iterative deep learning to design synthetic enhancers with strong differential activity between two human cell lines and characterize causal features of top enhancers via perturbation experiments and show enhancers as short as 50bp can mai... |
| 2025 | [JASPAR 2026: expansion of transcription factor binding profiles and integration of deep learning models](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkaf1209/8343514) | Nucleic Acids Research | This release features a deep learning (DL) collection, providing a paradigm shift in modeling and characterizing TF-DNA interactions with 1259 BPNet models trained on Homo sapiens ENCODE chromatin immunoprecipitation followed by sequencing datasets from 240... |
| 2025 | [Language models reveal a complex sequence basis for adaptive convergent evolution of protein functions](https://pnas.org/doi/10.1073/pnas.2418254122) | Proceedings of the National Academy of Sciences | PLM embeddings can indicate adaptive convergence of high-order protein features beyond site identities, demonstrating the power of deep learning tools for investigating the complex mapping between molecular sequences and functions. |
| 2025 | [Learning antibody sequence constraints from allelic inclusion](https://linkinghub.elsevier.com/retrieve/pii/S2405471225002017) | Cell Systems | A machine-learning framework is introduced to leverage a previously underutilized source of data to find instances of allelic inclusion, a rare event where B cells express two different antibody light chains as mRNA, and train machine-learning models to ide... |
| 2025 | [Leveraging protein language models to identify complex trait associations with previously inaccessible classes of functional rare variants](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25003246) | Cell Genomics |  |
| 2025 | [LucaPCycle: Illuminating microbial phosphorus cycling in deep-sea cold seep sediments using protein language models](https://www.nature.com/articles/s41467-025-60142-4) | Nature Communications |  |
| 2025 | [Machine learning identification of enhancers in the rhesus macaque genome](https://linkinghub.elsevier.com/retrieve/pii/S0896627325003137) | Neuron | Nonhuman primate (NHP) neuroanatomy and cognitive complexity make NHPs ideal models to study human neurobiology and disease. |
| 2025 | [Mapping the regulatory effects of common and rare non-coding variants across cellular and developmental contexts in the brain and heart](https://doi.org/10.1101/2025.02.18.638922) | bioRxiv | The findings demonstrate the potential of integrating single-cell maps with population genetics and deep learning-based variant effect prediction to elucidate mechanisms of development and disease-ultimately, supporting the notion that genetic contributions... |
| 2025 | [Massive experimental quantification allows interpretable deep learning of protein aggregation](https://doi.org/10.1126/sciadv.adt5111) | SCIENCE ADVANCES |  |
| 2025 | [Massively parallel characterization of transcriptional regulatory elements](https://www.nature.com/articles/s41586-024-08430-9) | Nature | This work uses lentivirus-based massively parallel reporter assays to test the regulatory activity of more than 680,000 sequences, representing an extensive set of annotated cCREs, and develops sequence-based models to predict cCRE function and variant effe... |
| 2025 | [Modeling the vertebrate regulatory sequence landscape by UUATAC-seq and deep learning](https://doi.org/10.1016/j.cell.2025.06.020) | Cell |  |
| 2025 | [Multi-dimensional annotation of porcine variants using genomic and epigenomic features in pigs](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-025-02279-8) | BMC Biology | Background Investigating the functional impact of genomic variants is essential to uncover the molecular mechanisms behind complex traits. |
| 2025 | [Multiscale footprints reveal the organization of cis-regulatory elements](https://www.nature.com/articles/s41586-024-08443-4) | Nature | Cis -regulatory elements (CREs) control gene expression and are dynamic in their structure and function, reflecting changes in the composition of diverse effector proteins over time 1 . |
| 2025 | [Neur-Ally: a deep learning model for regulatory variant prediction based on genomic and epigenomic features in brain and its validation in certain neurological disorders](https://academic.oup.com/nargab/article/doi/10.1093/nargab/lqaf080/8161655) | NAR Genomics and Bioinformatics | Large-scale quantitative studies have identified significant genetic associations for various neurological disorders. |
| 2025 | [Neural network-based cross-species chromatin annotation goes beyond sequence conservation](http://biorxiv.org/lookup/doi/10.1101/2025.10.16.682871) | bioRxiv | The ability of neural networks trained with human data to infer the missing chromatin annotations in livestock species is demonstrated and the widespread use of neural networks in cross-species genome annotation is advocated, a key step in understanding the... |
| 2025 | [Noncoding variants and sulcal patterns in congenital heart disease: Machine learning to predict functional impact](https://linkinghub.elsevier.com/retrieve/pii/S2589004224029341) | iScience |  |
| 2025 | [PhyloTune: An efficient method to accelerate phylogenetic updates using a pretrained DNA language model](https://www.nature.com/articles/s41467-025-61684-3) | Nature Communications |  |
| 2025 | [Predictable Engineering of Signal-Dependent Cis-Regulatory Elements](http://biorxiv.org/lookup/doi/10.1101/2025.03.07.642002) | bioRxiv | A high-throughput combinatorial screening strategy is developed that establishes quantitative principles for engineering synthetic regulatory elements with programmable signal responses to rewire genetic circuits and control stem cell differentiation, provi... |
| 2025 | [Predicting Disease-Specific Histone Modifications and Functional Effects of Non-coding Variants by Leveraging DNA Language Models](https://doi.org/10.1101/2025.06.15.659749) | bioRxiv |  |
| 2025 | [Predicting gene expression using millions of yeast promoters reveals cis -regulatory logic](https://doi.org/10.1093/bioadv/vbaf130) | Bioinformatics Advances | This work investigates the complex association between gene promoters and expression in S. |
| 2025 | [Predicting the structural impact of human alternative splicing](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03744-x) | Genome Biology | Background Protein structure prediction with neural networks is a powerful new method for linking protein sequence, structure, and function, but structures have generally been predicted for only a single isoform of each gene, neglecting splice variants. |
| 2025 | [Predicting the translation efficiency of messenger RNA in mammalian cells](https://www.nature.com/articles/s41587-025-02712-x) | Nature Biotechnology | A transcriptome-wide atlas of translation efficiency measurements encompassing more than 140 human and mouse cell types from 3,819 ribosomal profiling datasets is generated and RiboNN predicts the translational behavior of base-modified therapeutic RNA and... |
| 2025 | [Prediction of pathogenic mutations in human transmembrane proteins and their associated diseases via utilizing pre-trained Bio-LLMs](https://doi.org/10.1038/s42003-025-08452-7) | Communications Biology | MutDPAL is the first to combine transmembrane environment with disease encoding features for fine-grained disease classification, offering valuable insights into the pathogenicity of missense mutations in membrane protein. |
| 2025 | [Predictive Biophysical Neural Network Modeling of a Compendium of in vivo Transcription Factor DNA Binding Profiles for Escherichia coli](https://doi.org/10.1038/s41467-025-58862-8) | Nature Communications | BoltzNet, a novel neural network that predicts TF binding energy from DNA sequence, is used to train BoltzNet, a quantitative biophysical model that provides directly interpretable predictions genome-wide at nucleotide resolution and generates models for 12... |
| 2025 | [Protein codes promote selective subcellular compartmentalization](https://doi.org/10.1126/science.adq2634) | Science |  |
| 2025 | [Protein functional site annotation using local structure embeddings](https://pnas.org/doi/10.1073/pnas.2513219122) | Proceedings of the National Academy of Sciences | The rapid expansion of protein sequence and structure databases has resulted in a significant number of proteins with ambiguous or unknown function. |
| 2025 | [Protein large language model assisted one-to-one gene homology mapping in cross-species single-cell transcriptome integration](http://biorxiv.org/lookup/doi/10.1101/2025.10.17.683009) | bioRxiv | A protein large language model (pLLM)-based gene homology mapping strategy that boosts the number of homology gene pairs and identifies previously unannotated cell-type marker pairs, facilitating novel cross-species marker discovery is developed. |
| 2025 | [Rapid epigenomic classification of acute leukemia](https://www.nature.com/articles/s41588-025-02321-z) | Nature Genetics |  |
| 2025 | [Rewriting regulatory DNA to dissect and reprogram gene expression](https://doi.org/10.1016/j.cell.2025.03.034) | Cell | Variant-FlowFISH provides a powerful tool to map the effects of variants and transcription factor binding sites on gene expression, test and improve computational models of gene regulation, and reprogram regulatory DNA. |
| 2025 | [Semantic design of functional de novo genes from a genomic language model](https://www.nature.com/articles/s41586-025-09749-7) | Nature | Generative genomic models can design increasingly complex biological systems 1 . |
| 2025 | [Sequence-based chromatin activity modeling and regulatory impact prediction of genetic variants in farmed animals using deep learning](http://biorxiv.org/lookup/doi/10.1101/2025.02.21.639224) | bioRxiv | A deep learning-based framework is presented that utilizes functional genomics data to generate genome-wide predictions of the regulatory impact of non-coding vari-ants in cattle, chicken, pig, and Atlantic salmon, and functional scores derived from these m... |
| 2025 | [Sequence-based chromatin activity modeling and regulatory impact prediction of genetic variants in farmed animals using deep learning](https://academic.oup.com/nargab/article/doi/10.1093/nargab/lqaf139/8313454) | NAR Genomics and Bioinformatics | Noncoding genomic variations are crucial for the genetic regulation of traits; however, their functional impact in farmed animals remains underexplored due to limited genomic resources and the absence of tailored computational tools. |
| 2025 | [Single-Cell Genomics Elucidates Molecular Variations and Regulatory Mechanisms in Circulating Immune Cells](http://biorxiv.org/lookup/doi/10.1101/2025.01.26.634963) | bioRxiv | The Chinese Immune Multi-Omics Atlas (CIMA), elucidating sex-, age-, and genetic-related molecular variations by analyzing multi-omics data from 428 adults with over 10 million immune cells, represents a population-scale multi-omics resource of human immune... |
| 2025 | [Single-nucleus transcriptome atlas of orbitofrontal cortex in ALS with a deep learning-based decoding of alternative polyadenylation mechanisms](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25002630) | Cell Genomics | Amyotrophic lateral sclerosis (ALS) and frontotemporal lobar degeneration (FTLD) are fatal neurodegenerative diseases sharing clinical and pathological features. |
| 2025 | [Single-nucleus transcriptome atlas of orbitofrontal cortex in ALS with a deep learning-based decoding of alternative polyadenylation mechanisms](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25002630) | Cell Genomics | Amyotrophic lateral sclerosis (ALS) and frontotemporal lobar degeneration (FTLD) are fatal neurodegenerative diseases sharing clinical and pathological features. |
| 2025 | [SomaMutDB 2.0: A comprehensive database for exploring somatic mutations and their functional impact in normal human tissues](https://doi.org/10.1101/2025.09.14.676124) | bioRxiv | Recent advances in ultra-accurate sequencing technologies have revealed that somatic mutations accumulate across the human lifespan and may contribute to both normal aging and disease. |
| 2025 | [Systematic pegRNA design with PRIDICT2.0 and ePRIDICT for efficient prime editing](https://doi.org/10.1038/s41596-025-01244-7) | Nature Protocols |  |
| 2025 | [TFBS-Finder: Deep Learning-based Model with DNABERT and Convolutional Networks to Predict Transcription Factor Binding Sites](http://arxiv.org/abs/2502.01311) | arXiv | arXiv:2502.01311 \[cs\] TLDR: A deep learning model which uses pre-trained DNABERT, a Convolutional Neural Network module, a Convolutional Neural Network module, a Modified Convolutional Block Attention Module, a Multi-Scale Convolutions with Attention module... |
| 2025 | [TSProm: Deciphering the Genomic Context of Tissue Specificity](http://biorxiv.org/lookup/doi/10.1101/2025.10.30.685161) | bioRxiv | TSProm is introduced, a framework that specializes a DNA foundation model (DNABERT2) to decipher the long-range regulatory logic of TSp promoters at the gene isoform level, offering powerful computational tools for the study of tissue-specific gene regulati... |
| 2025 | [The evolution of gene regulation in mammalian cerebellum development](http://biorxiv.org/lookup/doi/10.1101/2025.03.14.643248) | bioRxiv | This study combined single-nucleus measurements of gene expression and chromatin accessibility from six mammals to uncover conserved and diverged regulatory networks in cerebellum development, and identifies core regulators of cell identity and developed se... |
| 2025 | [The role of chromatin state in intron retention: A case study in leveraging large scale deep learning models](https://dx.plos.org/10.1371/journal.pcbi.1012755) | PLOS Computational Biology | Complex deep learning models trained on very large datasets have become key enabling tools for current research in natural language processing and computer vision. |
| 2025 | [Training Flexible Models of Genetic Variant Effects from Functional Annotations using Accelerated Linear Algebra](https://doi.org/10.48550/arXiv.2506.19598) | arXiv | To understand how genetic variants in human genomes manifest in phenotypes - traits like height or diseases like asthma - geneticists have sequenced and measured hundreds of thousands of individuals. |
| 2025 | [Transfer learning reveals sequence determinants of the quantitative response to transcription factor dosage](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25000369) | Cell Genomics | Deep learning models have advanced our ability to predict cell-type-speciﬁc chromatin patterns from transcription factor (TF) binding motifs, but their application to perturbed contexts remains limited. |
| 2025 | [U-rich elements drive pervasive cryptic splicing in 3' UTR massively parallel reporter assays](https://www.nature.com/articles/s41467-025-62000-9) | Nature Communications | This work revisits the finding from a prior massively parallel reporter assay that AU-rich elements in 3' untranslated regions (3' UTRs) can drive upregulation or downregulation of mRNA expression depending on 3' UTR context and emphasizes U-rich sequences... |
| 2025 | [Uncovering differential tolerance to deletions versus substitutions with a protein language model](https://linkinghub.elsevier.com/retrieve/pii/S2405471225002066) | Cell Systems |  |
| 2025 | [Using the DNA language model, GROVER, to parse sequence and epigenetic effects on genome stability](http://biorxiv.org/lookup/doi/10.1101/2025.07.23.666402) | bioRxiv | Genome stability is shaped by DNA sequence and epigenomic context, but their relative contributions to double-strand break (DSB) sensitivity remain unclear. |
| 2025 | [Venus-MAXWELL: Efficient Learning of Protein-Mutation Stability Landscapes using Protein Language Models](https://doi.org/10.1101/2025.05.30.656964) | bioRxiv | In-silico prediction of protein mutant stability, measured by the difference in Gibbs free energy change (∆∆G), is fundamental for protein engineering. |
| 2025 | [scPrediXcan integrates deep learning methods and single-cell data into a cell-type-specific transcriptome-wide association study framework](https://linkinghub.elsevier.com/retrieve/pii/S2666979X25001314) | Cell Genomics | Transcriptome-wide association studies (TWASs) help identify disease-causing genes but often fail to pinpoint disease mechanisms at the cellular level because of the limited sample sizes and sparsity of celltype-specific expression data. |
| 2025 | [scTail: precise polyadenylation site detection and its alternative usage analysis from reads 1 preserved 3′ scRNA-seq data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03710-7) | Genome Biology | It is demonstrated that combining scTail and BRIE2 can discover differential alternative PAS usage in various biological processes including cancers and time-series development, giving critical insight into PAS regulation. |
| 2024 | [BRAIN-MAGNET: A novel functional genomics atlas coupled with convolutional neural networks facilitates clinical interpretation of disease relevant variants in non-coding regulatory elements](http://medrxiv.org/lookup/doi/10.1101/2024.04.13.24305761) | medRxiv | Brain-MAGNET is built, a convolutional neural network that allows the prediction of NCRE activity based on DNA sequence composition, and which identifies functionally relevant nucleotides and TF motifs within each NCRE that are required for NCRE function. |
| 2024 | [Cell-type-directed design of synthetic enhancers](https://www.nature.com/articles/s41586-023-06936-2) | Nature | Transcriptional enhancers act as docking stations for combinations of transcription factors and thereby regulate spatiotemporal activation of their target genes 1 . |
| 2024 | [Chromatin-dependent motif syntax defines differentiation trajectories](http://biorxiv.org/lookup/doi/10.1101/2024.08.05.606702) | bioRxiv | This work contrasting two TFs, NGN2 and MyoD1, which recognize ubiquitous E-box motifs yet instigate distinct cell fates-neurons and muscles, respectively, reveals a chromatin-dependent motif syntax, delineating both common and factor-specific binding and p... |
| 2024 | [Conservation of cis -regulatory codes over half a billion years of evolution](http://biorxiv.org/lookup/doi/10.1101/2024.11.13.623372) | bioRxiv | It is shown that the retina's highly conserved cellular architecture is mirrored by deep conservation of the underlying cis-regulatory codes that control gene expression, which predate the divergence of extant vertebrates and persist despite nearly complete... |
| 2024 | [Constrained Open Chromatin Regions Reveal Functional Elements Shaping Human Traits](http://biorxiv.org/lookup/doi/10.1101/2024.10.31.621195) | bioRxiv | By defining biologically constrained regulatory elements at high resolution, CAMBUS provides a framework for understanding the selective pressures shaping the non-coding genome and its role in human health and disease. |
| 2024 | [Decoding sequence determinants of gene expression in diverse cellular and disease states](http://biorxiv.org/lookup/doi/10.1101/2024.10.09.617507) | bioRxiv | Decima is a model that predicts the cell type- and condition- specific expression of a gene from its surrounding DNA sequence, trained on single-cell or single-nucleus RNA sequencing data from over 22 million cells, and successfully predicts the cell type-s... |
| 2024 | [Discovering CRISPR-Cas system with self-processing pre-crRNA capability by foundation models](https://www.nature.com/articles/s41467-024-54365-0) | Nature Communications |  |
| 2024 | [Dissecting the regulatory logic of specification and differentiation during vertebrate embryogenesis](http://biorxiv.org/lookup/doi/10.1101/2024.08.27.609971) | bioRxiv | This study describes instant differentiation, where pluripotent cells skip intermediate fate transitions and terminally differentiate, and develops a deep learning model to predict chromatin accessibility based on DNA sequence and finds that a small number... |
| 2024 | [Enhancing recognition and interpretation of functional phenotypic sequences through fine-tuning pre-trained genomic models](https://translational-medicine.biomedcentral.com/articles/10.1186/s12967-024-05567-z) | Journal of Translational Medicine | Background Decoding human genomic sequences requires comprehensive analysis of DNA sequence functionality. |
| 2024 | [Fitness translocation: improving variant effect prediction with biologically-grounded data augmentation](http://biorxiv.org/lookup/doi/10.1101/2024.12.17.628831) | bioRxiv | This study presents a novel data augmentation strategy called fitness translocation, which leverages fitness landscapes from related proteins to enhance the performance of variant effect predictors on a target protein to augment its dataset. |
| 2024 | [Flexible use of conserved motif vocabularies constrains genome access in cell type evolution](http://biorxiv.org/lookup/doi/10.1101/2024.09.03.611027) | bioRxiv | It is proposed that long-term stability of cell type families is maintained through genome access specified by conserved motif sets, or 'vocabularies', whereas cell types diversify through flexible use of motifs within each set. |
| 2024 | [Improving prediction performance of general protein language model by domain-adaptive pretraining on DNA-binding protein](https://www.nature.com/articles/s41467-024-52293-7) | Nature Communications |  |
| 2024 | [Integration of variant annotations using deep set networks boosts rare variant association testing](https://www.nature.com/articles/s41588-024-01919-z) | Nature Genetics | Rare genetic variants can have strong effects on phenotypes, yet accounting for rare variants in genetic analyses is statistically challenging due to the limited number of allele carriers and the burden of multiple testing. |
| 2024 | [Integrative analysis of noncoding mutations identifies the druggable genome in preterm birth](https://www.science.org/doi/10.1126/sciadv.adk1057) | Science Advances | This work built deep learning and graphical models to score mutational effects at base resolution and uncovered previously unidentified sPTB genes that are involved in myometrial muscle relaxation and inflammatory responses and that are regulated by the pro... |
| 2024 | [Leveraging Natural Language Processing models to decode the dark proteome across the Animal Tree of Life](http://biorxiv.org/lookup/doi/10.1101/2024.02.28.582465) | bioRxiv | FANTASIA (Functional ANnoTAtion based on embedding space SImilArity) integrates protein language models for large-scale functional annotation and predicts functions to virtually all proteins, revealing previously uncharacterized functions that enhance the u... |
| 2024 | [Machine-guided design of cell-type-targeting cis-regulatory elements](https://www.nature.com/articles/s41586-024-08070-z) | Nature | Cis -regulatory elements (CREs) control gene expression, orchestrating tissue identity, developmental timing and stimulus responses, which collectively define the thousands of unique cell types in the body 1-3 . |
| 2024 | [Optimizing 5'UTRs for mRNA-delivered gene editing using deep learning](https://www.nature.com/articles/s41467-024-49508-2) | Nature Communications | mRNA therapeutics are revolutionizing the pharmaceutical industry, but methods to optimize the primary sequence for increased expression are still lacking. |
| 2024 | [Predicting cell population-specific gene expression from genomic sequence](https://www.frontiersin.org/articles/10.3389/fbinf.2024.1347276/full) | Frontiers in Bioinformatics | Most regulatory elements, especially enhancer sequences, are cell population-specific. |
| 2024 | [Predicting microbial transcriptome using genome sequence](http://biorxiv.org/lookup/doi/10.1101/2024.12.30.630741) | bioRxiv | This work presents TXpredict, a transformer-based framework for predicting microbial transcriptomes using annotated genome sequences that highlights conserved and divergent transcriptional programs across understudied genera, providing a powerful resource f... |
| 2024 | [Quantifying the regulatory potential of genetic variants via a hybrid sequence-oriented model with SVEN](https://www.nature.com/articles/s41467-024-55392-7) | Nature Communications | SVEN is a hybrid sequence-oriented architecture that can accurately predict tissue-specific gene expression level and quantify the tissue-specific transcriptomic impacts of structural variants across more than 350 tissues and cell lines and is expected to e... |
| 2024 | [Regression convolutional neural network models implicate peripheral immune regulatory variants in the predisposition to Alzheimer's disease](https://dx.plos.org/10.1371/journal.pcbi.1012356) | PLOS Computational Biology | Alzheimer's disease (AD) involves aggregation of amyloid β and tau, neuron loss, cognitive decline, and neuroinflammatory responses. |
| 2024 | [Revealing the grammar of small RNA secretion using interpretable machine learning](https://linkinghub.elsevier.com/retrieve/pii/S2666979X24000648) | Cell Genomics | Small non-coding RNAs can be secreted through a variety of mechanisms, including exosomal sorting, in small extracellular vesicles, and within lipoprotein complexes. |
| 2024 | [Single-cell analysis of the epigenome and 3D chromatin architecture in the human retina](http://biorxiv.org/lookup/doi/10.1101/2024.12.28.630634) | bioRxiv | Most genetic risk variants linked to ocular diseases are non-protein coding and presumably contribute to disease through dysregulation of gene expression, however, deeper understanding of their mechanisms of action has been impeded by an incomplete annotati... |
| 2024 | [Single-cell chromatin accessibility reveals malignant regulatory programs in primary human cancers](https://www.science.org/doi/10.1126/science.adk9217) | Science | To identify cancer-associated gene regulatory changes, we generated single-cell chromatin accessibility landscapes across eight tumor types as part of The Cancer Genome Atlas. |
| 2024 | [Systematic discovery of directional regulatory motifs associated with human insulator sites](http://biorxiv.org/lookup/doi/10.1101/2024.01.20.573595) | bioRxiv | A systematic, comprehensive deep learning-based approach for identifying the DNA motifs of DBPs associated with insulators, and found that the key regulator MyoD-binding site is located at an insulator site near a gene involved in skeletal muscle differenti... |
| 2024 | [Targeted design of synthetic enhancers for selected tissues in the Drosophila embryo](https://www.nature.com/articles/s41586-023-06905-9) | Nature | Deep learning and transfer learning are combined to design tissue-specific enhancers for five tissues in the Drosophila melanogaster embryo, yielding models with 13% to 76% positive predictive value according to cross-validation. |
| 2024 | [The potential of regulatory variant prediction AI models to improve cattle traits](http://biorxiv.org/lookup/doi/10.1101/2024.08.01.606140) | bioRxiv | A new framework for predicting regulatory variants, that includes deriving key conservation metrics in cattle for the first time, variant annotation and model training is developed, that has potential utility for fine-mapping functional variants and improvi... |
| 2024 | [The regulatory grammar of human promoters uncovered by MPRA-trained deep learning](http://biorxiv.org/lookup/doi/10.1101/2024.07.09.602649) | bioRxiv | PARM, a cell-type specific deep learning model trained on specially designed massively parallel reporter assays that query human promoter sequences, captures regulatory grammar of human promoters and lays the foundation towards a deep understanding of the r... |
| 2024 | [Using a comprehensive atlas and predictive models to reveal the complexity and evolution of brain-active regulatory elements](https://www.science.org/doi/10.1126/sciadv.adj4452) | Science Advances | Most genetic variants associated with psychiatric disorders are located in noncoding regions of the genome. |
| 2024 | [Using artificial intelligence to document the hidden RNA virosphere](https://linkinghub.elsevier.com/retrieve/pii/S0092867424010857) | Cell | A deep learning algorithm that integrates both sequence and predicted structural information was employed to identify highly divergent RNA viral "dark matter" in 10,487 metatranscriptomes from diverse global ecosystems, identifying 161,979 potential RNA vir... |
| 2024 | [Variants in tubule epithelial regulatory elements mediate most heritable differences in human kidney function](https://www.nature.com/articles/s41588-024-01904-6) | Nature Genetics |  |
| 2024 | [Vocal learning-associated convergent evolution in mammalian proteins and regulatory elements](https://www.science.org/doi/10.1126/science.abn3263) | Science | Vocal production learning ("vocal learning") is a convergently evolved trait in vertebrates. |
| 2024 | [msBERT-Promoter: a multi-scale ensemble predictor based on BERT pre-trained model for the two-stage prediction of DNA promoters and their strengths](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-024-01923-z) | BMC Biology | Background A promoter is a specific sequence in DNA that has transcriptional regulatory functions, playing a role in initiating gene expression. |
| 2023 | [A comparative atlas of single-cell chromatin accessibility in the human brain](https://www.science.org/doi/10.1126/science.adf7044) | Science | Recent advances in single-cell transcriptomics have illuminated the diverse neuronal and glial cell types within the human brain. |
| 2023 | [An analytical framework for decoding cell type-specific genetic variation of gene regulation](https://doi.org/10.1038/s41467-023-39538-7) | Nature Communications | Huatuo is introduced, a framework to decode genetic variation of gene regulation at cell type and single-nucleotide resolutions by integrating deep-learning-based variant predictions with population-based association analyses and shows that it permits prior... |
| 2023 | [Chromatin accessibility in the Drosophila embryo is determined by transcription factor pioneering and enhancer activation](https://linkinghub.elsevier.com/retrieve/pii/S1534580723003477) | Developmental Cell | Chromatin accessibility is integral to the process by which transcription factors (TFs) read out cis-regulatory DNA sequences, but it is difﬁcult to differentiate between TFs that drive accessibility and those that do not. |
| 2023 | [Computational Assessment of the Expression-Modulating Potential for Non-Coding Variants](https://academic.oup.com/gpb/article/21/3/662/7588909) | Genomics, Proteomics & Bioinformatics | Carmen, a novel algorithm to identify functional non-coding expression-modulating variants that scales well with the massive datasets, and is available online as a web server at http://carmen.gao-lab.org. |
| 2023 | [Conserved and divergent gene regulatory programs of the mammalian neocortex](https://www.nature.com/articles/s41586-023-06819-6) | Nature | Divergence of cis- regulatory elements drives species-specific traits 1 , but how this manifests in the evolution of the neocortex at the molecular and cellular level remains unclear. |
| 2023 | [De novo distillation of thermodynamic affinity from deep learning regulatory sequence models of in vivo protein-DNA binding](http://biorxiv.org/lookup/doi/10.1101/2023.05.11.540401) | bioRxiv | Affinity Distillation (AD) is developed, a method that extracts thermodynamic affinities de-novo from deep learning models of TF chromatin immunoprecipitation experiments by marginalizing away the influence of genomic sequence context. |
| 2023 | [Genome-wide Functional Characterization of Escherichia coli Promoters and Sequence Elements Encoding Their Regulation](https://doi.org/10.7554/eLife.92558.1) | eLife | Despite decades of intense genetic, biochemical, and evolutionary characterizations of bacterial promoters, we lack the ability to identify or predict transcriptional activities of promoters using primary sequence. |
| 2023 | [Genome-wide prediction of disease variant effects with a deep protein language model](https://www.nature.com/articles/s41588-023-01465-0) | Nature Genetics | Predicting the effects of coding variants is a major challenge. While recent deep-learning models have improved variant effect prediction accuracy, they cannot analyze all coding variants due to dependency on close homologs or software limi |
| 2023 | [Integrative dissection of gene regulatory elements at base resolution](https://linkinghub.elsevier.com/retrieve/pii/S2666979X23000861) | Cell Genomics | Although vast numbers of putative gene regulatory elements have been cataloged, the sequence motifs and individual bases that underlie their functions remain largely unknown. |
| 2023 | [Learning functional conservation between human and pig to decipher evolutionary mechanisms underlying gene expression and complex traits](https://linkinghub.elsevier.com/retrieve/pii/S2666979X23001878) | Cell Genomics | Assessment of genomic conservation between humans and pigs at the functional level can improve the potential of pigs as a human biomedical model. |
| 2023 | [MalariaSED: a deep learning framework to decipher the regulatory contributions of noncoding variants in malaria parasites](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03063-z) | Genome Biology | Applying MalariaSED to 1.3 million variants shows that geographically differentiated noncoding variants are associated with parasite invasion and drug resistance, and reveals chromatin accessibility changes at Plasmodium falciparum rings are partly associat... |
| 2023 | [Modeling islet enhancers using deep learning identifies candidate causal variants at loci associated with T2D and glycemic traits](https://pnas.org/doi/10.1073/pnas.2206612120) | Proceedings of the National Academy of Sciences | Genetic association studies have identified hundreds of independent signals associated with type 2 diabetes (T2D) and related traits. |
| 2023 | [Predicting the impact of sequence motifs on gene regulation using single-cell data](https://doi.org/10.1186/s13059-023-03021-9) | Genome Biology | The binding of transcription factors at proximal promoters and distal enhancers is central to gene regulation. |
| 2023 | [Relating enhancer genetic variation across mammals to complex phenotypes using machine learning](https://www.science.org/doi/10.1126/science.abm7993) | Science | The Tissue-Aware Conservation Inference Toolkit (TACIT) is developed to associate candidate enhancers with species' phenotypes using predictions from machine learning models trained on specific tissues and cell types, and suggests that these phenotypes have... |
| 2023 | [Single-cell analysis of chromatin accessibility in the adult mouse brain](https://www.nature.com/articles/s41586-023-06824-9) | Nature | Recent advances in single-cell technologies have led to the discovery of thousands of brain cell types; however, our understanding of the gene regulatory programs in these cell types is far from complete 1-4 . |
| 2023 | [The EN-TEx resource of multi-tissue personal epigenomes & variant-impact models](https://linkinghub.elsevier.com/retrieve/pii/S0092867423001617) | Cell | Combining EN-TEx with existing genome annotations reveals strong associations between allele-specific and GWAS loci and enables models for transferring known eQTLs to difficult-to-profile tissues, and provides rich data and generalizable models for more acc... |
| 2023 | [The evolution and mutational robustness of chromatin accessibility in](https://doi.org/10.1186/s13059-023-03079-5) | Genome Biology | Background: The evolution of genomic regulatory regions plays a critical role in shaping the diversity of life. |
| 2023 | [The full set of potential open regions (PORs) in the human genome defined by consensus peaks of ATAC-seq data](https://doi.org/10.1101/2023.05.30.542889) | bioRxiv |  |
| 2023 | [Transcription factor stoichiometry, motif affinity and syntax regulate single-cell chromatin dynamics during fibroblast reprogramming to pluripotency](http://biorxiv.org/lookup/doi/10.1101/2023.10.04.560808) | bioRxiv | Together, the integrated single-cell resource and models reveal insights into the cis-regulatory code of reprogramming at unprecedented resolution, connect TF stoichiometry and motif syntax to diversification of cell fate trajectories, and provide new persp... |
| 2022 | [Annotating functional effects of non-coding variants in neuropsychiatric cell types by deep transfer learning](https://dx.plos.org/10.1371/journal.pcbi.1010011) | PLOS Computational Biology | By combining GWAS data with MetaChrom predictions, the prioritized 31 SNPs for Schizophrenia, suggesting potential risk genes and the biological contexts where they act and the general method can also be extended to other disease-related cell or tissue types. |
| 2022 | [Decoding gene regulation in the fly brain](https://www.nature.com/articles/s41586-021-04262-z) | Nature |  |
| 2022 | [Deep learning modeling m6A deposition reveals the importance of downstream cis-element sequences](https://www.nature.com/articles/s41467-022-30209-7) | Nature Communications | The N 6 -methyladenosine (m 6 A) modification is deposited to nascent transcripts on chromatin, but its site-specificity mechanism is mostly unknown. |
| 2022 | [Deep learning of cross-species single-cell landscapes identifies conserved regulatory programs underlying cell types](https://www.nature.com/articles/s41588-022-01197-7) | Nature Genetics | This work developed a deep-learning-based strategy, Nvwa, to predict gene expression and identify regulatory sequences at the single-cell level, and systematically compared cell-type-specific transcription factors to reveal conserved genetic regulation in v... |
| 2022 | [Deep learning predicts DNA methylation regulatory variants in the human brain and elucidates the genetics of psychiatric disorders](https://pnas.org/doi/full/10.1073/pnas.2206069119) | Proceedings of the National Academy of Sciences | This study demonstrates that deep learning-derived DNAm regulatory variants are not confounded by LD, are convergent with mQTL evidence from genetic association analysis, and underlie the genetic basis of brain-related traits. |
| 2022 | [DeepSTARR predicts enhancer activity from DNA sequence and enables the de novo design of synthetic enhancers](https://www.nature.com/articles/s41588-022-01048-5) | Nature Genetics |  |
| 2022 | [Designing sensitive viral diagnostics with machine learning](https://www.nature.com/articles/s41587-022-01213-5) | Nature Biotechnology | This work introduces Activity-informed Design with All-inclusive Patrolling of Targets (ADAPT), a system for automated design, and uses it to design diagnostics for 1,933 vertebrate-infecting viral species within 2'hours for most species and within 24 hours... |
| 2022 | [Inferring mammalian tissue-specific regulatory conservation by predicting tissue-specific differences in open chromatin](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-022-08450-7) | BMC Genomics | The framework presented here provides a mechanism to annotate tissue-specific regulatory function across hundreds of genomes and to study enhancer evolution using predicted regulatory differences rather than nucleotide-level conservation measurements. |
| 2022 | [Integrative single-cell analysis of cardiogenesis identifies developmental trajectories and non-coding mutations in congenital heart disease](https://linkinghub.elsevier.com/retrieve/pii/S0092867422015033) | Cell | To deﬁne the multi-cellular epigenomic and transcriptional landscape of cardiac cellular development, we generated single-cell chromatin accessibility maps of human fetal heart tissues. |
| 2022 | [Sequence determinants of human gene regulatory elements](https://www.nature.com/articles/s41588-021-01009-4) | Nature Genetics | DNA can determine where and when genes are expressed, but the full set of sequence determinants that control gene expression is unknown. |
| 2022 | [Single-cell multiome of the human retina and deep learning nominate causal variants in complex eye diseases](https://linkinghub.elsevier.com/retrieve/pii/S2666979X22001069) | Cell Genomics | A joint single-cell atlas of gene expression and chromatin accessibility of the adult human retina with >50,000 cells is presented, which is used to analyze noncoding single-nucleotide polymorphisms implicated by GWAS of age-related macular degeneration, gl... |
| 2022 | [The evolution, evolvability and engineering of gene regulatory DNA](https://www.nature.com/articles/s41586-022-04506-6) | Nature |  |
| 2022 | [scBasset: sequence-based modeling of single-cell ATAC-seq using convolutional neural networks](https://www.nature.com/articles/s41592-022-01562-8) | Nature Methods | It is shown that by leveraging the DNA sequence information underlying accessibility peaks and the expressiveness of a neural network model, scBasset achieves state-of-the-art performance across a variety of tasks on scATAC and single-cell multiome datasets... |
| 2021 | [Chromatin and gene-regulatory dynamics of the developing human cerebral cortex at single-cell resolution](https://linkinghub.elsevier.com/retrieve/pii/S0092867421009429) | Cell | Genetic perturbations of cortical development can lead to neurodevelopmental disease, including autism spectrum disorder (ASD). |
| 2021 | [Deep neural networks identify sequence context features predictive of transcription factor binding](https://www.nature.com/articles/s42256-020-00282-y) | Nature Machine Intelligence | A machine-learning framework leveraging existing convolutional neural network architectures and model interpretation techniques to identify and interpret sequence context features most important for predicting whether a particular motif instance will be bou... |
| 2021 | [DeepFun: a deep learning sequence-based model to decipher non-coding variant effect in a tissue- and cell type-specific manner](https://academic.oup.com/nar/article/49/W1/W131/6287843) | Nucleic Acids Research | A user-friendly web server to assess the functional activity of non-coding genetic variants, built on a convolutional neural network (CNN) framework that has been extensively evaluated and expected to be widely used in genetics, functional genomics, and dis... |
| 2021 | [Global properties of regulatory sequences are predicted by transcription factor recognition mechanisms](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02503-y) | Genome Biology | Background: Mammalian genomes contain millions of putative regulatory sequences, which are delineated by binding of multiple transcription factors. |
| 2021 | [Leveraging supervised learning for functionally informed fine-mapping of cis-eQTLs identifies an additional 20,913 putative causal eQTLs](https://www.nature.com/articles/s41467-021-23134-8) | Nature Communications | The large majority of variants identified by GWAS are non-coding, motivating detailed characterization of the function of non-coding variants. |
| 2021 | [REVA as A Well-Curated Database for Human Expression-Modulating Variants](https://academic.oup.com/gpb/article/19/4/590/7230396) | Genomics, Proteomics & Bioinformatics | REVA provides high-qualify experimentally tested expression-modulating variants with extensive functional annotations, which will be useful for users in the noncoding variants community. |
| 2021 | [The dynamic, combinatorial cis-regulatory lexicon of epidermal differentiation](https://www.nature.com/articles/s41588-021-00947-3) | Nature Genetics |  |
| 2020 | [Deep learning of immune cell differentiation](https://pnas.org/doi/full/10.1073/pnas.2011795117) | Proceedings of the National Academy of Sciences | Applying artificial intelligence tools to a highly complex question of immunology, we show that a deep neural network can learn to predict the patterns of chromatin opening across 81 stem and differentiated cells across the immune system, solely from the DN... |
| 2020 | [Deep learning suggests that gene expression is encoded in all parts of a co-evolving interacting gene regulatory structure](https://www.nature.com/articles/s41467-020-19921-4) | Nature Communications | Understanding the genetic regulatory code governing gene expression is an important challenge in molecular biology. |
| 2020 | [Genomic analyses implicate noncoding de novo variants in congenital heart disease](https://www.nature.com/articles/s41588-020-0652-z) | Nature Genetics | Computational analyses integrating whole-genome sequencing, cardiac epigenomic data and RNA-binding-protein data identify a role for noncoding de novo mutations in congenital heart disease. |
| 2020 | [Sequence-specific prediction of the efficiencies of adenine and cytosine base editors](https://www.nature.com/articles/s41587-020-0573-5) | Nature Biotechnology | Using deep-learning-based computational modeling, tools are built to predict the efficiencies and outcome frequencies of ABE- and CBE-directed editing at any target sequence, with Pearson correlations ranging from 0.50 to 0.95. |
| 2019 | [Deciphering regulatory DNA sequences and noncoding genetic variants using neural network models of massively parallel reporter assays](https://dx.plos.org/10.1371/journal.pone.0218073) | PLOS ONE | The relationship between noncoding DNA sequence and gene expression is not well-understood. |
| 2019 | [Deep Learning Implicitly Handles Tissue Specific Phenomena to Predict Tumor DNA Accessibility and Immune Activity](https://linkinghub.elsevier.com/retrieve/pii/S2589004219303566) | iScience | DNA accessibility is a key dynamic feature of chromatin regulation that can potentiate transcriptional events and tumor progression. |
| 2019 | [Saturation mutagenesis of twenty disease-associated regulatory elements at single base-pair resolution](https://www.nature.com/articles/s41467-019-11526-w) | Nature Communications | The majority of common variants associated with common diseases, as well as an unknown proportion of causal mutations for rare diseases, fall in noncoding regions of the genome. |
| 2019 | [Whole-genome deep-learning analysis identifies contribution of noncoding mutations to autism risk](https://www.nature.com/articles/s41588-019-0420-0) | Nature Genetics |  |
| 2018 | [Discovering epistatic feature interactions from neural network models of regulatory DNA sequences](https://academic.oup.com/bioinformatics/article/34/17/i629/5093210) | Bioinformatics | This work presents a new method called Deep Feature Interaction Maps (DFIM) to efficiently estimate interactions between all pairs of features in any input DNA sequence and makes significant strides in improving the interpretability of deep learning models... |
| 2017 | [Deep learning of the regulatory grammar of yeast 5′ untranslated regions from 500,000 random sequences](http://genome.cshlp.org/lookup/doi/10.1101/gr.224964.117) | Genome Research | Our ability to predict protein expression from DNA sequence alone remains poor, reflecting our limited understanding of cis -regulatory grammar and hampering the design of engineered genes for synthetic biology applications. |

</details>
