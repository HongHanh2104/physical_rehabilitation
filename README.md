# Physical Rehabilitation

* This research is conducted at VISHC



### Requirements
* `pip install dtw`
* `pip install opencv-python`
* `conda install --file requirements.txt`


### Training
* `python train.py`
* If you want to use different parts of the loss or change training settings, simply modify the `config.py`.

### Evaluation
Here we provide a sample evaluation procedure 
* `python evaluate_KT.py --logdir /path/to/trained/model/`
* Note that a useful function for framewise feature extraction is provided under `utils.py`


## Acknowledgment
The data processing, loading and training setup code was modified from this very useful repo:
https://github.com/google-research/google-research/tree/master/tcc
