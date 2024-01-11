# Energy Measurement System for Data Lakes: An Initial Approach


## Description
We have developed an energy measurement system for Data Lakes, designed to monitor and evaluate each OS process triggered by a Data Lake instance. This comprehensive system assesses each process in terms of its CPU, RAM, storage device, and NIC energy consumption. The effectiveness of our approach was verified through the execution of an already validated benchmark for Data Lakes evaluation: DLBench+[^1].

The paper describing the theoretical and technical context of our system was presented at the ACIIDS 2024 conference: https://aciids.pwr.edu.pl/2024/

## Repository Content

This repository serves as a supplementary resource for our submitted paper and includes the following:

1. **The results' values of the experiments**:  Contains raw energy measurement data along with the file summarizing average results.

2. **Benchmarking Experiments of**:
    - **PowerJoular[^2]**: A command line software to monitor, in real-time, the power consumption of software and hardware components.
    - **Scaphandre[^3]**: A metrology agent dedicated to electrical power consumption metrics.

## Citing
Details for citing this work will be provided upon paper acceptance.

[^1]Pegdwendé N. Sawadogo and Jérôme Darmont. 2023. DLBench+: A benchmark for quantitative and qualitative data lake assessment. Data Knowl. Eng. 145, C (May 2023). https://doi.org/10.1016/j.datak.2023.102154
[^2]: https://github.com/joular/powerjoular
[^3]: https://github.com/hubblo-org/scaphandre
