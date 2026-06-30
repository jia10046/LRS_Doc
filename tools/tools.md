# LRS_Tools: Long-Read Transcriptomics Analysis Toolkit
Full collection of long-read sequencing (LRS) transcriptome analysis tools, including functional annotations, GitHub links, and publication year.  
Tools marked with **※** are recommended.

## 📋 Full Tool List

### Basecalling
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※Dorado | ONT’s current production basecaller with GPU acceleration, supporting high-accuracy RNA and DNA basecalling, duplex calling, and integrated modification-aware models for simultaneous sequence and RNA modification detection. | https://github.com/nanoporetech/dorado | 2023 |
| ※DeepConsensus | Deep learning model for generating consensus sequences for PacBio cDNA sequencing to produce HiFi reads. | https://github.com/google/deepconsensus | 2022 |
| Guppy | A C++-based closed-source ONT basecaller that replaced Albacore, supporting GPU-accelerated high-accuracy basecalling for DNA and RNA. | | 2018 |
| Bonito | An open-source research basecaller developed by ONT based on PyTorch, enabling customizable neural network architectures and training for experimental nanopore basecalling models. | https://github.com/nanoporetech/bonito | 2020 |
| RODAN | A deep learning–based nanopore basecaller employing advanced neural network architectures to improve raw signal decoding accuracy. | https://github.com/biodlab/RODAN | 2022 |
| GCRTcall | A neural network–based nanopore basecaller optimized for improved accuracy and robustness in decoding ionic current signals from ONT sequencing data. | https://github.com/liqingwen98/GCRTcall | 2024 |
| DEMINERS | A deep learning framework for nanopore signal decoding that enhances basecalling performance and supports modification-aware sequence interpretation. | https://github.com/LuChenLab/DEMINERS | 2025 |
| Coral | A neural network–based nanopore basecaller designed to improve signal-to-sequence translation accuracy, particularly for challenging signal regions such as homopolymers. | https://github.com/BioinfoSZU/Coral | 2026 |
| SqueezeCall | Combines CNNs with a Squeezeformer and a CTC CRF decoder to reduce errors on multi species datasets, supports both direct RNA sequencing and cDNA sequencing. | https://github.com/labcbb/SqueezeCall | 2024 |
| BaseNet | Provides an open source framework that supports autoregressive models, non autoregressive models, and large pre trained models, supports both direct RNA sequencing and cDNA sequencing. | https://github.com/liqingwen98/BaseNet | 2024 |
| Chiron | Deep learning‑based nanopore basecaller that uses a recurrent neural network (RNN) with connectionist temporal classification (CTC) to translate raw ionic current signals directly into DNA sequences. | https://github.com/haotianteng/Chiron | 2018 |
| MinCall | Fast and lightweight nanopore basecaller designed for real‑time applications, employing a minimal neural network architecture to achieve efficient signal‑to‑sequence conversion with low computational overhead. | https://github.com/nmiculinic/minion-basecaller | 2017 |
| DeepNano | Early deep learning‑based nanopore basecaller that uses bidirectional recurrent neural networks (BRNNs) to improve basecalling accuracy compared to hidden Markov model (HMM)‑based approaches. | https://github.com/fmfi-compbio/deepnano-blitz | 2016 |
| SACall | Neural network‑based nanopore basecaller that incorporates a squeeze‑and‑excitation (SE) attention mechanism to enhance feature extraction from raw signals, improving accuracy for homopolymer regions. | https://github.com/huangnengCSU/SACall-basecaller | 2023 |
| Causalcall | Deep learning basecaller for Oxford Nanopore sequencing data that applies causal convolutions and dilated convolutions to capture long‑range dependencies in ionic current signals, enabling parallelized and efficient basecalling. | https://github.com/scutbioinformatic/causalcall | 2021 |
| DemuxTrans | Integrates 1D CNNs, Transformers, and Temporal Convolutional Networks to improve accuracy, supports both direct RNA sequencing and cDNA sequencing. | https://github.com/LiyuanShu116/Demuxtrans | 2025 |
| m6Abasecaller | Detects RNA modifications (m6A) by estimating per read modification probabilities during or after basecalling using trained neural networks. | https://github.com/novoalab/m6ABasecaller | 2025 |

### Quality control
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※LongQC | Provides reference-free quality assessment for major third-generation sequencing platforms (PacBio and ONT). | https://github.com/yfukasawa/LongQC | 2020 |
| ※NanoPlot | Quality control and visualization tool for long-read sequencing data (ONT and PacBio), generating interactive plots of read length distributions, quality scores, GC content, and yield summaries. | https://github.com/wdecoster/NanoPlot | 2018 |
| ※LongReadSum | Generates comprehensive statistical summaries of raw sequencing output, including read length, yield, and quality-related distributions. | https://github.com/WGLab/LongReadSum | 2024 |
| pycoQC | Parses Oxford Nanopore sequencing summary files to generate interactive HTML reports for post-run evaluation. | https://github.com/a-slide/pycoQC | 2018 |
| MinKNOW | Performs real-time signal-level monitoring and run control during Oxford Nanopore sequencing. | https://github.com/nanoporetech/minknow_api | 2018 |
| fastplong | Integrates QC reporting with read filtering, adapter trimming, and poly(A) tail processing for full-length cDNA and transcriptome-oriented workflows. | https://github.com/OpenGene/fastplong | 2024 |
| MultiQC | Aggregates results from multiple QC tools into a single interactive report for efficient sample and batch comparison. | https://github.com/MultiQC/MultiQC | 2016 |

