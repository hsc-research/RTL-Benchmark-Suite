# VHDL/Verilog IP Cores Repository

This repository contains a curated collection of approximately **860 free and open-source VHDL/Verilog IP cores**, assembled as a benchmark suite for the experimental evaluation presented in our **ICCAD 2026** paper.

The repository is intended to support research in hardware design automation, RTL analysis, synthesis, verification, security evaluation, and LLM-assisted EDA by providing a large and diverse corpus of real-world hardware designs.

## Overview

The IP cores in this repository were originally obtained from **OpenCores** and cover a broad range of application domains, including:

- Arithmetic cores
- Communication controllers
- Crypto cores
- DSP cores
- ECC cores
- Memory cores
- Processors
- SoC components
- System controllers
- Test and verification modules
- Video controllers
- Miscellaneous utility and application-specific designs

This diversity makes the repository useful as a benchmark for tool evaluation, dataset construction, RTL understanding, code repair, and hardware security research.

## Repository Organization

Each branch in this repository represents a **separate and distinct project**.

This means that:

- each branch corresponds to an individual IP core or project,
- projects can be fetched independently,
- users may download only the branch relevant to their work.

This branch-based structure makes the repository easier to use for benchmarking and selective experimentation.

## Accessing Individual Cores

Cores can be fetched independently by downloading only the branch of interest.

The repository includes branches spanning many categories such as:

- `library_*`
- `system_controller_*`
- `testing-verification_*`
- `prototype_board_*`
- `memory_core_*`
- `crypto_core_*`
- `system_on_chip_*`
- `communication_controller_*`
- `coprocessor_*`
- `other_*`
- `arithmetic_core_*`
- `dsp_core_*`
- `processor_*`
- `ecc_core_*`
- `video_controller_*`

Examples of available branches include:

- `library_random_number_generator_library`
- `memory_core_ddr2_sdram_controller`
- `crypto_core_sha3_keccak`
- `communication_controller_spi_core`
- `processor_ao486`
- `ecc_core_configurable_bch_encoder_and_decoder`
- `video_controller_jpeg_encoder`

Because the complete list of branches is very large, it is recommended to place the full inventory in a separate file such as `BRANCHES.md` or `branches.txt`, and reference it from this README.

## Benchmark Use

We assembled this repository as part of the benchmark infrastructure for our **ICCAD 2026** study. The goal was to create a large and varied corpus of open-source VHDL/Verilog designs that reflects practical hardware development scenarios.

This benchmark suite may be useful for:

- RTL generation and completion
- syntax and semantic repair
- simulation and verification studies
- synthesis and implementation experiments
- code understanding and summarization
- dataset creation for ML/LLM research in EDA
- hardware security analysis and benchmarking

## Source and Attribution

The code for each IP core was taken **as is** from **opencores.org**.

The copyright for each IP core belongs to the respective original author of that core. For details about the original projects and their provenance, please refer to the OpenCores website.

## Licensing

**Important:** This repository is a collection of many independent projects, and **there is no single license governing the entire repository**.

Each project may be distributed under a different open-source license. Therefore, users must inspect the files of each individual project to determine the exact licensing terms and usage conditions.

Before using any IP core in research, redistribution, modification, or commercial work, please verify the license associated with that specific project.

## Disclaimer

This repository is provided for research and benchmarking purposes.

- The code was collected from publicly available OpenCores projects.
- Each project is preserved in the form in which it was obtained.
- No guarantee is made regarding correctness, completeness, maintainability, or fitness for any particular purpose.

This code is distributed in the hope that it will be useful, but **without any warranty**, including without limitation any implied warranty of merchantability or fitness for a particular purpose.

## Issue Reporting

If you believe that any material in this repository is incorrect, improperly attributed, or causes a licensing or other issue, please open an issue or contact the repository maintainer so that it can be reviewed and addressed.

## Citation

If you use this repository or the benchmark suite in academic work, please cite our **ICCAD 2026** paper.

<!-- Add citation or BibTeX here -->
