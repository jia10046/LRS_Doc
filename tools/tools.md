# LRS_Tools: Long-Read Transcriptomics Analysis Toolkit
Full collection of long-read sequencing (LRS) transcriptome analysis tools, including functional annotations, GitHub links, publication year, and recommended usage scenarios.

---

## 📋 Full Tool List
| Category | Tool | Functional Description | GitHub | Year |
|----------|------|------------------------|--------|------|
| Basecalling | Guppy | A C++-based closed-source ONT basecaller that replaced Albacore, supporting GPU-accelerated high-accuracy basecalling for DNA and RNA. |  | 2018 |
| Basecalling | Bonito | An open-source research basecaller developed by ONT based on PyTorch, enabling customizable neural network architectures and training for experimental nanopore basecalling models. | https://github.com/nanoporetech/bonito | 2020 |
| Basecalling | RODAN | A deep learning–based nanopore basecaller employing advanced neural network architectures to improve raw signal decoding accuracy. | https://github.com/biodlab/RODAN | 2022 |
| Basecalling | Dorado | ONT’s current production basecaller with GPU acceleration, supporting high-accuracy RNA and DNA basecalling, duplex calling, and integrated modification-aware models. | https://github.com/nanoporetech/dorado | 2023 |
| Basecalling | GCRTcall | A neural network–based nanopore basecaller optimized for improved accuracy and robustness in decoding ionic current signals. | https://github.com/liqingwen98/GCRTcall | 2024 |
| Basecalling | DEMINERS | A deep learning framework for nanopore signal decoding that enhances basecalling performance and supports modification-aware sequence interpretation. | https://github.com/LuChenLab/DEMINERS | 2025 |
| Basecalling | Coral | A neural network–based nanopore basecaller designed to improve signal-to-sequence translation accuracy, particularly for homopolymers. | https://github.com/BioinfoSZU/Coral | 2026 |
| Basecalling | DeepConsensus | Deep learning model for generating consensus sequences for PacBio cDNA sequencing to produce HiFi reads. | https://github.com/google/deepconsensus | 2022 |
| Basecalling | SqueezeCall | Combines CNNs with a Squeezeformer and a CTC CRF decoder to reduce errors on multi-species datasets, supports direct RNA and cDNA sequencing. | https://github.com/labcbb/SqueezeCall | 2024 |
| Basecalling | BaseNet | Provides an open-source framework supporting autoregressive/non-autoregressive/pre-trained models, compatible with direct RNA and cDNA sequencing. | https://github.com/liqingwen98/BaseNet | 2024 |
| Basecalling | Chiron | Deep learning‑based nanopore basecaller using RNN+CTC to translate raw ionic current signals directly into DNA sequences. | https://github.com/haotianteng/Chiron | 2018 |
| Basecalling | MinCall | Fast and lightweight nanopore basecaller for real-time applications with low computational overhead. | https://github.com/nmiculinic/minion-basecaller | 2017 |
| Basecalling | DeepNano | Early deep learning‑based nanopore basecaller using BRNNs to outperform HMM-based methods. | https://github.com/fmfi-compbio/deepnano-blitz | 2016 |
| Basecalling | SACall | Neural network–based basecaller with squeeze‑and‑excitation attention to improve homopolyregion accuracy. | https://github.com/huangnengCSU/SACall-basecaller | 2023 |
| Basecalling | Causalcall | Applies causal/dilated convolutions to capture long‑range dependencies for parallelized efficient basecalling. | https://github.com/scutbioinformatic/causalcall | 2021 |
| Basecalling | DemuxTrans | Integrates 1D CNNs, Transformers, and TCNs to improve accuracy for direct RNA/cDNA sequencing. | https://github.com/LiyuanShu116/Demuxtrans | 2025 |
| Basecalling | m6Abasecaller | Detects RNA m6A modifications by estimating per-read modification probabilities during/after basecalling. | https://github.com/novoalab/m6ABasecaller | 2025 |
| Quality control | LongQC | Reference-free quality assessment for major third-generation sequencing platforms (PacBio and ONT). | https://github.com/yfukasawa/LongQC | 2020 |
| Quality control | LongReadSum | Generates comprehensive statistical summaries of raw sequencing output (length, yield, quality distributions). | https://github.com/WGLab/LongReadSum | 2024 |
| Quality control | MinKNOW | Performs real-time signal-level monitoring and run control during Oxford Nanopore sequencing. | https://github.com/nanoporetech/minknow_api | 2018 |
| Quality control | pycoQC | Parses ONT sequencing summary files to generate interactive HTML reports for post-run evaluation. | https://github.com/a-slide/pycoQC | 2018 |
| Quality control | NanoPlot | QC and visualization tool for long-read data, generating plots of length, quality, GC content, yield. | https://github.com/wdecoster/NanoPlot | 2018 |
| Quality control | fastplong | Integrates QC, filtering, adapter trimming, and poly(A) processing for full-length cDNA workflows. | https://github.com/OpenGene/fastplong | 2024 |
| Quality control | MultiQC | Aggregates results from multiple QC tools into a single interactive report. | https://github.com/MultiQC/MultiQC | 2016 |
| Error correction | PacBioToCA | Hybrid correction tool (alignment-based) using short reads to correct long reads via local consensus. | http://wgs-assembler.sourceforge.net/ | 2012 |
| Error correction | proovread | Hybrid correction tool (alignment-based) for long read error correction using short reads. | https://github.com/BioInf-Wuerzburg/proovread | 2014 |
| Error correction | Hercules | Hybrid correction tool (alignment-based) that may use deep learning for error correction. | https://github.com/BilkentCompGen/Hercules | 2018 |
| Error correction | LoRDEC | Hybrid correction tool (assembly-based) using short-read de Bruijn graphs to correct long reads. | https://bitbucket.org/mvdall/lordec | 2014 |
| Error correction | Jabba | Hybrid correction tool (assembly-based) for long read error correction. | https://github.com/GATB/Jabba | 2016 |
| Error correction | FMLRC | Hybrid correction tool (assembly-based) using short read information to correct long reads. | https://github.com/holobench/fmlrc | 2018 |
| Error correction | HALC | Hybrid correction tool (assembly-based) for long read error correction. | https://github.com/lanl001/halc | 2017 |
| Error correction | Canu | Self-correction tool (overlap-based) computing read-to-read overlaps and consensus sequences. | https://github.com/marbl/canu | 2015 |
| Error correction | MECAT/NECAT | Self-correction tool (overlap-based) for long read error correction via overlap analysis. | https://github.com/xiaochuanle/NECAT | 2017/2020 |
| Error correction | CONSENT | Self-correction tool (overlap-based) using consensus methods for long read error correction. | https://github.com/morispi/CONSENT | 2019 |
| Error correction | NextDenovo | Self-correction tool (overlap-based) via overlap analysis and consensus building. | https://github.com/Nextomics/NextDenovo | 2020 |
| Error correction | LoRMA | Self-correction tool (graph-based) iteratively constructing de Bruijn graphs from noisy long reads. | https://github.com/LM-UG/lorma | 2016 |
| Error correction | Longcell | UMI-based error correction for UMI-tagged long reads in single-cell/spatial transcriptomics. | https://github.com/yuntianf/Longcell | 2024 |
| Error correction | ScNaUmi-seq | UMI-based error correction clustering reads from the same molecule to reduce errors. | https://github.com/S-and-J/ScNaUmi-seq | 2021 |
| Error correction | FLAMES | UMI-based error correction clustering reads and collapsing into consensus sequences. | https://github.com/LuyiTian/FLAMES | 2021 |
| Error correction | ConSeqUMI | UMI-based error correction using pairwise consensus, much faster than conventional methods. | https://github.com/GenomicaMicrob/ConSeqUMI | 2023 |
| Error correction | UMI-nea | UMI-based error correction using Levenshtein distance to improve read grouping. | https://github.com/yyoshiaki/UMI-nea | 2022 |
| Error correction | DeepCorr | Deep learning-based correction capturing contextual dependencies and platform-specific error profiles. | https://github.com/S-and-J/DeepCorr | 2019 |
| Error correction | NmTHC | Deep learning-based correction method for long read error correction. | https://github.com/RinoYuki/NmTHC | 2021 |
| Read alignment | minimap2 | Fast minimizer-based splice-aware aligner, de facto standard for long-read transcriptomic alignment. | https://github.com/lh3/minimap2 | 2018 |
| Read alignment | Graphmap2 | Hashing-based splice-aware aligner improving recall and precise exon/transcript boundary placement. | https://github.com/lbcb-sci/graphmap2 | 2019 |
| Read alignment | deSALT | Splice-aware aligner using de Bruijn graph index to tolerate errors and recover small exons. | https://github.com/ydLiu-HIT/deSALT | 2019 |
| Read alignment | BWA-MEM2 | BWT-FM–based aligner for fast local/end-to-end alignment, not optimized for long-read spliced data. | https://github.com/bwa-mem2/bwa-mem2 | 2019 |
| Read alignment | UTRAL | BWT-FM–based aligner for small exons and complex splice-site detection. | https://github.com/ydLiu-HIT/UTRAL | 2023 |
| Read alignment | STAR | Suffix-array–based RNA-seq aligner extendable to long reads, less common for noisy LRS. | https://github.com/alexdobin/STAR | 2013 |
| Read alignment | 2passtools | Post-alignment refinement filtering false splice sites via machine learning. | https://github.com/dieterich-lab/2passtools | 2021 |
| Read alignment | Splam | ML-based splice-junction validation filtering false splice sites. | https://github.com/Kuanhao-Chao/splam | 2023 |
| Read alignment | FLAIR | Post-alignment splice-site correction to reduce junction errors before isoform reconstruction. | https://github.com/BrooksLabUCSC/flair | 2020 |
| Isoform identification | FLAIR | Splice site correction and transcript assembly for ONT long reads. | https://github.com/BrooksLabUCSC/flair | 2020 |
| Isoform identification | TALON | Classification and annotation of known/novel transcripts for downstream quantification. | https://github.com/dewyman/TALON | 2020 |
| Isoform identification | StringTie2 | Transcript assembly from long-read alignments based on reference genome and annotation. | https://github.com/gpertea/stringtie | 2019 |
| Isoform identification | Bambu | Reconstruction and merging of transcript structures with novel isoform identification. | https://github.com/GoekeLab/bambu | 2023 |
| Isoform identification | SQANTI3 | Structural annotation framework classifying isoforms, evaluating junctions, filtering artifacts. | https://github.com/ConesaLab/SQANTI3 | 2021 |
| Isoform identification | IsoTools | Framework for transcript classification, novel isoform discovery, splicing summarization. | https://github.com/MatthiasLienhard/isotools | 2023 |
| Isoform identification | LRAA | Unified framework for isoform identification/quantification across bulk/single-cell data. | https://github.com/MethodsDev/LongReadAlignmentAssembler | 2026 |
| Isoform identification | Mandalorion | Identification of splice isoforms from ONT long reads for rapid catalog generation. | https://github.com/mandalorion-evidence/mandalorion | 2023 |
| Isoform identification | ESPRESSO | Splice site error correction prior to isoform identification. | https://github.com/Xinglab/espresso | 2023 |
| Isoform identification | Freddie | Clustering reads by splicing structure for isoform inference under weak annotation. | https://github.com/vpc-ccg/freddie | 2023 |
| Isoform identification | FLAMES | Isoform identification for long-read transcriptomes. | https://github.com/LuyiTian/FLAMES | 2021 |
| Isoform identification | IsoSplitter | Partitioning reads by splicing features for complex isoform dissection. | https://github.com/Hengfu-Yin/IsoSplitter | 2021 |
| Isoform identification | RNA-Bloom2 | De novo/weak-reference transcript assembly for incomplete references. | https://github.com/bcgsc/RNA-Bloom | 2023 |
| Isoform identification | rnaSPAdes | De novo transcriptome assembly for unannotated transcripts. | https://github.com/ablab/spades | 2019 |
| Isoform identification | LyRic | Transcript identification tailored to ONT characteristics. | https://github.com/guigolab/LyRic | 2021 |
| Isoform identification | RATTLE | Reference-free clustering of ONT reads for consensus sequences. | https://github.com/comprna/RATTLE | 2022 |
| Isoform identification | isONform | Reference-free clustering/reconstruction of ONT transcripts. | https://github.com/ksahlin/isONform | 2023 |
| Isoform identification | Isosceles | ONT-oriented isoform clustering and integration. | https://github.com/Genentech/Isosceles | 2024 |
| Isoform identification | IsoQuant | Graph-based reference-guided tool, top performer in LRGASP benchmark. | https://github.com/ablab/IsoQuant | 2023 |
| Isoform identification | ISAtools | Classification tool with error correction and DBSCAN for TSS/TES. | https://github.com/Xinglab/ISAtools | 2024 |
| Isoform identification | IsoSeq3 | PacBio de novo assembly tool clustering long reads for consensus transcripts. | https://github.com/ylipacbio/IsoSeq3 | 2018 |
| Isoform quantification | isONform | De novo assembly reconstructing isoforms via gene graph bubble elimination. | https://github.com/ksahlin/isONform | 2023 |
| Isoform quantification | IsoQuant | Transcript identification/quantification with consistency assessment. | https://github.com/ablab/IsoQuant | 2023 |
| Isoform quantification | FLAIR | Isoform-level counting based on corrected splice sites. | https://github.com/BrooksLabUCSC/flair | 2020 |
| Isoform quantification | TALON | Classification/counting for consistent expression matrices. | https://github.com/dewyman/TALON | 2020 |
| Isoform quantification | NanoCount | Direct ONT read assignment for baseline quantification. | https://github.com/a-slide/NanoCount | 2021 |
| Isoform quantification | Bambu | Simultaneous transcript construction and isoform quantification. | https://github.com/GoekeLab/bambu | 2023 |
| Isoform quantification | Salmon | Rapid transcript expression estimation for LRS. | https://github.com/COMBINE-lab/salmon | 2015 |
| Isoform quantification | lr-kallisto | Long-read-oriented quantification sensitive to errors/bias. | https://github.com/pachterlab/kallisto | 2025 |
| Isoform quantification | LRAA | Unified framework for isoform identification/quantification. | https://github.com/MethodsDev/LongReadAlignmentAssembler | 2026 |
| Isoform quantification | LIQA | Probabilistic isoform expression estimation. | https://github.com/WGLab/LIQA | 2021 |
| Isoform quantification | JOLI | Cross-platform tool integrating long/short reads via Bayesian framework. | https://github.com/Xinglab/JOLI | 2024 |
| Isoform quantification | miniQuant | Lightweight hybrid long/short-read quantification. | https://github.com/Augroup/miniQuant | 2025 |
| TE detection | TLDR | Long-read TE detection using minimap2 for breakpoint inference. | https://github.com/adamewing/tldr | 2021 |
| TE detection | xTea | Long-read TE detection with statistical filtering and clustering. | https://github.com/parklab/xTea | 2021 |
| TE detection | sTELLeR | Long-read TE detection with optimized filtering for insertions. | https://github.com/Boyle-Lab/sTELLeR | 2024 |
| TE detection | PALMER | Local assembly to resolve complete TE structures. | https://github.com/WeichenZhou/PALMER | 2020 |
| TE detection | TrEMOLO | Local assembly + filtering for TE insertion detection. | https://github.com/D-I-L/TrEMOLO | 2022 |
| TE detection | TE-Seq | Profiles TE expression from RNA-seq data. | https://github.com/maxfieldk/TE-Seq | 2025 |
| TE quantification | TEtranscripts | Quantifies TE expression handling ambiguously mapped reads. | https://github.com/mhammell-laboratory/TEtranscripts | 2015 |
| TE quantification | SalmonTE | Rapid transcriptome-wide TE expression quantification. | https://github.com/LiuzLab/SalmonTE | 2018 |
| TE quantification | LongTEQuant | Quantifies TE-derived transcripts from long-read RNA-seq. | https://github.com/gaoshiwen/LongTEQuant | 2026 |
| TE quantification | LocusMasterTE | Integrates long/short-read evidence for locus-level TE quantification. | https://github.com/jasonwong-lab/LocusMasterTE | 2025 |
| Poly(A) tail analysis | Nanopolish | Signal-level analysis of ONT data for consensus, modifications, and variants. | https://github.com/jts/nanopolish | 2019 |
| Poly(A) tail analysis | Dorado | ONT production basecaller with integrated modification-aware models. | https://github.com/nanoporetech/dorado | 2023 |
| Poly(A) tail analysis | tailfindr | R package for estimating poly(A)-tail lengths in ONT reads. | https://github.com/adnaniazi/tailfindr | 2019 |
| Alternative splicing detection | rMATS-turbo | Event-level analysis of five classical splicing event types. | https://github.com/Xinglab/rmats-turbo | 2014 |
| Alternative splicing detection | IRFinder-S | High-precision quantification of intron retention. | https://github.com/RitchieLab/IRFinder | 2023 |
| Alternative splicing detection | IsoformSwitchAnalyzeR | Isoform-level tool integrating ORF, domain, NMD, and functional analysis. | https://github.com/kvittingseerup/IsoformSwitchAnalyzeR | 2017 |
| Fusion gene detection | LongGF | Bulk fusion detection using splice-aware aligners to identify chimeric reads. | https://github.com/WGLab/LongGF | 2020 |
| Fusion gene detection | Genion | Chimeric read clustering + statistical filtering to reduce false positives. | https://github.com/Xinglab/Genion | 2023 |
| Fusion gene detection | FLAIR-fusion | Fusion detection with full-length fusion transcript reconstruction. | https://github.com/BrooksLabUCSC/flair | 2020 |
| Allele-specific expression analysis | LORALS | Long-read ASE and allele-specific splicing analysis using haplotype references. | https://github.com/LappalainenLab/lorals | 2022 |
| Allele-specific expression analysis | RPVG | Aligns to variation graphs to reduce reference bias in ASE. | https://github.com/jonassibbesen/rpvg | 2023 |
| APA / poly(A) site analysis | LAPA | Long-read APA framework for poly(A) site definition and quantification. | https://github.com/mortazavilab/lapa | 2022 |
| APA / poly(A) site analysis | APALORD | Long-read APA tool focusing on transcript-end heterogeneity. | https://github.com/markandtwin/APALORD | 2025 |
| Circular RNA analysis | CIRI-long | Detects back-splice junctions and reconstructs full-length circRNA sequences. | https://github.com/bioinfo-biols/CIRI-long | 2021 |
| Circular RNA analysis | isoCirc | Builds full-length circRNA isoform catalogs. | https://github.com/Xinglab/isoCirc | 2021 |
| Differential transcript expression | DESeq2 | Negative binomial model for differential expression, ideal for small cohorts. | https://github.com/mikelove/DESeq2 | 2014 |
| Differential transcript expression | edgeR | Negative binomial model for digital expression analysis. | https://github.com/Bioconductor/edgeR | 2010 |
| Differential transcript expression | Limma-voom | Linear model for complex designs with batch/covariate handling. | https://github.com/Bioconductor/limma | 2014 |
| Differential splicing | MAJIQ | Characterizes local splicing variation for multi-branch events. | https://github.com/biocore/MAJIQ | 2016 |
| Differential splicing | SUPPA2 | Calculates PSI values based on isoform abundance. | https://github.com/comprna/SUPPA | 2018 |
| Differential splicing | LeafCutter | Intron-cluster-based analysis reducing annotation dependence. | https://github.com/davidaknowles/leafcutter | 2018 |
| Visualization | IGV | Genome browser for inspecting long-read alignments and junctions. | https://github.com/igvteam/igv | 2011 |
| Visualization | Swan | Graph-based framework for comparing isoform structures across samples. | https://github.com/mortazavilab/swan_vis | 2021 |
| Visualization | IsoVis | Interactive web tool for isoform structure and protein feature mapping. | https://github.com/ClarkLaboratory/IsoVis | 2023 |

