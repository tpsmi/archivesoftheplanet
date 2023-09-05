# archivesoftheplanet
Code belonging to the paper/article Revisiting the Kahn Collection: Multimodal Machine Learning and Visual Patterns in the Archives de la Planète, 1909-1931

# Installation and setup
Please note that CLIP will not run on every system. I used a Macbook M1. To clone and run this application, you'll need Git, Python, and Anaconda (or Miniconda) installed on your computer. You will also need to install some Python packages to run this application. From your command line, run:
```
# Clone this repository
git clone https://github.com/tpsmi/archivesoftheplanet

# Go into the repository
cd archivesoftheplanet

# Create a dedicated Conda environment and install dependencies
conda env create -f environment.yml --name planetarchives

# Activate the Conda environment
conda planet archives
```
#Use
Please use the notebooks in the order 1 to 5. The first notebooks downloads the autochromes of the Kahn collection, the second crops them, the third uses the metadata for spatial analysis, the fourth analyses the role of photographers (not in the article), and the fifth uses CLIP to cluster the images.

# Cite
If you want, you can cite the article for which this code was written
