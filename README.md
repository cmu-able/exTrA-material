# Supplemental Material
__ExTrA: Explaining Architectural Design Tradeoff Spaces via Dimensionality Reduction__

Example datasets:
- Tele Assistance System (TAS)
  - [V1](/TAS/tas-data.csv): The regular version of the system.
  - [V2](/TAS/tas-prime-data.csv): In this variant of TAS, we have modified the reliabilities and response times of AS3, which have become worse, and of MS5, which have become better.
  - [Analysis R Markdown file for data analysis, including PCA and Decision Tree Learning](/tele-assistance-system.Rmd)
  - [Example plots](/TAS)
  - [Link to the SEAMS Tele Assistance System (TAS) exemplar](https://www.hpi.uni-potsdam.de/giese/public/selfadapt/exemplars/tas/)

- Network Architecture Scenario (network)
  - [V1](network/network-data.csv): In this first variant, we have a 3x3 network without any modifications in the structural constraints of the system.
  - [V2](network/network-nobarrier-data.csv): In this second variant, we have a 3x3 network without enforcement of barrier nodes between low and high nodes.
  - [V3](network/network-sbarrier-data.csv): In this third variant, we have a 3x3 network that enforces communication between all nodes through a barrier node.
  - [Analysis R Markdown file for data analysis, including PCA and Decision Tree Learning](/network-architecture.Rmd)
  - [Example plots](/network)