### Error correction
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※FMLRC | Hybrid correction tool (assembly-based) that uses short read information to correct long reads. | https://github.com/holobench/fmlrc | 2018 |
| ※Canu | Self-correction tool (overlap-based) that computes read-to-read overlaps, builds multiple sequence alignments, and derives consensus sequences. | https://github.com/marbl/canu | 2015 |
| ※FLAMES | UMI-based error correction method that clusters reads and collapses each family into a consensus sequence. | https://github.com/LuyiTian/FLAMES | 2021 |
| Clair3 | A deep learning-based small variant caller for long-read sequencing data. | https://github.com/HKU-BAL/Clair3 | 2022 |
| Medaka | A neural network-based tool for polishing and variant calling from ONT reads. | https://github.com/nanoporetech/medaka | 2018 |
| DeepVariant | A deep learning-based variant caller for SNP and indel detection from sequencing alignments. | https://github.com/google/deepvariant | 2018 |
| Clair3-RNA | A deep learning-based small variant caller tailored for long-read RNA-seq data. | https://github.com/HKU-BAL/Clair3-RNA | 2025 |
| PacBioToCA | Hybrid correction tool (alignment-based) that aligns short reads to long reads and corrects errors using local consensus. | http://wgs-assembler.sourceforge.net/ | 2012 |
| proovread | Hybrid correction tool (alignment-based) for long read error correction using short reads. | https://github.com/BioInf-Wuerzburg/proovread | 2014 |
| Hercules | Hybrid correction tool (alignment-based) that may use deep learning for error correction. | https://github.com/BilkentCompGen/Hercules | 2018 |
| LoRDEC | Hybrid correction tool (assembly-based) that builds de Bruijn graph from short reads to correct erroneous long read segments. | https://bitbucket.org/mvdall/lordec | 2014 |
| Jabba | Hybrid correction tool (assembly-based) for long read error correction using short read de Bruijn graphs. | https://github.com/GATB/Jabba | 2016 |
| HALC | Hybrid correction tool (assembly-based) for long read error correction. | https://github.com/lanl001/halc | 2017 |
| MECAT/NECAT | Self-correction tool (overlap-based) for long read error correction through overlap analysis. | https://github.com/xiaochuanle/NECAT | 2017/2020 |
| CONSENT | Self-correction tool (overlap-based) for long read error correction using consensus methods. | https://github.com/morispi/CONSENT | 2019 |
| NextDenovo | Self-correction tool (overlap-based) for long read error correction through overlap analysis and consensus building. | https://github.com/Nextomics/NextDenovo | 2020 |
| LoRMA | Self-correction tool (graph-based) that iteratively constructs de Bruijn graphs from noisy long reads and refines with multiple sequence alignment. | https://github.com/LM-UG/lorma | 2016 |
| Longcell | UMI-based error correction method for UMI tagged long read protocols in single cell and spatial transcriptomics. | https://github.com/yuntianf/Longcell | 2024 |
| ScNaUmi-seq | UMI-based error correction method that clusters reads from same original molecule to reduce random and PCR errors. | https://github.com/S-and-J/ScNaUmi-seq | 2021 |
| ConSeqUMI | UMI-based error correction method using pairwise consensus strategy, reported to be two orders of magnitude faster than conventional approaches. | https://github.com/GenomicaMicrob/ConSeqUMI | 2023 |
| UMI-nea | UMI-based error correction method that replaces Hamming distance with Levenshtein distance to improve read grouping. | https://github.com/yyoshiaki/UMI-nea | 2022 |
| DeepCorr | Deep learning-based correction method that trains neural networks to capture contextual dependencies and platform-specific error profiles. | https://github.com/S-and-J/DeepCorr | 2019 |
| NmTHC | Deep learning-based correction method for long read error correction using neural networks. | https://github.com/RinoYuki/NmTHC | 2021 |

### Read alignment
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※minimap2 | Fast minimizer-based splice-aware aligner and the de facto standard for long-read transcriptomic alignment, with presets for PacBio Iso-Seq, ONT cDNA, and ONT direct RNA sequencing. | https://github.com/lh3/minimap2 | 2018 |
| Graphmap2 | Hashing-based splice-aware long-read aligner that improves alignment recall and can more precisely place exon and transcript boundaries. | https://github.com/lbcb-sci/graphmap2 | 2019 |
| deSALT | Splice-aware long-read aligner using a de Bruijn graph-based index to better tolerate sequencing errors and improve recovery of small exons. | https://github.com/ydLiu-HIT/deSALT | 2019 |
| BWA-MEM2 | BWT-FM–based aligner supporting fast local and end-to-end alignment as well as chimeric alignment reporting, though not primarily optimized for long-read spliced transcript alignment. | https://github.com/bwa-mem2/bwa-mem2 | 2019 |
| UTRAL | BWT-FM–based aligner that applies parallel loss-free maximal exact match retrieval and is well suited to small exons and complex splice-site detection. | https://github.com/ydLiu-HIT/UTRAL | 2023 |
| STAR | Suffix-array–based RNA-seq aligner widely used in transcriptomics and extendable to long-read mapping, although less commonly used than minimap2 for noisy long reads. | https://github.com/alexdobin/STAR | 2013 |
| 2passtools | Post-alignment refinement toolkit that uses machine learning to filter false splice sites and improve splice-junction accuracy from general-purpose aligners such as minimap2. | https://github.com/dieterich-lab/2passtools | 2021 |
| Splam | Machine learning–based splice-junction validation tool that filters likely false splice sites from long-read alignments to improve junction reliability. | https://github.com/Kuanhao-Chao/splam | 2023 |
| FLAIR | Long-read transcriptome toolkit that includes post-alignment splice-site correction to reduce junction errors in noisy ONT alignments before isoform reconstruction. | https://github.com/BrooksLabUCSC/flair | 2020 |

