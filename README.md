# AI4SE
![GitHub last commit](https://img.shields.io/github/last-commit/zanejins/ai4se)

This repository contains a curated list of papers, datasets, and tools that are devoted to research on Artificial Intelligence for Software Engineering. 

This repository is referred to [saltudelft/ml4se](https://github.com/saltudelft/ml4se). Next, I will keep adding papers I read、datasets and tools. 

Welcome to send a pull request to add papers and relevant content.

## Content
- [Papers](#papers)
  - [Surveys](#surveys)
  - [Empirical Studies](#empirical-studies)
  - [Type Inference](#type-inference)
  - [Code Completion](#code-completion)
  - [Code Generation](#code-generation)
  - [Code Recommand](#code-recommand)
  - [Code Summarization](#code-summarization)
  - [Code Changes](#code-changes)
  - [Code Test](#code-test)
  - [Bug/Vulnerability Detection](#bugvulnerability-detection)
  - [Source Code Modeling](#source-code-modeling)
  - [Program Repair](#program-repair)
  - [Program Translation](#program-translation)
  - [Program Analysis](#program-analysis)
  - [Code Clone Detection](#code-clone-detection)
- [Models](#models)
- [Datasets](#datasets) 
- [Tools](#tools)
- [PhD Theses](#phd-theses)
- [Talks](#talks)
- [Research Groups](#research-groups)

# Papers
## Surveys
## Empirical Studies
## Type Inference
## Code Completion
- **Code Completion with Neural Attention and Pointer Networks**(2018),arxiv 2019,Li,Jian,et al. [[pdf]](https://arxiv.org/pdf/1711.09573)- **All You Need Is Logs: Improving Code Completion by Learning from Anonymous IDE Usage Logs** (2022), arxiv, Bibaev, Vitaliy, et al. [[pdf]](https://arxiv.org/pdf/2205.10692.pdf)[[code]](https://github.com/jack57lee/neuralCodeCompletion)
- **pythia: Ai-assisted Code Completion System**(2019),KDD'19,Svyatkovskiy, Alexey, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3292500.3330699)
- **Fast and Memory-Efficient Neural Code Completion**(2020),, arxiv 2020, Svyatkovskoy, Alexey, et al. [[pdf]](https://arxiv.org/pdf/2004.13651)
- **Code Prediction by Feeding Trees to Transformers**(2021),ICSE'21.Kim,
  Seohyun, et al. [[pdf]](https://arxiv.org/pdf/2003.13848)
- **Code Completion by Modeling Flattened Abstract Syntax Trees as Graphs** (2021), AAAI'21, Wang, Yanlin, et al. [[pdf]](https://www.aaai.org/AAAI21Papers/AAAI-1654.WangY.pdf)
- **CodeFill: Multi-token Code Completion by Jointly Learning from Structure and Naming Sequences** (2022), ICSE'22, Izadi, Maliheh, et al. [[pdf]](https://arxiv.org/pdf/2202.06689.pdf) [[code]](https://github.com/saltudelft/codefill)
- **All You Need Is Logs: Improving Code Completion by Learning from Anonymous IDE Usage Logs** (2022), arxiv, Bibaev, Vitaliy, et al. [[pdf]](https://arxiv.org/pdf/2205.10692.pdf)
- **Learning to Prevent Profitless Neural Code Completion** (2022), arxiv, Sun, Z., et al. [[pdf]](https://arxiv.org/pdf/2209.05948)
- **Syntax-Aware On-the-Fly Code Completion** (2022), arxiv, Takerngsaksiri, W., et al. [[pdf]](https://arxiv.org/pdf/2211.04673)
- **Boosting source code suggestion with self-supervised Transformer Gated Highway** (2022), JSS, Hussain, Yasir, et al.
- **COCOMIC: Code Completion By Jointly Modeling In-file and Cross-file Context** (2022), Ding, Yangruibo, et al. [[pdf]](https://arxiv.org/pdf/2212.10007)


## Code Generation
- **CodeScore: Evaluating Code Generation by Learning Code Execution**(2023),arxiv,Dong, Yihong, et al.[[pdf]](https://arxiv.org/pdf/2301.09043)
- **Program Generation from Diverse Video Demonstrations** (2023), arxiv, Manchin, Anthony, et al. [[pdf]](https://arxiv.org/pdf/2302.00178) 
## Code Recommand
## Code Summarization
## Code Changes
## Code Test
## Bug/Vulnerability Detection
## Source Code Modeling
## Program Repair
## Program Translation
## Program Analysis
## Code Clone Detection


# Models
- [Code-Clippy](https://github.com/CodedotAl/gpt-code-clippy) - an open-source version of Github Copilot,an ai pair programmer based on GPT-3.
- []
# Datasets
- [Python Dataset](https://www.sri.inf.ethz.ch/py150) - A dataset consisting of 150k python files and their corresponding parsed ASTs.
- [Python Dataset](https://huggingface.co/rgismondi/python-50k-dedup/tree/main) - A dataset consisting of 50k python source code which have been deduplicated.
- [Javascript Dataset](https://www.sri.inf.ethz.ch/js150) - A dataset consisting of 150k JavaScript files and their corresponding parsed ASTs.
- [PURE Dataset](https://zenodo.org/record/1414117#.Y7mDrHZBy3A) - a Dataset of Public Requirements Documents
- [PROMISE SOFTWARE ENGINEERING REPOSITORY](http://promise.site.uottawa.ca/SERepository/) - Here we can find a collection of publicly available datasets and tools to serve researchers in building predictive software models.
- [UCI Machine Learning Reposity](http://archive.ics.uci.edu/ml/datasets.php) - center for Machine Learning and Intelligent Systems.
- [Code Clippy Data](https://the-eye.eu/public/AI/training_data/code_clippy_data/) - a opensource dataset for code generation





# Tools
## Source Code Analysis&Processing
- [PVTS parser](https://github.com/Microsoft/PTVS) - we can use it to extract AST.
- [java-callgraph](https://github.com/gousiosg/java-callgraph) - a suite of programs for generating static and dynamic calls graphs in Java
- [pydeps](https://github.com/thebjorn/pydeps) - Python Module Dependency graphs
- [LibSA4Py](https://github.com/saltudelft/libsa4py) - LibSA4Py:Light-weight static analysis for extracting type hints and features
- [LibCST](https://github.com/Instagram/LibCST) - A concrete syntax tree parser library for Python
- [python-graphs](https://github.com/google-research/python-graphs) - A static analysis library for computing graph representations of Python programs suitable for use with graph neural networks.
- [Semantic](https://github.com/github/semantic) - Parsing, analyzing, and comparing source code across many languages
- [GraphGen4Code](https://wala.github.io/graph4code/) - A toolkit for creating code knowledge graphs based on WALA code analysis and extraction of documentation
- [Joern](https://github.com/joernio/joern) - Code analysis platform for C/C++/Java/Binary/Javascript/Python/Kotlin based on code property graphs
- [NaturalCC](https://xcodemind.github.io/papers/icse22_naturalcc_camera_submitted.pdf) - An Open-Source Toolkit for Code Intelligence
- [Scalpel](https://github.com/SMAT-Lab/Scalpel) - The Python Static Analysis Framework
- [WALA](https://github.com/wala/WALA) - T.J. Watson Libraries for Analysis, with frontends for Java, Android, and JavaScript

## Code de-duplication
- [CD4Py](https://github.com/saltudelft/CD4Py) - Code De-Duplication for Python
- [Near-duplicate Source Code Detector](https://github.com/microsoft/near-duplicate-code-detector)


# PhD Theses

# Talks

# Research Groups
- [Secure, Reliable, and Intelligent Systems Lab (SRI)](https://www.sri.inf.ethz.ch/), ETH Zurich

