# Flanker task first level analysis script via SPM12
This script provides a streamlined and highly readable pipeline for analyzing the Flanker dataset from OpenNeuro (ds000102). It is designed to maximize reproducibility of the group-level results demonstrated in Andy’s Brain Book, while adopting a different coding logic that emphasizes code clarity, automation, and ease of use.
While Andy’s original scripts are educational and comprehensive, they could be difficult to read or adapt for new users and more flexible batch processing. This script addresses these limitations by:

* Separating preprocessing and first-level modeling, allowing users to run each step independently or substitute alternative preprocessing tools as needed.
* Focusing on code readability and maintainability: The logic is modular, the variables are clearly named, and the code is thoroughly commented. 
* Facilitating reproducibility: By closely matching the analysis steps from Andy’s tutorials, this script allows users to replicate Andy’s results with minimal setup.
* Batch-friendly structure: Easily extend or modify the script for multiple subjects or sessions.

Whether you are new to SPM scripting or looking to automate your analyses, this script aims to provide a robust, user-friendly solution that balances transparency and flexibility.