### Isoform identification
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※IsoQuant | Graph-based reference-guided tool that mitigates long-read alignment noise and reduces false positives in novel isoform calls, ranked first in LRGASP benchmark. | https://github.com/ablab/IsoQuant | 2023 |
| ※StringTie3 | Transcript assembly from long-read alignments based on reference genome and annotation. | https://github.com/gpertea/stringtie | 2026 |
| ※Bambu | Reconstruction and merging of transcript structures from long reads, with identification of novel isoforms to accommodate uneven full-length coverage. | https://github.com/GoekeLab/bambu | 2023 |
| ※FLAIR | Post-alignment splice site correction and transcript assembly for ONT long reads, mitigating the impact of ONT sequencing errors on splice junction detection. | https://github.com/BrooksLabUCSC/flair | 2020 |
| TALON | Classification and annotation summarization of known and novel transcripts from long reads, generating transcript sets suitable for downstream quantification. | https://github.com/dewyman/TALON | 2020 |
| SQANTI3 | Structural and quality annotation framework for long-read transcript models that classifies isoforms, evaluates splice junctions, detects artifacts, and supports transcript filtering. | https://github.com/ConesaLab/SQANTI3 | 2021 |
| IsoTools | Analytical framework for transcript classification, novel isoform discovery, and splicing event summarization in long-read transcriptomes. | https://github.com/MatthiasLienhard/isotools | 2023 |
| LRAA | Unified framework integrating splice-graph modeling and EM-based optimization for isoform identification and quantification across bulk, single-cell, and single-nucleus long-read data, supporting reference-guided, de novo, and quantification-only modes. | https://github.com/MethodsDev/LongReadAlignmentAssembler | 2026 |
| Mandalorion | Identification of splice isoforms and generation of transcript models from ONT long reads, suitable for rapid isoform catalog generation within the ONT ecosystem. | https://github.com/mandalorion-evidence/mandalorion | 2023 |
| ESPRESSO | Splice site error correction in long reads prior to isoform identification, reducing false splice junctions caused by higher LRS error rates. | https://github.com/Xinglab/espresso | 2023 |
| Freddie | Clustering long reads by splicing structure and inferring isoforms under weak or absent annotation, suitable for exploratory LRS datasets. | https://github.com/vpc-ccg/freddie | 2023 |
| FLAMES | Isoform identification and organization for long-read transcriptomes, commonly used to standardize long-read transcript sets for comparative analysis. | https://github.com/LuyiTian/FLAMES | 2021 |
| isONclust2 | A long-read transcript clustering tool for grouping transcript reads into gene- or isoform-level clusters. | https://github.com/nanoporetech/isonclust2 | 2022 |
| Transgram | A long-read transcriptome analysis tool for transcript model construction and refinement. | https://github.com/yutingsdu/TransGram | 2025 |
| IsoSplitter | Partitioning and classification of long reads by splicing and structural features, facilitating the dissection of complex isoforms and alternative splicing patterns in LRS data. | https://github.com/Hengfu-Yin/IsoSplitter | 2021 |
| RNA-Bloom2 | De novo or weak-reference transcript assembly tools that support LRS, useful for constructing transcript sequence sets when annotation is incomplete or reference genomes are limited. | https://github.com/bcgsc/RNA-Bloom | 2023 |
| rnaSPAdes | De novo transcriptome assembly to recover transcripts absent from reference annotations. | https://github.com/ablab/spades | 2019 |
| LyRic | Transcript identification and expression analysis tools or pipelines tailored to ONT characteristics. | https://github.com/guigolab/LyRic | 2021 |
| RATTLE | Reference-free clustering of ONT reads to generate transcript consensus sequences, enabling isoform reconstruction without reliable reference genomes. | https://github.com/comprna/RATTLE | 2022 |
| isONform | Reference-free clustering and reconstruction of ONT transcripts, improving structural consistency under high sequencing error rates. | https://github.com/ksahlin/isONform | 2023 |
| Isosceles | ONT-oriented isoform clustering and integration approaches, suitable for consolidating LRS reads into high-confidence transcript structure sets. | https://github.com/Genentech/Isosceles | 2024 |
| Isotools 2.0 | Graph-based reference-guided tool emphasizing systematic alternative-splicing analysis and differential splicing profiling, high sensitivity for novel transcripts. | https://github.com/MatthiasLienhard/isotools | 2023 |
| ISAtools | Classification-based reference-guided tool introducing Splice Site Chain format, implements systematic error correction, uses DBSCAN clustering for TSS/TES. | https://github.com/Xinglab/ISAtools | 2024 |
| IsoSeq3 | De novo assembly tool (clustering-based) from PacBio, identifies transcripts by clustering single-molecule long reads and generating consensus sequences. | https://github.com/ylipacbio/IsoSeq3 | 2018 |

