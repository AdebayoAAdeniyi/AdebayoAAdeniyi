# Dr. Adebayo A. Adeniyi

Computational chemist and data scientist. I build Python workflows for machine learning, cheminformatics, molecular modelling and genomic data analysis, with a focus on drug discovery and natural product research.

## About me

- MSc in Computing Science, University of Alberta (June 2026). My thesis builds chemical language models (recurrent neural network and MolGPT style transformer) for de novo generation of natural products, trained separately on bacterial, fungal and plant metabolites.
- PhD in Chemistry, with about ten years as a university researcher and lecturer in computational chemistry.
- 71 peer reviewed articles on drug design, vaccine design, electrochemistry and photochemistry (h-index 18 on Google Scholar). The full list is catalogued in the scientific-research-and-publications repository below.
- I also hold the LLQP and the Canadian Securities Course, and I run Strategic Financial Building, the company behind FINWISE.

## What I work with

- Data and machine learning: Python, pandas, NumPy, scikit-learn, LightGBM, PyTorch, SQL (MySQL, SQLite, BigQuery, DuckDB), Matplotlib, seaborn
- Models written from the mathematics in NumPy: least squares, ridge, logistic and softmax regression, hidden Markov models with Viterbi decoding, and reinforcement learning algorithms after Sutton and Barto
- Genomics and bioinformatics: gene expression from public GEO studies, genomic prediction with SNP data, leave one study out validation
- Cheminformatics and molecular modelling: RDKit, docking, molecular dynamics, DFT, QM/MM
- Spatial data basics: QGIS (first project)
- Experiment analysis basics: A/B test analysis with confidence intervals, bootstrap and power analysis (first project)
- Web engineering: HTML, CSS, JavaScript, Node.js, Express, SQLite, Nginx, PM2, with browser tests in Playwright

## Repositories

Machine learning and data analysis

- [Data-Analysis](https://github.com/AdebayoAAdeniyi/Data-Analysis): a Kaggle credit risk competition entry (American Express Default Prediction, 4,137th of 4,874 teams) and six practice projects in Python and SQL, covering regression, classification, text mining, a relational database and Google BigQuery. Each project README lists the errors I found when I reviewed my original notebooks. The verification table in the README states which projects were run on real data and which were checked on synthetic data.
- [Machine-learning](https://github.com/AdebayoAAdeniyi/Machine-learning): five studies from CMPUT 566 rebuilt as a tested package, with least squares, ridge, logistic and softmax regression written in NumPy. Examples: housing test MAE from 3.2963 to 2.7990 with squared features, and 92.53% test accuracy on MNIST with a linear softmax model. 14 tests.
- [PGM-projects](https://github.com/AdebayoAAdeniyi/PGM-projects): a hidden Markov model part of speech tagger with Viterbi decoding, from CMPUT 651. On the Penn Treebank test set it tags 93.67% of words correctly (macro over sentences) against 90.09% for a most frequent tag baseline. 12 tests, including a check of Viterbi against exhaustive enumeration. The README states that results are from one corpus only.
- [Reinforcement-Learning](https://github.com/AdebayoAAdeniyi/Reinforcement-Learning): eight chapters after Sutton and Barto, from dynamic programming to actor critic, grown out of CMPUT 655. Each experiment runs from one command. 28 tests.

Bioinformatics and chemistry

- [computational-bioinformatics-and-genomic-machine-learning](https://github.com/AdebayoAAdeniyi/computational-bioinformatics-and-genomic-machine-learning): genomic prediction with LightGBM on 304 animals and 1,040 SNPs using 7 fold cross validation (NRMSE 0.2027 against 0.2327 for a mean baseline), together with run time measurements for the HAPI-UR haplotype phasing program.
- [breast-cancer-gene-expression](https://github.com/AdebayoAAdeniyi/breast-cancer-gene-expression): a Python toolkit, exprkit, for combining gene expression from five public GEO studies, with 51 tests and leave one study out validation. It grew out of my CMPUT 606 course project. The README reports that normal samples coming from a single study confound a cancer versus normal classifier, which is the reason for the study level validation.
- [Quantum-Docking-MD-Preparation-and-Analysis](https://github.com/AdebayoAAdeniyi/Quantum-Docking-MD-Preparation-and-Analysis): a toolkit of 15 modules for quantum chemistry, docking and molecular dynamics preparation and analysis. The free programs were run. The parsers for licensed programs were tested on public reference outputs only.
- [scientific-research-and-publications](https://github.com/AdebayoAAdeniyi/scientific-research-and-publications): a catalogue of my 71 published articles.

Web engineering and deployment

- [SoftwareDevelopment](https://github.com/AdebayoAAdeniyi/SoftwareDevelopment): front end and back end web development portfolio.
- [finwise-engineering-showcase](https://github.com/AdebayoAAdeniyi/finwise-engineering-showcase): the engineering behind FINWISE: Node.js and Express with SQLite in WAL mode, behind Nginx, run by PM2 on a DigitalOcean server in Toronto, with Cloudflare, Google Workspace, Resend for email and Playwright test suites. The FINWISE source code itself is not public.

Short practice projects

- [qgis-prairie-provinces-demo](https://github.com/AdebayoAAdeniyi/qgis-prairie-provinces-demo): a first QGIS practice project covering provincial boundaries, a Canadian projection, a table join, area calculation checked against Statistics Canada totals, and a map.
- [ab-test-cookie-cats-analysis](https://github.com/AdebayoAAdeniyi/ab-test-cookie-cats-analysis): a practice A/B test analysis on a public mobile game dataset of 90,189 players, with a data quality check, retention tests, confidence intervals, a bootstrap check and a power analysis. The README states its limitations, including a group size imbalance I could not explain.

## Thesis project

- [FlexCLMs](https://github.com/AdebayoAAdeniyi/FlexCLMs): code for my MSc thesis on kingdom specific chemical language models for natural product generation. The repository is private until the planned publication, and access is granted on request.

## Deployed project

- [FINWISE](https://www.strategicfinancialbuilding.ca): a free educational financial planning web tool for Canada and the USA that I designed and deployed through my company, Strategic Financial Building. The source code is not public.

## Find me

[Google Scholar](http://scholar.google.co.uk/citations?user=QDAoQt8AAAAJ) · [ORCID](http://orcid.org/0000-0003-2421-1382) · [LinkedIn](https://linkedin.com/in/adebayo-adeniyi-80976658/)

Email: azeez.adebayo.adeniyi2@gmail.com
