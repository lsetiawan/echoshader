# echoshader

Open Source Python package for building ocean sonar data visualizations based on the HoloViz suite of Python tools.

## What are ocean sonar systems?

Ocean sonar systems, such as echosounders, are the [workhorse to study life in the ocean](https://storymaps.arcgis.com/stories/e245977def474bdba60952f30576908f). They provide continuous observations of fish and zooplankton by transmitting sounds and analyzing the echoes bounced off these animals, just like how medical ultrasound images the interior of human body. In recent years these systems are widely deployed on ships, autonomous vehicles, or moorings, bringing in a lot of data that allow scientists to study the change of the marine ecosystem.

## Conda Development Environment Setup

The setup below assumes that you have installed [Conda](https://docs.conda.io/projects/conda/en/latest/), an open-source package management system.

1. Install echoshader conda environment

    ```bash
    conda create -n echoshader-dev -c conda-forge --file requirements.txt
    ```

2. Activate the `echoshader-dev` environment

    ```bash
    conda activate echoshader-dev
    ```

3. Install development version of echoshader package

    ```bash
    pip install -e .
    ```
