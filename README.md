##DeepFace use basenji as the backbone model
##Install https://github.com/calico/basenji in virtual environment basenji

source activate basenji

##preprocess the bigWig file following these steps https://github.com/calico/basenji/blob/master/tutorials/preprocess.ipynb

##train model
! /PATH_to/DeepFace_train.py -o /PATH_to_save_model/ /PATH_to_params.json /PATH_to_processed_bigwig_data

##more details please check https://github.com/calico/basenji
