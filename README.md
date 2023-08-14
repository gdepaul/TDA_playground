# TDA_playground
Repo dedicated to the research efforts on advancing sublevelset persistence in Topological Data Analysis. 

# Setup 

conda create --name TDAresearch scipy scikit-learn numpy pandas jupyter matplotlib
conda activate TDAresearch    
conda install -c conda-forge pybind11   
### download phat from https://bitbucket.org/phat-code/phat/src/master/ and extract the folder 
cd ${phat folder}
pip install .                       