### Isoform quantification
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※Bambu | Simultaneous transcript construction/integration and isoform quantification from LRS, suitable when unannotated transcripts are present. | https://github.com/GoekeLab/bambu | 2023 |
| ※IsoQuant | Transcript identification and quantification from long reads with consistency assessment, suitable for robust estimation under uneven full-length coverage. | https://github.com/ablab/IsoQuant | 2023 |
| ※FLAIR | Isoform-level counting of LRS based on corrected splice sites and transcript sets, reducing the impact of mismatches and mis-splicing on quantification. | https://github.com/BrooksLabUCSC/flair | 2020 |
| ※miniQuant | Lightweight quantification tool that integrates long- and short-read data, uses K value (generalized condition number) to balance data contributions. | https://github.com/Augroup/miniQuant | 2025 |
| isONform | De novo assembly tool (clustering-based) that reconstructs isoforms by iterative bubble elimination on gene graphs, higher sensitivity than RATTLE. | https://github.com/ksahlin/isONform | 2023 |
| TALON | Classification and counting of LRS within a known/novel transcript framework, producing consistent transcript expression matrices. | https://github.com/dewyman/TALON | 2020 |
| NanoCount | Direct assignment of ONT reads to transcripts or genes based on alignment results for baseline long-read quantification. | https://github.com/a-slide/NanoCount | 2021 |
| Salmon | Rapid transcript expression estimation (for LRS, requiring attention to 3′ bias and alignment/indexing strategies). | https://github.com/COMBINE-lab/salmon | 2015 |
| lr-kallisto | Long-read–oriented transcript quantification applicable to LRS, though sensitive to read errors and coverage bias; often used as a comparison method. | https://github.com/pachterlab/kallisto | 2025 |
| LRAA | Unified framework integrating splice-graph modeling and EM-based optimization for isoform identification and quantification across bulk, single-cell, and single-nucleus long-read data, supporting reference-guided, de novo, and quantification-only modes. | https://github.com/MethodsDev/LongReadAlignmentAssembler | 2026 |
| Isosceles | Isoform-level expression estimation within the ONT ecosystem, consolidating LRS at the transcript level. | https://github.com/Genentech/Isosceles | 2024 |
| IsoTools | Quantification of LRS transcripts with support for splicing and isoform usage change summarization. | https://github.com/MatthiasLienhard/isotools | 2023 |
| LIQA | Estimation of isoform expression and detection of differential isoform usage, leveraging LRS to distinguish closely related isoforms. | https://github.com/WGLab/LIQA | 2021 |
| Freddie | Clustering long reads by splicing structure and inferring isoforms under weak or absent annotation, suitable for exploratory LRS datasets. | https://github.com/vpc-ccg/freddie | 2023 |
| Mandalorion | Integrated ONT workflow outputs of isoform counts and expression estimates, serving as unified solutions for LRS isoform quantification. | https://github.com/christopher-vollmers/Mandalorion | 2023 |
| ESPRESSO | Bias-aware quantification tool with dedicated filtering strategies targeting chimeric reads and RT template switching artifacts. | https://github.com/Xinglab/espresso | 2023 |
| IsoSeq3 | Platform-specific (PacBio) quantification tool relying on upstream error correction (CCS), uses hard assignment for read counting. | https://github.com/ylipacbio/IsoSeq3 | 2018 |
| RATTLE | Platform-specific (ONT) quantification tool applying clustering-based consensus error correction, uses read counting for abundance estimates. | https://github.com/comprna/RATTLE | 2022 |
| JOLI | Cross-platform quantification tool incorporating platform-aware error models, integrates long- and short-read data using empirical Bayesian hierarchical framework. | https://github.com/Xinglab/JOLI | 2024 |
| StringTie3 | Lightweight quantification tool that combines transcript assembly with basic quantification capabilities. | https://github.com/gpertea/stringtie | 2026 |
| FLAMES | Assembly-based quantification tool that resolves inconsistent reads and provides quantification for bulk and single-cell data. | https://github.com/LuyiTian/FLAMES | 2021 |
| IsoSplitter | Assembly-based quantification tool that includes quantification capabilities after transcript identification. | https://github.com/Hengfu-Yin/IsoSplitter | 2021 |
| Oarfish | Assembly-based quantification tool that combines transcript assembly with expression estimation. | https://github.com/COMBINE-lab/oarfish | 2023 |
| ISAtools | Assembly-based quantification tool that provides quantification after systematic error correction and isoform identification. | https://github.com/Xinglab/ISAtools | 2024 |
| MPAQT | Hybrid (long+short read) quantification tool that integrates both data types within a unified likelihood framework using EM algorithm. | https://github.com/esbg/MPAQT | 2023 |

### Post-Quality control
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※SQANTI-reads | Evaluates read level and expression level signals (inter-sample correlation, batch effects) to reduce quantification bias and confirm consistency. | https://github.com/ConesaLab/SQANTI3 | 2023 |
| AlignQC | Uses LRGASP dataset to build error feature library, separates sequencing errors from alignment artifacts, summarizes alignment error patterns with static plots. | https://github.com/jason-weirather/AlignQC | 2016 |

### TE detection
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※TLDR | Long-read TE detection tool that aligns reads to reference genome and TE consensus libraries (using minimap2) for accurate breakpoint inference. | https://github.com/adamewing/tldr | 2021 |
| ※xTea | Long-read TE detection tool with statistical filtering and clustering optimization to improve detection specificity and robustness. | https://github.com/parklab/xTea | 2021 |
| ※sTELLeR | Long-read TE detection tool that incorporates statistical filtering and clustering optimization for improved TE insertion detection. | https://github.com/Boyle-Lab/sTELLeR | 2024 |
| ※TE-Seq | Profiles transposable element expression from RNA sequencing data. | https://github.com/maxfieldk/TE-Seq | 2025 |
| PALMER | Long-read TE detection tool that resolves complete TE structures by locally reassembling candidate insertion regions. | https://github.com/WeichenZhou/PALMER | 2020 |
| TrEMOLO | Long-read TE detection tool that locally reassembles candidate regions and incorporates statistical filtering for TE insertion detection. | https://github.com/D-I-L/TrEMOLO | 2022 |

