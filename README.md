# DLCV Final Project ( Visual Queries 2D Localization Task )

# How to run your code?
* TODO: Please provide the scripts for TAs to reproduce your results, including training and inference. For example, 

```shell script=
bash train.sh <Path to clips folder> <Path to annot file>
bash inference.sh <Path to clips folder> <Path to annot file> <Path to output json file>
```

# Usage
To start working on this final project, you should clone this repository into your local machine by the following command:

    git clone https://github.com/ntudlcv/DLCV-Fall-2023-Final-2-<team name>.git
  
Note that you should replace `<team_name>` with your own team name.

For more details, please click [this link](https://docs.google.com/presentation/d/1TsR0l84wWNNWH7HaV-FEPFudr3o9mVz29LZQhFO22Vk/edit?usp=sharing) to view the slides of Final Project - Visual Queries 2D Localization Task. **The introduction video for final project can be accessed in the slides.**

# Visualization
We provide the code for visualizing your predicted bounding box on each frame. You can run the code by the following command:

    python3 visualize_annotations.py --annot-path <annot-path> --clips-root <clips-root> --vis-save-root <vis-save-root>

Note that you should replace `<annot-path>`, `<clips-root>`, and `<vis-save-root>` with your annotation file (e.g. `vq_val.json`), the folder contains all clips, and the output folder of the visualization results, respectively.

# Evaluation
We also provide the evaluation for you to check the performance (stAP) on validation set. You can run the code by the following command:

    cd evaluation/
    python3 evaluate_vq.py --gt-file <gt-file> --pred-file <pred-file>

Note that you should replace `<gt-file>` with your val annotation file (e.g. `vq_val.json`) and replace `<pred-file>` with your output prediction file (e.g. `pred.json`)  

# Submission Rules
### Deadline
112/12/28 (Thur.) 23:59 (GMT+8)
    
# Q&A
If you have any problems related to Final Project, you may
- Use TA hours
- Contact TAs by e-mail ([ntudlcv@gmail.com](mailto:ntudlcv@gmail.com))
- Post your question under `[Final challenge 2] VQ2D discussion` section in NTU Cool Discussion
