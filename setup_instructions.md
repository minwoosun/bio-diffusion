conda env create -f environment.yaml
conda init bash
# start new terminal after conda init
conda activate bio-diffusion
pip3 install -e .
conda install huggingface_hub

# from top directory
wget https://zenodo.org/record/10995319/files/GCDM_Checkpoints.tar.gz
tar -xzf GCDM_Checkpoints.tar.gz
rm GCDM_Checkpoints.tar.gz