### TE quantification
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※LongTEQuant | Quantifies transposable element-derived transcripts from long-read RNA sequencing data. | https://github.com/gaoshiwen/LongTEQuant | 2026 |
| ※LocusMasterTE | Integrates long- and short-read evidence for locus-level transposable element quantification. | https://github.com/jasonwong-lab/LocusMasterTE | 2025 |
| TEtranscripts | Quantifies transposable element expression from RNA-seq data while accounting for ambiguously mapped reads. | https://github.com/mhammell-laboratory/TEtranscripts | 2015 |
| SalmonTE | Provides rapid transcriptome-wide transposable element expression quantification from RNA-seq data. | https://github.com/LiuzLab/SalmonTE | 2018 |
| REdiscoverTE | Estimates genome-wide repeat and transposable element expression using a reference transcriptome-based framework. | https://github.com/bardin-lab/REdiscoverTE | 2020 |
| TEtools | Analyzes differential expression of transposable elements from high-throughput sequencing data. | https://github.com/l-modolo/TEtools | 2019 |
| RepEnrich2 | Quantifies repetitive elements from sequencing data using a repeat-enrichment strategy. | https://github.com/nerettilab/RepEnrich2 | 2020 |
| TeXP | Deconvolves transposable element expression signals from pervasive transcription using a regression-based model. | https://github.com/ay-lab/TeXP | 2020 |
| Telescope | Resolves and quantifies locus-specific transposable element expression from ambiguous RNA-seq alignments. | https://github.com/mlbendall/telescope | 2019 |
| TE-Seq | A Snakemake pipeline for end‑to‑end analysis of RNA‑seq data, examining both genes and TEs. It supports locus‑level and clade‑level quantification, incorporates optional long‑read DNA data to detect non‑reference (polymorphic) TE insertions, and handles multi‑mapping reads via probabilistic assignment (e.g., Telescope). | https://github.com/maxfieldk/TE-Seq | 2025 |
| SQuIRE | Provides locus-level quantification and analysis of interspersed repeat expression from RNA-seq data. | https://github.com/wyang17/SQuIRE | 2019 |
| L1EM | Quantifies locus-specific LINE-1 RNA expression using an expectation-maximization framework. | https://github.com/FenyoLab/L1EM | 2019 |
| ERVmap | Detects and quantifies human endogenous retrovirus expression at specific genomic loci. | https://github.com/mtokuyama/ERVmap | 2018 |
| SoloTE | Quantifies transposable element expression at locus and family levels from RNA-seq data. | https://github.com/bvaldebenitom/SoloTE | 2020 |
| scTE | Quantifies transposable element expression in single-cell sequencing data. | https://github.com/JiekaiLab/scTE | 2021 |
| IRescue | Assigns multimapping reads to quantify transposable element expression in single-cell RNA-seq data. | https://github.com/bodegalab/irescue | 2023 |
| Stellarscope | Resolves ambiguous alignments for locus-specific transposable element quantification in single-cell and bulk RNA-seq data. | https://github.com/nixonlab/stellarscope | 2022 |
| CELLO-seq | Enables locus-specific transposable element expression analysis using long-read single-cell RNA sequencing. | https://github.com/dianalow/CELLO-seq | 2021 |
| MATES | Quantifies locus-specific transposable element expression in single-cell long-read transcriptomic data. | https://github.com/mcgilldinglab/MATES | 2024 |
| ExplorATE | Characterizes transposable element expression from RNA-seq data across TE families and loci. | https://github.com/FemeniasM/ExplorATE_shell_script | 2022 |
| T-lex2 | TE genotyping tool repurposed for long-read datasets, provides locus-centric framework for analyzing TE activity. | https://github.com/petrov-lab/tlex2 | 2014 |
| TEspeX | Quantifies transposable element expression while reducing interference from exon-derived reads. | https://github.com/fansalon/TEspeX | 2022 |

### Computational pipelines for single‑cell/spatial
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※SpotGLM | A mixture‑aware framework for cell‑type–resolved isoform‑level inference from spatial data, enabling direct testing of spatial context‑dependent isoform switching. | https://github.com/kaishumason/SpotGLM | 2025 |
| ※Longcell | Recovers cell barcodes/UMIs, corrects errors, and models splicing diversity for single‑cell and spatial long‑read data. | https://github.com/yuntianf/Longcellsrc | 2024 |
| FLAMES | Integrates cell barcode/UMI assignment, transcript identification/quantification, alternative splicing analysis, and mutation detection. | https://github.com/mritchielab/FLAMES | 2021 |
| scNanoGPS | A comprehensive toolbox for characterizing genotype and phenotype in single cells without requiring NGS data or predefined barcode whitelists. | https://github.com/gaolabtools/scNanoGPS | 2023 |
| Isopod | Detects differential transcript usage from long‑read single‑cell data. | https://github.com/michael-nakai/isopod | 2026 |
| ScisorWiz | Visualization tool for differential isoform expression in single‑cell long‑read data. | https://github.com/ans4013/ScisorWiz | 2022 |
| UMI-nea | A fast, robust tool for reference‑free UMI deduplication and accurate quantification. | https://github.com/Qiaseq-research/UMI-nea | 2025 |
| Spl‑ISOquant | Tool for analyzing spatially barcoded long reads to quantify isoform expression in tissue sections. | https://github.com/algbio/spl-IsoQuant | 2025 |

### Poly(A) tail analysis
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※Dorado | ONT’s current production basecaller with GPU acceleration, supporting high-accuracy RNA and DNA basecalling, duplex calling, and integrated modification-aware models for simultaneous sequence and RNA modification detection. | https://github.com/nanoporetech/dorado | 2023 |
| ※tailfindr | R package for estimating poly(A)-tail lengths in Oxford Nanopore reads. | https://github.com/adnaniazi/tailfindr | 2019 |
| Nanopolish | Signal-level analysis of Oxford Nanopore sequencing data. Nanopolish can calculate an improved consensus sequence for a draft genome assembly, detect base modifications, call SNPs and indels with respect to a reference genome and more. | https://github.com/jts/nanopolish | 2019 |

