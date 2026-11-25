# AndroidDFT-GA: Genetic Algorithm-Based Test Data Generation Tool
## 1. Project Overview
This repository contains the implementation of a Genetic Algorithm (GA)-based tool for automatic test data generation in Android applications under the All-Uses data-flow testing criterion.
The tool represents Android user interface (UI) controls as chromosome genes and organizes them into activity-based blocks. It applies block crossover and control-based mutation to evolve candidate test cases toward improved cumulative def-use coverage.
## 2. Main Components
The tool integrates the following components:
- Static analysis and instrumentation of Android applications.
- Extraction of variables and definition-use (DU) pairs.
- UI-control-based chromosome representation.
- Block crossover and control-based mutation.
- Coverage-based fitness evaluation.
- Automated test execution using Android Espresso.
- Generation of test cases and coverage reports.
## 3. Requirements
The following software and dependencies are required:
- Java: [Specify the exact version].
- Android Studio: [Specify the exact version].
- Android SDK: [Specify the tested API level].
- AndroidX Espresso: [Specify the exact version].
- Genetic Algorithm Framework (GAF): [Specify the exact version].
- AndroidDFT analysis and instrumentation component: [Specify its version and access instructions].
## 4. Installation and Configuration
1. Clone or download this repository.
2. Install the required Java and Android development environment.
3. Configure the required dependencies.
4. Configure the AndroidDFT analysis and instrumentation component.
5. Open the project using the appropriate development environment.
6. Configure the target Android application and its input-control information.
Detailed installation instructions and configuration steps are provided in the documentation.
## 5. Running the Tool
The testing workflow consists of:
1. Selecting the Android application under test.
2. Performing static analysis and instrumentation.
3. Extracting UI controls and DU pairs.
4. Specifying input types, ranges, and GA parameters.
5. Executing the GA-based test generation process.
6. Running generated tests using Espresso.
7. Inspecting the generated test cases and coverage reports.
## 6. Experimental Data
Available execution reports, generated test cases, and experimental results are organized in the `results/` directory. Only the experiments and raw records actually included in this repository are documented here.
## 7. Research Publication
This tool accompanies the research paper:
"A User Interface-Aware Genetic Algorithm for Data-Flow Test Data Generation in Android Applications: Method, Tool, and Empirical Evaluation."
## 8. Reproducibility
The repository documentation specifies the required environment, dependencies, configuration, and execution procedure. Experimental results should be interpreted in accordance with the raw records provided in the repository.
## 9. License and Third-Party Components
See the LICENSE file and the documentation for information about software ownership, third-party dependencies, and the licenses of external components.
