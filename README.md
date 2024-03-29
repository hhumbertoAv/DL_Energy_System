# Energy Measurement System for Data Lakes: An Initial Approach


## Description
We have developed an energy measurement system for Data Lakes, designed to monitor and evaluate each OS process triggered by a Data Lake instance. This comprehensive system assesses each process in terms of its CPU, RAM, storage device, and NIC energy consumption. The effectiveness of our approach was verified through the execution of an already validated benchmark for Data Lakes evaluation: DLBench+[^1].

The paper describing the theoretical and technical context of our system was presented at the ACIIDS 2024 conference: https://aciids.pwr.edu.pl/2024/

## Repository Content

This repository serves as a supplementary resource for our submitted paper and includes the following:

1. **Experiment Results from the Paper:**  Includes raw energy measurement data and a file with summarized average results.

2. **Benchmarking Experiments of**:
    - **PowerJoular[^2]**: A command line software to monitor, in real-time, the power consumption of software and hardware components.
    - **Scaphandre[^3]**: A metrology agent dedicated to electrical power consumption metrics.

2. **Our system's code**:
   
https://github.com/hhumbertoAv/FLOC

## Citing
Details for citing this work will be provided upon paper acceptance.

[^1]: https://doi.org/10.1016/j.datak.2023.102154
[^2]: https://github.com/joular/powerjoular
[^3]: https://github.com/hubblo-org/scaphandre
