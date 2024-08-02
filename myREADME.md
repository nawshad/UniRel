### Installation
 - Create a conda environment with python 3.8
 - install pytorch 1.7.1 
 - install transformers: pip install transformers==4.12.5
 - install torch:  pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu101
### Training:
 - Download data: https://drive.google.com/file/d/1-3uBc_VfaCEWO2_FegzSyBXNeFmqhv7x/view
 - Download model using: huggingface-cli download bert-base-cased
 - put data and model in data directory.
 - Go to /home/nawshad/.cache/huggingface/hub/models--bert-base-cased
 - edit run_nyt.sh 
   - --model_dir ./data/bert-base-cased/snapshots/cd5ef92a9fb2f889e972770a36d4ed042daf221e
   - --dataset_name nyt
 ###TODO:
   - Use the prediction model to predict relations.
