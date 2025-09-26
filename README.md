# Preproc & First-Level Analysis Scripts for Flanker Task via SPM12

This repository offers a streamlined, highly readable pipeline for analyzing the Flanker dataset from OpenNeuro (https://openneuro.org/datasets/ds000102/versions/00001) using SPM12. The scripts prioritize reproducibility of group-level results as demonstrated in Andy’s Brain Book (https://andysbrainbook.readthedocs.io/en/latest/SPM/SPM_Overview.html), while adopting a distinct coding approach that emphasizes clarity, automation, and ease of use.

While Andy’s original scripts are comprehensive and educational, new users may find them challenging to read or adapt for flexible batch processing. This pipeline addresses those limitations by:

* Separating preprocessing and first-level modeling: Each step can be run independently, and users may substitute alternative preprocessing tools as needed.
* Emphasizing code readability and maintainability: The pipeline is modular, variables are clearly named, and the code is thoroughly commented.
* Facilitating reproducibility: By closely following Andy’s analysis steps, users can replicate published results with minimal setup.
* Supporting batch processing: The structure is easily adaptable for multiple subjects or sessions in other experiments.

Whether you are new to SPM scripting or seeking to automate your analyses, this pipeline is designed to offer a robust, transparent, and flexible solution.
