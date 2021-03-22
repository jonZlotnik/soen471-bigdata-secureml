# Secure Machine Learning on Big Data: An exploration of secure protocols that allow public computation on private medical images

## Abstract

Obtaining medical imagery for building machine learning models, and testing image analysis techniques, is a time consuming and costly process. It traditionally requires getting approved by ethics boards, recruiting hundreds, if not thousands, of subjects, and obtaining written consent from every "data donor". Another means by which one can gather data sets is by requesting anonymized data from hospitals and research centers which can involve meticulous de-identification pipelines.

With advances in cryptography over the last 20 years in the areas of multi-party computation, homomorphic encryption, and smart-contracts, several options for computing on private data sets have been developped. In order to better understand the tools currently available to the big-data researcher, we develop a prototype solution for analyzing private medical images. We discuss the implications of the overhead introduced by the available tools for computing securely on private datasets as they scale. Finally, we analyze the trade-offs one could consider if the overhead, introduced by the secure protocols, proves to be crippling.

We ensure meaningful comparison of tools by builing an "end to end" pipeline for medical image processing and pinpointing where each protocal is used in the pipeline. In documenting our experience and concerns, with regards to security, privacy, efficiency, and complexity of these processes, we provide a sense of how feasible publicly computing on private medical images is with current tooling.

## Introduction

### Context and objectives

### Presentation of the problem

### Related work

- [DeepSecure: Scalable Provably-Secure Deep Learning](https://arxiv.org/ftp/arxiv/papers/1705/1705.08963.pdf)

## Materials and Methods

### Datasets

- [EchoNet from Stanford](https://github.com/echonet/dynamic)

### Technologies and algorithms

#### Homomorphic Cryptography

- [FHE Image Processing](https://github.com/wfus/Fully-Homomorphic-Image-Processing)
- [Microsoft SEAL FHE Libraries](https://www.microsoft.com/en-us/research/project/microsoft-seal/)
- [homomorphicencryption.org](https://homomorphicencryption.org/introduction/)

#### Secure Multiparty Computation

https://mortendahl.github.io/2018/03/01/secure-computation-as-dataflow-programs/#basics
https://blog.openmined.org/training-cnns-using-spdz/

#### Blockchains and Smart Contracts