### Alternative splicing detection
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※rMATS-turbo | Event-level tool that performs replicate-aware statistical modeling of five classical splicing event types (exon skipping, alternative splice sites, intron retention). | https://github.com/Xinglab/rmats-turbo | 2014 |
| ※IRFinder-S | Specialized event-level tool for high precision quantification of intron retention with tailored filtering and QC procedures. | https://github.com/RitchieLab/IRFinder | 2023 |
| ※IsoformSwitchAnalyzeR | Isoform-level tool that integrates ORF prediction, domain annotation, NMD sensitivity assessment, and functional diversity analysis. | https://github.com/kvittingseerup/IsoformSwitchAnalyzeR | 2017 |
| ※MAJIQ | Characterizes local splicing variation through probabilistic changes and uncertainty, highly suitable for differential splicing analysis of multi-branch splicing. | https://github.com/biocore/MAJIQ | 2016 |
| MISO | Quantifies isoform expression and alternative splicing from RNA‑seq data using a probabilistic framework based on the expectation‑maximization (EM) algorithm; calculates percent spliced‑in (PSI) values for exons and junction reads. | https://github.com/yarden/MISO/ | 2010 |
| DRIMSeq | R/Bioconductor package that models transcript counts with a Dirichlet‑multinomial distribution for differential transcript usage (DTU) analysis between conditions; also supports transcript‑level QTL (tuQTL) mapping. | https://github.com/bioc/DRIMSeq | 2016 |
| satuRn | R/Bioconductor package for highly performant and scalable differential transcript usage analysis in bulk and single‑cell RNA‑seq data; fits quasi‑binomial generalized linear models to model transcript usage across groups. | https://github.com/statOmics/satuRn | 2021 |
| tappAS | First framework for Functional Iso‑Transcriptomics (FIT) analysis; evaluates the functional impact of differential splicing by integrating isoform‑resolved expression with protein domain, motif, and pathway annotations. | https://github.com/ConesaLab/tappAS | 2020 |
| IsoQuant | Graph‑based reference‑guided isoform discovery and quantification tool for long‑read RNA‑seq data (PacBio and ONT); ranked first in LRGASP benchmark; mitigates alignment noise and reduces false positives in novel isoform calls. | https://github.com/ablab/IsoQuant | 2023 |
| FLAIR | Full‑Length Alternative Isoform analysis of RNA; performs splice‑site correction, transcript assembly, and alternative splicing analysis for noisy long reads (nanopore cDNA, direct RNA, and PacBio). | https://github.com/BrooksLabUCSC/flair | 2020 |
| DIGGER | Functional annotation framework that evaluates how exon skipping events perturb protein-protein interactions based on exon-level annotations. | https://github.com/louadi/DIGGER | 2020 |
| Exon Ontology | Functional annotation framework that assigns functional labels (domains, motifs) to individual exons for splicing event analysis. | https://github.com/Xinglab/ExonOntology | 2017 |
| NEASE | Functional annotation tool that links alternative splicing events to protein functional changes through exon-to-domain mapping and interaction network analysis. | https://github.com/ZarnackGroup/NEASE | 2022 |
| DoChaP | Functional annotation tool that connects alternative splicing events to protein functional changes using conservation-based approaches. | https://github.com/gal-av/DoChaP | 2020 |
| StringTie3 | Isoform-level tool that assembles full-length transcripts to enable complex splicing pattern analysis. | https://github.com/gpertea/stringtie | 2026 |
| Bambu | Isoform-level tool that reconstructs transcript structures to support complex alternative splicing analysis. | https://github.com/GoekeLab/bambu | 2023 |

### Fusion gene detection
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※LongGF | Bulk-level fusion detection tool that uses splice-aware aligners (Minimap2) to map reads and identify chimeric reads spanning two gene loci. | https://github.com/WGLab/LongGF | 2020 |
| ※JAFFAL | JAFFA is a multi-step pipeline that takes either raw RNA-Seq reads, or pre-assembled transcripts, then searches for gene fusions. | https://github.com/Oshlack/JAFFA | 2021 |
| ※IFDlong | Transcript-level long-read fusion quantification framework that estimates fusion transcript abundance after fusion detection using isoform-aware probabilistic modeling. | https://github.com/SilviaLiu12345/IFDlong2 | 2026 |
| ※GFHunter | Single-cell fusion detection tool with lightweight workflow specifically optimized for single-cell sequencing data. | https://github.com/WGLab/GFHunter | 2024 |
| Genion | Bulk-level fusion detection tool that applies chimeric read clustering (dynamic programming) plus statistical filtering to reduce false positives. | https://github.com/Xinglab/Genion | 2023 |
| Biosurfer | Proteoform analysis tools that compare the effects of splicing differences at the transcript, codon, and protein levels to help determine functional consequences. | https://github.com/sheynkmanlab/biosurfer | 2025 |
| FLAIR-fusion | Bulk-level fusion detection tool well suited for fusion subtype and isoform resolution, reconstructs full-length fusion transcripts. | https://github.com/BrooksLabUCSC/flair | 2020 |
| FusionSeeker | Bulk-level fusion detection tool that performs DBSCAN density clustering on breakpoint coordinates for improved tolerance of heterogeneous breakpoints. | https://github.com/Maggi-Chen/FusionSeeker | 2023 |
| FUGAREC | Bulk-level fusion detection tool that reconstructs full-length fusion transcripts and re-aligns candidates to strengthen breakpoint support. | https://github.com/Hideo-Matsuda/FUGAREC | 2024 |
| CTAT-LR-fusion | Bulk-level fusion detection tool robust for complex cancer samples, adaptable to single-cell data, focuses on reliable breakpoint detection. | https://github.com/TrinityCTAT/CTAT-LR-fusion | 2023 |
| GFvoter | Fusion detection tool that integrates calls from multiple methods (Minimap2, Winnowmap2, LongGF, JAFFAL) using multi-voting strategy. | https://github.com/WGLab/GFvoter | 2024 |
| LongFUSE | Single-cell fusion detection tool that applies XOR logic gates and strict filtering to identify cell-specific fusion genes and isoforms. | https://github.com/WGLab/LongFUSE | 2024 |
| SQANTI3 | Quality control, curation and annotation tool for long‑read transcript models (PacBio/ONT). It classifies isoforms into structural categories, including fusion (F) transcripts that span two annotated genes. The --is_fusion parameter enables dedicated classification of fusion isoforms, reporting which annotated or novel genes each fusion component maps to. | https://github.com/ConesaLab/SQANTI3 | 2024 |

