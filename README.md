# Energy Measurement System for Data Lakes: An Initial Approach

## Paper Abstract
Data Lakes are increasingly deployed as a solution for Big Data analytics. Recent improvements in Data Lake technology have focused on improving data access, governance, and discoverability. However, the energy consumption of data operations, a non-trivial issue for eco-conscious organizations, is currently overlooked. Furthermore, existing monitoring tools do not adequately address the complexities of Data Lake architectures.

This paper presents the initial phase of developing a system for measuring energy in Data Lake pipeline operations. The novelty of our solution lies in the fact that we define four measures to assess the power usage of crucial hardware components in a Data Lake context: CPU, RAM, NIC, and storage devices. To validate our approach, we developed a monitoring tool grounded in real-world datasets from a Data Lake benchmark.

## Description
We created an energy measuring system for Data Lakes, which considers all OS processes a Data Lake instance triggers. We evaluated our system using an already validated benchmark: DLBench+. This repository contains 1) The paper pdf file, 2) The raw data files of the experiments' results, and 3) the benchmarking results of PowerJoular and Scaphandre in the server where the experiments were conducted.

## Content
1. **The Article PDF**: Find the full research paper here. This includes all the methodologies, findings, discussions, and conclusions drawn from the study.

2. **Benchmarking Experiments of**:
    - **PowerJoular[^1]**: A command line software to monitor, in real-time, the power consumption of software and hardware components.
    - **Scaphandre[^2]**: A metrology agent dedicated to electrical power consumption metrics.
 
3. **Raw Data of the Experiments**:
    - The raw data collected during our experiments is available for further analysis and verification. We provide detailed information on the dataset, including how it was gathered, any preprocessing done, and its structure.

## Citing
Will be uploaded upon paper acceptance.

[^1]: https://github.com/joular/powerjoular
[^2]: https://github.com/hubblo-org/scaphandre

