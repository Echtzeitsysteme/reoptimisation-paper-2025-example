# GIPS MODELS 2025 Example

[**GIPS**](https://github.com/Echtzeitsysteme/gips) is an open-source framework for **G**raph-Based (M)**I**LP **P**roblem **S**pecification.
This repository holds the GIPS example projects for the MODELS 2025 paper submission.


## Setup

* Install [GIPS](https://github.com/Echtzeitsysteme/gips) as described in its [repository](https://github.com/Echtzeitsysteme/gips).
* Launch a runtime workspace (while using a runtime Eclipse) as stated in the eMoflon::IBeX installation steps. (Please refer to the installation steps of GIPS above.)
* Import all projects contained in this repository.
* Build all your projects with the black eMoflon hammer. Sometimes, it is required to trigger a cleaning in Eclipse (*Project -> Clean... -> Clean all projects*).
* Some of the projects have a runnable Java class with a `main` function.
* You can now launch a GIPS project like `teachingassistant.uni.plaster.basic`:
    * Go to `teachingassistant.uni.plaster.basic` -> `src` -> `teachingassistant.uni.plaster.basic.runner` in the project explorer.
    * Launch `TaPlasterBasicPipelineRunner.java` with a right click -> _Run As_ -> _Java_.


## Eclipse Project Overview

| **Name**              | **Description**                                           |
| --------------------- | --------------------------------------------------------- |
| `teachingassistant.*` | Teaching Assistant (TA) example: mapping TAs to tutorials |


## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for more details.