### Allele-specific expression analysis
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※RPVG | Aligns RNA reads to variation graphs or pangenomes and estimates allele-specific expression, suitable for reducing reference bias in highly polymorphic regions when using LRS. | https://github.com/jonassibbesen/rpvg | 2023 |
| ※LORALS | Performs allele-specific expression and allele-specific splicing analysis using long reads, enabling direct association of haplotypes with transcripts through LRS data. | https://github.com/LappalainenLab/lorals | 2022 |
| ※longcallR | A unified framework consisting of three integrated modules for long-read RNA-seq data. | https://github.com/huangnengCSU/longcallR | 2026 |
| IsoLaser | Integrates long-read splicing structures with variant information to infer allele-specific expression and splicing (the long span of LRS facilitates linking variants to isoforms). | https://github.com/gxiaolab/isoLASER | 2025 |
| IDP-ASE | Hybrid analysis framework integrating long-read and short-read sequencing, improving haplotyping and allele-specific quantification accuracy at gene and isoform levels. | https://github.com/au-lab/IDP-ASE | 2017 |
| FLAIR2 | ASE tool that enables allele-specific expression analysis by incorporating haplotype-aware transcript annotation. | https://github.com/BrooksLabUCSC/flair | 2020 |
| HapIso | ASE tool that reconstructs haplotype-specific isoforms and helps disentangle cis- and trans-regulatory contributions. | https://github.com/smangul1/HapIso | 2019 |
| IsoPhase | ASE tool that reconstructs haplotype-specific isoforms from long-read transcriptome data, supports allele-specific splicing analysis. | https://github.com/Magdoll/IsoPhase | 2018 |

### Alternative transcription start site
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※NAGATA | Long-read transcript start site clustering tool for identifying and refining TSS usage patterns from noisy long-read RNA sequencing data. | https://github.com/DepledgeLab/NAGATA | 2021 |
| ※LoRTIA | Toolkit for identifying transcript start and end sites, adapter sequences, and full-length transcript boundaries from long-read sequencing data. | https://github.com/zsolt-balazs/LoRTIA | 2019 |
| ※FLAIR | Full‑Length Alternative Isoform analysis of RNA for long‑read data (nanopore cDNA, direct RNA, and PacBio). It incorporates promoter chromatin states to distinguish true transcription start sites from 5′ truncations, and uses read start coordinate density to define TSS boundaries. | https://github.com/BrooksLabUCSC/flair | 2020 |
| StringTie3 | Reference‑guided transcriptome assembler that works with both short and long reads. It assembles full‑length transcript models from read alignments, enabling identification of transcription start sites and end sites as part of complete isoform reconstruction. | https://github.com/gpertea/stringtie | 2026 |
| IsoQuant | Genome‑based tool for long RNA read analysis (PacBio/ONT). It reconstructs and quantifies transcript models with high precision, and provides dedicated TSS and poly(A) site analysis options for full‑length isoform characterization. | https://github.com/ablab/IsoQuant | 2023 |
| Bambu | R package for reference‑guided transcript discovery and quantification from long‑read RNA‑Seq data. It performs context‑aware transcript reconstruction, enabling detection of transcription start sites and end sites for both known and novel transcripts. | https://github.com/GoekeLab/bambu | 2023 |
| CAGE | Cap analysis of gene expression framework widely used to profile promoter usage and validate transcription start sites at high resolution. | https://github.com/ncvetesic/SLIC-CAGE | 2003 |
| ReCappable-seq | Experimental method for genome-wide mapping of transcription start sites from capped and recapped RNA molecules, useful for validating TSS catalogs. | https://github.com/elitaone | 2020 |

### APA / poly(A) site analysis
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※LAPA | Long-read APA analysis framework for defining poly(A) sites and quantifying alternative cleavage and polyadenylation usage. | https://github.com/mortazavilab/lapa | 2022 |
| ※APALORD | Long-read alternative polyadenylation (APA) analysis tool that defines poly(A) sites and quantifies APA usage from full-length transcriptome data, with emphasis on transcript-end heterogeneity and isoform-level APA dynamics. | https://github.com/markandtwin/APALORD | 2025 |
| FLAIR | Full‑Length Alternative Isoform analysis of RNA for long‑read data (nanopore cDNA, direct RNA, and PacBio). The resulting transcript models include complete 3′ ends, enabling downstream identification and quantification of alternative polyadenylation (APA) sites. | https://github.com/BrooksLabUCSC/flair | 2020 |
| IsoQuant | Genome‑based tool for long RNA read analysis (PacBio/ONT). It reconstructs and quantifies transcript models with high precision, and provides dedicated analysis modes for both transcription start sites (TSS) and poly(A) end sites (PolyA) to support full‑length isoform characterization and APA studies. | https://github.com/ablab/IsoQuant | 2023 |
| StringTie3 | Reference‑guided transcriptome assembler that outputs complete transcript structures including transcription start sites (TSS) and transcription end sites (TES). These 3′ end annotations can be directly used to profile APA events and quantify alternative poly(A) site usage. | https://github.com/gpertea/stringtie | 2026 |
| Bambu | R package for reference‑guided transcript discovery and quantification from long‑read RNA‑Seq data (ONT/PacBio). It performs context‑aware transcript reconstruction, enabling detection of both known and novel transcript isoforms with accurate transcript end boundaries, which can be used to characterize alternative polyadenylation (APA) sites and 3′ UTR isoform diversity. | https://github.com/GoekeLab/bambu | 2023 |

