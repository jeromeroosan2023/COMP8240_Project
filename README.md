# COMP8240_Project
## COMP8240 Application of Data Science Major Project - Group C

#### Team members:
- Sri Venkata Kameswara Naga Phanindra Kavipurapu
- Jerome Roosan
- Chandrashekhar Meenakshisundaram
- Raja Pedapudi

### Files and Directories

- `Group C - Project Proposal Presentation.pdf`: Project proposal presentation.
- `Group C - Project Update Presentation.pdf`: Update presentation.
- `Group C - Project Final Presentation.pdf`: Final presentation.
- `Group C - Final Report.pdf`: Final Project Report.
- `Original_Automated_Hate_Speech_Detection_and_the_Problem_of_Offensive_Language_Python_3_6.ipynb`: Original source work code used to replicate the project. This file has some additional code to get it working on Python v3, and minor edits to use the current file paths and Google Colab mounting.
- `New_data_Automated_Hate_Speech_Detection_and_the_Problem_of_Offensive_Language_Python_3_6.ipynb`: This is a copy of the original work which is used to run using the new data and do necessary modelling and validations.
- `hate-speech-and-offensive-language-master/`: The original source work downloaded from the URL mentioned in the paper.
  - `data/`: The directory of data files used in this project.
    - `labeled_data.csv`: The labeled data file used in the source work. This is used for replicating the source work.
    - `new_labeled_data.csv`: Newly created labeled data which is used to execute as part of validation.

### Getting Started

To replicate the project work,
- Download the files and directories.
- Make necessary corrections to based on the platform used to execute the python file.
- Make sure to use the correct file paths in the code.

### Prerequisites

The following **packages** are required, if not already installed.
- VaderSentiment: This package is used to do the sentiment analysis. `!pip install vaderSentiment` can be used to install the package.
- Textstat: This package is used to calculate statistics from the text. `!pip install textstat` can be used to install the package.