---

## 🎯 Recommended Tools & Usage Scenarios
| Category | Tool | Use Scenarios and Rationale |
|----------|------|-----------------------------|
| Basecalling | Dorado | Default for ONT RNA-seq: high accuracy, fast inference, official support, modification-aware. |
| Basecalling | DeepConsensus | PacBio HiFi/Iso-Seq: maximizes consensus accuracy for splice junctions and isoforms. |
| Quality control | LongQC | Cross-platform baseline QC for PacBio/ONT, reference-free assessment. |
| Quality control | NanoPlot | Visualizes length, quality, GC, yield for outlier detection and figure preparation. |
| Quality control | pycoQC | ONT-specific post-run evaluation of sequencing performance and stability. |
| Error correction | FMLRC | Hybrid correction with short reads to improve alignment/transcript accuracy. |
| Error correction | Canu | Long-read-only data self-correction with sufficient coverage. |
| Error correction | FLAMES | UMI-tagged single-cell/spatial LRS: molecule-level error correction. |
| Read alignment | minimap2 | Standard aligner for all LRS transcriptome studies: fast, splice-aware, robust. |
| Read alignment | deSALT | High-error datasets or sensitive small-exon recovery. |
| Read alignment | Graphmap2 | Priority on boundary accuracy and recall over speed. |
| Isoform identification | IsoQuant | Default reference-guided discovery: balanced accuracy and robustness. |
| Isoform identification | Bambu | Novel isoform discovery with conservative false-positive control. |
| Isoform identification | FLAIR | ONT data: splice-site correction + isoform reconstruction. |
| Isoform quantification | IsoQuant | General-purpose quantification integrated with identification. |
| Isoform quantification | Bambu | Combined discovery and quantification in incomplete annotations. |
| Isoform quantification | miniQuant | Hybrid long/short-read analysis with optimal weight learning. |
| TE detection | TLDR | Detects sample-specific TE insertions with structural context. |
| TE detection | xTea | Robust detection with statistical filtering in repetitive regions. |
| TE quantification | LongTEQuant | Long-read-specific TE-derived transcript quantification. |
| TE quantification | LocusMasterTE | Locus-level TE quantification integrating long/short reads. |
| Poly(A) tail analysis | tailfindr | Default for ONT direct RNA poly(A) length estimation. |
| Poly(A) tail analysis | Nanopolish | Signal-level poly(A) and modification analysis. |
| Alternative splicing | rMATS-turbo | Event-level differential analysis of classical splicing types. |
| Alternative splicing | IsoformSwitchAnalyzeR | Links isoform changes to functional consequences (ORF, domain, NMD). |
| Fusion gene detection | LongGF | Default bulk long-read fusion detection: efficient chimeric identification. |
| Fusion gene detection | FLAIR-fusion | Full-length fusion isoform structure analysis. |
| Allele-specific expression | LORALS | Best long-read ASE with personalized haplotype references. |
| APA analysis | LAPA | Defines poly(A) sites and quantifies APA in long-read data. |
| Circular RNA | CIRI-long | Default long-read circRNA: BSJ detection, full-length reconstruction, filtering. |
| Differential expression | DESeq2 | Widely accepted default for transcript-level differential analysis. |
| Differential splicing | MAJIQ | Complex local splicing variation detection. |
| Visualization | IGV | Essential for validating alignments, junctions, breakpoints. |

---

### 📁 File Download
Full original Excel file: [LRS_tools.xlsx](LRS_tools.xlsx)

---