### Circular RNA analysis
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※CIRI-long | CircRNA analysis tool that maps reads to genome, detects back-splice junctions (BSJs), applies stringent filtering, reconstructs full-length circRNA sequences. | https://github.com/bioinfo-biols/CIRI-long | 2021 |
| ※CIRIquant | CircRNA quantification tool that constructs pseudo-circRNA references, models RNase R bias to improve expression estimates and detect expression switching. | https://github.com/bioinfo-biols/CIRIquant | 2020 |
| isoCirc | CircRNA analysis tool that builds catalogs of full-length circRNA isoforms (>100 kb), resolves distinct splice isoforms (relatively costly). | https://github.com/Xinglab/isoCirc | 2021 |
| circFL-seq | CircRNA analysis tool that leverages repeated passes through circle for error correction, can detect fusion circRNAs, supports relative quantification. | https://github.com/yang-laboratory/circFL-seq | 2021 |
| circNick-LRS | CircRNA analysis tool that selectively cleaves circRNAs to generate linearized templates (no RCRT/RCA needed), performs well for ultra-long circRNAs (>3,000 bp). | https://github.com/yang-laboratory/circNick-LRS | 2022 |

### Differential transcript expression
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※DESeq2 | Models counts using negative binomial distribution, stabilizes dispersion with empirical Bayes method, suitable for differential expression analysis with small to medium sample sizes. | https://github.com/mikelove/DESeq2 | 2014 |
| ※edgeR | Differential expression analysis for digital gene expression data based on negative binomial distribution, stabilizes dispersion with empirical Bayes method, suitable for small to medium sample sizes. | https://github.com/Bioconductor/edgeR | 2010 |
| ※Limma-voom | Elucidates mean-variance relationship, provides precision weights for linear models, adaptable to complex experimental designs including batch, gender, tissue origin and interaction factors. | https://github.com/Bioconductor/limma | 2014 |
| Sleuth | RNA-seq differential analysis integrating quantitative uncertainty, suitable for scenarios where transcript abundance is the analysis object and uncertainty needs to be explicitly handled. | https://github.com/pachterlab/sleuth | 2017 |

### Differential splicing
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※MAJIQ | Characterizes local splicing variation through probabilistic changes and uncertainty, highly suitable for differential splicing analysis of multi-branch splicing. | https://github.com/biocore/MAJIQ | 2016 |
| ※LeafCutter | Reduces annotation dependence using intron clusters, widely used to identify unique splicing changes, can also be used in combination with LRS-guided intron sets. | https://github.com/davidaknowles/leafcutter | 2018 |
| SUPPA2 | Calculates PSI values of splicing events based on transcript isoform abundance, analysis results are affected by annotation and quantification quality, LRS annotation optimization can improve its interpretability. | https://github.com/comprna/SUPPA | 2018 |
| DEXSeq | Count-based analysis framework that can detect differential exon usage, serving as a reliable baseline and supplementary research tool for differential splicing analysis. | https://github.com/Bioconductor/DEXSeq | 2012 |
| JunctionSeq | Count-based analysis framework that enables detection and visualization of differential splicing in RNA-seq data, serving as a reliable baseline for differential splicing analysis. | https://github.com/olgabot/junctionseq | 2016 |

### Isoform-specific regulatory network
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※WGCNA | Constructs gene/isoform co-expression modules and identifies hub nodes based on correlation, a typical tool for co-expression/co-variation network analysis. | https://github.com/horvathbiostat/WGCNA | 2008 |
| ※TargetScan | Predicts effective miRNA target sites in mammalian mRNAs, providing miRNA target information for sequence and element-driven regulatory network analysis. | https://github.com/TargetScan/targetscan_70 | 2015 |
| ※RBPmap | Motif/model-based RNA binding protein binding site prediction tool, providing candidate RBP binding edge information for regulatory network analysis. | https://github.com/ybmanel/RBPmap | 2014 |
| MEGENA | When isoform features are abundant, further depicts multi-scale and hierarchically nested co-expression modules, expanding the dimension of co-expression network analysis. | https://github.com/cran/MEGENA | 2015 |
| PureCLIP | Enhanced CLIP experimental framework for transcriptome-wide mapping of RNA-binding protein binding sites, often used as orthogonal evidence for isoform-specific regulatory interactions. | https://github.com/skrakau/PureCLIP | 2016 |
| RegNetwork | Curated regulatory network resource integrating transcription factor, miRNA, and gene regulatory interactions for network annotation and benchmarking. | https://github.com/zpliulab/RegNetwork-1.0 | 2015/2025 |
| QTLtools | Used for discovery and analysis of molecular QTLs (such as sQTL, apaQTL), a core tool for multi-omics evidence integration. | https://github.com/qtltools/qtltools | 2017 |
| coloc | Bayesian test method based on summary statistics, enabling colocalization analysis between genetic association studies, verifying cross-trait QTL signal support. | https://github.com/chr1swallace/coloc | 2014 |

### Visualization
| Tool | Functional Description | GitHub | Year |
|------|------------------------|--------|------|
| ※IGV | Widely used genome browser for visual inspection of long-read alignments, splice junctions, coverage, fusion breakpoints, and short-/long-read concordance. | https://github.com/igvteam/igv | 2011 |
| ※isoespy | Visualization and reporting toolkit for isoform expression, structure, and differential analysis results in long-read transcriptomics workflows. | https://github.com/PlantDr430/isoespy | 2023 |
| IsoVis | Interactive web-based isoform visualization tool that displays transcript structures and protein feature mappings for isoform-centric interpretation. | https://github.com/ClarkLaboratory/IsoVis | 2023 |
| Swan | Graph-based long-read transcriptome visualization framework for comparing isoform structures, transcript ends, and differential transcript usage across samples. | https://github.com/mortazavilab/swan_vis | 2021 |
| NanoPack2 | Supports detailed visualization (read length histograms, length–quality scatter plots, GC content distributions) for ONT and PacBio data, includes NanoPlot. | https://github.com/wdecoster/nanopack | 2023 |

---

### 📁 File Download
Full original Excel file: [LRS_tools.xlsx](LRS_tools.xlsx)
